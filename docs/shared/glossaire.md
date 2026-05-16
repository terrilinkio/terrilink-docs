# Glossaire métier

Ce glossaire définit les termes employés dans la documentation Terrilink. Il est commun aux réseaux alumni et diaspora, et précise les nuances spécifiques à chaque contexte.

---

## Administrateur

Personne disposant des droits de configuration et de modération sur un réseau. Les administrateurs voient l'ensemble des contenus, peuvent valider ou suspendre des membres, modérer le fil d'actualités, configurer les modules et le branding. Au moins un administrateur est désigné lors de la création du réseau ; d'autres peuvent être ajoutés ensuite.

Voir aussi : [Rôles et permissions](roles.md).

---

## Alumni

Désigne un ancien étudiant ayant terminé son cursus dans l'établissement de référence. Sur Terrilink, le statut **alumni** est un type de membre attribué automatiquement à la fin du cursus (cf. lifecycle automatique) ou manuellement par l'administrateur.

S'oppose à :

- **Étudiant** : membre encore en cours de formation
- **Membre** : statut neutre par défaut
- **Enseignant** : personnel pédagogique de l'établissement
- **Entreprise partenaire** : contact externe (partenariat, sponsor)

---

## Campus

Site géographique d'un établissement multi-sites. Un programme peut être enseigné sur un ou plusieurs campus, et un alumni est rattaché au(x) campus où il a effectivement étudié.

Exemple : un campus Paris, un campus Lyon, un campus Bordeaux pour un même groupe d'écoles.

---

## Chapitre (diaspora)

Sous-groupe d'une diaspora, organisé par pays de résidence, ville ou thématique. Permet une animation locale autonome au sein d'un réseau diaspora plus large.

Exemple : « Chapitre Aveyronnais à Londres », « Chapitre Bretons en Allemagne ».

---

## Diaspora

Réseau d'individus partageant une origine territoriale ou culturelle commune, généralement répartis dans plusieurs pays. Sur Terrilink, une diaspora est un type d'organisation distinct des écoles alumni.

Le ciblage des communications côté diaspora se fait par **pays de résidence**.

---

## Filière / Programme

Cursus pédagogique proposé par un établissement. Un alumni est rattaché à au moins une filière. Le terme « filière » est plus fréquent dans les BTS et formations courtes ; « programme » dans les écoles d'ingénieurs et de commerce.

Exemples : BTS Informatique, Master Marketing Digital, Licence pro Tourisme.

---

## Membre

Toute personne inscrite et validée sur un réseau Terrilink. Un membre est rattaché à exactement une organisation (un tenant).

Selon le contexte :

- **Alumni** : ancien étudiant diplômé
- **Diaspora** : adhérent d'une association territoriale

Le terme **« membre »** peut aussi désigner un *type de membre* spécifique sur un réseau alumni (neutre, ni étudiant ni alumni — typiquement un partenaire institutionnel).

---

## Modérateur

Rôle intermédiaire entre administrateur et membre. Un modérateur peut animer le fil d'actualités, supprimer des contenus inappropriés et valider des inscriptions, mais ne peut pas modifier les paramètres globaux du réseau (branding, modules, domaine).

Voir : [Rôles et permissions](roles.md).

---

## Organisation

Entité cliente de Terrilink (école, université, association diaspora, fondation). Une organisation possède son propre espace, sa propre base de membres, ses propres paramètres. Synonyme technique : **tenant**.

---

## Promotion

Sur un réseau alumni, désigne l'année de diplôme d'une cohorte d'étudiants. Une promotion regroupe tous les alumni ayant obtenu leur diplôme la même année. Le ciblage par promotion est l'une des dimensions clés du fil d'actualités alumni.

Exemple : « Promo 2024 BTS Informatique ».

---

## Publication ciblée

Post du fil d'actualités diffusé à une audience précise plutôt qu'à l'ensemble du réseau (broadcast).

Sémantique du ciblage Terrilink :

- **OU** au sein d'une catégorie : plusieurs valeurs cochées = union (France + Espagne = membres dans l'un OU l'autre)
- **ET** entre catégories : plusieurs catégories cochées = intersection (France + BTS Info = membres en France ET en BTS Info)

Côté alumni, 5 dimensions disponibles : pays, programme, campus, promotion, type de membre.
Côté diaspora, 1 dimension disponible : pays de résidence.

Voir : [Publications et ciblage (alumni)](../alumni/admin/publications.md) — [Ciblage par pays (diaspora)](../diaspora/admin/country-targeting.md).

---

## Tenant

Terme technique désignant une organisation cliente de Terrilink, à laquelle est associée une base de données isolée. Un tenant = une école ou une diaspora. Synonyme métier : **organisation**.

L'isolation tenant garantit qu'aucune donnée d'une organisation cliente n'est jamais visible par une autre.

---

## Territoire d'origine

Pour un réseau diaspora, désigne le territoire de référence commun aux adhérents : un département, une région, un pays, une communauté culturelle. Le territoire d'origine conditionne le centrage cartographique et l'identité visuelle du réseau.

Exemples : Aveyron, Bretagne, Corse, République Démocratique du Congo, Vietnam.

---

## Type de membre

Catégorisation métier d'un membre, distincte de son rôle de permission. Sur un réseau alumni : étudiant, alumni, membre, enseignant, entreprise partenaire. Sur un réseau diaspora : membre, contact local.

Le type est utilisé pour le ciblage des publications, l'éligibilité au mentorat, et l'affichage des badges.

---

[Retour à l'index général](../index.md)
