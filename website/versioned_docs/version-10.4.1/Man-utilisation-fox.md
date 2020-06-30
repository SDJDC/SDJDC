---
id: version-10.4.1-man-utilisateur-fox
title: Manuel d'utilisation Foxorders
sidebar_label: Manuel d'utilisation Foxorders
original_id: man-utilisateur-fox
---




## Introduction

Ce manuel d'utilisation couvrira toutes les fonctions et applications proposées par FOXORDERS. 


## 1 - Mise en place

Lors de la mise en place de votre compte foxorders, vous serez demandé de fournir votre carte de restaurant sous format excel, .csv ou .pdf pour la première création de votre compte. 

Si vous souhaitez accepter des règlements par CB en ligne c'est également à ce moment que nous vous conseillons de créer un compte avec notre partenaire Stripe (stripe.com). Vous pourrez alors créer et finaliser votre compte le temps de la préparations de votre compte Foxorders. 

A fournir également sera votre logo d'établissement qui figurera sur votre site marque blanche ainsi que des photos de fond si vous souhaitez en ajouter. 

Une fois votre compte créé par nos équipe il vous sera envoyé un email contenant le lien de votre site marque blanche ainsi que vos identifiant d'accès à votre Back office. 

## 2 - Back Office 

Lorsque vous vous connectez à votre back office vous arriverez par défaut sur la page Commandes, c'est ici que vous allez recevoir, accepter et modifier les statuts de vos commandes entrantes. (L'application FoxBusiness est également disponible sur iOS et iPadOS qui rempli ce même rôle et permet également une impression de commande directe à la réception - Voir chapitre Foxbusiness)

### 2.1 - Configuration

La configuration de votre back office et par conséquent du fonctionnement de votre magasin en ligne est assez simple avec peu de paramètres à régler. 

#### 2.1.1 - Gestion des horaires

**Infos restaurant > Gestion des horaires**

La gestion des horaires se programme en plages / jour

Cliquez sur ajouter une plage horaire, sélection le jour de la semaine, heure de début et heure de fin. 

Plusieurs plages horaires peuvent être programmé sur une même journée. 

Chaque plage horaire peut être activé ou désactivé individuellement. 

#### 2.1.2 - Dates de fermetures

Dans cette section vous pouvez renseigner vos dates de fermeture exceptionnels afin de ne pas devoir modifier vos horaires pré-programmé.

#### 2.1.3 - Gestion des modes 

**Infos restaurant > Gestion des modes**

Les modes sont les modes par lesquels le client pourra récupérer sa commandes :

- A emporter 
- Livraison

Pour chaque modes sont disponible un montant minimum de commande, des frais de gestion et un délais de récupération ou livraison. 

Dans le mode **Livraison** il est également nécéssaire de créer des zones de livraison. 
dans cette zone de livraison vous sélectionnerez la ville de livraison, montant minimum de commande, frais de livraison et temps de livraison.

**Ces 4 options sont à renseigner pour chaque zone de livraison que vous créez**

#### 2.1.4 - Cuisines

Cette section vous permet de choisir quels types de cuisines qui sont proposés par votre établissement.

#### 2.1.5 - Modes de règlement 

Cochez les modes de règlement que vous souhaitez accepter. 

Si vous souhaitez accepter des règlement en ligne nous vous demandons de créer un compte stripe et d'ensuite nous transmettre vos clé publique et secrète. Ces clés commencent pas Pk_live et Sk_live. 

Une fois vos clés réceptionné nous activerons ensuite vos règlements en ligne.


#### 2.1.6 - Partenaires

**Outils marketing > Partenaires**

Nius vous proposons de mettre à disposition direct à vos clients des liens vers vos autres partenaires de type Uber Eats, Deliveroo, ou Just Eat 

Sélectionnez le type, le fournisseur et ensuite collez votre URL d'établissement de ce site dans la case "lien". Vous aurez ensuite une lien direct vers cette page sur votre site marque blanche. 

### 2.2 - Programmation

#### 2.2.1 - Programmation simple

**Gestion des menus > PLATS**

Ici vous retrouverez tous les articles programmé dans votre base de données. En haut de cette page se trouve une barre de filtre par catégorie et sous-catégorie afin de retrouver plus facilement l'article que vous souhaitez modifier. 

Le stylo en début de chaque ligne permet de modifier chacun de ces articles. Vous pouvez alors changer le nom, prix, TVA, description ou photo.

#### 2.2.2 - Programmation Avancé

**Gestion des menus > Catégories**

##### **Catégories**

Cette section est plus complet et est moins adapté a des modifications rapide de vos article. Vous pouvez par contre effectuer plus de modification dans cet espace.

Vous êtes d'abord présenté avec la colonne Catégories contenant les différentes catégories et sous catégories de votre base. En haut de cette colonne vous avec la possibilité de créer une nouvelle catégorie. 

Sur chaque catégorie vous pouvez soit éditer celui-ci. Lui attribuer une sous-catégorie ou voir les articles qui sont contenus à l'intérieur. 

----

##### **Articles**

Une fois que vous avez sélectionnez la visualisation des articles d'une catégorie vous aurez maintenant une deuxième colonne contenant ces articles à droite de votre écran. 

tout comme pour les catégories en haut de cette colonne vous avez la possibilité de créer un nouvel article. 

Chaque article dans cette colonne contient 3 boutons pour l'**éditer**, le **dupliquer** et **voir les options**

----

##### **Options d'articles et suppléments**

Sur un de vos articles sélectionnez **Voir les options** vous aurez alors la possibilité de modifier ou ajouter des listes d'options (ex: cuisson, sauce, parfum de glace etc...)

Lord de la modification d'une liste vous avez le choix de le rendre un choix obligatoire et/ou choix multiple. 

Ensuite renseigner les différents choix dans la suite de la colonne.

Chaque choix peut avoir son propre prix et TVA. 

#### 2.2.3 - Promotions 

**Outils marketing > Promotions**

Sur cette fenêtre Sélectionnez **Nouvelle promotion**. 

Vous serez alors présenté avec l'interface de création de promotion. Saisissez un code promo que votre client devra lui renseigner lors de sa commande. **Il est conseiller de le renseigner entièrement en majuscules afin d'éviter des erreurs**. 

Vous avez également la possibilité de rajouter une description a votre promo.

Ensuite renseigner votre taux en % ou montant et vérifier que cette case contient bien le bon méthode de remise. 

D'autres paramètres afin de limiter son utilisation sont a votre disposition dans ce volet. 

### 2.3 - Utilisation en service (Ecran commandes)

Sur l'écran **Commandes** vous aurez vos commandes clients qui arriveront ici. 

Lors de la réception d'une commande vous avez la possibilité d'ensuite l'accepter. Le bouton **Voir** qui apparait par la suite ouvrira une nouvelle fenêtre contenant le ticket du client. 

Une fois la commande du client récupérée ou livré vous pouvez ensuite changer le statut de celui-ci en livré. 

Il est également possible de changer le statut à **Retard** ou **Autre** le client sera alors notifié de cette modification. 

### 2.4 - Exports et statistiques

#### 2.4.1 - Export

A partir de votre back office vous avez la possibilité de d'effectuer un export avec TVA détaillé d'une période que vous choisissez. 

Pour ce faire, rendez vous dans l'onglet Export des commandes avec TVA et sélectionnez la période voulu. Appuyer ensuite sur le bouton **Export** en haut à droite de cet écran. 

Cet export s'effectuera en format .csv qui peut etre exploité par tout logiel de traitement de tableur (Excel, Numbers, Open Office, etc...).

#### 2.4.2 - Statistiques

Afin d'avoir une visualisation de vos statistique sur le jour, semaine, mois ou année en cours, rendez vous sur la page tableau de bord. 

Ici vous trouverez un récapitulatif avec statistiques des données. Afin de choisir la période cliquez sur le menu déroulant en haut à droite. 

### 2.5 - Clients 

Au sein de votre back office vous avez la possibilité de consulter et exporter votre base de données clients. 

Rendez vous dans **Outils marketing > Utilisateurs**.

Vous pouvez alors effectuez une recherche parmi vos clients ou exporter cette base sous format .csv. 

## 3 - FoxEat 

Foxeat est l'application mis a disposition des clients sur smartphone et est disponible sur **iOS** et **Android**.

Une fois votre site entièrement configuré contacté le service client par le chat en bas a droit de votre back office ou par mail à support@foxorders.com afin d'activer votre parution sur l'application. 

Pour qu'un client puisse effectuer une commande sur cette application il doit créer un compte. 

## 4 - Foxbusiness 

Foxbusiness et l'application de réception de commandes disponible sur iOS et iPadOS qui vous permet de visualiser, imprimer et modifier le statut de vos commandes en service. 

Une fois l'application téléchargé connectez vous à l'aide de vos identifiants administrateur Foxorders. 

Vous recevrez alors vos commandes sur cette plateforme en plus de votre back office. 

### 4.1 - Connexion imprimante

Si vous souhaitez ajouter une imprimante à votre application munissez vous d'une imprimante **Epson TM-M30 Bluetooth** 

**ℹ️ (Si vous souhaitez en acquérir un merci de contacter le support qui vous mettrons en contact avec notre équipe commerciale)**

Une fois l'imprimante allumée, entrez dans les réglages de votre iPad et sélectionnez l'onglet Bluetooth. allumé le bluetooth puis une fois l'imprimante trouvé par l'appareil sélectionnez la. 
L'imprimante sera nommée **Epson TM-M30 "XXXXXXXX"**. Une fois connectez et que vous avez le mot oui à la fin de la ligne de l'imprimante, ouvrez l'application Foxbusiness. 

Sélectionnez l'engrenage en bas à gauche et appuyez sur paramètres d'imprimante. Puis sélectionnez l'imprimante bluetooth que vous avez connecté. 

Votre imprimante est maintenant connectée à l'application et imprimera les tickets des clients à leur réception.

### 4.2 Finalisation d'une commande 

Une fois une commande reçu et acceptée vous la trouverez dans l'onglet en préparation. 

Si vous sélectionnez celui-ci vous trouverez plus de détail de la commande ainsi que la possibilité de le réimprimer. 

Sur la commande appuyé sur **"En préparation"** puis modifier le statut à celui souhaité. 