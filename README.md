# Cahier des charges du product_manager 📃 

![header_img](https://www.com3elles.com/images/blog/2016/07/cahier-charges.jpg)

Table des matières  :
 1. [Contexte🎍](#contexte)
 2. [Description app📳](#description-app)
 3. [Fonctionnalite demande🔭](#fonctionnalite-demande)
 4. [Regles des gestions📒](#regles-des-gestions)
 5. [Fonctionnalités optionnelle👑](#fonctionnalités-optionnelle)
 6. [Exigences techniques🎣](#exigences-techniques)
 7. [Criteres de qualite🚗](#critères-de-qualite)
 8. [Plan de livraison🚃](#plan-de-livraison)
 9. [Documentation📂](#documentation)
 10. [Raci🚂](#raci)
 11. [Plan de formation🎓](#plan-de-formation)
 12. [Plan d'action🎢](#plan-action)
 13. [Autheurs👾](#autheurs)

### Contexte 

La banque Edifier nous a contacter pour afin d'amélioration leurs application déjà mise en place qui concernant la gestion des comptes bancaires.

#### Objectif 🌟

Une demande d'évolution sur les fonctionnalités suivantes par la banque edifier :
- dépôt d'argent
- le retrait d'argent 
- consultation de l'historique des transactions

💹`Et une fonctionnalités optionnelle`
- Prise rdv avec un conseiller 

### Description app

#### Environnement

L'application Edifier est :
- utilisable dans les guichets automatiques à disposition dans les différents lieux
- disponible sur le Web en responsive
- app disponible sur mobile Ios/android avec la technologie flutter

#### Fonctionnalités déjà présent

L'application Edifier dispose déjà des fonctionnalités fonctionneles qui sont :
- Utilisateur (CIN, prénom, nom, date de naissance, date de création, date de modification, métier, bouton enregistrer)
- Les opérations (ID de l’opération, type de l’opération, montant, date d'exécution, date réel, utilisateur concerné, compte concerné, bouton exécuter l’opération)
- la gestion de compte (Id compte, Type de compte, Surnom, date de création, sélectionner utilisateur, bouton enregistrer) 

#### Règles de gestion

*Pour les comptes bancaires :*
- visualiser les informationss de l'utilisateur
- afficher le solde du client

*Les opérations :*
- connaître le RIB du destinataire 
- connaître les informations bancaires du destinataire

*Les utilisateurs :*
- avoir une pièce d’identité
- vérifier l'identité de l'user

#### Utilisateur visées

*Les utilisateurs sont des :*
- particulier
- professionnel
- personnel de la banque Edifier (support, admins, dev...)

### Fonctionnalite demande

*dépot d'argent :*
- En tant que client de la banque
- Je veux effectuer un dépôts d’argent au guichet
- Afin d'alimenter mon compte bancaire

*retrait d’argent :*
- En tant que le client de la banque
- Je veux faire un retrait d’argent au guichet
- Afin de retirer de l’argent physiquement

*Consultation historique de transactions :*
- En tant que client de la banque
- Je veux consulter l’historique de mon compte
- Afin de voir mes différents transactions

### Regles des gestions
*dépot d'argent :*
- Se connecter à son espace en ligne avec ses identifiants 
- Disposer d’un RIB
- Disposer des informations de la personne destinataire (nom, prénom)
- Disposer d’un RIB destinataire

*retrait d’argent :*
- s’identifier auprès du personnel de la banque au guichet
- Retirer de l’argent dans un distributeur automatique
- S’identifier au distributeur automatique à partir de ma carte bancaire/bleu
- Disposer son code pin à 4 chiffres

*Consultation historique de transactions :*
- Se connecter sur son compte avec ses identifiants et mot de passe
- Consulter son historique sur un distributeur automatique

### Fonctionnalités optionnelle

*User stories :*
- En tant que : client de la banque
- Je veux : avoir la possibilté de souscrire une assurance habitation/auto/moto sur internet.
- Afin de : s’assurer contre les risques liés aux habitation/auto/moto

*Règles de gestion :*
- Disposer des différentes offres d’assurances
- Avoir une connexion internet
- Avoir un smartphone ou un ordinateur
- Se connecter sur son compte avec son identifiant et mot de passe

### Exigences techniques

#### Performance :

- L'application doit être disponible 7j/7 et 24h/24
- une latence inférieur à 50 ms
- Clean code

#### Sécurité :

- l'application sera héberger dans un herbegement de sécurité de niveau haute tel que OVH avec les normes

<sub>voir badge ci-dessous en cliquant dessus pour voir les différents sécurités proposés par OVH pour les banques:</sub>

[![PCI DSS](https://badgen.net/amo/stars/markdown-viewer-chrome)](https://www.ovhcloud.com/fr/enterprise/certification-conformity/pci-dss/)
[![AICPA SOC](https://badgen.net/amo/stars/markdown-viewer-chrome)](https://www.ovhcloud.com/fr/enterprise/certification-conformity/soc-1-2-3/)
[![ISO](https://badgen.net/amo/stars/markdown-viewer-chrome)](https://www.ovhcloud.com/fr/enterprise/certification-conformity/soc-1-2-3/)

#### Charge :

- L'application sera de type SaaS pour notre client.	
- L'application sera autoscalable pour répondre aux pics d'activités

#### Technologies à utilisés :

- HTML et CSS 
- React
- Flutter/DART
- Docker
- GitHub

### Criteres de qualite :

L'application doit répondre aux critères ci-dessous :

- User friendly
- Etre maintenable

### Plan de livraison
Un gantt a été mise en place pour le plan de livraison possibilté de le telecharge dans la branch images ou en clickant sur l'image
[dossier images](https://github.com/MiyaOneTerrian/m2_po_veasna_TANG/tree/images)
![Gantt](https://raw.githubusercontent.com/MiyaOneTerrian/m2_po_veasna_TANG/images/Gantt.png)

### Documentation

SWOT de matrice de faisabilité*
CQQCOQP 
Cahier des charges
Flash report(s)
Cahier de tests
Pv de recettes

### Raci
Un Raci a été mise en place pour le plan de livraison possibilté de le telecharge dans la branch images ou en clickant sur l'image
[dossier images](https://github.com/MiyaOneTerrian/m2_po_veasna_TANG/tree/images)
![RACI](https://raw.githubusercontent.com/MiyaOneTerrian/m2_po_veasna_TANG/images/raci.png)

### Plan de formation
Pour tous les fonctionnalités ils auront tous la même boucle de formation:

- Formation des agences pilotes définies (phase pilote) => envois de vidéo de formation + PPT => **durée 1 semaine**
*accès aux classes virtuelles si besoin*

✅ `si succès des agences pilotes` 

- Formation des agences nationales => envois de vidéo de formation + PPT => **durée 1 semaine**

### Plan action 

- Etape 1 : Validation des développeurs en phase de tests de la fonctionnalité 
- Etape 2 : chef de projet après validation des développeurs 
- Etape 3 : parties prenantes après validation du chef de projet 

## Auteurs:

- [Veasna TANG @MiyaOneTerrian](https://github.com/MiyaOneTerrian)