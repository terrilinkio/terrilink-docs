# Onboarding administrateur — Réseau Alumni

## Objectif

Cette page guide la première connexion d'un administrateur de réseau alumni sur Terrilink, depuis la réception de l'email de bienvenue jusqu'aux premiers paramètres essentiels à valider avant d'ouvrir l'accès aux membres.

## Quand utiliser cette fonctionnalité

L'onboarding administrateur intervient au **tout début** de la vie de votre réseau alumni :

- L'organisation vient de souscrire un abonnement Terrilink
- Vous avez été désigné(e) administrateur(trice) par votre établissement
- Vous recevez un email de Terrilink avec un lien d'activation de votre compte

!!! info "Bon à savoir"
    L'onboarding administrateur ne se fait qu'**une seule fois**. Les administrateurs ajoutés ultérieurement (voir [Permissions](../../shared/configuration/permissions.md)) suivront un parcours simplifié sans configuration initiale.

## Étapes

### 1. Recevoir l'email d'invitation

Après la création de votre organisation par notre équipe, vous recevez un email intitulé **« Bienvenue sur \<nom-de-votre-école\> — Configurez votre mot de passe »**.

<!-- TODO capture: alumni/admin/01-welcome-email.png — email reçu en boîte mail, objet visible, bouton "Configurer mon mot de passe" -->

Cet email contient un lien personnalisé valable **24 heures**. Si vous l'ouvrez après expiration, demandez un nouveau lien via la page de connexion (« Mot de passe oublié »).

### 2. Définir votre mot de passe

Cliquez sur le bouton **Configurer mon mot de passe**. Vous arrivez sur la page de définition du mot de passe.

<!-- TODO capture: alumni/admin/02-setup-password.png — formulaire avec mot de passe + confirmation + critères de complexité affichés -->

Votre mot de passe doit contenir :

- Au moins 8 caractères
- Une majuscule
- Une minuscule
- Un chiffre

Une fois validé, vous êtes automatiquement connecté(e) à votre espace administrateur.

### 3. Compléter votre profil personnel

Au premier login, un assistant vous demande de compléter votre profil personnel en trois étapes : informations personnelles, localisation et activité professionnelle, conditions générales.

<!-- TODO capture: alumni/admin/03-profile-wizard-step1.png — wizard étape 1 (prénom/nom/email/photo + sélecteur "Vous êtes") -->

!!! tip "Conseil Terrilink"
    Renseignez votre profil avec soin : il est visible par tous les membres de votre réseau. Pour un administrateur, nous recommandons de choisir le type **Membre** (et non Étudiant ou Alumni) pour clarifier votre rôle institutionnel.

### 4. Découvrir le tableau de bord

Une fois le profil validé, vous arrivez sur le tableau de bord administrateur.

<!-- TODO capture: alumni/admin/04-dashboard-overview.png — dashboard d'accueil (sidebar + compteur + bandeau "Configuration incomplète") -->

Les éléments principaux à identifier :

- **Sidebar gauche** : navigation entre les sections (Fil d'actualités, Membres, Annuaire, Événements, Carte, Configuration)
- **Compteur de membres** : nombre de membres réels (les comptes système ne sont pas comptabilisés)
- **Bandeau de configuration** : alerte rouge ou orange si des paramètres essentiels manquent (logo, école de référence, filières)

### 5. Configurer l'identité visuelle

Rendez-vous dans **Configuration → Personnalisation** pour ajouter le logo de votre école, choisir la palette de couleurs et personnaliser l'apparence de votre espace.

Voir la documentation détaillée : [Personnalisation et branding](../../shared/configuration/branding.md).

### 6. Renseigner le référentiel école

Avant d'inviter les premiers membres, configurez le référentiel pédagogique de votre établissement :

- **École de référence** : votre établissement principal
- **Programmes et filières** : la liste des cursus que vous proposez
- **Campus** : si vous avez plusieurs sites

Voir : [Configuration des écoles et programmes](schools.md).

### 7. Inviter les premiers administrateurs et modérateurs (optionnel)

Si vous souhaitez partager l'administration avec des collègues, ajoutez-les depuis **Membres → Ajouter un membre**, puis attribuez-leur le rôle administrateur ou modérateur.

Voir : [Rôles et permissions](../../shared/roles.md).

## Résultat attendu

À la fin de cette procédure, vous devez avoir :

- ✅ Un mot de passe sécurisé et un profil personnel renseigné
- ✅ Un accès au tableau de bord administrateur
- ✅ Le logo de votre école affiché dans l'en-tête
- ✅ L'école de référence et au moins une filière configurées
- ✅ Une vision claire des prochaines étapes (voir [Check-list 30 premiers jours](checklist-30-jours.md))

<!-- TODO capture: alumni/admin/05-dashboard-ready.png — dashboard sans bandeau d'alerte rouge, logo école visible -->

## Bonnes pratiques

!!! tip "Conseil Terrilink"
    Avant d'inviter massivement vos alumni, **testez la plateforme avec 5 à 10 collègues de confiance**. Ils pourront remonter les premières incohérences (libellés de filières, photo de couverture, ton des emails) et vous éviterez de réparer des paramètres avec un public déjà connecté.

!!! tip "Conseil Terrilink"
    Renseignez votre référentiel **école → filière → campus** avant le premier import de membres. Sinon vos alumni devront ressaisir manuellement leur cursus, ce qui crée des données polluées (typos, libellés divergents).

!!! tip "Conseil Terrilink"
    Désignez **au moins deux administrateurs** dans votre établissement. Si la personne unique chargée du réseau alumni est absente (vacances, départ), vous évitez le risque de blocage.

## Points d'attention

!!! warning "Le lien d'activation expire en 24 heures"
    Si vous n'avez pas activé votre compte dans les 24 heures suivant la réception de l'email, le lien devient invalide. Demandez un nouveau lien depuis la page de connexion (« Mot de passe oublié »).

!!! warning "Vérifiez vos spams"
    L'email de bienvenue est envoyé depuis `noreply@terrilink.io`. Selon votre messagerie, il peut être classé en spam ou en « Promotions ». Pensez à ajouter cette adresse à vos contacts pour les communications futures.

!!! warning "Pas de personnalisation avant les membres"
    Le logo, les couleurs et le nom affiché doivent être configurés **avant** d'inviter les premiers membres. Les emails de bienvenue envoyés aux membres reprennent ces paramètres au moment de l'envoi : un email envoyé sans logo restera sans logo dans les boîtes de réception.

## FAQ liée

??? question "Je n'ai pas reçu l'email d'activation. Que faire ?"
    Vérifiez d'abord vos spams. Si l'email n'est pas dans votre boîte, contactez l'équipe Terrilink à `contact@terrilink.io` en précisant le nom de votre organisation. Nous renvoyons un nouveau lien sous 24 heures ouvrées.

??? question "Puis-je changer l'administrateur principal après coup ?"
    Oui. Un administrateur peut désigner un autre membre comme administrateur depuis **Membres → \<le membre\> → Ajouter admin**. Si vous souhaitez retirer vos propres droits, il faut qu'un autre administrateur le fasse — vous ne pouvez pas vous rétrograder vous-même.

??? question "Plusieurs personnes peuvent-elles être administrateurs en même temps ?"
    Oui, sans limite. Nous recommandons d'avoir au minimum deux administrateurs pour éviter tout blocage en cas d'absence.

??? question "Combien de temps prend la configuration initiale ?"
    Comptez environ **30 à 45 minutes** pour une configuration soignée : profil, branding, référentiel école, premiers programmes. Le reste (import des membres, animation du fil, premiers événements) se fait dans les jours suivants. Voir la [check-list des 30 premiers jours](checklist-30-jours.md).

??? question "Que se passe-t-il si je ne configure pas l'école de référence ?"
    Vos membres pourront s'inscrire mais seront orientés vers la saisie manuelle de leur cursus, sans autocomplétion. Cela génère des données hétérogènes (BTS Info / B.T.S Informatique / Bts informatique = trois entrées différentes). Nous recommandons fortement de configurer le référentiel **avant** la première invitation.

---

[← Retour à l'index Alumni](../index.md) — [Suite : Check-list 30 premiers jours →](checklist-30-jours.md)
