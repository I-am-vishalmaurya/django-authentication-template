# Django Authentication Template

Django Authentication Template
## Functionality

- Log in
    - via username & password
    - via email & password
    - via email or username & password
    - with a remember me checkbox (optional)
- Create an account
- Log out
- Profile activation via email
- Reset password
- Remind a username
- Resend an activation code
- Change password
- Change email
- Change profile


## Installing

### Clone the project

```
git clone https://github.com/I-am-vishalmaurya/django-authentication-template.git
cd django-authentication-template
```

### Create Virtual environment and activate it.
```
python -m venv venv
```
Activate it by running the following command:
MacOS or Linux:
```
source venv/bin/activate
```
For windows:
```
.\venv\Scripts\activate
```

### Install the requirements
```
pip install -r requirements.txt
```

### Configure the settings (connection to the database, connection to an SMTP server, and other options)

1. Edit `source/app/conf/development/settings.py` if you want to develop the project.

2. Edit `source/app/conf/production/settings.py` if you want to run the project in production.

### Apply migrations

```
python source/manage.py migrate
```

### Collect static files (only on a production server)

```
python source/manage.py collectstatic
```

### Running

#### A development server

Just run this command:

```
python source/manage.py runserver
```
