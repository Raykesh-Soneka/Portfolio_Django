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

~~djangocms myCMSproject~~ (déjà fait)

$ cd C:\Users...\Portfolio_Django\myCMSproject

```
cd myCMSproject
$ python -m manage runserver
```
[django CMS](/myCMSproject/README.md)

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

## Django CMS

page Admin : http://127.0.0.1:8000/fr/admin/cms/pagecontent/
$ cd C:\Users...\Portfolio_Django\myCMSproject

```
cd myCMSproject
$ python -m manage runserver 127.0.0.1:8001

```
En cas de problème un autre doc est disponible : [django CMS](/myCMSproject/README.md)

Utilisateur : 
`Visiteur`
MDP : 
`Ce mot de passe est trop court. Il doit contenir au minimum 8 caractères.`