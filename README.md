# Projet Final - Deep Learning (EMSI)

Ce dépôt contient l'ensemble des travaux pratiques et des projets réalisés dans le cadre du module de Deep Learning. Le projet est structuré en trois grandes parties, explorant différentes architectures de réseaux de neurones (MLP, CNN et RNN) appliquées à des cas d'usage variés.

---

##  Structure du Projet

Le projet est divisé en trois notebooks principaux :

### 1. Partie I : Classification de Revenus avec un Perceptron Multicouche (MLP)
* **Fichier :** `partie1_mlp_adult_income.ipynb`
* **Objectif :** Prédire si le revenu d'un individu dépasse 50k\$/an en se basant sur des données démographiques (Dataset *Adult Income*).
* **Concepts clés :**
  * Prétraitement de données tabulaires (encodage *One-Hot*, normalisation).
  * Gestion du déséquilibre des classes (*Class Weights* / Rééchantillonnage).
  * Conception d'une architecture MLP (Couches denses, Dropout, BatchNorm).
  * Évaluation de la performance (Courbe ROC, Matrice de confusion, F1-Score).

### 2. Partie II : Classification d'Images de Mode avec un Réseau de Neurones Convolutif (CNN)
* **Fichier :** `partie2_cnn_fashionmnist.ipynb`
* **Objectif :** Reconnaître et classifier des vêtements et accessoires à partir d'images en niveaux de gris (Dataset *Fashion-MNIST*).
* **Concepts clés :**
  * Manipulation et augmentation de données d'images (PyTorch `Transforms`).
  * Architecture CNN personnalisée (Convolutions 2D, Max Pooling, Flatten).
  * Analyse des erreurs de prédiction (Visualisation des prédictions correctes vs incorrectes).

### 3. Partie III : Modélisation de Séquences et Traduction avec RNN / Seq2Seq
* **Fichier :** `Partie_III_RNN_Seq2Seq.ipynb`
* **Objectif :** Implémenter et comparer des architectures de réseaux de neurones récurrents pour le traitement du langage naturel (NLP).
* **Concepts clés :**
  * Tokenisation, création de vocabulaire et *Padding* de séquences textuelles.
  * Modèles Récurrents fondamentaux : **RNN**, **LSTM**, et **GRU**.
  * Évaluation de modèles de langage via la métrique de **Perplexité**.
  * Architecture Avancée : Modèle **Seq2Seq** (Encodeur-Décodeur).

---

##  Installation et Utilisation

### Prérequis
Pour exécuter ces notebooks, vous devez disposer d'un environnement Python avec les bibliothèques suivantes installées :
* PyTorch
* Torchvision
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

##  Comment lancer le projet
1. Téléchargez le fichier `Untitled2 (1).ipynb` présent sur ce repository.
2. Ouvrez-le dans **Google Colab**.
3. Exécutez les cellules de code une par une. Les images et les données se téléchargent automatiquement à l'exécution.
