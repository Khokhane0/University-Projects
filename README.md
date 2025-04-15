# 🚗 YOLOv8 - Détection de Voitures avec Streamlit

Ce projet est une application web simple qui utilise **YOLOv8** et **Streamlit** pour détecter les voitures dans une image.

## 🎯 Objectif

- L’utilisateur téléverse une image
- Le modèle détecte les voitures (classe "car")
- Les résultats sont affichés dans l’interface
- L’image annotée peut être téléchargée

## 📦 Installation

1. **Cloner le dépôt** :

```bash
git clone https://github.com/Khokhane0/yolo8_voiture_app.git
cd yolo8_voiture_app

2. **Créer et activer un environnement virtuel** :

python -m venv env
# Windows
env\Scripts\activate
# macOS/Linux
source env/bin/activate

3. **Installer les dépendances** :

pip install -r requirements.txt

4. **Lancer l’application** :

streamlit run app.py

