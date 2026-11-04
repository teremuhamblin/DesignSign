###### README.md >> markdown
# 🛡️ DesignSign
- *Projet de démonstration GitHub Actions*

DesignSign est un projet minimaliste conçu pour démontrer l'utilisation de GitHub Actions :

```text
- Build automatique
- Tests techniques
- Déploiement statique
- Publication d’un package Docker dans GitHub Packages
```

- 》》 **Ce projet sert de base pour apprendre, montrer ou enseigner les workflows GitHub**.

---
---

### Structure
```text
DesignSign/
│
├── README.md
├── .gitignore 
├── LICENSE 
├── Dockerfile
│
└── .github/
    ├── dependabot.yml
    └── ISSUE_TEMPLATE/
        ├── bug_report.yml
        ├── .yml
        ├── test.yml
    └── workflows/
        ├── build.yml
        ├── package.yml
        ├── test.yml
        └── static.yml
└── assets/
    ├── ascii
    └── logo.txt
```

### 📦 Package GitHub
> Une image Docker est automatiquement publiée dans :

```text
**ghcr.io/<ton-user>/DesignSign:latest**
```

### 📁 Workflows inclus
```text
- `build.yml` : Build technique
- `test.yml` : Tests techniques
- `static.yml` : Déploiement GitHub Pages
- `package.yml` : Construit et publie l'image Docker
```

### 🪪 Licence
》》 **Unlicense — libre, gratuit, open source**.

---
---

- ***Badges GitHub Actions***

[![Dependabot Updates](https://github.com/teremuhamblin/DesignSign/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/teremuhamblin/DesignSign/actions/workflows/dependabot/dependabot-updates)

---

[![Deploy static content to Pages](https://github.com/teremuhamblin/DesignSign/actions/workflows/static.yml/badge.svg)](https://github.com/teremuhamblin/DesignSign/actions/workflows/static.yml)
