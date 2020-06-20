# Virtualenv

Crée un virtualenv Python et y installe les paquets requis.

## Configuration

Les paramètres génériques suivants permettent d'indiquer où et avec quel Python
créer le virtualenv, et quelles dépendances y installer.

| Variable                     | Description                                              |
|------------------------------|----------------------------------------------------------|
| virtualenv_directory         | Chemin où créer le virtualenv                            |
| python_version               | Version de l'exécutable Python à utiliser                |
| virtualenv_packages          | Une liste de paquets à installer dans le venv            |
| virtualenv_requirements_txt  | Le chemin d'un fichier requirements.txt                  |
| virtualenv_pipfile_directory | Le chemin d'un dossier contenant Pipfile et Pipfile.lock |
