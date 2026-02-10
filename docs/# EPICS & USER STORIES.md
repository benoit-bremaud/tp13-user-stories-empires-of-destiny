# EPICS & USER STORIES


## ÉTAPE 1 — Extraction des fonctionnalités

Feature :

- Démarrer une partie à l’âge de pierre
- Faire évoluer une civilisation sur plusieurs ères historiques
- Accéder à 4 ères distinctes (âge de pierre, bronze, fer, médiéval)
- Ressentir une rupture forte lors du changement d’ère
- Accumuler des ressources classiques (bois, pierre, nourriture, or)
- Accumuler une ressource abstraite : la connaissance
- Débloquer une nouvelle ère via des conditions non automatiques
- Construire des bâtiments spécifiques pour progresser
- Rechercher des technologies
- Gérer une économie tribale puis structurée
- Découvrir, collecter et stocker des artefacts culturels
- Obtenir des artefacts via exploration
- Obtenir des artefacts via commerce
- Obtenir des artefacts via pillage
- Appliquer des bonus uniques liés aux artefacts
- Construire des bâtiments librement sur la carte
- Prendre en compte l’environnement dans la construction
- Augmenter la productivité des fermes près des fleuves
- Améliorer la défense des forteresses en hauteur
- Optimiser les carrières proches de falaises
- Planifier l’urbanisme de la civilisation
- Recruter des unités militaires selon l’ère
- Faire évoluer les types d’unités au fil des âges
- Gérer des combats en temps réel
- Intégrer le terrain dans les combats
- Intégrer la météo dans les combats
- Utiliser des formations militaires
- Recruter des généraux
- Assigner des généraux à des armées
- Bénéficier de compétences propres aux généraux
- Prendre en compte les traits psychologiques des généraux
- Déclarer la guerre à d’autres civilisations
- Éviter la guerre par des moyens diplomatiques
- Former des alliances militaires
- Signer des traités de paix
- Mettre en place des pactes de non-agression
- Négocier des accords complexes avec contreparties
- Mettre en place des échanges commerciaux entre civilisations
- Définir un panthéon religieux
- Choisir des divinités tutélaires
- Créer des traditions culturelles
- Promulguer des lois impériales
- Modifier le gameplay selon l’idéologie choisie
- Orienter une civilisation vers un style militariste, marchand ou théocratique
- Jouer des campagnes scénarisées historiques
- Atteindre des objectifs narratifs
- Jouer en mode Sandbox
- Construire un empire sans contrainte scénaristique
- Jouer en multijoueur compétitif
- Jouer en multijoueur coopératif
- S’allier contre des menaces systémiques
- Gérer des invasions barbares
- Faire face à des catastrophes naturelles
- Gérer des crises économiques
- Construire des merveilles du monde
- Obtenir des effets persistants entre les parties
- Créer un héritage civilisationnel
- Accéder à une carte stratégique détaillée
- Visualiser les ressources et la démographie
- Planifier des actions militaires
- Gérer les relations diplomatiques via l’interface

## ÉTAPE 2 — EPICS (macro-fonctionnalités)

### EPIC 1 — Progression des ères & évolution civilisationnelle

Fonctionnalités associées :
- 4 ères jouables (Âge de pierre → Médiéval)
- Conditions de passage d’ère
- Ressource « connaissance »
- Prérequis technologiques et structurels

### EPIC 2 — Gestion des ressources

Fonctionnalités associées :
- Ressources classiques (bois, pierre, nourriture, or)
- Ressource connaissance
- Production et consommation
- Bonus liés à l’environnement

### EPIC 3 — Construction & urbanisme

Fonctionnalités associées :
- Placement libre des bâtiments
- Impact du terrain (fleuve, colline, falaise)
- Bâtiments spécialisés (ferme, carrière, forteresse)
- Urbanisme stratégique

### EPIC 4 — Système militaire & combats

Fonctionnalités associées :
- Unités évolutives selon les ères
- Influence du terrain et de la météo
- Formations de combat
- Généraux avec compétences

### EPIC 5 — Diplomatie & relations internationales

Fonctionnalités associées :

- Alliances
- Traités de paix
- Pactes de non-agression
- Échanges commerciaux
- Négociations complexes

### EPIC 6 — Identité culturelle & religion

Fonctionnalités associées :
- Choix du panthéon
- Traditions culturelles
- Lois impériales
- Impacts gameplay des choix idéologiques

### EPIC 7 — Artefacts & héritage historique

Fonctionnalités associées :
- Découverte d’artefacts
- Bonus uniques
- Pillage / commerce d’artefacts
- Merveilles du monde persistantes

### EPIC 8 — Modes de jeu & multijoueur

Fonctionnalités associées :
- Campagnes scénarisées
- Mode Sandbox
- Multijoueur compétitif
- Multijoueur coopératif
- Menaces systémiques

##  ÉTAPE 3 — USER STORIES (20 US)

En tant que [utilisateur]
Je peux [action]
Afin de [bénéfice]

### EPIC 1 — Progression des ères

En **tant** que *joueur*, je **peux** débloquer une nouvelle ère **afin** de faire évoluer technologiquement ma civilisation.

En **tant** que *joueur*, je **dois** remplir des prérequis (ressources, bâtiments, connaissances) **afin** de mériter le passage d’ère.

En **tant** que *joueur*, je **peux** accumuler de la connaissance **afin** d’accéder à des technologies avancées.

### EPIC 2 — Ressources

En **tant** que *joueur*, je **peux** collecter différentes ressources **afin** de développer mon empire.

En **tant** que *joueur*, je **peux** visualiser ma production et ma consommation **afin** d’optimiser mon économie.

### EPIC 3 — Construction

En **tant** que *joueur*, je **peux** placer librement mes bâtiments **afin** de construire une ville adaptée à ma stratégie.

En **tant** que *joueur*, je **bénéficie** de bonus environnementaux **afin** d’encourager une construction stratégique.

### EPIC 4 — Militaire

En **tant** que *joueur*, je **peux** recruter des unités variées selon l’ère **afin** de constituer une armée adaptée.

En **tant** que *joueur*, je **peux** utiliser le terrain et la météo **afin** d’influencer l’issue des combats.

En **tant** que *joueur*, je **peux** recruter des généraux **afin** de renforcer mes armées grâce à leurs compétences.

### EPIC 5 — Diplomatie

En **tant** que *joueur*, je **peux** former des alliances **afin** de sécuriser ma position face aux ennemis.

En **tant** que *joueur*, je **peux** négocier des traités **afin** d’éviter des conflits coûteux.

En **tant** que *joueur*, je **peux** commercer avec d’autres civilisations **afin** de renforcer mon économie.

### EPIC 6 — Culture & religion

En **tant** que *joueur*, je **peux** choisir un panthéon religieux **afin** d’orienter l’identité de ma civilisation.

En **tant** que *joueur*, je **peux** instaurer des lois impériales **afin** de modifier durablement mon gameplay.

### EPIC 7 — Artefacts

En **tant** que *joueur*, je **peux** découvrir des artefacts **afin** d’obtenir des bonus uniques.

En **tant** que *joueur*, je **peux** voler ou échanger des artefacts **afin** d’affaiblir ou renforcer une civilisation.

### EPIC 8 — Modes de jeu

En **tant** que *joueur*, je **peux** jouer une campagne scénarisée **afin** de vivre une expérience narrative historique.

En **tant** que *joueur*, je **peux** jouer en mode Sandbox **afin** de créer librement mon empire.

En **tant** que *joueur*, je **peux** jouer en multijoueur coopératif **afin** de faire face à des menaces communes avec d’autres joueurs.



## ÉTAPE 4 — Critères d’acceptation & Definition of Done

### User Story 1 — Passage à une nouvelle ère

User Story
En tant que joueur, je peux débloquer une nouvelle ère afin de faire évoluer technologiquement ma civilisation.


#### Critères d’acceptation

Étant donné que le joueur possède les ressources requises
Quand il remplit tous les prérequis de l’ère
Alors l’option de passage à la nouvelle ère devient disponible

Étant donné que tous les prérequis ne sont pas remplis
Quand le joueur tente de changer d’ère
Alors le passage est refusé et les prérequis manquants sont affichés

Étant donné que le joueur valide le changement d’ère
Quand la transition est lancée
Alors les nouveaux bâtiments, unités et technologies sont débloqués


#### Definition of Done

Mécanisme de passage d’ère implémenté

Vérification des prérequis fonctionnelle

Interface de transition intégrée

Tests fonctionnels validés

Validation du Product Owner

### User Story 2 — Collecte de ressources

User Story
En tant que joueur, je peux collecter différentes ressources afin de développer mon empire.

#### Critères d’acceptation

Étant donné que des bâtiments de production sont construits
Quand le temps de jeu s’écoule
Alors les ressources correspondantes augmentent

Étant donné que la capacité de stockage est atteinte
Quand la production continue
Alors l’excédent de ressources est perdu ou bloqué

Étant donné que le joueur consomme des ressources
Quand une action est effectuée
Alors les stocks sont mis à jour en temps réel

#### Definition of Done

- Système de production opérationnel
- Gestion du stockage implémentée
- Affichage des ressources fonctionnel
- Tests unitaires et fonctionnels validés
- Validation du Product Owner

### User Story 3 — Construction libre avec bonus environnementaux

User Story
En tant que joueur, je peux placer librement mes bâtiments afin de construire une ville adaptée à ma stratégie.

#### Critères d’acceptation

Étant donné que le joueur sélectionne un bâtiment
Quand il le place sur la carte
Alors le bâtiment est construit à l’emplacement choisi

Étant donné que le bâtiment est placé près d’un élément environnemental
Quand la construction est terminée
Alors un bonus de production ou de défense est appliqué

Étant donné que l’emplacement est invalide
Quand le joueur tente de construire
Alors la construction est refusée avec un message explicatif

#### Definition of Done

- Placement libre des bâtiments fonctionnel
- Calcul des bonus environnementaux implémenté
- Feedback visuel et messages d’erreur intégrés
- Tests de placement validés
- Validation du Product Owner

### User Story 4 — Recrutement et gestion des unités militaires

User Story
En tant que joueur, je peux recruter des unités variées selon l’ère afin de constituer une armée adaptée.

#### Critères d’acceptation

Étant donné que le joueur possède les bâtiments requis
Quand il recrute une unité
Alors l’unité apparaît après un temps de formation

Étant donné que l’ère change
Quand le joueur accède au recrutement
Alors de nouvelles unités deviennent disponibles

Étant donné que les ressources sont insuffisantes
Quand le joueur tente un recrutement
Alors l’action est bloquée avec un message explicatif

#### Definition of Done

- Catalogue d’unités par ère implémenté
- Système de recrutement fonctionnel
- Consommation de ressources validée
- Tests de recrutement validés
- Validation du Product Owner

### User Story 5 — Diplomatie : alliances et traités

User Story
En tant que joueur, je peux former des alliances afin de sécuriser ma position face aux ennemis.

#### Critères d’acceptation

Étant donné que deux civilisations sont en paix
Quand une alliance est proposée et acceptée
Alors elles deviennent alliées

Étant donné que deux civilisations sont alliées
Quand l’une est attaquée
Alors l’autre peut intervenir militairement

Étant donné que une alliance est rompue
Quand le joueur la rompt volontairement
Alors des conséquences diplomatiques sont appliquées

#### Definition of Done

- Système d’alliance fonctionnel
- Gestion des états diplomatiques implémentée
- Interface de diplomatie intégrée
- Tests des scénarios diplomatiques validés
- Validation du Product Owner


## ÉTAPE 5 — Priorisation du Product Backlog


Format : Priorité – User Story – Dépend de – Justification

### Priorité 1 — Cœur du gameplay (fondations)

- **P1** – Collecter des ressources afin de développer mon empire
Dépend de : —
Justification : Base de toute progression et de toutes les autres mécaniques.

- **P2** – Placer librement des bâtiments afin de construire une ville stratégique
Dépend de : Collecte de ressources
Justification : Permet l’économie, l’armée et la progression.

- **P3** – Visualiser la production et la consommation afin d’optimiser l’économie
Dépend de : Collecte de ressources
Justification : Indispensable à la prise de décision du joueur.

### Priorité 2 — Boucle stratégie & progression

- **P4** – Accumuler de la connaissance afin d’accéder à des technologies avancées
Dépend de : Collecte de ressources
Justification : Introduit une progression non purement économique.

- **P5** – Débloquer une nouvelle ère afin de faire évoluer la civilisation
Dépend de : Ressources, connaissance, construction
Justification : Pilier identitaire du jeu.

- **P6** – Recruter des unités selon l’ère afin de constituer une armée
Dépend de : Construction, ressources, changement d’ère
Justification : Permet les conflits et la défense.

### Priorité 3 — Profondeur stratégique

- **P7** – Bénéficier de bonus environnementaux lors de la construction
Dépend de : Construction
Justification : Ajoute de la stratégie sans bloquer le gameplay.

- **P8** – Utiliser le terrain et la météo afin d’influencer les combats
Dépend de : Système militaire
Justification : Complexifie les affrontements.

- **P9** – Recruter des généraux avec compétences afin de renforcer les armées
Dépend de : Système militaire
Justification : Ajoute une couche tactique avancée.

### Priorité 4 — Diplomatie & identité

- **P10** – Former des alliances afin de sécuriser sa position
Dépend de : Système militaire
Justification : Offre une alternative à la guerre.

- **P11** – Négocier des traités afin d’éviter des conflits coûteux
Dépend de : Diplomatie
Justification : Approfondit les relations internationales.

- **P12** – Choisir un panthéon religieux afin d’orienter la civilisation
Dépend de : Progression des ères
Justification : Spécialisation du gameplay.

### Priorité 5 — Contenu avancé & long terme

- **P13** – Découvrir des artefacts afin d’obtenir des bonus uniques
Dépend de : Exploration, combats
Justification : Enrichissement de la progression.

- **P14** – Construire des merveilles du monde avec effets persistants
Dépend de : Progression avancée
Justification : Objectifs long terme.

- **P15** – Jouer en mode multijoueur coopératif
Dépend de : Systèmes cœur stables
Justification : Forte valeur mais coûteux techniquement.

## ÉTAPE 6 — Définition du MVP (V1 jouable)

User Stories incluses dans le MVP (7 US)

- Collecter des ressources afin de développer mon empire
- Visualiser la production et la consommation des ressources
- Placer librement des bâtiments
- Accumuler de la connaissance
- Débloquer une nouvelle ère
- Recruter des unités militaires selon l’ère
- Combattre sur la carte en utilisant le terrain

### Description de la V1 jouable (MVP)

La version MVP d’Empires of Destiny propose une expérience solo en temps réel où le joueur débute à l’âge de pierre.
Il peut collecter des ressources, construire une base, gérer son économie, accumuler de la connaissance et faire évoluer sa civilisation vers une nouvelle ère.

Le joueur peut recruter des unités militaires pour se défendre ou attaquer, avec une première prise en compte du terrain dans les combats.
Cette version permet une boucle de gameplay complète :
	produire → construire → progresser → combattre → évoluer.

### Fonctionnalités volontairement exclues du MVP

- Diplomatie avancée (alliances, traités complexes)
- Religion et lois impériales
- Artefacts culturels
- Généraux et traits psychologiques
- Multijoueur compétitif et coopératif
- Campagnes scénarisées
- Merveilles du monde et héritage inter-parties
- Météo dynamique dans les combats