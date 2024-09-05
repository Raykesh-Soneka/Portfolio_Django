# Portfolio_Django

### 1. Clonner le Repo

### 2. python -m venv .venv

peut nécessité le passage par CMD 

### 3. .venv\Scripts\activate

EN ADMIN : `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned` en cas d'erreur

[détail](https://tutorial.djangogirls.org/fr/django_installation/)

Résultat : 

$\color{rgba(100,255,100, 0.75)}{\textsf{(.venv)}}$ PS C:\Users...\Portfolio_Django> |

On peux aussi (Si c'est un problème de l'éditeur) `$ . .venv\Scripts\activate.ps1`

### 4. python -m pip install --upgrade pip

### 5. pip install -r requirementsR.txt

```pip freeze > requirementsR.txt``` pour remplir automatiquement le requirementsR

### 5. django-admin startproject Portfolio_Django

django-admin --help
django-admin help ...

### 6. cd src

### 7. python manage.py runserver

## Lancement / Setup / Deploy : 


```zsh
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
`(.venv)` pip install -r requirementsR.txt
pip install -r requirementsR.txt
```
