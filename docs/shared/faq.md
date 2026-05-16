# FAQ générale

## Objectif

Répondre rapidement aux questions les plus fréquentes des administrateurs et des membres. Pour les questions spécifiques à une fonctionnalité, voir la rubrique « FAQ liée » de chaque page.

---

## Accès au réseau et authentification

??? question "Je n'ai jamais reçu mon email d'invitation, que faire ?"
    Vérifiez d'abord vos courriers indésirables (spam). Si l'email n'y est pas, demandez à votre administrateur de relancer l'invitation depuis l'espace **Membres**. Le lien d'activation expire 24 heures après l'envoi.

??? question "J'ai oublié mon mot de passe."
    Sur l'écran de connexion, cliquez sur **Mot de passe oublié**. Saisissez votre adresse email, vous recevrez un lien de réinitialisation valable 1 heure.

??? question "Pourquoi ma connexion expire au bout d'un moment ?"
    Par défaut, votre session reste active 7 jours sur un même appareil. Si vous changez de navigateur, vous devrez vous reconnecter.

??? question "Puis-je me connecter avec Google ou LinkedIn ?"
    Pas en version 1.0. La connexion par identifiants email / mot de passe est la seule méthode disponible. Le single sign-on (SSO) est prévu pour la version 1.2.

## Gestion des membres

??? question "Comment importer ma liste de membres en masse ?"
    Espace Administration → **Membres** → **Importer un fichier CSV**. Le modèle de fichier est téléchargeable depuis cet écran. Voir [Onboarding alumni](../alumni/admin/onboarding.md) pour le détail.

??? question "Un membre m'écrit pour être supprimé du réseau, comment procéder ?"
    Le membre peut le faire lui-même depuis **Mon profil** → **Confidentialité** → **Supprimer mon compte**. Si vous devez le faire pour lui, ouvrez sa fiche dans **Membres** → **Actions** → **Anonymiser**. L'action est irréversible (conformité RGPD article 17).

??? question "Pourquoi certains membres n'apparaissent plus dans la recherche ?"
    Soit ils ont demandé leur suppression (anonymisation RGPD), soit ils ont masqué leur profil dans leurs réglages de confidentialité. Les administrateurs voient toujours les comptes anonymisés en tant qu'« Utilisateur supprimé ».

## Publications et fil d'actualités

??? question "Ma publication n'est vue par personne, pourquoi ?"
    Vérifiez votre ciblage. Avec un ciblage trop restrictif (ex : pays + filière + promotion), il est possible qu'aucun membre ne corresponde aux critères. Voir [Publications et ciblage](../alumni/admin/publications.md) pour la sémantique OU/ET.

??? question "Puis-je programmer une publication ?"
    La programmation de publications est prévue pour la version 1.1. En version 1.0, les publications sont diffusées immédiatement après envoi.

??? question "Comment épingler une publication importante en tête de fil ?"
    Sur la publication, cliquez sur le menu **…** → **Épingler**. Seuls les administrateurs et modérateurs peuvent épingler. Une seule publication épinglée à la fois par réseau.

??? question "Comment supprimer un commentaire inapproprié ?"
    Survolez le commentaire, cliquez sur le menu **…** → **Supprimer**. Les administrateurs et modérateurs voient l'action sur tous les commentaires ; un membre voit l'action uniquement sur les siens.

## Confidentialité et données

??? question "Mes données sont-elles hébergées en France ?"
    Oui. Les serveurs principaux de Terrilink sont hébergés en France (OVH Strasbourg / Gravelines). Les sauvegardes chiffrées sont répliquées dans un second centre européen. Voir [RGPD](rgpd.md).

??? question "Combien de temps les données sont-elles conservées ?"
    Tant que le compte est actif. À la suppression d'un compte, les données personnelles sont anonymisées sous 30 jours conformément au RGPD. Les sauvegardes sont purgées après 90 jours.

??? question "Puis-je exporter toutes les données de mon réseau ?"
    Oui. Espace Administration → **Données** → **Exporter au format CSV**. L'export inclut la liste des membres, les publications et les statistiques agrégées.

## Facturation et abonnement

??? question "Comment voir ma facture ?"
    Espace Administration → **Abonnement** → **Historique de facturation**. Toutes les factures émises depuis votre souscription sont disponibles au téléchargement PDF.

??? question "Puis-je changer de plan en cours d'année ?"
    Oui, à tout moment. Le passage à un plan supérieur prend effet immédiatement (prorata calculé automatiquement). Le passage à un plan inférieur prend effet au prochain renouvellement.

??? question "Que se passe-t-il si je résilie ?"
    Votre réseau reste accessible jusqu'à la fin de la période payée. Au-delà, l'accès est suspendu pendant 90 jours (mode lecture seule, possibilité de réactiver). Après 90 jours, les données sont supprimées de manière irréversible. Un export complet vous est proposé avant suppression.

## Support et incidents

??? question "Comment signaler un bug ?"
    Voir [Signaler un bug](support/reporting-a-bug.md). Vous pouvez utiliser le formulaire intégré ou écrire à `support@terrilink.io`.

??? question "Le site est en panne, où puis-je vérifier ?"
    Notre page de statut public est à venir. En cas d'incident, contactez `support@terrilink.io`. Les administrateurs sont notifiés par email lors d'incidents majeurs.

??? question "Quel est le délai de réponse du support ?"
    24h ouvrées en plan Standard, 4h ouvrées en plan Premium, 1h en plan Enterprise pour les incidents critiques.

??? question "Puis-je demander une fonctionnalité ?"
    Oui ! Voir [Contact support](support/contact-support.md). Toutes les demandes sont étudiées et priorisées avec les autres clients.

---

[Retour à l'index général](../index.md)
