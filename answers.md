# Answers of Nathan Savioz SaviozHES

## Basics
### Task 1
Les changements ont ete faits, mais ils n'ont pas ete ni comit ni push.

### Task 2
-Le message propose en exemple signifie que les donnes personelles ont ete modifiees dans le fichier answers.md
-non, nous ne pouvons pas cree de commit sans message
-Le fichier modifie sont enregistres dans l’historique ainsi que les donnes de l'auteur
-Non, car le fichier n'a pas encore ete push sur git

### Task 3
Nous avons maintenant 2 unstaged files, et lorsque l'on clique sur le depot actuel, 1 untracked files est affiche

### Task 4
Quand on revient au commit « Initial commit », on voit le projet tel qu’il était au tout début : seuls les premiers fichiers sont presents. On est en mode "detache", donc on ne travaille plus sur une branche. En revenant au dernier commit (par exemple via main), on retrouve l’etat actuel complet du projet.

### Task 5
Le depot local permet de travailler et sauvegarder les changements sans connexion Internet (stockee sur notre ordinateur).
Le depot distant, lui, est une version du projet hebergee sur un serveur (comme GitHub) pour partager et collaborer.
Si vous supprimez le depot local, vous perdez tout votre travail sur votre machine, mais le depot distant reste intact et vous pouvez recuperer le projet en le clonant a nouveau.

### Task 6
Non, le depot original qui a ete forke n'a pas ete modifie car toutes les modifications sont faites uniquement sur ta copie (ton fork) et ton depot local.
Tant que tu ne fais pas de pull request et qu'elle n'est pas acceptee, le depot original reste identique a sa version initiale.

## Gitgraph

### Task 7
1. nom de la brache
2. hash de commit
3. message de comit
4. auteur du commit
5. v1.0.0 (tag)
6. dernier comit 
7. branch secondaire (feature-auth)
8. last commit de la branche initiale
9. branch secondaire (develop)
10. branch main
![Gitgraph](img/gitgraph.svg)