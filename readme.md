# Tournois Dogfight BFR - Sierra Hotel
Classement des pilotes des tournois Dogfight BFR.

## Etablissement du classement
Classement établi sur une base de calcul ELO, proposée par CoubyStark.
Principe du classement ELO : [Wikipédia - Classement ELO](https://fr.wikipedia.org/wiki/Classement_Elo)
Eléments de calcul retenus :
- K = 60 jusqu’au 10ème match du joueur,
- K = 20 pour un classement Elo en dessous de 2 400 Elo,
- K = 10 pour un classement Elo au-dessus de 2 400
- Bonus 1/6ème de K si victoire de match sans mort (2 - 0)
- En cas de défaite pour tout ELO inférieur à 1100, pas de pénalisation, ELO incrémenté de 1 par match

## Données brutes
Elles se trouvent dans le fichier **data\bfr_1v1_raw_data.csv**.
En cas d'erreur, ne pas hésiter à ouvrir un ticket.

## Infos sur le tournoi
Site organisant les tournois : https://bullseye-francophone.fr
Discord BFR : https://discord.gg/8mpyQxPaZf
Streams des tournois :
- https://www.twitch.tv/0cage0
- https://www.twitch.tv/thefrencheagle

## En travaux
- exploitation de plus data (nombre de saisons jouées, de tournois joués...)
- data supplémentaires de gun hit à partir des ACMIs lorsque disponibles
- pages individuelles des pilotes comprenant leurs résultats dans les tournois lorsque finalistes, évolutions du ELO et classement
- ajout des présentations et infos des pilotes
