# Module Network Radar

!!! info "Disponibilité"
    Module **en développement actif**. Disponible en bêta pour les clients partenaires de lancement, ouverture commerciale progressive.

## Objectif

Activer le réseau alumni comme **outil de prospection ciblée** : identifier rapidement quels alumni travaillent dans une entreprise, un secteur ou un poste précis, et révéler les chemins relationnels pour entrer en contact avec un décisionnaire.

Là où un annuaire alumni classique répond à *« qui est dans ma promo ? »*, Network Radar répond à *« quel chemin emprunter pour atteindre la DRH de Carrefour ? »*.

## Comment ça marche

Network Radar exploite trois sources de données déjà présentes dans Terrilink :

1. **Le graphe alumni → entreprise** : qui travaille où, à quel poste, depuis quand
2. **Les liens de promotion** : qui était dans la même promo / filière / campus
3. **Le statut de mentorat actif** : qui est prêt à parler au nom du réseau

Le module croise ces dimensions pour produire deux types de réponses :

- **Recherche entreprise** : « Quels alumni travaillent chez TotalEnergies ? » → liste, postes, ancienneté
- **Recherche décisionnelle** : « Comment atteindre quelqu'un de la direction commerciale chez TotalEnergies ? » → suggestions d'alumni intermédiaires, avec le degré de connexion (même promo, même filière, mentor actif)

## Cas d'usage typiques

### Pour un service relations entreprises

- Identifier des contacts internes dans une entreprise visée pour un partenariat de taxe d'apprentissage
- Préparer un événement professionnel ciblé sur un secteur (énergie, santé, banque)
- Mesurer la présence alumni dans le bassin d'emploi régional

### Pour le bureau alumni

- Recruter des intervenants pour une conférence métier
- Identifier des mentors potentiels dans un domaine précis
- Cartographier les alumni d'une promotion sortante

### Pour un alumni

- Demander conseil à un pair dans l'entreprise qu'il vise
- Identifier qui a fait la même reconversion que lui
- Trouver un mentor sur un parcours métier spécifique

## Différenciation Terrilink

| Comparaison | Annuaire alumni classique | Network Radar |
| --- | --- | --- |
| Recherche par entreprise | Liste plate | Liste + chemins d'introduction |
| Recherche par poste | Champ texte libre | Champs normalisés + suggestions |
| Confidentialité | Tout-ou-rien | Granulaire (l'alumni choisit ce qu'il expose) |
| Engagement | Statique | Notifie l'alumni s'il est cherché et accepte d'être contacté |

C'est un atout structurel : aucun concurrent généraliste du marché alumni français ne propose cette boucle « recherche → chemin → mise en relation tracée ».

## Configuration et activation

!!! info "Page en cours de rédaction"
    Le détail de l'activation, des permissions et des paramètres de confidentialité sera ajouté à la sortie du module en disponibilité générale.

## Points d'attention

!!! warning "Confidentialité et consentement"
    Les alumni gardent à tout moment le contrôle sur leur exposition dans Network Radar : opt-in explicite à l'activation, possibilité de masquer leur entreprise actuelle, refus possible des sollicitations même internes au réseau.

!!! warning "Qualité des données employeurs"
    L'efficacité du module dépend de la mise à jour des profils alumni (entreprise actuelle, poste, secteur). La [check-list 30 jours](../../alumni/admin/checklist-30-jours.md) intègre une campagne de relance « mettez à jour votre situation pro » à J+45.

## FAQ liée

??? question "Qui peut faire une recherche sur Network Radar ?"
    Par défaut, seuls les administrateurs et le service relations entreprises de l'établissement. L'extension aux membres alumni (« demander une introduction à un pair ») est en bêta restreinte.

??? question "Un alumni peut-il refuser d'apparaître dans les résultats ?"
    Oui, à tout moment depuis son profil → Confidentialité → Visibilité Network Radar.

??? question "Quelle est la fréquence de mise à jour du graphe ?"
    Le graphe est mis à jour en temps réel à chaque modification de profil alumni. Pas de batch nocturne.

---

[Retour à l'index général](../../index.md)
