# Captures d'écran

Ce dossier contient toutes les captures d'écran référencées dans la documentation. Il est organisé miroir de la structure `docs/` :

```
screenshots/
├── alumni/
│   └── admin/
│       ├── onboarding-step-1.png
│       ├── dashboard-overview.png
│       └── …
├── diaspora/
│   └── admin/
│       └── …
└── shared/
    └── …
```

## Convention de nommage

- `kebab-case` uniquement, sans accents ni espaces
- Format : `<contexte>-<action>-<numéro>.png` (ex : `onboarding-step-3.png`, `feed-targeting-modal.png`)
- Préférer PNG pour les captures d'interface, JPG uniquement pour les photos

## Métadonnées (dans la page Markdown)

Chaque capture est précédée d'un bloc de métadonnées en commentaire HTML :

```markdown
<!-- SCREENSHOT:
file: alumni/admin/dashboard-overview.png
title: Tableau de bord administrateur
resolution: 1920x1080
theme: light
updated: 2026-05-16
-->
![Tableau de bord administrateur](../screenshots/alumni/admin/dashboard-overview.png)
```

Ces métadonnées permettent :

- de retrouver rapidement quelles captures doivent être refaites lors d'une refonte UI ;
- de vérifier la cohérence visuelle (thème, résolution) ;
- d'auditer la fraîcheur de la documentation.

## Standards de capture

| Élément | Spécification |
| --- | --- |
| Résolution | 1920x1080 (desktop), 390x844 (mobile iPhone 14) |
| Format | PNG (compression sans perte) |
| Navigateur | Chrome ou Firefox (interface plus neutre que Safari) |
| Thème | Clair par défaut, sombre uniquement si la fonctionnalité diffère |
| Données affichées | Données factices ou tenant de démonstration (jamais de production réelle) |
| Annotations | Encadrés rouges ou flèches uniquement si nécessaire, via Excalidraw ou Cleanshot |

## Données affichées

!!! warning "Pas de données réelles"
    N'utilisez jamais de captures contenant des données de clients en production. Les exemples doivent provenir du tenant de démonstration ou être anonymisés.

## Outils recommandés

- **Capture** : Cleanshot X (macOS), ShareX (Windows), Flameshot (Linux)
- **Annotation** : Excalidraw, Cleanshot intégré
- **Compression** : TinyPNG (en ligne) ou ImageOptim (macOS)

Cible : moins de 300 Ko par capture après compression.

---

[Retour à l'index général de la documentation](../docs/index.md)
