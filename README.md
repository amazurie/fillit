# fillit

Fillit is about searching for the optimal solution among a huge set of possibilities.

Fillit ne consiste pas à recoder Tetris, mais reste une variante du jeu dans l’esprit.
Le programme prendra en paramètre un fichier décrivant une liste de Tetriminos qu’il devra ensuite agencer entre eux pour
former le plus petit carré possible.

Ce programme doit respecter un nombre de règles parmis celle-ci :

Les fonctions autorisées sont : exit, open, close, write, read, malloc et free.
Le Makefile doit compiler avec au moins les règles suivantes: all, clean, fclean et re.
L'executable devra compiler avec les flags Wall, Wextra et Werror.
Tout autre flag, et en particulier d’optimisation, est interdit.
