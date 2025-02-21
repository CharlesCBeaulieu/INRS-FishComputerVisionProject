# **INRS - Fish Computer Vision Project** 🐟🎥  

## **Institut National de la Recherche Scientifique (INRS) - Centre Eau Terre Environnement, Québec**  

### **Filière** : Science Informatique  
### **Projet** : Détection, Identification, Classification et Journalisation Automatique des Poissons avec le Machine Learning  

### **Présenté par :**  
📌 *Charles Beaulieu*  

### **Sous la direction des professeurs :**  
👨‍🏫 *Normand Bergeron (INRS)*  
👨‍🏫 *Erwan Gloaguen (INRS)*  
👨‍🏫 *Usef Faghihi (UQTR)*  

---

## **À propos du projet** 🎯  
Ce projet a été réalisé dans le cadre de mon stage d’été 2022 au sein de l’INRS (*Institut National de la Recherche Scientifique*). Il vise à développer une solution d’apprentissage profond pour **la détection, l'identification, la classification et la journalisation automatique des poissons** à partir d’images vidéo capturées dans un passage à poissons.  

Le projet est structuré en **trois notebooks Colab**, chacun ayant un rôle spécifique dans la pipeline de traitement vidéo :  

1. **📌 Filter Algorithm And More (Prétraitement des vidéos)**
2. **📌 YOLOv5 Custom Training (Détection des poissons)**
3. **📌 YOLOv5 & StrongSORT (Tracking et comptage des poissons)**  

---

## **📂 Détails des notebooks**  

### **1️⃣ Filter Algorithm And More (Prétraitement des vidéos) 🎞️**  
- Contient des **fonctions de traitement vidéo** et d’**extraction des caractéristiques** des vidéos et fichiers.  
- Implémente la fonction clé **background_substraction** qui permet de trier les données brutes en supprimant l’arrière-plan.  

🔗 **Lien vers le notebook :**  
[Colab - Filter Algorithm And More](https://colab.research.google.com/drive/127TmPbFmqgPNCnvwOfWUyizulDDJELu1?usp=sharing)  

---

### **2️⃣ YOLOv5 Custom Training (Détection des poissons) 🖼️**  
- Permet d’**importer un jeu de données personnalisé** via **Roboflow**.  
- Contient les scripts nécessaires pour **entraîner un modèle YOLOv5** sur ce dataset.  
- Intègre l’outil **Weights & Biases (WandB)** pour **suivre les entraînements en temps réel**.  

🔗 **Lien vers le notebook :**  
[Colab - YOLOv5 Custom Training](https://colab.research.google.com/drive/1jE2fDWlTREdMXsdHkqJ63_q6nu2Xywxx?usp=sharing)  

---

### **3️⃣ YOLOv5 & StrongSORT (Tracking et comptage) 🔢**  
- Associe **YOLOv5** avec **StrongSORT**, un algorithme avancé de **suivi des objets**.  
- Implémente un système de **comptage automatique des poissons** à l’aide d’un fichier **Track.py modifié**.  
  ⚠️ *Il est important d’utiliser la version modifiée de ce fichier pour garantir le bon fonctionnement du comptage vidéo !*  

🔗 **Lien vers le notebook :**  
[Colab - YOLOv5 & StrongSORT](https://colab.research.google.com/drive/1xqwae8afRIfQo-XvHKN9INI7nseNKGfS?usp=sharing)  

---

## **📬 Contact**  
📧 **Email** :  
- [Charles.beaulieu@INRS.ca](mailto:Charles.beaulieu@INRS.ca)  
- [Charles.c.beaulieu@UQTR.ca](mailto:Charles.c.beaulieu@UQTR.ca)  

---

### **📌 Notes complémentaires :**  
✔️ Ce projet s’inscrit dans une approche **d’automatisation et d’analyse** des flux migratoires des poissons via des méthodes d’**apprentissage profond**.  
✔️ Il pourrait être amélioré en explorant **d’autres modèles de détection et de suivi**, ainsi qu’en intégrant **des techniques d’optimisation des performances**.  

---
