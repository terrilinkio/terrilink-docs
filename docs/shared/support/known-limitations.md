# Limitations connues

## Objectif

Lister de manière transparente les limites volontaires ou techniques connues de la plateforme dans sa version actuelle, pour qu'aucun administrateur ne soit pris au dépourvu.

## Limitations fonctionnelles — version 1.0

### Authentification

- Pas de single sign-on (SSO SAML / OAuth) — prévu en version 1.2.
- Pas de connexion par Google ou LinkedIn — non prévu pour l'instant (positionnement réseau professionnel sérieux).
- Sessions de 7 jours maximum sur un même appareil.

### Publications et fil d'actualités

- Pas de programmation différée (publier à une date future) — prévue en version 1.1.
- Pas de brouillons partagés à plusieurs administrateurs — prévu en version 1.2.
- Maximum 5 dimensions de ciblage simultanées par publication.
- Pas de modification d'une publication après envoi (uniquement suppression et republication).

### Membres et permissions

- Pas de rôles personnalisés au-delà des 4 rôles standards (admin / modérateur / membre / recruteur).
- Pas de gestion par équipe (sous-administrations par département).
- Maximum 50 000 membres par réseau en version 1.0 (limite technique levée en version 1.1).

### Mobile

- Pas d'application mobile native (iOS / Android) — version PWA disponible, native sur la roadmap 2027.
- Les notifications push mobiles sont limitées aux navigateurs supportant le standard Web Push (Chrome, Edge, Firefox ; partiel sur Safari iOS).

### Intégrations

- Pas d'API publique en version 1.0 — accessible aux clients Enterprise sur demande, déploiement public prévu en 1.3.
- Pas de connecteur Zapier / Make en version 1.0.
- Pas d'export en temps réel vers un CRM tiers (Salesforce, HubSpot…) — prévu via l'API publique.

## Limitations techniques

- Taille maximale d'un fichier joint : 25 Mo.
- Taille maximale d'une photo de profil : 5 Mo.
- Nombre maximal de destinataires d'une publication ciblée : illimité (la diffusion est asynchrone).
- Conservation des messages privés : illimitée tant que le compte est actif.

## Pour aller plus loin

- [Politique de version](release-policy.md)
- [Contact support](contact-support.md) pour signaler une limitation gênante

---

[Retour à l'index général](../../index.md)
