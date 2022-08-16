# INRS-FishComputerVisionProject

Institut National de la Recherche Scientifique Centre Eau Terre Environnement Québec

**Filière** : Science Informatique

**Projet** : Détection, Identification, Classification et Journalisation Automatique des Poissons dans le Passage des Poissons avec le Machine Learning

**Présenté par :** 
Charles BEAULIEU

**Sous la Direction des Professeurs :** 
Normand BERGERON (INRS)
Erwan GLOAGUEN (INRS)
Usef FAGHIHI (UQTR)

Ce travail est rédigé dans le cadre de mon stage de l’été 2022 au sein de l’INRS (Institut National de la Recherche Scientifique). Le projet vise à développer une application d’apprentissage profond permettant la détection, l'identification, la classification et la journalisation automatisé des poissons sur les images vidéo.

Le projet se compose de 3 différents NoteBook (colab)

* Filter Algorithm And More (Filter)
* YOLOV5 Custom Trainning (Detection)
* YoloV5 and StrongSort(Tracking)

**Filter Algorithm And More (Filter) =>**
Contient des fonctions pour le traitement vidéo et l'extraction des caractéristique des videos et des fichiers, mais principalement la fonction qui permet de trier les données brute "backgound_substraction"

**YOLOV5 Custom Trainning (Detection) =>**
Contient le necessaire pour importer un jeu de données personnalisés à partir de robotflow, puis entrainer un modèle YoloV5 sur ce jeu. Contient aussi ce qu'il faut afin de suivre les entrainements en direct grâce à la plateforme weight and biaise (WandB).

**YoloV5 and StrongSort(Tracking) =>**
Contient ce qu'il faut pour combiner notre modèle YoloV5 déjà entrainer avec le modèle StrongSort qui prend en charge le tracking des objets. De plus, ce noteBook prend en charge le comptage des individu à l'aide d'un ficher Track.py modifier (il est important d'utiliser la version modifier pour que le vidéo comptage fonctionne). 
