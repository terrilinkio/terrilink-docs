# Module Marketplace recruteur

!!! info "Disponibilité"
    Module **en bêta** disponible sur le plan Premium. Activation sur demande pour les tenants pilotes.

## Objectif

Ouvrir votre réseau alumni à des **recruteurs externes** (entreprises, cabinets de recrutement, ETI locales) qui peuvent publier des offres d'emploi ciblées, contre paiement à l'offre. Vos alumni gardent un accès gratuit pour leurs propres publications.

L'enjeu : monétiser un comportement déjà existant (les recruteurs cherchent déjà à toucher vos alumni via LinkedIn ou Indeed) en captant une partie de la valeur **dans votre réseau**, sans perdre la culture communautaire.

## Comment ça marche

### Côté recruteur

- Création d'un compte recruteur dédié, séparé des comptes membres
- Vérification de l'entreprise (SIRET, validation manuelle Terrilink les premiers mois)
- Publication d'une offre avec ciblage (filière, promotion, localisation)
- Paiement à l'offre, validation par l'administrateur du réseau avant publication
- Trust badge sur les annonces des recruteurs vérifiés

### Côté alumni

- Filtre dédié dans le fil d'actualités pour basculer entre publications communautaires et offres d'emploi
- Possibilité de marquer un statut « en recherche » visible des recruteurs uniquement
- Pas de notification push intrusive sur les nouvelles offres

### Côté administrateur

- Validation des recruteurs avant activation
- Validation des offres avant publication (modération a priori)
- Cadence limitée par recruteur (pas de spam)
- Vue des revenus générés sur le réseau

## Modèle économique

| Élément | Détail |
| --- | --- |
| Première offre | Gratuite (test recruteur) |
| Offres suivantes | 100 € HT par offre, valide 30 jours |
| Reversement réseau | À négocier au cas par cas, hors plateforme |
| Plan tenant requis | Premium |

## Différenciation Terrilink

| Comparaison | LinkedIn / Indeed | Marketplace Terrilink |
| --- | --- | --- |
| Audience | Globale, peu qualifiée | Alumni qualifiés du réseau cible |
| Modération | Algorithmique, peu de filtre | Validation humaine de l'administrateur |
| Coût recruteur | Élevé en visibilité | 100 € HT par offre |
| Confiance | Annonceurs anonymes | Trust badge + vérification SIRET |
| Engagement | Application externe | Intégré au fil alumni |

## Configuration et activation

!!! info "Activation Premium"
    Le module est disponible sur le plan **Premium** uniquement. Contactez `contact@terrilink.io` pour activer en bêta sur votre réseau.

## Points d'attention

!!! warning "Pas un ATS"
    Terrilink n'a pas vocation à devenir un système de gestion des candidatures (*Applicant Tracking System*). Les candidatures se font hors plateforme via le lien fourni par le recruteur (mail, formulaire entreprise…). C'est volontaire pour ne pas dériver hors du métier.

!!! warning "Protection de la culture communautaire"
    Pour éviter que le module dérive vers une pollution du fil d'actualités, plusieurs garde-fous sont en place : quotas par recruteur, validation administrateur a priori, filtre dédié dans le fil pour les membres qui ne veulent pas voir les offres.

!!! tip "Stratégie d'amorçage"
    Le succès du module dépend du nombre d'offres disponibles. Au lancement, nous accompagnons les premiers tenants pour pré-sourcer 5 à 10 recruteurs locaux fidèles, le temps que l'amorce s'installe.

## FAQ liée

??? question "Les alumni continuent-ils à publier des offres gratuitement ?"
    Oui, sans changement. Un alumni qui partage une offre de son entreprise dans le fil reste gratuit. Le paiement ne concerne que les comptes **recruteur externe** dédiés.

??? question "Combien d'offres simultanées peut-on avoir par réseau ?"
    Pas de plafond technique. La cadence est limitée par recruteur (1 à 3 offres simultanées selon configuration) pour préserver la lisibilité du fil.

??? question "Comment se passent le paiement et la facturation ?"
    Le paiement est encaissé par Stripe au nom de Terrilink, qui facture le recruteur. Le reversement à l'établissement (s'il est négocié) est traité commercialement hors plateforme. La marketplace Stripe Connect en mode pass-through est sur la roadmap.

---

[Retour à l'index général](../../index.md)
