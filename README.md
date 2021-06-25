# Projet_Programmation_systeme
PROJET PROGRAMMATION SYSTÈME SH13

Description générale de projet 

L’objectif de ce projet est de fabriquer une application pour le jeu Sherlock 13. Il se joue avec un serveur et 4 clients.
Le fichier Rapport.pdf est le rapport de programmation correspondant

#Dépendances 
Sur une distribution debian il est nécessaire (en plus de gcc) d'avoir installé les libs SDL2 Classiques ainsi que les add-ons image et ttf.
Le plus simple est d'éxecuter cette commande :
`sudo apt install libsdl2-2.0-0 libsdl2-image-2.0-0 libsdl2-ttf-2.0-0 libsdl2-ttf-dev libsdl2-image-dev`

#Compilation
Pour compiler le projet il est nécessaire d'excecuter le script cmd.sh comme ceci :
`./cmd.sh`

#Execution
Poue executer le serveur il faut taper la commande avec le numeros de port.
Exemple : `./server 32000`

Pour le client il faut les arguments suivants :
- adresse du serveur
- port d'écoute du serveur
- adresse du client (votre machine)
- port d'écoute du client (pour recevoir les messages du serveur)
- nom du joueur

Exemple (local) : `./sh13 localhost 32000 localhost 32001 TOTO`
