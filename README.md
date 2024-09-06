# Portfolio_Django

### 1. Clonner le Repo

### 2. `python -m venv .venv`

peut nécessité le passage par CMD (Crée le fichier .venv)

### 3. `.venv\Scripts\activate`

EN ADMIN : `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned` en cas d'erreur
([détail](https://tutorial.djangogirls.org/fr/django_installation/))

Résultat : 

$\color{rgba(100,255,100, 0.75)}{\textsf{(.venv)}}$ PS C:\Users...\Portfolio_Django> |

On peux aussi (Si c'est un problème de l'éditeur) `$ . .venv\Scripts\activate.ps1`
(lance l'environnement virtuelle)

### 4. `python -m pip install --upgrade pip`

(met à jour pip)

### 5. `pip install -r requirementsR.txt`

```pip freeze > requirementsR.txt``` pour remplir automatiquement le requirementsR

### 6. ~~`django-admin startproject Portfolio_Django`~~ (déjà fait)

django-admin --help

django-admin help ...
(Créé le dossier Portfolio_Django/Portfolio_Django, le manage.py, init, settings, url , ...)

### 7. `cd src`

### 8. `python manage.py runserver`

python manage.py migrate
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)
  (Demarre le serveur)

```
djangocms myCMSproject
$ cd C:\Users...\Portfolio_Django\myCMSproject
$ python -m manage runserver
```

## Lancement / Setup / Deploy : 


```zsh
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
`(.venv)` pip install -r requirementsR.txt
pip install -r requirementsR.txt
cd src
python manage.py runserver
```
