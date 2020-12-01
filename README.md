# Projet_MPG
The goal of this project is to create a shiny app that can advice the user in his mercato process in the french video game called MPG. 

### Objectif du projet : #####

Créer une application shiny qui conseillera les joueurs du jeu de football virtuel MPG.


### Principe du jeu : ######

Ce jeu oppose differents utilisateurs en ligne qui s'affronte lors de matchs virtuels.
Les performances des joueurs de chaque équipes sont directement liées au performances réelles de ces joueurs chaque weekend. 

Par exemple, Kylian Mbappe (joueur de PSG) marque dans la réalité contre Marseille lors des matchs hebdomadaires du championnat de football francais. Alors le joueur qui possède Kylian Mbappe dans son equipe marque également un but MPG, cette fois virtuel, contre son adversaire du jour.

Avoir une équipe avec des joueurs performants qui marquent souvent et réalisent des bonnes performances chaque weekend est donc primordial. 

La conception des équipes se fait lors d'un étape de Mercato en début de jeu. Durant cette étape, chaque joueur enchère sur les joueurs qu'ils désirent avec un budget limité. Le joueur avec l'enchère la plus élevée remporte le joueur. L'étape du mercato se répète jusqu'a ce que tous les joueurs aient une équipe complète. 


### But de l'application : ######

L'application shiny à donc pour but de conseiller l'utilisateur dans la réalisation de son mercato.

L'utilisateur peut indiquer le nombre de joueurs qu'il désire à chaque poste, et le nom des joueurs qu'il souhaite spécifiquement avoir dans son équipe. 

Puis, selon les critères choisis et dans la limite du budget, l'application affiche grâce à un alogrithme d'optimisation le mercato ideal permettant d'avoir les joueurs avec le meilleure ratio performance/prix.

L'application conseille aussi à l'utilisateur le montant à miser pour maximiser les chances d'obtention du joueur. 
