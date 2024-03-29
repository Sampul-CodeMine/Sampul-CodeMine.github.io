# PORTFOLIO PROJECT for ALX SE Africa

## app-Secrets

<strong>app-Secrets</strong> as envisaged is an online System that will be designed for users to note or write down certain occurrences or future plans they would love to keep secret and confidential. It is a simple app meant to fulfill the portfolio project requirements for ALX Software Engineering Foundational stage and may likely be used for fun purposes.

From this project, users will have little "Logged Out Experience" and the routes that can be assessed by the user or customer includes:

- The landing page
- The About page
- Login Page
- Registration Page
- Users' Profile

### DEVELOPMENT TOOLS

To develop this application, we have to state some tools that will be used for the software development:

- Django
- MySQL DBMS
- Bootstrap CSS library
- JQuery JavaScript library

First we will create a virtual environment where Django will be installed.

But we need to have Python and Virtual Environment installed

### Install virtual Environment

```shell
$ sudo apt update
$ sudo apt upgrade -y
$ sudo apt install virtualenv -y
```

### Creating a Virtual Environment

```shell
$ virtualenv .secrets
```

### Activating the virtual Environment

```shell
# on a unix based operating system

$ source .secrets/bin/activate
(.secrets) /home/nerd $

# on a windows based operating system
.secrets\Scripts\activate.bat
(.secrets) C:\Users\nerd>
```

### Deactivating a Virtual Environment

```shell
(.secrets) /home/nerd $ deactivate
```

### INSTALLING DEPENDENCIES

We have the following dependencies saved in a file called requirements.txt:

- asgiref==3.7.2
- crispy-bootstrap4==2023.1
- Django==4.2.9
- django-crispy-forms==2.1
- mysqlclient==2.2.4
- pillow==10.2.0
- sqlparse==0.4.4
- typing_extensions==4.9.0

> this was achieved using
>
> ```shell
> (.secrets) /home/nerd $ pip freeze > requirements.txt
> ```

To install all these requirements do the following:

- Activate the virtual environment

```shell
/home/nerd $ source .secrets/bin/activate

(.secrets) /home/nerd $
```

- Install the dependencies

```shell
(.secrets) /home/nerd $ pip install -r requirements.txt
```

### VIEW OF THE APPLICATION'S LANDING PAGE

#### Home Page
<p>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/home1.PNG"><br>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/home2.PNG"><br>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/home3.PNG">
</p>

#### About Page
<p>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/about.PNG">
</p>

#### Contact Page
<p>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/contact.PNG">
</p>

#### Registration Page
<p>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/register.PNG">
</p>

#### Login Page
<p>
<img src="https://github.com/Sampul-CodeMine/Sampul-CodeMine.github.io/blob/master/screens/login.PNG">
</p>


---

### AUTHORS

> Dukeson Ehigboria - [Github](https://github.com/Sampul-CodeMine) / [Twitter](https://twitter.com/Sampul_CodeMine)
>

### License

Public Domain. No copy write protection.

