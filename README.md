# tuto_react

![logoReact](https://github.com/LegrandThomas/tuto_react/assets/103045194/42468eff-1777-4c62-9a5d-c14acce1546b)

---

## Table des matières

1. [Le Projet](#le-projet)
2. [Contexte du projet](#contexte-du-projet)
3. [ScreenShot](#ScreenShot)
4. [Commentaires divers](#Commentaires-divers)
5. [Installation/Mise en route](#installationmise-en-route)


## Le Projet:

* Mise en route apllication mobile avec React Native
* Objectif : Suivre et reproduire le tuto suivant 👉
                         https://docs.expo.dev/tutorial/introduction/

 ### Contexte du projet:
  
  <details>
      <summary>contexte</summary>
    👋 Hey les ami.es, vous connaissez la dernière nouvelle ? 🤔 Vraiment ? Eh bien j'ai été élu Maire avec 99,9% de voix des Alumnis et Simplonien.es (merci Cambridge Analytica 💰💰💰), eh ouais ma gueule.....euh enfin OUI mes chèr.es concitoyen.es 🇫🇷🥖.

Et en tant que Maire de Simplonville, je souhaite développer des outils numériques accessibles par toutes & tous.

Priorité numéro 1, la sécurité de tous. Je souhaite faire développer une application pour alerter dans ma ville. Alors alerter de quoi ? Accident, travaux, problème de voirie (propreté, éclairage,...), chien perdu, etc... et comment ? via une application mobile. Mon équipe IT étant débordé, je compte sur votre talent pour mettre en place ce projet. L'étude a été réalisé en amont et le choix des technos également.​

Comment va fonctionner cette application ? C'est ultra simple. Un simple formulaire de signalement avec :

un champ pour choisir le type d'alerte (voirie, stationnement, travaux,etc)
un champ de type textarea pour décrire l'alerte
un champ date
un champ horaires
un champ pour l'adresse sous forme de carte intéractive avec possibilité de géolocalisation et reverse geocoding
un champ photo (caméra smartphone)
les champs classiques (nom, prenom, adresse, cp, ville, email, téléphone)
BONUS :

possibilité d'envoyer une vidéo de 30 secondes max
reCAPTCHA Google
Bandeau cookie avant utilisation de l'application
une navigation dans l'application pour aller sur la page mentions légales​

Chaque alerte sera envoyer à différentes adresses emais selon le sujet d'alerte.

Pour la voirie, envoyer à voirie@simplonville.co

Pour les animaux, envoyer à animaux@simplonville.co

Etc....
exemple de ce que j'attends : https://criquebeuf-seine.fr/alertez-nous/


  </details>
  
  
<details>


<summary> Résumé de l'attente du livrable pour Vendredi 22 Sept 2023 13h30</summary>
Application Mobile déployée via EAS
1 SCREEN d'accueil avec lien pour arriver sur un 2eme SCREEN avec le formulaire (Routing)
Un formulaire avec les différents champs demandés dans le brief projet
Une MAP dans le formulaire avec Marker et GEOLOCALISATION + GEO REVERSE pour récupérer l'adresse postale
Un Composant CAMERA pour prendre une photo du délit 😉
La DATE & HEURE du crime
Envoie de mail avec TOUS les éléments et en Cci mon email : cdelobel.ext@simplon.co
BONUS : Mise en place bandeau RGPD, vidéo, Splashscreen et + encore j'adore les Kinder et les jouets à l'intérieur 😉 


  </details>




   ### ScreenShot:

<details>
<summary>Application mobile</summary>
 *screen expo start

 ![screen_expo_start](https://github.com/LegrandThomas/tuto_react/assets/103045194/db54003a-7410-4f81-9a01-ec173d597052)

 *screen home

![screen1](https://github.com/LegrandThomas/tuto_react/assets/103045194/569d6951-d1e8-4de7-9fd8-9679fb69dd65)


 *screen select_image

![screen_pick_image](https://github.com/LegrandThomas/tuto_react/assets/103045194/c09c152f-d257-48f7-b9de-93e596beb550)


 *screen open modal

![modal_sticker](https://github.com/LegrandThomas/tuto_react/assets/103045194/956a594a-759f-47b2-990b-2538f1ae6c4e)


 *screen pick_sticker

![screen_sticker_move](https://github.com/LegrandThomas/tuto_react/assets/103045194/0d9a9264-2ab9-4d73-9082-b72c0028bda4)


 *screen result

![screen_result](https://github.com/LegrandThomas/tuto_react/assets/103045194/6be610aa-843e-4983-bfa3-df20dcfda791)


  </details>
<details>
<summary>code</summary>

Voir code ;)

   
  </details>



### Commentaires divers:

### Installation/Mise en route:

