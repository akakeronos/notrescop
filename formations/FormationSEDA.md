class: inverse, center, middlebackground-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;
.footnote[Ceci est fait en texte avec du logiciel libre]

## Objectifs

- comprendre la gestion des données de référence
- comprendre la notion de profil SEDA, unités d'archives et objets-données
- maîtriser la création de profil SEDA

---

background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Présentation : 20"

Objectifs : faire un tour de table, ouverture des échanges (pas de mauvaises questions, loi des 2 pieds, détente collective)

- pourquoi nous sommes là ?
- quel est notre objectif commun ?

**Dispositif** :

Nuage de mots : https://answergarden.ch/create/

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Programme de la formation : 5"


- matinée : concepts et usages
- après-midi : manipulation (les mains dans le cambouis)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Introduction sur processus de versement

### Un petit détour par la vision processus

> **processus** : ensemble ordonnées d'activités qui délivre un produit et/ou un service, à un "client" interne ou externe, lui apporte de la valeur, répond à ses besoins exprimés ou implicites et nécessite d'être maîtrisé/piloté

> **processus métier** : ensemble des activités qui s’enchaînent pour créer un produit ou un service à partir d’éléments de base. Un processus se décompose en sous-processus. (MAC, glossaire de l'archivage)

![illustration d'un processus](./images/dessinerProcessus2.jpg)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Modélisation d'un processus

1. On commence par définir les diagrammes de cas d'utilisation (Use Case)

![exemple de cas d'utilisation archiver](./images/useCaseArchiver.png)

<!--
Qui permettent de donner une vue globale de l'application. Pas seulement pour un client non avisé qui aura l'idée de sa future application mais aussi le développeur s'en sert pour le développement des interfaces.

La représentation d'un cas d'utilisation met en jeu trois concepts : l'acteur, le cas d'utilisation et l'interaction entre l'acteur et le cas d'utilisation.

Cas d'utilisation : Un cas d'utilisation (use case) représente un ensemble de séquences d'actions qui sont réalisées par le système et qui produisent un résultat observable intéressant pour un acteur particulier

-->

---

background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Modélisation d'un processus

2. Ensuite on va présenter la chronologie des opérations par les diagrammes de séquences.

![exemple de diagramme de classe verser archives](./images/diagrammeSequenceArchiver.png)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

## Modélisation d'un processus

1. Et finir par les diagrammes statiques, qui sont celles de classe de conception, de classe participantes et le modèle physique.

![exemple de diagramme de classe verser archives](./images/diagrammeClasseVerserArchives.png)

---

### Les métadonnées de pérennisation

![métaphore métadonnées comme partie imergée iceberg](./images/icebergMetadonnees.jpg)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

#### Introduction sur les Métadonnées en général

**définition**

> Une métadonnée est une donnée servant à **définir ou décrire** une autre donnée. **Porteuse d'information** sur le **contexte**, le **sens** et la **finalité** de la ressource informationnelle portée par la **donnée brute**.

![explication des métadonnées par un métaphore sur le vin](./images/vinContexte.png)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

#### Le standard des échanges d'archives publiques : SEDA

.pull-left[
![schema SEDA](./images/schemaSeda.PNG)
]
.pull-right[

- Le schéma SEDA permet de décrire les relations entre les acteurs au cours des échanges (transfert, de communication, de modification, d'élimination ou de restitution d’archives).

- Il permet d'automatiser les procédures d'échange d'information en décrivant les règles contractuelles qui régissent le versement et la prise en charge d'un paquet d'information.

- Les messages SEDA décrivent les contraintes (format, support, identification) et fournissent un historique des opérations effectuées (transfert, réception, destruction, etc..)

- La grammaire XML permet de définir des règles formelles vérifiables par les machines (est égal à, ne peut pas être différent de, n'existe qu'en un seul exemplaire, provient de, etc...)
  ]

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

#### modélisation des échanges d’informations dans le cadre de l’archivage

- les acteurs de l'échange
  - service producteur
  - service versant
  - service d'archives
  - service de contrôle
  - service demandeur

.reduite[
![illustration des moyens transverses](./images/desertB.jpg)
]

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

### La structuration des messages SEDA

![le schéma SEDA](./images/seda1.png)

---
background-position: top;
background-repeat: no-repeat;
background-image: url(./images/fondCorporate.png)
background-size: contain;

### La structuration des messages SEDA

![Les échanges SEDA](./images/seda2.png)

