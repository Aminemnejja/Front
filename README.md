# Calcul Matriciel avec Streamlit et Flask

Bienvenue dans le projet de calcul matriciel, une application conviviale qui combine l'efficacité des algorithmes matriciels du dossier `Functions` avec une interface utilisateur attrayante construite à l'aide de Streamlit pour le front-end et Flask pour le back-end.

## Structure du Projet

- **Functions/** : Ce répertoire regroupe des algorithmes de calcul matriciel réutilisables.
- **FrontBack/** : Contient le serveur backend (Flask) et l'affichage des résultats avec Streamlit.
- **Flask.py** : Implémente les requêtes GET pour récupérer des matrices.
- **flaskapp.py** : Initialise le serveur backend avec prise en charge de CORS.
- **menu.py** : Fichier principal pour exécuter l'interface utilisateur Streamlit.

## Utilisation

Pour accéder à l'interface utilisateur, [cliquez ici](https://ppywgxapdvurynzbbqi4dq.streamlit.app/).



## Installation

Clonez le dépôt et installez les dépendances avec les commandes suivantes :
Assurez-vous d'avoir Python installé sur votre machine avant d'exécuter ces commandes.
N'hésitez pas à explorer les différents dossiers et fichiers pour découvrir les fonctionnalités et les algorithmes matriciels proposés.

```bash
git clone https://github.com/Aminemnejja/Front
cd Front
pip install -r requirements.txt
streamlit run menu.py


