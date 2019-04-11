Ce projet a �t� r�alis� par Juliette Rengot et Val�ry Dewil, en Mars 2019, dans le cadre du master MVA (Remote sensing data: from sensor to large-scale geospatial data exploitation). Gabriele Facciolo et Enric Meinhardt ont supervis�s ce travail.

Ce projet propose une nouvelle approche pour l'estimation de cartes de hauteurs � partir d'images de satellites. L'objectif est d'adapter l'algorithme PatchMatch, initialement con�u pour le traitement d'images, pour estimer les hauteurs du terrain et des b�timents survol�s en une seule �tape. L'avantage principal de notre m�thode est d'�tre tr�s rapide.

Le code est diponible dans le notebook "height_estimation.ipynb". Plusieurs modules sont utilis�s: "rectification.py" (pour rectifier des paires d'images), "stereo.py", "utils.py" et "vistolls.py" (pour la visualisation).

Le rapport "Projet_Remote_sensing_rapport.pdf" fournit une description compl�te du projet et des r�sultats obtenus. Un diaporama de pr�sentation peut �tre consult� dans le document "PatchMatch_slides.pdf".