# File Share Application

File Share is a simple file-sharing web application. The backend is written in Python, using the Django framework.
This application live at https://goshare- app.herokuapp.com

## Installation

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with.

```bash
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```bash
virtualenv env
```
That will create a new folder env in your project directory. Next activate it with this command on mac/linux:

```bash
env\Scripts\activate
```

Then install the project dependencies with

```bash
pip install -r requirements.txt
```

Now you can run the project with this command


```bash
python manage.py runserver
```
