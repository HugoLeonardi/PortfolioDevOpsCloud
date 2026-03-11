# Portfolio DevOps & Cloud — CLAUDE.md

## Structure du projet

```
PortfolioDevOpsCloud/
├── index.html                        # Landing page principale
├── css/style.css                     # Feuille de style globale (Srcery terminal palette)
└── projects/
    └── nextcloud-terraform.html      # Page détaillée du projet Nextcloud
```

## Stack

- HTML/CSS statique, aucun framework JS
- Thème sombre : palette **Srcery terminal** (variables CSS dans `css/style.css`)
- Police système (`-apple-system`, `Segoe UI`, etc.), monospace pour le code

## Conventions CSS

- Variables centralisées dans `:root` (`:root { --bg-primary, --accent-cyan, ... }`)
- Classes de tags colorés : `.tag-terraform`, `.tag-aws`, `.tag-ec2`, `.tag-rds`, `.tag-s3`, `.tag-iam`, `.tag-vpc`, `.tag-iac`, `.tag-apache`, `.tag-mysql`, `.tag-linux`
- Composants réutilisables : `.btn`, `.project-card`, `.skill-block`, `.tag`, `.callout`, `.sidebar-card`
- Grilles : `.projects-grid` (cards projets), `.skill-blocks-grid` (compétences en blocs)

## Landing page (`index.html`)

- **Nav** : logo + liens Projets / Compétences / GitHub
- **Hero** : titre, sous-titre, boutons CTA
- **Projets** (`#projets`) : grille de cards — actuellement 1 projet réel affiché
- **Compétences** (`#competences`) : grille de blocs par catégorie (Cloud AWS, IaC, Sécurité, Réseau, Linux, BDD)
- **Footer** : nom, formation, liens GitHub / LinkedIn

## Liens à mettre à jour

- GitHub : `https://github.com/HugoLeonardi` (remplacer les `https://github.com/` génériques dans le HTML)
- LinkedIn : à renseigner dans le footer

## Remote GitHub

```
origin  https://github.com/HugoLeonardi/PortfolioDevOpsCloud.git
```
