# Exercices CSS - Le CSS c'est magique - Maquette Discord

Il est temps de mettre en pratique tout ce qu'on a vu jusqu'à maintenant. Tu vas devoir réaliser la page ci-dessous sans que je te donnes toutes les étapes.

## Mise en place

1. Copie et colle le code HTML fournit plus bas dans un nouveau fichier HTML.
2. Crée une nouvelle feuille de style et lie-là à ton fichier HTML.
3. Affiche la page dans ton navigateur pour voir le résultat. Tous les éléments sont là mais rien n'est mis en place.
4. Regarde le screenshot plus bas et tente de reproduire le même style.
5. Je te fournis plus bas le code HTML, les couleurs utilisées, quelques indications de taille et le code CSS avec seulement les sélecteurs.
6. Il n'y a pas une bone méthode, si tu veux utiliser tes propres sélecteurs, tu peux!
7. Tu as vus toute la théorie nécessaire à réaliser cet exercices.
8. Souviens-toi, utilise l'inspecteur d'élément pour tester des valeurs directement dans ton navigateur.
9. N'hésite pas à retourner voir la théorie et la documentation en cas de besoin.
10. Essaye d'allez le plus loin possible sans demander de l'aide.
11. Bon courage!

## Screenshot

![exo-css](./img/11/ex-css.png)

![exo-css](./img/11/ex-css-2.png)

## HTML

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Discord</title>
  <!-- insère ici ta feuille de style -->
</head>
<body>
  <header>
    <div class="container">
      <img src="https://raw.githubusercontent.com/sirius-school/metiers-numeriques/main/1-html-css-debutant/assets/discord/logo-discord.png" alt="logo-discord">
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <section>
    <h2>C'est quoi Discord ?</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores eveniet rerum assumenda deleniti consectetur nesciunt inventore debitis possimus ut omnis corporis nam, at alias animi, laudantium et, expedita ipsam? Beatae.</p>
  </section>
  <section>
    <h2>Téléchargez-le!</h2>
    <img src="https://raw.githubusercontent.com/sirius-school/metiers-numeriques/105398fc1ba6231e054fb25a327131a6acd8f539/1-html-css-debutant/assets/discord/illu-discord.svg" alt="">
  </section>
  <footer>
    <div>Mon premier site web qu'avec du HTML et CSS simple</div>
  </footer>
</body>
</html>
```

## Couleurs

- background page: #0f0e17
- texte blanc: #fffffe
- background section: #fffffe
- titre: #ff8906
- background footer: #e53170

## Tailles

- le logo fait 100px de large
- la largeur des sections est de 790px max
- pour ce qui est des marges et padding, utilise les valeurs que tu veux tant que ça ressemble un minimum à ce qu'il y a sur les screenshots

## CSS

```css
body{
  /* insère ton style ici */
}
header .container{
  /* insère ton style ici */
}

header .container img{
  /* insère ton style ici */
}

nav{
  /* insère ton style ici */
}

nav ul {
  /* insère ton style ici */
}

nav li {
  /* insère ton style ici */
}

nav li a {
  /* insère ton style ici */
}

section{
  /* insère ton style ici */
}

h2{
  /* insère ton style ici */
}

p{
  /* insère ton style ici */
}

footer{
  /* insère ton style ici */
}
```

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
