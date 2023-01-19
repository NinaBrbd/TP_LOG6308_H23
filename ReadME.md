# LOG6308

![Python](https://img.shields.io/badge/Python-blue)![Jup](https://img.shields.io/badge/JupyterNotebook-orange)

## Installer Python

Il suffit de télécharger la bonne version de `Python3.8` compatible avec votre système d'exploitation sur le [site officiel de Python](https://www.python.org/downloads/release/python-380/).

## Installer Visual Studio Code

Il suffit de télécharger `VSCode` sur le [site officiel](https://code.visualstudio.com/download).

Voici un lien vers un [tutoriel](https://code.visualstudio.com/docs/languages/python#:~:text=Install%20Python%20and%20the%20Python%20extension&text=For%20a%20quick%20install%2C%20use,the%20Python%3A%20Select%20Interpreter%20command.) de `VSCode` avec `Python` qui est assez utile.

#### Extensions Utiles à VSCode

- Python
- Jupyter
- Pylance
- Intellicode
- Python Environment Manager

## Environnement Virtuel en Python

*Ce petit tuto express est inspiré par [ce tutoriel en ligne](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/).*

Pour installer `virtualenvironment` taper ceci dans votre ligne de commande préférée

```bash
pip install virtualenv
```

### Création d'Environnement

Pour créer un environnement, assurer vous d'être dans le fichier racine du projet sur lequel vous souhaitez travailler, puis taper la commande suivante `<virtual-environment-name>` par le nom souhaiter de votre environnement, comme par exemple **envtp1**

```bash
python -m venv <virtual-environment-name>
```

### Requirements

Une fois l'environnement activé, vous pouvez générer un fichier avec toutes les dépendances des librairies que vous avez utiliser grâce à cette commande

```bash
pip freeze > requirements.txt
```

 ## License

Copyrights 2023 team LOG6308.

## Auteurs

- Professeur Michel Desmarais, [michel.desmarais@polypolymtl.ca](mailto:michel.desmarais@polymtl.ca).

- Jean-Charles LAYOUN, [jean-charles.layoun@polymtl.ca](mailto:jean-charles.layoun@polymtl.ca).