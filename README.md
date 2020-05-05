# Checkpoint 2 - 4h

---
### EN version (Scroll down for FR version)
---

You will have 4 hours to finish this checkpoint. This checkpoint is not an exam, it will allow us to validate your skills, so try to do it as much as possible on your side.
This checkpoint is very consistent, if you can't do everything it doesn't matter, do your best;)

## !!! FIRST STEP REQUIRED BEFORE STARTING THE FIRST EXERCISE!

- Clone this project
- Create a `city_lastname_firstname` branch, which will contain your progress. Replace `city_lastname_firstname` with the city of your campus, your last name and first name.

## Step 1 - React

<img src="https://giphygifs.s3.amazonaws.com/media/14hVsVZomE4hj2/giphy.gif" height="150">

In this step, you will create a new React project in which there will be 2 components that will display data from an API.

The API is available on this url [https://wild-games.herokuapp.com/api/v1](https://wild-games.herokuapp.com/api/v1).
You can use either [axios](https://github.com/axios/axios) or [fetch](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API/Using_Fetch) to recover the data.

Think about `commit' regularly with an explicit message. For example: ``Create GameList and Game components``.

**Friendly Tip:** before starting, make the *component tree* and *wireframes*! :)

- Create a new React project named **list-games** using `create-react-app`.
- Create 2 components `<GameList />` and `<Game />`.
- Use `<GameList />` component to fetch from the API and display each game on a `<Game />` component.
- `<Game />` retrieves with `props` the information of each game (`name`, `background_image`, `rating`...) and displays it in the format of your choice.
- `<Game />` contains a `<button>` that removes a game on click from the `state`. There is no need to remove it from the API.

## Step 2 - Bonus

Do you have any time left? Perfect! Perfect! You will be able to add some useful features to your React project!

#### Filter games by rating

- Add a `Best Games` button to filter games by `rating`.
- When you click on the button, only games with a `rating` greater than or equal to 4.5 are displayed.
- The button text is replaced by `All Games` and when clicked, all games are displayed again.

#### Add a screenshots page

For this bonus, use the `react-router` library.

- Add a navigation link in each game to see the images listed in the `short_screenshots` field. 
- Clicking on this link changes the page to `http://localhost:3000/jeu/screenshots/5` where 5 is the id of the selected game.
- Also display a navigation link to return to the home page.

## Step 3 - Congratulations!

You can quench your thirst at the brewery, you've earned it!

**N.B.: You don't have to start with this step...;)**

![Good Luck](https://media.giphy.com/media/AC1PtbdsJZyOQ/giphy.gif)


---
### FR version
---

Pour ce travail tu as 4h devant toi. Ce checkpoint n'est pas un examen, il va nous permettre de valider tes compétences, essaye donc de le faire au maximum de ton côté.
Ce checkpoint est très consistant, si tu n'arrives pas à tout faire ce n'est pas grave, fais de ton mieux ;)

## !!! PREMIERE ÉTAPE OBLIGATOIRE AVANT DE COMMENCER LE PREMIER EXERCICE !!!

- Clone ce projet
- Crée une branche `ville_nom_prenom`, qui va contenir ton avancée. Remplace `ville_nom_prenom` par la ville de ton campus, ton nom et ton prénom.

## Étape 1 - Quiz

- Pour répondre au quiz rend toi sur [cette application](https://wild-quiz-client.herokuapp.com/).
- Réponds aux questions du Quiz **Checkpoint 2 - JS - React**
- Une fois le quiz terminé, copie le lien fourni par l'application
- Crée un fichier Quiz.md à la racine du projet
- Colles-y le lien que tu viens de récupérer
- `commit` ton fichier

## Étape 2 - React

<img src="https://giphygifs.s3.amazonaws.com/media/14hVsVZomE4hj2/giphy.gif" height="150">

Dans cette étape, tu vas créer un nouveau projet React dans lequel il y aura 2 composants qui afficheront des données provenant d'une API.

L'API est accessible sur cette url [https://wild-games.herokuapp.com/api/v1](https://wild-games.herokuapp.com/api/v1).
Tu peux utiliser au choix [axios](https://github.com/axios/axios) ou [fetch](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API/Using_Fetch) pour récupérer les données.

Pense bien à `commit` régulièrement avec un message explicite. Par exemple : `"Create GameList and Game components"`.

- Crée un nouveau projet React nommé **list-games** grâce à `create-react-app`.
- Crée 2 composants `<GameList />` et `<Game />`.
- `<GameList />` récupère les jeux de l'API et  les affiche dans autant de composants `<Game />`.
- `<Game />` récupère avec des `props` les informations de chaque jeu (`name`, `background_image`, `rating`…) et les affiche au format de ton choix.
- `<Game />` contient un `<button>` qui permet au click de supprimer un jeu du `state`. _Il n'y a pas besoin de le supprimer de l'API._

## Étape 3 - Bonus

Il te reste du temps ? Parfait ! Tu vas pouvoir ajouter quelques fonctionnalités utiles à ton projet React !

### Filter les jeux par note

- Ajoute un bouton `Best Games` pour filter les jeux par `rating`
- Quand on clique sur le bouton seuls les jeux dont le `rating` est supérieur ou égal à 4.5 sont affichés
- Le texte du bouton est remplacé par `All Games` et quand on clique dessus, tous les jeux sont affichés à nouveau

### Ajouter une page screenshots

Pour ce bonus, utilise la librairie `react-router`.

- Ajoute un lien de navigation dans chaque jeu pour voir les images listées dans le champ `short_screenshots`. 
- Cliquer sur ce lien change la page pour `http://localhost:3000/jeu/screenshots/5` ou 5 est l'id du jeu selectionné.
- Affiche également un lien de navigation permettant de revenir sur la page d'accueil.

## Étape 4 - Félicitations !

Tu peux aller te désaltérer à la brasserie, tu l'as amplement mérité !

**N.B. : Tu ne dois pas commencer par cette étape… ;)**

![Good Luck](https://media.giphy.com/media/AC1PtbdsJZyOQ/giphy.gif)
