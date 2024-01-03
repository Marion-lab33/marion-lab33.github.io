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
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/projet2-pagedemo.jpg" alt="Image 1" width="300" style="display: block; margin: 0 auto; margin-bottom: 10px;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/projet2-pagecinemas.jpg" alt="Image 2" width="300" style="display: block; margin: 0 auto; margin-bottom: 10px;"/>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/projet2-pagetendances.jpg" alt="Image 3" width="300" style="display: block; margin: 0 auto; margin-bottom: 10px;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/projet2-pagefilms.jpg" alt="Image 4" width="300" style="display: block; margin: 0 auto; margin-bottom: 10px;"/>
    </td>
  </tr>
</table>
<br>

**Machine Learning & Interface** : Nous avons ensuite utilisé des algorithmes de machine learning pour développer un système de recommandations de films. Fonctionnement : à partir d'un choix de 5 films programmés par le cinéma, notre modèle permet d'afficher une nouvelle sélection de films qui proposent des similarités (genres, acteurs, réalisateurs, pays de production, description des films avec la création de nuages de mots)
- Test et choix du modèle de machine learning avec Scikit-Learn : KKN (les plus proches voisins) 
- Implantation du modèle dans un template HTML / CSS avec le microframework Flask


![App page d'accueil](/assets/EDENwebsite-accueil3.jpg)

<table style="border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/EDENwebsite-film1.jpg" alt="Image 1" width="300" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/EDENwebsite-film2.jpg" alt="Image 2" width="300" style="display: block; margin: 0 auto;"/>
    </td>
  </tr>
</table>

---

<br>

## Jeux Steam 🎮 - EDA

Une petite EDA (Analyse Exploratoire de Données) réalisée pendant les vacances de Noël sur un dataset de 27000 jeux Steam. L'objectif était d'appliquer une gamme étendue de connaissances et de méthodes acquises au cours de la formation, en Python et en visualisation de données.

**Quelques axes d'analyse**
- Découverte de tendances parmi les jeux Steam
- Analyse des genres de jeux préférées des utilisateurs
- Recherche de corrélations entre les différentes variables

**Outils utilisés**
- Python & Pandas pour le nettoyage et l'analyse des données
- Matplotlib & Seaborn pour la datavisualisation

**Lien vers le projet**🔗 
Je partage l'intégralité de mon travail sur [GitHub](https://github.com/Marion-lab33/steam-games/).


<table style="border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/steam1.jpg" alt="Image 1" width="300" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/steam3.jpg" alt="Image 2" width="300" style="display: block; margin: 0 auto;"/>
    </td>
  </tr>
</table>

---

<br>

## Toys & Models - Décisions datadriven

**Le projet** : La société Toys & Models a besoin d'un tableau de bord de gestion qui lui fournit une vision en temps réel des KPIs pertinents. Le but : aider à la prise de décisions datadriven.

**Modélisation / requêtes SQL** : 
- Modélisation de la base de données relationnelle (clés primaires, clés étrangères, relations) 
- Réalisation des requêtes SQL sous mySQL workbench. Techniques utilisées : fonctions d'aggregation, jointures, sous-requêtes, fonctions mathématiques, de dates...

<table style="border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/Modelisation-projet1.jpg" alt="Image 1" width="250" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/requeteSQL-finances.jpg" alt="Image 2" width="350" style="display: block; margin: 0 auto;"/>
    </td>
  </tr>
</table>

<br>

**Data visualisation** : Réalisation d'un dashboard sur un outil de Business Intelligence, qui permettra à l'entreprise d'améliorer ses performances
- Intégration mySQL - POWER BI (lien direct des bases de données)
- Développement de visualisations (histogramme, graphique en courbe / secteurs / ruban, segment...) répartis sur 4 onglets (ventes, finances, logistique, RH)

<table style="border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <td align="center" style="padding: 0; border: none; margin-right: 10px;">
      <img src="/assets/projet1-pageventes.jpg" alt="Image 1" width="300" style="display: block; margin: 0 auto;"/>
    </td>
    <td align="center" style="padding: 0; border: none; padding-left: 10px;">
      <img src="/assets/projet1-pagerh.jpg" alt="Image 2" width="300" style="display: block; margin: 0 auto;"/>
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

<div style="text-align: center;">
  <img src="/assets/Rodolf.png" alt="Rodolp page 1" style="width: 80%; display: block; margin: 0 auto;">
</div>

[Voir la vidéo du projet Rodolf](/assets/AppRodolf.mov)



