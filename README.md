# FR Version| Bonjour et bienvenue sur le Tutorial Pour avoir l'acces Token de Instagram

Nous allons voir comme utiliser [API Instagram ](https://www.instagram.com/developer/authentication/)

***
## Parti I Connexion

Dans un premier temps vous allez vous retrouver sur la page suivante :
![Instagram-base](https://user-images.githubusercontent.com/38752522/56944904-88f46680-6b68-11e9-8121-b65a16181695.PNG)

Ensuite voulez devoir vous connecter en Cliquan sur ["Connectez-vous"](https://www.instagram.com/accounts/login/?next=/developer/authentication/) 
![Instagram-connexion](https://user-images.githubusercontent.com/38752522/56944996-d670d380-6b68-11e9-9b0f-118d20a22f02.PNG)

***
## Parti II Création de l'application
Maintenant rendez-vous dans ["Manage-clients"](https://www.instagram.com/developer/clients/manage/) 
Puis vous-allez pouvoir créer votre application ici 
![Instagram-CreatApplication](https://user-images.githubusercontent.com/38752522/56945196-9a8a3e00-6b69-11e9-84d4-470f07109039.PNG)


Application Name: NomDeVotreApplication (NE pas utiliser Instagram, IG,insta,gram dans le nom)

***
Description: A Quoi Elle Va Servire
***
Company Name: Nom de votre entreprise
***
Website URL:le lien de Votre site 
***
Valid redirect URIs: Lien de redirection après c'être connecter a votre application ou identifier
***
Privacy Policy URL: Le lien de votre politique d'entreprise
***
Contact email: L'email pour que vous puisiez vous confirmer et pour avoir de futur information de votre application
***

Après l'avoir créer vous tomber sur cette image :
![Instagram-Applivisu](https://user-images.githubusercontent.com/38752522/56945422-82ff8500-6b6a-11e9-9ba0-a4be479fc955.PNG)

ou vous avez l'onglet manage pour avoir plus d'information comme votre ID client et ID secret qui vont vous servir pour avoir le token.

## Parti III Avoir le token
 Maintenant cela est très simple il faut vous rendre ["ici"](https://www.instagram.com/developer/authentication/).
 Et scroller vers le bas et trouver le lien : 
 - https://api.instagram.com/oauth/authorize/?client_id="VOTRE_ID_D'APPLICATION"&redirect_uri="LE_LIEN_DE_REDIRECTION_QUE_VOUS_AVEZ_RENTRER_AVANT"&response_type=token
![Instagram-get token](https://user-images.githubusercontent.com/38752522/56946635-01a9f180-6b6e-11e9-91c8-ee1be18c1da9.PNG)
 Après avoir rendrez vos information cela vous renvoie un lien :
![Instagram-Token](https://user-images.githubusercontent.com/38752522/56946637-02428800-6b6e-11e9-9db0-a3e59dbd370d.PNG)
 
 ## Parti IV Avoir les informations qui nous intéresse
 Après avoir récupérer tous les informations qui nous intéresse
 
 Juste en utilisant ce lien : https://api.instagram.com/v1/users/self/media/recent/?access_token="VOTRE_TOKEN"
 Vous voyez les information suivante:
 ![Instagram-INFO](https://user-images.githubusercontent.com/38752522/56946827-a4fb0680-6b6e-11e9-8055-f60da1fef332.PNG)
 
Vous pouvez Allez voir aussi pour AUTRE API :
# API Pinterest Tutorial : https://github.com/AxelGUZA/ApiPinterestTutorialToken/
# API FACEBOOK : https://github.com/AxelGUZA/tutorialAPIFacebook/

 
 


 



