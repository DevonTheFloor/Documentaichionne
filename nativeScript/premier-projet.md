---
title: Premier projet nativScript
description: On va voir ici comment commencer un projet nativScript pour android. On ne parlera que de la connexion à un véritable smartphone android. L'émulatuier fera l'objet d'un autre tutoriel.
img: ''
---
   
## Connexion de l'appareil   
   
Alors une fois que tu as créer ton projet avec le framewoirk de ton choix, pour ma part je t'ai déjà dis dans [installation de l'environnment](/blog/article/installation-environnement-ns) que pour éviter plein de souscis de transpilmage dû aux différents version des dépandence des framework, je vais rester en JS natif pour mes application nativScript.   
Je te rappelle la commande: ```ns create MaSuperApp --js``` .   
   
Tout naturellement tu vas dans le dossier MaSuperApp et tu lance ```ns run android``` .   
Il est possible qu'il te réponde: ``` Cannot find connected devices.
Emulator start failed with: No emulator image available for device identifier 'undefined'.```   
Ce à quoi il faut lui répliquer: ``` tns device``` . Si là il t'explique qu'il ne cannoty find connected device, il faut allez dans le téléphone pour autoriser le mode developpement. En gros il faut faire ça: 
    Accéder aux paramètres de l’appareil Android
    Aller dans les paramètres système
    Aller dans « À propos du téléphone »
    Tapoter 7 fois « numéro de build »   

Les options pour les développeurs apparaissent dans les paramètres système.   
TU trouveras un suoper sujet sur phone Android ici: [Comment activer ou désactiver le mode développeur sur Android](https://www.frandroid.com/comment-faire/tutoriaux/184906_comment-acceder-au-mode-developpeur-sur-android) .   



