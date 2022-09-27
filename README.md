# WILDCAT INNOVATION LABS
------------
![WILMS banner](https://raw.githubusercontent.com/JukKie-ai/wilms-readme/main/banner.jpg)
------------
# Table of Contents
- [WILDCAT INNOVATION LABS](#wildcat-innovation-labs)
- [Services](#services)
- [Infrastructure Software](#infrastructure-software)
	- [WILMS](#wilms-efficient-operation)
	- [Techno Tools](#techno-tools)
- [Requirements](#requirements)
- [Installation](#installation)
	- [Modules](#modules)
	- [Database](#database)
	- [Server](#server)
	- [WILMS System Credentials](#wilms-system-credentials)
		- [Admin Credentials](#admin-credentials)
		- [Instructor and Student Credentials](#instructor-and-student-credentials)
- [Contributors](#contributors)
- [Contact us](#contact-us)
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

 - [Django](https://www.djangoproject.com/download/)
 - [Visual Studio Code](https://code.visualstudio.com/Download)

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
### WILMS System Credentials
#### Admin Credentials
    username: jrama
    password: Tbipassword123
#### Instructor and Student Credentials

	    INSTRUCTOR 2
    username: instructor2acct
    password: Tbipassword123
    
	    STUDENT	2 - 3 - 4
	username: student2acct
	password: Tbipassword123
	
	username: student3acct
	password: Tbipassword123
	
	username: student4acct
	password: Tbipassword123
	-------------------------
	    INSTRUCTOR 3
    username: instructor3acct
    password: Tbipassword123
    
	    STUDENT	5 - 6 - 7
	username: student5acct
	password: Tbipassword123
	
	username: student6acct
	password: Tbipassword123
	
	username: student7acct
	password: Tbipassword123

    
    

------------
# Contributors
![Wild Pack](https://raw.githubusercontent.com/JukKie-ai/wilms-readme/main/wild%20pack.jpg)

# Contact Us
Should you have concerns, we are reachable via the following:
* Back End Support: Jay Vince Serato - jayvince.serato@gmail.com
* Front End Support: Pinkfloyd Adonay - pinkfloyd.adonay@gmail.com

Happy coding! 🎉
