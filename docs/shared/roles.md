# Rôles et permissions

## Objectif

Comprendre la hiérarchie des rôles dans Terrilink, ce que chaque profil peut faire, et comment attribuer les bons droits aux bonnes personnes.

## Quand utiliser cette page

- Avant de désigner un nouvel administrateur ou modérateur
- Pour comprendre pourquoi un membre voit ou ne voit pas une fonctionnalité
- Pour préparer la passation d'un réseau à un nouveau responsable

## Vue d'ensemble des rôles

Terrilink distingue deux notions complémentaires :

- Le **rôle de permission** : ce que la personne *a le droit de faire* dans le réseau (administrer, modérer, consulter…).
- Le **type de membre** : la nature métier de la personne (étudiant, alumni, membre, enseignant, entreprise partenaire). Voir [Glossaire — Type de membre](glossaire.md#type-de-membre).

Un même utilisateur a **un seul rôle de permission** et **un seul type de membre**. Les deux dimensions sont indépendantes : un alumni peut être administrateur, un étudiant peut être modérateur, etc.

## Les rôles de permission

### Super administrateur Terrilink

Personnel de Terrilink uniquement. N'apparaît pas dans la liste des membres du réseau et ne peut pas publier en son nom dans un fil d'actualités.

| Peut | Ne peut pas |
| --- | --- |
| Accéder à plusieurs organisations pour assistance technique | Modifier des données métier sans accord explicite du client |
| Diagnostiquer un incident en production | Voir les messages privés entre membres |
| Réinitialiser un accès administrateur en cas de perte | Publier dans le fil au nom d'un membre |

!!! info "Mode opérateur"
    Lorsqu'un membre du support Terrilink intervient sur votre réseau, l'action est tracée dans le journal d'audit avec la mention `terrilink_operator`. Vous pouvez nous demander l'historique à tout moment.

### Administrateur

Responsable opérationnel du réseau côté client. Au moins un administrateur est désigné lors de la création du réseau, mais nous recommandons d'en avoir **au minimum deux** pour la continuité de service.

| Peut | Ne peut pas |
| --- | --- |
| Configurer le branding, le domaine personnalisé, les modules | Voir le contenu des messages privés entre membres |
| Inviter, valider, suspendre, supprimer des membres | Modifier la facturation (réservé au signataire principal) |
| Modérer le fil d'actualités, supprimer des publications | Accéder aux données d'une autre organisation |
| Désigner d'autres administrateurs et modérateurs | |
| Exporter les données du réseau au format CSV | |
| Accéder aux statistiques globales | |

!!! tip "Bonne pratique"
    Désignez au moins deux administrateurs, idéalement avec des fonctions différentes (ex : un côté direction, un côté communication). Cela évite le risque de blocage si l'un est indisponible.

### Modérateur

Rôle intermédiaire entre administrateur et membre. Adapté pour les responsables de communication, animateurs de communauté ou ambassadeurs alumni qui ont besoin de gérer le contenu sans accéder aux paramètres globaux.

| Peut | Ne peut pas |
| --- | --- |
| Publier dans le fil d'actualités et fixer des publications | Modifier le branding, le domaine ou les modules |
| Modérer les commentaires et supprimer du contenu inapproprié | Désigner d'autres administrateurs ou modérateurs |
| Valider ou refuser une demande d'inscription | Exporter la base de membres |
| Répondre aux signalements de premier niveau | Accéder à la facturation |

!!! example "Exemple d'usage"
    Sur un réseau alumni d'école d'ingénieurs, le service communication désigne deux modérateurs (une chargée de comm et un alumni ambassadeur) pour animer le fil au quotidien. La direction garde le rôle administrateur pour les paramètres stratégiques.

### Membre

Profil standard de l'écrasante majorité des utilisateurs. Reçoit l'accès au réseau après validation.

| Peut | Ne peut pas |
| --- | --- |
| Compléter son profil et le tenir à jour | Voir les profils masqués par d'autres membres |
| Publier dans le fil d'actualités (selon réglages du réseau) | Modérer les publications d'autrui |
| Commenter, réagir, signaler une publication | Voir la liste complète des emails des membres |
| Échanger en messagerie privée avec d'autres membres | Accéder aux statistiques du réseau |
| S'inscrire à des événements | Configurer quoi que ce soit |
| Demander la suppression de son compte (RGPD) | |

### Recruteur (à venir)

Profil spécifique au module Carrière premium. Compte séparé des membres, dédié aux entreprises et cabinets qui publient des offres d'emploi payantes sur le réseau.

!!! info "Module premium"
    Ce rôle n'est disponible que sur les organisations ayant souscrit au module Recruteur. Voir [Modules activables](configuration/modules.md).

## Matrice de décision rapide

| Cas | Rôle à attribuer |
| --- | --- |
| Direction qui paramètre le réseau et facture | Administrateur |
| Service communication qui anime le fil | Modérateur |
| Alumni ambassadeur de promotion | Modérateur ou Membre |
| Étudiant en cours de cursus | Membre |
| Enseignant relais auprès des promotions | Membre |
| Entreprise partenaire ponctuelle | Membre |
| Service IT qui dépanne sans gérer le contenu | Administrateur (à révoquer après usage) |

## Changer un rôle

1. Espace Administration → **Membres**.
2. Cliquer sur le membre concerné, puis sur **Modifier le rôle**.
3. Sélectionner le nouveau rôle, confirmer.
4. Le membre reçoit une notification automatique.

<!-- TODO capture: shared/admin/role-change-modal.png — modale de changement de rôle -->

## Points d'attention

!!! warning "Pas d'auto-rétrogradation"
    Un administrateur ne peut pas se retirer son propre rôle administrateur s'il est le dernier administrateur du réseau. Désignez d'abord un second administrateur, puis demandez à ce dernier de modifier votre rôle.

!!! warning "Suppression d'un administrateur"
    Supprimer un compte administrateur supprime aussi son historique de publications (anonymisation RGPD). Préférez la rétrogradation en membre puis la suspension, sauf demande RGPD explicite.

!!! tip "Audit régulier"
    Tous les six mois, vérifiez la liste des administrateurs et modérateurs et révoquez les accès devenus inutiles (changement de poste, départ, fin de mission ponctuelle).

## FAQ liée

??? question "Combien d'administrateurs maximum puis-je avoir ?"
    Il n'y a pas de limite technique. Nous recommandons toutefois 2 à 4 administrateurs pour garder une gouvernance lisible.

??? question "Un membre peut-il avoir plusieurs rôles ?"
    Non. Chaque membre a un seul rôle de permission à la fois. Il peut en revanche cumuler avec n'importe quel type de membre.

??? question "Si je suspend un administrateur, perd-il son rôle ?"
    La suspension bloque l'accès au réseau. Le rôle reste enregistré pour le moment où vous réactivez le compte. Pour révoquer définitivement, modifiez d'abord le rôle, puis suspendez.

??? question "Peut-on définir des rôles personnalisés ?"
    Pas en version 1.0. Les rôles personnalisés font partie de la feuille de route enterprise.

??? question "Les enseignants ont-ils automatiquement un rôle particulier ?"
    Oui. Un membre dont le type est « enseignant » dispose automatiquement de droits d'administration sur son réseau. Voir [Glossaire — Type de membre](glossaire.md#type-de-membre).

---

[Retour à l'index général](../index.md) — [Glossaire](glossaire.md)
