# Politique de version

## Objectif

Comprendre comment Terrilink publie ses mises à jour, ce qui change pour vous à chaque version, et comment être informé.

## Cadence de publication

Terrilink applique le standard *semantic versioning* sur le format **MAJOR.MINOR.PATCH**.

| Type | Fréquence | Exemple | Impact pour vous |
| --- | --- | --- | --- |
| Patch (correctifs) | À la demande | 1.0.1, 1.0.2 | Aucun — déployé automatiquement, transparent |
| Mineure (nouvelles fonctionnalités) | Trimestrielle | 1.1, 1.2, 1.3 | Email récapitulatif aux administrateurs, formation optionnelle |
| Majeure (changements structurants) | Annuelle au maximum | 2.0 | Communication anticipée 3 mois avant, accompagnement |

## Notifications de version

À chaque version mineure ou majeure, les administrateurs reçoivent :

1. Un email récapitulatif 7 jours avant la mise à jour
2. Un email de confirmation après déploiement
3. Un encadré informatif dans le tableau de bord pendant 14 jours

Les patches sont déployés sans notification (sauf si un comportement utilisateur change).

## Compatibilité

- **Données** : nous garantissons que vos données restent accessibles entre versions. Aucune migration côté client n'est jamais demandée.
- **URLs et liens externes** : les URLs des profils, publications et événements restent stables. Les liens partagés en dehors de Terrilink (emails, réseaux sociaux) continuent de fonctionner.
- **Navigateurs supportés** : Chrome, Firefox, Safari et Edge en version N-1 minimum (deux dernières versions stables).

## Fenêtres de maintenance

- Les déploiements se font de préférence le mardi entre 22h et minuit (heure de Paris).
- Une fenêtre de maintenance programmée est communiquée 48h à l'avance.
- Durée typique d'une indisponibilité programmée : 5 à 15 minutes (mode lecture seule).

## Versions supportées

Nous maintenons la version courante et la version précédente avec correctifs de sécurité. Au-delà, la mise à jour est requise pour bénéficier du support standard.

## Roadmap publique

Les grandes orientations produit sont partagées avec les clients sur demande à `produit@terrilink.io`. Une roadmap publique sera mise en ligne ultérieurement.

---

[Retour à l'index général](../../index.md) — [Voir la version 1.0](../../releases/v1.0.md)
