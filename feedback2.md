# Feedback pour l'Apprenant 2

**Félicitations** ! Tu as presque terminé le parcours 👍. Je suppose qu'il t'a manqué un peu de temps pour terminer l'étape 3.4. En tout cas, tu as bien assimilé les principes abordés dans ce parcours. Tu es capable de manipuler les données de manière correcte et tu as réussi à mettre en place les sessions.

---

## Axes d'amélioration :

- Il y a quelques sauts de ligne en trop, notamment dans le router. Je te conseille d'utiliser l'extension Prettier pour formater automatiquement tes fichiers lorsque tu les enregistres. Cela te fera gagner beaucoup de temps !

- Dans le fichier `dataMapper.js`, la fonction `getElements` pourrait être plus explicite, par exemple en l'appelant `getCardsByElement`. Le choix des noms est crucial pour la compréhension et la lisibilité de ton code. Pour éviter toute confusion, il existe des conventions bien établies à ce sujet. Je t'invite à consulter ce lien : [Naming Conventions 101 for Developers](https://medium.com/swlh/naming-conventions-101-for-developers-8997bb96fd60).

- Dans le fichier `cardsController.js`, c'est dommage d'avoir appelé la fonction "item" alors que les autres contrôleurs ont des noms plus appropriés.

- Dans le fichier `deckController.js`, tu as deux constantes inutilisées (`request` et `client`). Je te conseille de toujours relire ton code avant de présenter le résultat final. Ce genre d'oubli arrive régulièrement, même aux développeurs expérimentés, comme des `console.log` ou du code commenté. En plus, cela te permet de vérifier si tu peux améliorer la lisibilité de ton code et la clarté de tes noms de variables.

- Il n'y a pas de limite de cartes dans le deck. Une simple vérification dans le fichier `deckController.js` peut y être ajoutée.

- Le fait qu'on ne puisse pas supprimer les cartes du deck est un point à noter. Je suis sûr qu'avec un peu plus de temps, tu aurais pu le mettre en œuvre.

---

## En conclusion :

Les bases sont acquises, et c'est ce qui compte le plus. Je comprends que cela puisse être frustrant de ne pas avoir eu le temps de finir à temps. Si tu t'es bloqué à une étape particulière, nous pouvons revoir ensemble la notion qui t'a posé problème en détail. Si c'est simplement un manque de temps, je peux te donner des conseils et des bonnes pratiques pour gagner en efficacité. 🙂

Dans tous les cas, n'hésite pas à me solliciter. Nous pouvons même terminer la dernière étape ensemble, il ne manque pas grand-chose ! 😉
