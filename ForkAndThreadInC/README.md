
`fork00.c` :  crée un processus, affiche valeur de retour du `fork()`

`fork01.c` :  crée un processus, puis le père s'arrête et le fils attend 4s avant d'afficher. 
                Illustre la technique fork and die. Utiliser pstree pour observer que le fils est adopté par `systemd` ou `init`

`fork02.c` : fork multiples

`fork03.c` : création  de processus en boucle sans test de la valeur de retour