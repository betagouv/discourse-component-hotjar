Ce composant permet d'activer Hotjar dans un forum Discourse auto-hébergé. 

Allez dans Discourse, puis cliquez sur Personnaliser > Thèmes > Composants > Installer.
Sélectionnez l'option "Depuis un dépôt git" puis collez le lien vers ce dépôt.

Une dernière étape ! Connectez-vous sur Hotjar et récupérez le _site ID_.

![Copie d'écran explicative](img/hotjar.png)

Collez cet identifiant dans Paramètres de thème > hotjar site id. Puis incluez le composant à votre thème et attendez quelques minutes. 

Vérifier que l'installation a réussi est très simple. Il vous suffit d'ajouter le paramètre `?hjVerifyInstall=siteID` au nom de domaine de votre forum, en remplaçant bien entendu `siteID` par la véritable valeur. Un message apparaîtra en haut à gauche de l'écran.

![Copie d'écran du message de succès](img/hotjar2.png)
