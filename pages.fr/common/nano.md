# nano

> Éditeur de texte simple et convivial. C'est un clone libre et amélioré de Pico.
> Plus d'informations : <https://nano-editor.org/dist/latest/nano.html>.

- Ouvre un fichier :

`nano {{chemin/vers/fichier}}`

- Ouvre un fichier en positionnant le curseur à une rangée et colonne donnée :

`nano +{{ligne}},{{colonne}} {{chemin/vers/fichier}}`

- Active le défilement fluide :

`nano {{[-S|--softwrap]}} {{fichier}}`

- Indente les nouvelles lignes à la même indentation que les lignes précédentes :

`nano {{[-i|--autoindent]}} {{fichier}}`

- Avant la modification, sauvegarde le fichier actuel sous le format `nom_du_fichier_actuel~` :

`nano {{[-B|--backup]}} {{fichier}}`
