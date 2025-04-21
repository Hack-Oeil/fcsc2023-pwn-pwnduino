# FCSC 2023 pwnduino

Dans le cadre d’un contrôle d’accès à un système industriel, une board AVR avec un firmware dédié implémente des calculs sur un secret stocké ne devant pas quitter la mémoire interne du microcontrôleur. Pour déclencher ces calculs, il est nécessaire de fournir un mot de passe d’authentification. La console se déconnecte au bout de 10 secondes sans activité.

Lors d’une mission d’audit, on vous demande d’évaluer la sécurité de ce système, et notamment valider que le secret très sensible ne fuite pas. Vous avez réussi à accéder à un serveur de développement sur lequel un binaire de firmware de debug et ses fichiers source sont accessibles. Armé de ces informations, vous pensez pouvoir récupérer ce secret sur le firmware de production !



Fichiers:
- [firmware_debug.bin](firmware_debug.bin)
- [pwnduino-src-debug.tar.xz](pwnduino-src-debug.tar.xz)



Auteur : rbe


Origine : [pwnduino](https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-pwnduino/)



-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc pwnduino.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2023-pwn-pwnduino.git

> cd fcsc2023-pwn-pwnduino


-----------


## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-pwnduino/