---
id: version-10.4.1-man-installation-pop
title: Manuel d'installation
sidebar_label: Manuel d'installation
original_id: man-installation-pop
---


## 1 - Installation matériel

A noter que les imprimantes peuvent être relié soit en Bluetooth soit par un câble réseau, toutefois une imprimante relié en Bluetooth ne peut être relié qu'à une seule caisse au contraire d'une imprimante connectée en réseau qui peut être contactée par différentes caisses du réseau.

### Cas 1 : Installation simple

Matériel : 1 iPad, 1 imprimante, 1 routeur, 1 tiroir caisse

1. Branchez le câble ethernet (RJ45) entre l'imprimante (port 4 sur l'image ci dessous) et un des ports jaune situé au dos de votre routeur (ce câble peut être remplacé par deux boitiers CPL). 


| ![](https://imgur.com/XDEDcYI.png) | ![](https://imgur.com/O0zHLpc.png) | ![](https://imgur.com/FUob9jm.png)|
|--|--|--|

2. Branchez le tiroir-caisse au port DK (Port 6 sur l'image au dessus) sous l'imprimante (via le câble du tiroir-caisse). 
3. Branchez le câble Ethernet fourni avec Popina entre le port Ethernet bleu situé au dos du routeur et un des ports Ethernet situé au dos de votre box internet. Selon votre fournisseur d'accès internet l'étiquetage des parts ethernet peut être différent. Les plus communs sont des port **jaunes** et/ou étiquetés **LAN**.

Un fois tout branchez vous pouvez démarrer votre iPad et vous connecter au réseau Wi-Fi nommé Popina ou Popina_5G. Le mot de passe se trouve sur l'étiquette de votre routeur.

**NB :** Dans le cas où vous n'avez pas de routeur, branchez directement l'imprimante à un port ethernet de votre box.



### Cas 2 : Installation 2 iPads 2 imprimantes 

Matériel : 2 iPads, 2 imprimantes, 1 routeur POE (Edge routeur de Unifi), 1 borne Unifi


1.  Branchez le câble ethernet (RJ45) entre l'imprimante (port 4 sur l'image ci dessous) et le port étiqueté IMP. sur votre routeur (Généralement le port **eth1**). 

| ![](https://imgur.com/XDEDcYI.png) | ![](https://imgur.com/lrxUaKA.jpg) |
|--|--|


2. Branchez le tiroir-caisse au port DK (Port 6 sur l'image au dessus) sous l'imprimante (via le câble du tiroir-caisse). 
3. Branchez le câble Ethernet fourni avec Popina entre le port Ethernet **eth0** (étiqueté **Internet**) et un des ports Ethernet situé au dos de votre box internet. Selon votre fournisseur d'accès internet l'étiquetage des parts ethernet peut être différent. Les plus communs sont des port **jaunes** et/ou étiquetés **LAN**.
4. Branchez le câble Ethernet fourni avec Popina entre la borne **Unifi** et le port **eth4/PoE out** du routeur.
5. Une fois votre antenne connectée nous vous invitons à contacter votre service technique par chat dans l'onglet support de l'application Popina ou par téléphone, afin d'appairer votre antenne à votre nouveau routeur.




## 2 - Mise en place de l'App Popina

### **Téléchargez Popina** 

Rendez-vous dans l'**App Store**, recherchez **"Popina"**, pour télécharger votre nouvelle caisse Popina, appuyez sur **"Obtenir"** ou sur le **"Nuage"** si vous avez déjà téléchargé une fois l'application. 
Vous la retrouverez ensuite sur la page d'accueil de votre iPad. 

### **Connectez-vous au réseau Popina** 
Si vous avez reçu un routeur **Popina** connectez-vous au réseau **Popina** avec le mot de passe indiqué derrière le routeur (WPS PIN). Sinon restez connecté au réseau wifi de votre box internet.

En allant dans **Réglages** -> **Compte Popina** -> **SSID**, en appuyant sur **Configurer** à droite de SSID, un pop-up apparaît permettant de renseigner le nom et le mot de passe du réseau Wi-Fi sur lequel doit passer l'iPad lors du lancement de l'application **Popina**. Cela permet d'être toujours connecté au bon réseau Wi-Fi sans que cela nécessite de manipulation supplémentaire.

### **Lancez Popina**  
Connectez-vous ou inscrivez-vous si cela n'est pas déjà fait. 
Une fois dans Popina, touchez la barre noire à gauche de l'écran et allez dans **Réglages / Impression**.
Vérifiez que votre (vos) imprimante(s) sont bien présentes dans cet écran et qu'elles sont **"reconnues"**, pour cela elles doivent apparaître en **"vert"**. Si ce n'est pas le cas, appuyez sur **"Test"** pour voir si un ticket sort bien du (des) imprimante(s).
Si ce n'est pas le cas, vérifiez que votre imprimante a bien du papier, est bien allumée et branchée au routeur, éteignez et rallumer le routeur et l'imprimante.

### **Si iPad secondaire ou iPhone / iPod**

Sur les appareils secondaires, connectez-vous avec votre compte **Popina**.
Accédez à Réglages > Flotte puis clique sur se connecter au niveau de la carte contenant le nom de votre iPad principale.

*Popina est maintenant prêt !*

### **Configurez**  
En appuyant sur la barre noire à gauche de l'écran, vous pouvez configurer **Popina** en allant sur : 
Produits pour éditer votre carte.
Salles pour créer, activer et gérer vos différentes salles.
Réglages pour paramétrer vos moyens de paiement, employés, ticket de caisse... 

Pour plus d'informations par rapport à la configuration veuillez vous référez à la **documentation utilisateur** disponible depuis votre caisse dans Support et documentation puis utilisateur.
