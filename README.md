# Data Analyst Junior
Top Skills : Python / SQL / Power BI / Excel

---
<br>

## Système de recommandation de films 

**Le projet** : Le Cinéma EDEN (dans la Creuse) est en perte de vitesse. Son gérant nous demande de l'aider à le redynamiser.

**Dashboard et KPIs** : En situation de cold start, la première étape consitait à analyser le marché du cinéma en France. Le but : faire parler les données pour comprendre les besoins du cinéma et lui proposer des axes d’orientation. 
- Collecte des données (4 sources): base de données IMDB, base de données TMDB (via requête de l'API), données de l'observatoire national des territoires, données INSEE
- Analyse, nettoyage et filtrage des données avec Python (Pandas)
- Recherche de corrélations entre les données, mise en avant de marges de progression avec Python (librairies de datavisualisation: MatplotLib, Seaborn)
- Réalisation du dashboard sur Power BI : outil de prise de décision pour le gérant du cinéma


<table style="border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none;">
      <img src="/assets/projet2-pagedemo.jpg" alt="Image 1" width="300" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none;">
      <img src="/assets/projet2-pagecinemas.jpg" alt="Image 2" width="300" style="display: block; margin: 0 auto;"/>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none;">
      <img src="/assets/projet2-pagetendances.jpg" alt="Image 3" width="300" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none;">
      <img src="/assets/projet2-pagefilms.jpg" alt="Image 4" width="300" style="display: block; margin: 0 auto;"/>
    </td>
  </tr>
</table>


**Machine Learning & Interface** : Nous avons ensuite utilisé des algorithmes de machine learning pour développer un système de recommandations de films. Fonctionnement : à partir d'un choix de 5 films programmés par le cinéma, notre modèle permet d'afficher une nouvelle sélection de films qui proposent des similarités (genres, acteurs, réalisateurs, pays de production, description des films avec la création de nuages de mots)
- Test et choix du modèle de machine learning avec Scikit-Learn : KKN (les plus proches voisins) 
- Implantation du modèle dans un template HTML / CSS avec le microframework Flask


![App page d'accueil](/assets/EDENwebsite-accueil3.jpg)

<table style="border: none;">
  <tr style="border: none;">
    <td align="center">
      <img src="/assets/EDENwebsite-film1.jpg" alt="Image 1" width="300">
    </td>
    <td align="center">
      <img src="/assets/EDENwebsite-film2.jpg" alt="Image 2" width="300">
    </td>
  </tr>
</table>



---
<br>

## Toys & Models - datadriven decisions

**Le projet** : La société Toys & Models a besoin d'un tableau de bord de gestion qui lui fournit une vision en temps réel des KPIs pertinents. Le but : permettre la prise de décision sous 4 axes (ventes, finances, logistique, RH)

**Modélisation / requêtes SQL** : 
- Modélisation de la base de données relationnelle (clés primaires, clés étrangères, relations) 
- Réalisation des requêtes SQL sous mySQL workbench. Techniques utilisées : fonctions d'aggregation, jointures, sous-requêtes, fonctions mathématiques, de dates...

<div style="text-align: center;">
  <img src="/assets/Modelisation-projet1.jpg" alt="Modélisation Projet 1" width="60%">
</div>
<br><br>

```sql
SELECT 
    o.customerNumber AS Numéro_Client,
    c.customerName AS Nom_Client,
    Montant.Montant,
    TotalPaiement.Paiement,
    Montant.Montant - TotalPaiement.Paiement AS Reste_à_payer
FROM orders AS o
INNER JOIN (
    SELECT 
        o.customerNumber,
        SUM(od.quantityOrdered * od.priceEach) AS Montant
    FROM orderdetails AS od
    INNER JOIN orders AS o ON od.orderNumber = o.orderNumber
        WHERE o.status != 'Cancelled'
    GROUP BY o.customerNumber
) AS Montant ON o.customerNumber = Montant.customerNumber
INNER JOIN (
    SELECT 
        p.customerNumber,
        SUM(p.amount) AS Paiement
    FROM payments AS p
    GROUP BY p.customerNumber
) AS TotalPaiement ON o.customerNumber = TotalPaiement.customerNumber
INNER JOIN customers AS c ON c.customerNumber = o.customerNumber
WHERE Montant.Montant - TotalPaiement.Paiement > 0
GROUP BY o.customerNumber, c.customerName
ORDER BY Reste_à_payer;
```

**Data visualisation** : Réalisation d'un dashboard sur un outil de Business Intelligence, qui permettra à l'entreprise d'améliorer ses performances
- Intégration mySQL - POWER BI (lien direct des bases de données)
- Développement de visualisations (noms des graphs) répartis sur 4 onglets (ventes, finances, logistique, RH)

<table style="border: none;">
  <tr style="border: none;">
    <td align="center">
      <img src="/assets/projet1-pageventes.jpg" alt="Image 1" width="300"/>
    </td>
    <td align="center">
      <img src="/assets/projet1-pagerh.jpg" alt="Image 2" width="300"/>
    </td>
  </tr>
</table>

---
<br>

## Mon premier hackathon ! 

Les règles étaient simples : ~24h pour réaliser un projet répondant au thème des fêtes de fin d'année, avec une équipe mixte composée d'étudiants en Data, PHP et JS. 

**Le Projet : Rodolf** 

Notre objectif : faire de Rodolf votre compagnon festif, animant vos longues soirées de Noël avec des jeux, des débats insolites, des blagues et des énigmes. Une app simple, conçue pour toute la famille !

- 🐍 Python pour la collecte et le nettoyage de données
- 🐬 MySQL Workbench pour la création de la BDD
- 🖥️ PHP pour l'élaboration d'une API robuste
- ⚛️ React.js pour le développement front-end
- 🐳 Docker pour une collaboration fluide entre les équipes

Récompenses Remportées 🏆 : Nous sommes ravis d'annoncer que notre projet a remporté deux prix : "Meilleur Concept" et "Meilleure Démo d'Application".

Remerciements : Un grand merci à toute l'équipe pour leur collaboration exceptionnelle et à la Wild Code School pour l'organisation impeccable ! 

<img src="/assets/Rodolf.png" alt="Rodolp page 1" width="80%" style="text-align: center;">

[Voir la vidéo du projet Rodolf](/assets/AppRodolf.mov)



