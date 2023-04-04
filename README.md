Project name: PATIENT RECORD SYSTEM

This project is about record keeping in hospitals. To reduce the volumnious work of staff, and
to reduce time wastage and to get things done on time.

link to the deployed project:
https://totybeca.github.io/


Assignment
==========

change to working directory
```$ cd .```

update python packages
```$ python -m pip install -U pip setuptools wheel ```

create virtual environment
```$ python -m venv venv```

Activate virtual environment on windows
```$ venv/Scripts/activate```

Activate virtual environment on linux
```$ source venv/bin/activate```

Install python packages
```(venv) $ python -m pip install -r requirements.txt```

Create database repository
```(venv) $ flask db init```

Migration
```(venv) $ flask db migrate -m "users table"```
```(venv) $ flask db upgrade```

Setup environment. replace export with set on windows.
Don't worry about this, it is handled in .flaskenv
```(venv) $ export FLASK_APP=main.py```
```(venv) $ export FLASK_PORT=```

Start server
```(venv) $ flask run```


SCREENSHOTS OF THE PROJECT LANDING PAGE
![landingpage1](https://user-images.githubusercontent.com/106770765/229877903-3fa69d86-e09c-4cc3-a92e-c982a5cee047.jpg)
![landingpage2](https://user-images.githubusercontent.com/106770765/229877973-31e302f3-3547-4626-8f93-0d6e52f378ec.jpg)
![landingpage3](https://user-images.githubusercontent.com/106770765/229878015-43076fa5-5bef-4b49-b28b-db1d909c93c6.jpg)
![landingpage4](https://user-images.githubusercontent.com/106770765/229878413-ab123882-d591-4f6c-ade4-a901854191c4.jpg)

LANDING PAGE
The landing page of this project includes the features, about and contact of kinetic hospital. The landing page also includes the patient id and the submit button, then a link to take the user to the registration page. When the user clicks "register now" it takes the user to the registration page.

REGISTRATION PAGE
The registration page is basically to get input from the user. The inputs are saved in the database of the company.
