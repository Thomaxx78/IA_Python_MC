# 🎨 Reconnaissance de Chiffres MNIST

<div align="center">

![AI](https://img.shields.io/badge/IA-Machine%20Learning-blue?style=for-the-badge)
![Web](https://img.shields.io/badge/Web-App-green?style=for-the-badge)
![Real-time](https://img.shields.io/badge/Temps-Réel-red?style=for-the-badge)

**🚀 Application web intelligente qui reconnaît vos chiffres manuscrits en temps réel**

[🎯 Essayer la Demo](#utilisation) • [⚙️ Installation](#installation) • [🧠 Comment ça marche](#fonctionnement)

</div>

---

## 🌟 Qu'est-ce que c'est ?

Cette application web utilise l'intelligence artificielle pour **reconnaître instantanément les chiffres** que vous dessinez à la main ! 

Dessinez simplement un chiffre (0 à 9) sur l'écran avec votre souris ou votre doigt, et notre modèle d'IA vous dira immédiatement quel chiffre vous avez écrit avec un pourcentage de confiance.

### ✨ Fonctionnalités

- 🖌️ **Dessinez facilement** sur un canvas interactif
- 🧠 **IA intelligente** qui reconnaît vos chiffres manuscrits  
- ⚡ **Résultats instantanés** - pas d'attente !
- 📱 **Fonctionne partout** - ordinateur, tablette, téléphone
- 🎯 **Très précis** - plus de 94% de réussite
- 🎨 **Interface moderne** et intuitive

---

## 🧠 Comment ça marche ?

### Le Modèle d'Intelligence Artificielle

Notre application utilise un **réseau de neurones convolutionnel (CNN)** - un type d'IA spécialement conçu pour analyser les images. Ce modèle a été :

- 📚 **Entraîné sur 60,000 exemples** de chiffres manuscrits (dataset MNIST)
- 🎯 **Optimisé pour la précision** avec une architecture en 3 couches
- ⚡ **Converti au format web** pour fonctionner directement dans votre navigateur
- 🏆 **Testé et validé** sur 10,000 images supplémentaires

### Le Processus de Reconnaissance

1. **Vous dessinez** un chiffre sur le canvas noir
2. **L'image est traitée** - redimensionnée et nettoyée automatiquement
3. **L'IA analyse** les pixels et compare avec ses connaissances
4. **Le résultat s'affiche** avec le chiffre détecté et sa confiance

---

## 🚀 Installation

### Option Simple (Recommandée)
1. Téléchargez tous les fichiers
2. Ouvrez un terminal dans le dossier
3. Lancez un serveur web local :
   ```bash
   python -m http.server 8000
   ```
4. Ouvrez votre navigateur sur `http://localhost:8000`

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Python installé (pour le serveur local)
- Les fichiers `index.html` et `mnist_cnn.onnx`

---

## 🎯 Utilisation

### C'est très simple !

1. **Ouvrez l'application** dans votre navigateur
2. **Attendez** que le modèle se charge (quelques secondes)
3. **Dessinez un chiffre** (0-9) dans le carré noir
4. **Cliquez sur "Prédire"** 
5. **Admirez le résultat** ! 🎉

### 💡 Conseils pour de meilleurs résultats

- Dessinez des chiffres **clairs et bien formés**
- Utilisez **tout l'espace** du carré de dessin
- **Centrez** votre chiffre dans le carré
- Évitez les traits trop fins ou trop épais

---

## 🏆 Performances

- **Précision** : 98.3% sur les données de test
- **Vitesse** : Prédiction en moins de 50ms
- **Taille** : Modèle léger de ~200KB seulement
- **Compatibilité** : Fonctionne sur tous les navigateurs modernes

---

## 🎓 Aspects Techniques

### Technologies Utilisées

- **PyTorch** - Pour entraîner le modèle d'IA
- **ONNX** - Pour optimiser et exporter le modèle
- **JavaScript** - Pour l'interface web interactive
- **HTML5 Canvas** - Pour le système de dessin
- **ONNX Runtime Web** - Pour faire tourner l'IA dans le navigateur

### Pourquoi MNIST ?

MNIST est le dataset de référence en reconnaissance d'images. Il contient 70,000 images de chiffres manuscrits écrits par des étudiants américains et employés du bureau de recensement, parfait pour apprendre et démontrer les capacités de l'IA !

---

## 🤝 Contribution

Ce projet est parfait pour :
- **Apprendre** le machine learning et le web
- **Comprendre** comment déployer une IA sur le web
- **Expérimenter** avec différents modèles ou interfaces
- **Enseigner** les concepts d'IA de manière interactive

---

<div align="center">

**🎉 Amusez-vous bien avec la reconnaissance de chiffres ! 🎉**

*Créé avec ❤️ pour démontrer la puissance de l'IA accessible à tous*

</div>
