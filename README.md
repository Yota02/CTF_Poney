## BREAK THE CODE


---
## Description 


---

## Structure du projet

---

````
/Break the code
│
├── /public            # Fichiers accessibles publiquement
│   ├── css            # Fichiers css
│   ├── img            # Fichiers avec les images
│   ├── includes       # Fichiers avec les fichiers php
│   ├── js             # Fichiers avec le javascript
│   └── index.php      # Point d'entrée de l'application
│
├── /src               # Code source de l'application
│   ├── Controllers    # Gestion des requêtes et logique métier
│   ├── Models         # Représentation des données et interactions avec la base de données
│   └── Views          # Templates et génération d'interface utilisateur
│       ├── layout.php            # Template de mise en page (header, footer communs)
│       ├── home.php              # Vue de la page d'accueil
│       ├── post.php              # Vue d'une page article spécifique
│       ├── auth/
│       │   ├── login.php         # Vue de la page de connexion
│       │   └── register.php      # Vue de la page d'inscription
│       └── partials/
│           ├── header.php        # En-tête commun à toutes les pages
│           └── footer.php        # Pied de page commun à toutes les pages
│
├── /config            # Fichiers de configuration de l'application
│   └── database       # Configuration de la base de données
│   └── config.php     # Configuration générale
│
├── /logs              # Fichiers logs pour les erreurs
│
├── /tests             # Tests unitaires et d'intégration
│
├── composer.json      # Fichier de configuration des dépendances Composer
├── .gitignore         # Liste des fichiers/dossiers à ignorer par Git
└── README.md  
````

---
