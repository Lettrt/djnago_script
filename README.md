# djnago_script
- Script for automatically creating a django project with preset settings, pytest, dotenv, .env, drf and jwt. 
- Connection to the postgresql database is also configured

Run project in project directory
```bash
./django_script.sh
```
After the script is finished, copy your secret key from the settings.py file to the .env file
then delete the extra lines in the settings.py file (up to line 125 import os)

To run the project, go to the core folder (at the same level as the manage.py file) and run the command
```bash
python3 manage.py runserver
```
