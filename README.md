# Poubelle Intelligente

Ce projet consiste en une application Streamlit intégrée à un serveur FastAPI pour la prédiction de la recyclabilité d'objets à partir d'images.

## Installation

Assurez-vous d'avoir Python installé. Clonez ensuite le dépôt et installez les dépendances :


git clone https://github.com/votre-utilisateur/votre-projet.git
cd votre-projet
pip install -r requirements.txt
fastapi
uvicorn
python-multipart
tensorflow
pillow
streamlit


## Utilisation

1. Exécutez le serveur FastAPI :

  
   uvicorn fastapi_app:app --reload
   

2. Exécutez l'application Streamlit :

   bash
   streamlit run streamlit_app.py
   

3. Ouvrez votre navigateur et accédez à l'URL indiquée par Streamlit pour utiliser l'application.

## Fonctionnalités

- L'utilisateur peut charger une image d'objet.
- L'application envoie l'image à un serveur FastAPI pour la prédiction.
- Le résultat de la prédiction et le pourcentage de confiance sont affichés à l'utilisateur.
- L'interface Streamlit est simple et conviviale.

## Configuration

- L'URL du serveur FastAPI est configurée dans le fichier `streamlit_app.py`.
- Assurez-vous que le serveur FastAPI est accessible depuis l'application Streamlit.

## Remarques

- Veillez à gérer les erreurs et les exceptions, notamment lors de la connexion au serveur FastAPI.
- Assurez-vous d'avoir les autorisations nécessaires pour accéder au serveur FastAPI depuis Streamlit.


