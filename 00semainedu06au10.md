Lundi-06-01

grant select, create, on skila to « user1 » @ ‘localhost’;

grant all privileges on

alter : modifier

add

modifie : modifier element dans une colonne

comment

revoke : enlever un droit, ex : revoke select

read : table en lecture uniquement

write : inaccessible

lever le verrou avec unlock

grant references : droit de créer une clef primaire

drop : supprimer une table

delete : supprimer les donnés d’une table

documentation create engine remplacer pymysql ? car problème import pymysql « no module found »

mardi-07-01

telechargement de tableau public data visualisation avec matplotlib :

import matplotlib.pyplot as plt

views = [300, 40, 256, 444, 326, 277, 33] days = range (1,8)

plt.plot(days, views, label = "Running stats ») : element dans le graphique plt.xlabel("Days") plt.ylabel("Running km") plt.legend(loc = "upper left") plt.title("Matplotlib test") plt.show()

dashploty : viz

mercredi-08-01

debloquage pymysql telechargement pycharm installation pygame -présentation projet de groupe Micropousse

vendredi-10-01

veille : meetup, thèmes data, python, tech atelier en groupe : git partagé, readthedocs, devdaata*6 atelier en groupe : mise a jour google sheet, stage, export des données dans un fichier csv

Veille Meetup : Voir si ya pas des événements au niveau DATA

google sheet : liste 1ere ligne = occurence 2eme ligne = objet

PROJET PERSO: (ouvrir une fenetre pour un jeu)

import pygame import

pygame.init()

surface = 500 surfaceH = 800

surface = pygame.display.set_mode((surface,surfaceH)) pygame.display.set_caption("çapoussé")

game_over = False

while not game_over: for event in pygame.event.get(): if event.type == pygame.QUIT: game_over = True

pygame.quit() quit()
