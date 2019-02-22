StackOverflow est un site de question-r�ponses li�es au d�veloppement informatique.
Pour poser une question sur ce site, il faut entrer plusieurs tags de mani�re � retrouver
facilement la question par la suite.  
L�objectif du projet que nous devons r�aliser est de pr�dire les tags associ�s
� une question pos�e par un utilisateur de la plateforme. 



1. Notebooks
"PROJET 6_Entrainement et Pr�dictions.ipynb"
"PROJET 6_Exploration et Pipeline.ipynb"

2. Scripts python
- Fichier pipeline.py
--> � ex�cuter pour construire pipeline et fichiers de sauvegardes n�cessaires
pour le training et la pr�diction

- Fichier modules.py 
--> Fichier contenant les modules qui permettent l'ex�cution des autres scripts

- Fichier training_testing.py 
--> � ex�cuter pour lancer un entrainement et un tester notre mod�le

- Fichier predictions.py
--> On teste notre mod�le avec de nouvelles donn�es utilisateur 

3. R�pertoires
classifiers/logistical_regression
--> Contient les classifieurs suivant mod�le de r�gression logistique au format .pkl

classifiers/naive_bayes
--> Contient les classifieurs suivant mod�le naive Bayes au format .pkl

classifiers/random_forest
--> Contient les classifieurs suivant mod�le de Random Forest au format .pkl

data
--> Contient les donn�es initiales au format .csv

pipeline
--> Contient les �l�ment n�cessaire pour entrainer le mod�le

resources
--> Contient la liste des stopwords

output
--> Fichiers .csv en sortie

scripts
Scripts au format .py

notebooks
Emplacement de nos notebooks


4. Packages � installer
pandas
numpy
scikit-learn
nltk
pyLDAvis
mglearn
seaborn
matplotlib
bs4 (beautifulsoup)

5. Site (API)
Disponible � l�adresse suivante :  http://leftyboy.pythonanywhere.com

6.lien vers projet Github
https://github.com/leftyboy/Projet-6

7. Proc�dure d'�xecution des scripts (se trouvant dans le r�pertoire "scripts")
Ex�cuter le fichier pipeline.py tout d'abord pour cr�er le jeu de donn�es/test pour l'entrainement.
 
Ex�cuter le fichier training_testing.py pour entrainer notre mod�le
avec notre jeu d'entrainement et le tester avec notre jeu de test.

Ex�cuter le fichier predictions.py avec comme argument le fichier "InputQuestions.csv"
qui se trouve dans le r�pertoire "data". Il n'est pas n�cessaire d'ajouter le lien
complet pour acc�der au fichier "InputQuestions.csv"
