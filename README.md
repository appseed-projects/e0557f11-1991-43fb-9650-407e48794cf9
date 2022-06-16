# [Volt Dashboard](https://appseed.us/generator/volt-dashboard/) Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Volt Dashboard](https://appseed.us/generator/volt-dashboard/)**, a modern `Bootstrap 5` dashboard design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

- 👉 [Volt Dashboard Flask](https://flask-volt-dashboard.appseed-srv1.com/) - LIVE Demo
- 👉 [Volt Dashboard Flask](https://appseed.us/product/volt-dashboard/flask/) - Product page
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
  - ✅ [Set up the environment](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#environment)
  - ✅ [Start in Docker](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#start-the-app-in-docker)
  - ✅ [Codebase structure](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#codebase-structure)
  - ✅ [UI Assets and Templates](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#ui-assets-and-templates)

<br />

> Built with [Volt Dashboard Generator](https://appseed.us/generator/volt-dashboard/)

- Timestamp: `2022-06-16 03:39`
- Build ID: `e0557f11-1991-43fb-9650-407e48794cf9`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Volt Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168843604-b026fd94-5969-4be7-81ac-5887cf0958e5.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

<br />

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/e0557f11-1991-43fb-9650-407e48794cf9.git
$ cd e0557f11-1991-43fb-9650-407e48794cf9
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Volt Pro is a premium Bootstrap 5 Admin Dashboard featuring over 800 components, 20 example pages and 10 fully customized plugin written in Vanilla Javascript. 

- 👉 [Flask Volt PRO](https://appseed.us/product/volt-dashboard-pro/flask/) - product page
- 👉 [Flask Volt PRO](https://flask-volt-pro.appseed-srv1.com/) - LIVE deployment

<br >

![Volt Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172672843-8c40a801-3438-4e9c-86db-38a34191fbdf.png)

<br />

---
Volt Dashboard Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
