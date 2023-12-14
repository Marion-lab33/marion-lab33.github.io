# Data Analyst Junior
Top Skills : Python / SQL / Power BI / Excel

---

## Système de recommandation de films 

**Le projet** : Le Cinéma EDEN (dans la Creuse) est en perte de vitesse. Son gérant nous demande de l'aider à le redynamiser.

**Dashboard** : En situation de cold start, la première étape consitait à analyser le marché du cinéma en France. Le but : faire parler les données pour comprendre les besoins du cinéma et lui proposer des axes d’orientation. 
- Collecte des données (4 sources): base de données IMDB, base de données TMDB (via requête de l'API), données de l'observatoire national des territoires, données INSEE
- Analyse, nettoyage et filtrage des données avec Python (Pandas)
- Recherche de corrélations entre les données, mise en avant de marges de progression avec Python (librairies de datavisualisation: MatplotLib, Seaborn)
- Réalisation du dashboard sur Power BI : outil de prise de décision pour le gérant du cinéma


<table style="border: none;">
  <tr style="border: none;">
    <td align="center">
      <img src="/assets/projet2-pagedemo.jpg" alt="Image 1" width="300"/>
    </td>
    <td align="center">
      <img src="/assets/projet2-pagecinemas.jpg" alt="Image 2" width="300"/>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center">
      <img src="/assets/projet2-pagetendances.jpg" alt="Image 3" width="300"/>
    </td>
    <td align="center">
      <img src="/assets/projet2-pagefilms.jpg" alt="Image 4" width="300"/>
    </td>
  </tr>
</table>

**Machine Learning & Interface** : Nous deviosn ensuite utiliserez des algorithmes de machine learning pour développer un système de recommandations de films en recommander des films en fonction de films qui ont été propgarmmés par le cinéma (suite au choix de l'orientation)
Nous avons choisi d'implanter 
- Création des modèles de machine learning avec Scikit-Learn.
- ML utilisé : KKN (les plus proches voisins) avec prise en compte 
- Implantation du modèle dans un template HTML / CSS avec le microframework Python : Flask
- Connexion entre les pages, réactualisation automatique (choix aléatoire de 5 films parmi la programmation), au clic, mise à disposition des infos du film choisi, recommandations de 12 films qui proposent des similarités


![App page d'accueil](/assets/EDENwebsite-accueil3.jpg)

<table style="border: none;">
  <tr style="border: none;">
    <td align="center">
      <img src="/assets/EDENwebsite-film1" alt="Image 1" width="300"/>
    </td>
    <td align="center">
      <img src="/assets/EDENwebsite-film2.jpg" alt="Image 2" width="300"/>
    </td>
  </tr>
</table>


---

## Projet : Toys & Models 
Analyse et traitement de la base de données de l'entreprise, création d’un dashboard sur Power BI (vision en temps réel des KPIs pertinents pour permettre la prise de décision)

<pre>
```python
def hello_world():
    print("Hello, World!")
```
</pre>


---

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

![Rodolp page 1](/assets/Rodolf.png)

[Voir la vidéo du projet Rodolf](/assets/AppRodolf.mov)



