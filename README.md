# InitChecker
## Checker pour le projet Init de l'ecole 42.
![InitChecker](https://zupimages.net/up/19/02/hcfw.png)
<p align="center">
  <b>Petit checker pour le projet Init de 42.</b><br>
</p>

## options

#### `--path` + *`$PATH`*

Specify the absolute path of directory of your init project.

#### `--part` + *`$PART`*

This option is used to activate some tests you should specify parts you want to test separated by spaces or as letter or number.
(This option activate the non interactive mode)

| Name    | Numbers | Letter | Option  | Long Option |
| ------- | ------- | ------ | ------- | ----------- |
| network | 1       | n      | `--net` | `--network` |
| system  | 2       | o      | `--sys` | `--system`  |
| script  | 3       | s      | `--scr` | `--script`  |
| credits | 4       | c      | `--cre` | `--credits` |

e.g.:  
	`bash initchecker --part 13`  
	`bash initchecker --part ns`  
	`bash initchecker --part network script`  
	`bash initchecker --network --script`  

#### `--no-interactive`

Do not run the script in interactive mode.

#### `--no-colors`

Do not display color tags.

### ATTENTION
Ce checker ne detient absolument pas la verité absolue.
Ce checker donne une idée des resultats obtenus en verifiant les commandes réalisées par l'eleve.
En cas d'erreur un affichage de la commande permet au correcteur de comprendre ce qui ne va pas.
