# Cahier des charges du product_manager

### Contexte

La banque Edifier nous a contacter pour afin d'amélioration leurs application déjà mise en place qui concernant la gestion des comptes bancaires.

#### Objectif

Une demande d'évolution sur les fonctionnalités suivantes par la banque edifier :
- dépôt d'argent
- le retrait d'argent 
- consultation de l'historique des transactions

`Et une fonctionnalités optionnelle`
- Prise rdv avec un conseiller 

### Description de app

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

### Fonctionnalités demandés

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

### Règles des gestions pour les fonctionnatés demandés
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
