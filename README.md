# QR Code pour roue de la fortune

Page web simple pour un restaurant :
- demande d'avis Google avant de pouvoir tourner la roue
- ouvre les avis Google dans un nouvel onglet
- affiche ensuite la roue de la fortune
- propose des récompenses comme dessert, plat, boisson, réduction

## Utilisation
1. Ouvrez `index.html` dans un navigateur.
2. Changez `YOUR_PLACE_ID` dans le code JavaScript par l'identifiant Google Maps de votre restaurant.
3. Générez un QR code vers l'URL de la page (ex. hébergée sur un site ou via un service local).

## Générer un QR code
- Exemple de service : `https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=URL_DE_VOTRE_PAGE`
- Remplacez `URL_DE_VOTRE_PAGE` par l'adresse de la page web hébergée.

## Exemple de fonctionnement
- L'utilisateur scanne le QR code.
- La page demande de laisser un avis.
- Après validation, elle ouvre les avis Google dans un nouvel onglet.
- La roue est alors disponible et peut être lancée.
