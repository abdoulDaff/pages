# PAGES

## Initial Set Up

• navigate to your **_desktop_**
• make a new directory in your **_desktop_** called **_code_** and navigate into it
• make a new directory in **_code_** called **_pages_** and navigate into it  
• create a new virtual environment called **.venv** and activate it  
• install Django  
• create a new Django project called django_project  
• create a new app called pages

```Shell
# Windows (powershell)
> cd desktop
> mkdir code
> cd code
> mkdir pages
> cd pages
> python -m venv .venv
> .venv\Scripts\Activate.ps1
(.venv) > python -m pip install django~=4.0.0
(.venv) > django-admin startproject django_project .
(.venv) > python manage.py startapp pages

# macOS
% cd ~/desktop
% mkdir code
% cd code
% mkdir pages
% cd pages
% python3 -m venv .venv
% source .venv/bin/activate
(.venv) % python3 -m pip install django~=4.0.0
(.venv) % django-admin startproject django_project .
(.venv) % python3 manage.py startapp pages
```

## Git and GitHub

### Create a new repository on the command line

```echo "# pages" >> README.md
> git init
> git add README.md
> git commit -m "first commit"
> git branch -M main
> git remote add origin https://github.com/abdoulDaff/pages.git
> git push -u origin main
```

### Push an existing repository from the command line

```CMD:
> git remote add origin https://github.com/abdoulDaff/pages.git
> git branch -M main
> git push -u origin main
```
