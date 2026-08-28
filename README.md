###### README.md >> markdown 
# 🛡️ DesignSign
- Mini projet de démonstration GitHub Actions

DesignSign est un projet minimaliste conçu pour **démontrer l'utilisation de GitHub Actions** :
- Build automatique
- Tests techniques
- Déploiement statique
- Publication d’un package Docker dans GitHub Packages

Ce projet sert de base pour apprendre, montrer ou enseigner les workflows GitHub.

### Structure
```text
DesignSign/
│
├── README.md
├── Dockerfile
│
└── .github/
    └── workflows/
        ├── build.yml
        ├── test.yml
        └── static.yml
```

### 📦 Package GitHub
>Une image Docker est automatiquement publiée dans :
```text
**ghcr.io/<ton-user>/DesignSign:latest**
```

### 📁 Workflows inclus
- `build.yml` : Build technique
- `test.yml` : Tests techniques
- `static.yml` : Déploiement GitHub Pages

### 🪪 Licence
Unlicense — libre, gratuit, open source.

- ***Badges GitHub Actions***

[![Dependabot Updates](https://github.com/teremuhamblin/DesignSign/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/teremuhamblin/DesignSign/actions/workflows/dependabot/dependabot-updates)

---

[![Security Scan](https://github.com/teremuhamblin/DesignSign/actions/workflows/security.yml/badge.svg)](https://github.com/teremuhamblin/DesignSign/actions/workflows/security.yml)


---

[![Deploy static content to Pages](https://github.com/teremuhamblin/DesignSign/actions/workflows/static.yml/badge.svg)](https://github.com/teremuhamblin/DesignSign/actions/workflows/static.yml)
