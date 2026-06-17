#  Projet Final de Deep Learning (PyTorch)

## Idée Générale du Projet
Ce projet contient mon travail d'évaluation final sur l'apprentissage profond avec **PyTorch**. Il est divisé en 3 parties principales :

1. **Partie I : Analyse de données (MLP)**
   - **Objectif :** Prédire si un logement en Californie est cher ou non (Classification binaire).
   - **Technique :** Création d'un réseau de neurones classique (Multi-Layer Perceptron), gestion de la sauvegarde du meilleur modèle, et affichage des graphiques de performance.

2. **Partie II : Reconnaissance d'images (CNN)**
   - **Objectif :** Reconnaître et classer des images en couleur (avions, voitures, oiseaux, etc.) du dataset **CIFAR-10**.
   - **Technique :** Création d'un réseau de neurones convolutif (CNN). Cette partie contient aussi du code écrit manuellement (sans PyTorch) pour comprendre le fonctionnement de la convolution et du pooling.

3. **Partie III : Traduction automatique (NLP)**
   - **Objectif :** Traduire des phrases simples du Français vers l'Anglais.
   - **Technique :** Utilisation d'un modèle de type *Seq2Seq* (Séquence à Séquence) avec un mécanisme d'Attention pour lier les mots correctement.

---

##  Structure du Repository
* `Untitled2 (1).ipynb` : Le fichier contenant tout le code source, les entraînements et les résultats visuels.
* `README.md` : Ce fichier texte qui explique le projet.

---

##  Outils utilisés
* **Framework principal :** PyTorch
* **Visualisation :** Matplotlib et Seaborn (pour les courbes de perte et les matrices de confusion)
* **Traitement de données :** Pandas, NumPy et Scikit-Learn

---

##  Comment lancer le projet
1. Téléchargez le fichier `Untitled2 (1).ipynb` présent sur ce repository.
2. Ouvrez-le dans **Google Colab**.
3. Exécutez les cellules de code une par une. Les images et les données se téléchargent automatiquement à l'exécution.
