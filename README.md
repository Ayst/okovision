# OKOVISION
Interface web de supervison d'une chaudiere Okofen

# Quelle chaudiere ?
Pour ma part, j'ai une chaudiere Pellomatic. Elle est relié au reseau IP de mon installation via son port ethernet
Ainsi je recupere le log généré toutes les 2 heures et je les integre dans ma bdd.

# Quelle techno ?
Js + PHP + MariaDb, le tout sur un nas Synology.
Mais vous pouvez le faire tourner sur une RPI où n'importe quelle distrib linux.

# Mais pourquoi ?
Parce que...
pour mieux suivre le fonctionnement de la chaudiere, afin d'affiner le reglage, il est important de pouvoir
mettre en graphique toutes les informations fournies par la chaudiere.
J'ai donc mis au point cette application web. Elle me permet d'analyser et de suivre ma consommation de pellet.


