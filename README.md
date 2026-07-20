# Booki

Projet 2 réalisé dans le cadre de la formation **Intégrateur Web d’OpenClassrooms**.

L’objectif était d’intégrer la page d’accueil responsive de **Booki**, une agence de voyage fictive permettant aux utilisateurs de rechercher des hébergements et de découvrir des activités dans la ville de leur choix.

## Présentation du projet

Booki est un prototype de site de planification de vacances. La page présente une recherche d’hébergements à Marseille ainsi qu’une sélection de logements et d’activités touristiques.

Elle comprend notamment :

- une navigation vers les sections « Hébergements » et « Activités » ;
- un formulaire de recherche par destination ;
- plusieurs filtres thématiques ;
- une sélection d’hébergements à Marseille ;
- une section regroupant les hébergements les plus populaires ;
- une sélection d’activités à découvrir dans la ville ;
- un footer contenant les liens d’information du site.

## Travail réalisé

- intégration de la page à partir de la maquette Figma fournie ;
- structuration du contenu avec des balises HTML sémantiques ;
- création des cartes d’hébergements et d’activités ;
- intégration du formulaire de recherche et des filtres ;
- mise en place de la navigation interne entre les sections ;
- adaptation de l’interface aux formats ordinateur, tablette et mobile ;
- utilisation de Flexbox pour organiser les différents éléments ;
- séparation des styles CSS en plusieurs fichiers selon les sections ;
- ajout des icônes Font Awesome et de la police Raleway ;
- ajout de textes alternatifs aux images et d’informations destinées aux lecteurs d’écran.

## Technologies utilisées

- HTML5
- CSS3
- Flexbox
- Media queries
- Variables CSS
- Font Awesome
- Google Fonts — Raleway
- Figma pour la maquette

## Organisation des branches

- **`main`** : contient le code de départ fourni par OpenClassrooms.
- **`dev_branch`** : contient l’intégration et les modifications que j’ai réalisées.

Pour consulter ma version du projet :

```bash
git switch dev_branch
```

## Installation et lancement

Ce projet est un site statique et ne nécessite aucune dépendance.

1. Clonez le dépôt :

```bash
git clone <URL_DU_DEPOT>
```

2. Placez-vous dans le dossier du projet :

```bash
cd PROJET-2-Booki
```

3. Sélectionnez la branche contenant la version finalisée :

```bash
git switch dev_branch
```

4. Ouvrez le fichier `index.html` dans votre navigateur.

## Structure du projet

```text
PROJET-2-Booki/
├── css/
│   └── main.css        # Styles globaux, variables et imports
├── images/
│   ├── activites/      # Images des activités à Marseille
│   ├── hebergements/   # Images des hébergements
│   ├── icon/           # Icônes du site
│   └── logo/           # Logo Booki
├── parts/
│   ├── activity.css    # Section des activités
│   ├── filter.css      # Filtres
│   ├── footer.css      # Pied de page
│   ├── header.css      # En-tête et navigation
│   ├── heberg.css      # Hébergements et populaires
│   ├── info.css        # Bandeau d’information
│   └── search.css      # Formulaire de recherche
├── index.html          # Page d’accueil
└── README.md           # Documentation du projet
```

## Responsive design

L’interface s’adapte à trois types d’écrans :

- **ordinateur** : affichage complet sur une largeur allant jusqu’à 1 440 px ;
- **tablette** : mise en page adaptée entre 768 px et 1 024 px ;
- **mobile** : réorganisation des sections en dessous de 768 px.

Sur mobile, la section « Les plus populaires » est notamment placée avant les autres hébergements et le bouton de recherche est remplacé par une icône.

## Compétences travaillées

- intégrer une interface à partir d’une maquette Figma ;
- structurer une page web avec HTML ;
- réaliser des mises en page avec Flexbox ;
- créer une interface responsive avec des media queries ;
- organiser et découper les styles CSS ;
- utiliser des ressources externes comme Google Fonts et Font Awesome ;
- versionner un projet avec Git et travailler avec plusieurs branches.

## Remarque

Le projet correspond à un prototype d’intégration HTML/CSS. Le formulaire de recherche, les filtres et les liens des cartes ne disposent donc pas de logique dynamique.

## Contexte

Projet pédagogique réalisé dans le cadre de la formation **Intégrateur Web** d’OpenClassrooms.
