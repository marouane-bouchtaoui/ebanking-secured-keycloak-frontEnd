# Ebanking Frontend

<br>

Vous pouvez voir le backend et la configuration du Keycloak <br>
LINK: (https://github.com/marouane-bouchtaoui/ebanking-secured-keycloak-backend)

<hr>
Pour la configuration du front-end on doit  ajouter la dependence suivante : <br>

```
npm install --save keycloak-js keycloak-angular
```
<br>
Apres on ajoute la fonction kcFactory dans la classe app.module.ts et KeycloakAngularModule dans "imports" : <br>

<img src="caps/imports.png">

puis la création d'un guard classe dans le dossier guard : <br>

<img src="caps/guard.png">

et pour les routes: <br>

<img src="caps/roots.png">

La configurer la classe security.service.ts :<br>

<img src="caps/securityService.png">

L'affichage du navbar sera comme le suivant :<br>

<img src="caps/navbar.png">

L'implementation des methodes Login et Logout :<br>

<img src="caps/loginLogout.png">

## Resultat

<br>
Pour s'authentifier :
<br>

<img src="caps/loginTemp.png">

<br>

Pour s'enregistrer :
<br>

<img src="caps/register.png">

<br>


La page d'accueil :
<br>

<img src="caps/home.png">
