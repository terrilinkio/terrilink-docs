# Terrilink Docs

Documentation officielle de la plateforme [Terrilink](https://terrilink.io) — réseaux alumni et diasporas.

Source en Markdown, généré en site statique via [MkDocs Material](https://squidfunk.github.io/mkdocs-material/), versionné via [mike](https://github.com/jimporter/mike).

**Site en ligne** : [terrilinkio.github.io/terrilink-docs](https://terrilinkio.github.io/terrilink-docs/) (Phase 1) — futur domaine `docs.terrilink.io` (Phase 2).

---

## Structure du dépôt

```
terrilink-docs/
├── docs/
│   ├── index.md                    Page d'accueil
│   ├── alumni/                     Documentation réseaux alumni (écoles)
│   │   └── admin/                  Espace administrateur alumni
│   ├── diaspora/                   Documentation réseaux diaspora
│   │   └── admin/                  Espace administrateur diaspora
│   ├── shared/                     Modules communs aux deux types de réseaux
│   │   ├── configuration/          Paramètres de l'organisation
│   │   ├── support/                Contact, bugs, limitations
│   │   ├── glossaire.md            Vocabulaire métier Terrilink
│   │   ├── roles.md                Rôles et permissions
│   │   ├── authentication.md       Connexion, mot de passe
│   │   ├── profile.md              Profil membre
│   │   ├── notifications.md        Notifications in-app et email
│   │   ├── messaging.md            Messagerie
│   │   ├── rgpd.md                 Confidentialité, droit à l'oubli
│   │   ├── events.md               Événements
│   │   └── faq.md                  Questions fréquentes
│   └── releases/                   Notes de version de la plateforme
├── screenshots/                    Captures d'écran (organisées par section)
├── assets/                         Logos, CSS, images statiques
├── .github/workflows/              CI/CD : build + déploiement GitHub Pages
├── mkdocs.yml                      Configuration MkDocs
├── requirements.txt                Dépendances Python
└── CHANGELOG.md                    Historique des évolutions de cette documentation
```

---

## Lancer la documentation en local

### Pré-requis

- Python 3.10+
- pip

### Installation

```bash
python -m venv .venv
source .venv/bin/activate          # Linux/macOS
.venv\Scripts\activate             # Windows

pip install -r requirements.txt
```

### Servir en local

```bash
mkdocs serve
```

Le site est accessible sur [http://localhost:8000](http://localhost:8000) avec live reload.

### Construire le site statique

```bash
mkdocs build
```

Le site est généré dans `site/` (ignoré par git).

---

## Conventions d'écriture

### Structure standard d'une page

Chaque page (sauf glossaire, FAQ, release notes) suit cette structure :

```markdown
# Titre

## Objectif
À quoi sert cette fonctionnalité — en 2 phrases courtes.

## Quand utiliser cette fonctionnalité
Cas d'usage réels, exprimés du point de vue de l'utilisateur final.

## Étapes
Procédure pas-à-pas, numérotée, avec captures.

## Résultat attendu
Ce que l'utilisateur doit voir une fois les étapes accomplies.

## Bonnes pratiques
Conseils issus de l'expérience Terrilink (admonition `tip`).

## Points d'attention
Erreurs fréquentes, limitations connues (admonition `warning`).

## FAQ liée
Questions fréquentes en lien direct avec la page.
```

### Admonitions Material

Utiliser les admonitions pour signaler visuellement les éléments importants :

```markdown
!!! tip "Conseil Terrilink"
    Texte du conseil.

!!! warning "Important"
    Avertissement.

!!! example "Cas concret"
    Exemple d'usage.

!!! info "Bon à savoir"
    Information complémentaire.
```

### Ton rédactionnel

- **Phrases courtes**, pas de subordonnées en cascade
- **Vocabulaire métier** (école, alumni, promotion, diaspora) — pas de jargon technique
- **Capture d'écran toutes les 2-3 étapes** pour ancrer visuellement
- **Exemples concrets** avec noms d'écoles fictifs ("École Saint-Joseph", "Diaspora Aveyronnaise")
- **Pas** de "click ici", "le bouton ci-dessous" — préférer "Ouvrez le menu **Paramètres**"

### Conventions screenshots

Chaque image doit être précédée d'un commentaire HTML métadonné, pour audit ultérieur :

```markdown
<!-- SCREENSHOT:
file: alumni/admin/dashboard-overview.png
title: Tableau de bord principal
resolution: 1920x1080
theme: light
updated: 2026-05-16
-->
![Tableau de bord administrateur](../../screenshots/alumni/admin/dashboard-overview.png)
```

Voir [screenshots/README.md](./screenshots/README.md) pour la convention complète.

---

## Versioning

La documentation est versionnée en parallèle de la plateforme Terrilink, via [mike](https://github.com/jimporter/mike).

| Version doc | Version plateforme | État |
|-------------|--------------------|------|
| `1.0` | Terrilink V1.0 (mai 2026) | En cours |

### Publier une nouvelle version

```bash
mike deploy --push --update-aliases 1.0 latest
mike set-default --push latest
```

Le selector de version apparaît automatiquement en haut du site.

---

## Contribution

La documentation est gérée comme du code (doc-as-code) :

1. Créer une branche `doc/<section>-<sujet>`
2. Modifier les `.md` correspondants
3. Ajouter / mettre à jour les captures dans `screenshots/`
4. Ouvrir une Pull Request vers `main`
5. Au merge sur `main`, GitHub Actions déploie automatiquement

Voir [CHANGELOG.md](./CHANGELOG.md) pour l'historique des modifications.

---

## Licence

© 2026 Terrilink. Tous droits réservés.
