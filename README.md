# WILDCAT INNOVATION LABS
**Where ventures thrive and ideas come alive**
------------
![WILMS LOGO](https://raw.githubusercontent.com/JukKie-ai/wilms-readme/main/w4.c1a6d8d7161b.png)
------------
# Table of Contents
- [WILDCAT INNOVATION LABS](#wildcat-innovation-labs)
- [Services](#services)
- [Infrastructure Software](#infrastructure-software)
	- [WILMS](#wilms-efficient-operation)
	- [Techno Tools](#techno-tools)
- [Requirements](#requirements)
- [Installation](#installation)
------------
# Services
- Licensing and Technology Commercialization
- Intellectual Property and Technology Management
- Grant Application Assistance
- Mentorship in Technical, Legal, Finance, and the Marketing Aspects of the Start-ups
------------

# Infrastructure Software
## WILMS (Efficient Operation)
#### Features:
	1. Manage the Technopreneurship classes
	2. Handle the reservation
	3. Track the utilization of resources
## Techno Tools
**Online tools to efficiently manage the delivery of Technopreneurship and activities**

------------
# Requirements

    django==3.1.14
    python-decouple>=3.1
    Pillow>=5.1.0
    gunicorn
    django-heroku
    sendgrid
    django-scheduler
    django-tempus-dominus
    django-star-ratings
    django-datatables-view
    django-cron
    django-multiselectfield
    requests
    xlwt
    mysqlclient
    openpyxl
    beautifulsoup4
    django-bootstrap-modal-forms
    beautifulsoup4
    schedule
  ------------
   # Installation
   ### Modules
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required modules for this app.

```bash
pip install -r requirements.txt
```
### Database
You would also need to have [XAMPP](https://www.apachefriends.org/download.html) for the database.
After installing XAMPP, do the following tasks:
* Before Starting MySQL, click the "Config" button and choose "my.ini".
* Under [mysqld], add the following line, typically at line 45:
```text
skip-grant-tables
```
* Save the file.
* Start MySQL in XAMPP.
* Go to the database admin at localhost/phpmyadmin.
* Go to Import tab.
* Download [db (new).sql](https://drive.google.com/file/d/15YsOx3r5ggKC994W_Eop8JNMyewR2GO8/view).
* Click "Choose file" and choose db (new).sql.

### Server
In order to run the application in Django, do the following in your command prompt:
```bash
pip uninstall schedule
pip install schedule
python manage.py migrate
python manage.py runserver
```
