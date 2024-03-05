# Calcul Matriciel avec Streamlit et Flask

Bienvenue dans le projet de calcul matriciel, une application conviviale qui combine l'efficacité des algorithmes matriciels du dossier `Functions` avec une interface utilisateur attrayante construite à l'aide de Streamlit pour le front-end et Flask pour le back-end.

#Contexte Académique
Ce projet a été réalisé par une équipe d'étudiants sous la supervision du Dr. Sirine MARRAKCHI dans le cadre de la matière "Algorithmes Numériques". Il fait partie du programme du cycle d'ingénieur en informatique et communications à la Faculté des Sciences de Sfax.
#Equipe
Ce projet a été réalisé par une équipe composée des membres suivants :

Amine Mnejja
Ali Cheffi
Hana Kanoun
Iyed Djebbi
## Structure du Projet

- **Functions/** : Ce répertoire regroupe des algorithmes de calcul matriciel réutilisables.
- **FrontBack/** : Contient le serveur backend (Flask) et l'affichage des résultats avec Streamlit.
- **Flask.py** : Implémente les requêtes GET pour récupérer des matrices.
- **flaskapp.py** : Initialise le serveur backend avec prise en charge de CORS.
- **menu.py** : Fichier principal pour exécuter l'interface utilisateur Streamlit.

## Utilisation


Pour accéder à l'interface utilisateur, [cliquez ici](https://ppywgxapdvurynzbbqi4dq.streamlit.app/).

![Capture d’écran 2024-03-05 003154](https://github.com/Aminemnejja/Front/assets/101280583/45a898cd-d737-4f8f-93c5-d02118380bbc)

![image](https://github.com/Aminemnejja/Front/assets/101280583/269e76fc-c4ad-4eed-8b7d-45ec1789887e)

## Installation

Clonez le dépôt et installez les dépendances avec les commandes suivantes :
Assurez-vous d'avoir Python installé sur votre machine avant d'exécuter ces commandes.
N'hésitez pas à explorer les différents dossiers et fichiers pour découvrir les fonctionnalités et les algorithmes matriciels proposés.

```bash
git clone https://github.com/Aminemnejja/Front
cd Front
pip install -r requirements.txt
streamlit run menu.py


