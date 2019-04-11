Ce projet a été réalisé par Juliette Rengot et Valéry Dewil, en Mars 2019, dans le cadre du master MVA (Remote sensing data: from sensor to large-scale geospatial data exploitation). Gabriele Facciolo et Enric Meinhardt ont supervisés ce travail.

Ce projet propose une nouvelle approche pour l'estimation de cartes de hauteurs à partir d'images de satellites. L'objectif est d'adapter l'algorithme PatchMatch, initialement conçu pour le traitement d'images, pour estimer les hauteurs du terrain et des bâtiments survolés en une seule étape. L'avantage principal de notre méthode est d'être très rapide.

Le code est diponible dans le notebook "height_estimation.ipynb". Plusieurs modules sont utilisés: "rectification.py" (pour rectifier des paires d'images), "stereo.py", "utils.py" et "vistolls.py" (pour la visualisation).

Le rapport "Projet_Remote_sensing_rapport.pdf" fournit une description complète du projet et des résultats obtenus. Un diaporama de présentation peut être consulté dans le document "PatchMatch_slides.pdf".