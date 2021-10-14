1. il est conseillé de créer un nouvel environnement python pour éviter les conflits sinon effectuer uniquement les étape 3. 5. et 6. :

`python3 -m venv ./PyP3/`

2. activer l'environnement :

`source ./PyP3/bin/activate`

3. installer les dépendances:

`pip install -r requiremements.txt`

4. ajouter le noyau pour jupyter :

`./PyP3/bin/python -m ipykernel install --user --name 'PyP3'`

5. ouvrir le notebook 

`jupyter notebook ./P3_01_notebooknettoyage.ipynb`

6. changer le noyau dans jupyter : / Noyau / Changer le noyau / PyP3
