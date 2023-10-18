# Hospital-management-system
# PharmacyManagementSystem
<h2>Clinical Management System using Python Django</h2>
  
  
   <p>This is a simple Hospital Management System programmed using Python Django. The system has 5 types of users are the Administrator, Pharmacist, Doctor, and Receptionist(HospitalClerk) and Patient.This project has user-friendly functionalities.</p>
   
   



## How to Install and Run this project?

### Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```



Then, Enter the project
```
$  cd student-management-using-django
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip3 install -r requirements.txt
```
**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Use **[]** as your host. 
```python
ALLOWED_HOSTS = []
```
*Do not use the fault allowed settings in this repo. It has security risk!*

**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

**7. Login Credentials**
Create Super User (HOD) Command for PC:

$  python manage.py createsuperuser 

Then Add Email and Password

or Use Default Credentials listed in belows
-----------------------------------------------------------------------------------

### Admin User Login: 
- Username: admin
- password: 1234  
  
          Administrator Main Features
     - Manage Admissions/Patients
     - Manage System Users
     - Manage Patient's Prescription
     - Manage Medicinal Drugs Categories
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Personal Accounti

------------------------------------------------------------------------------------
### Patient Login:
- Username: patient1
- password: 1234

           Patient Main Featues
     -  Manage his/her medications
     - Feedback Pharmacist incase of dispensing issue
     -  manage Personal Account
      
 
-----------------------------------------------------------------------------------
### Pharmacist Login:
- Username: pharmacist1
- password: 1234

        Pharmacist  Main Features
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Patient Feedback messeges
     - Manage Personal Account
     
        

-------------------------------------------------------------------------------------
### PharmacyClerk Login:
- Username: pharmacyclerk1
- password: 1234

            Receptionist Main Features
     - Manage Admissions/Patients
     - Manage Personal Account

------------------------------------------------------------------------------------
### Doctor Login:
- Username: doctor1
- password: 1234
        
        Doctor Main Featues
     - Manage Patient's Prescription
     - Manage Personal Account
   
-----------------------------------------------------------------------------------

## Helpful Links
- https://stackoverflow.com/questions/55969952/how-can-i-avoid-a-user-from-registering-an-already-used-email-in-django
- https://stackoverflow.com/questions/7562573/how-do-i-get-django-forms-to-show-the-html-required-attribute
- https://stackoverflow.com/questions/40910149/django-exists-versus-doesnotexist
- https://www.edureka.co/community/80982/how-can-i-have-multiple-models-in-a-single-django-modelform
- https://stackoverflow.com/questions/12848605/django-modelform-what-is-savecommit-false-used-for
- https://simpleisbetterthancomplex.com/tutorial/2018/01/18/how-to-implement-multiple-user-types-with-django.html
- https://stackoverflow.com/questions/32576348/how-can-i-create-django-modelform-for-an-abstract-model
- https://www.fomfus.com/articles/how-to-use-email-as-username-for-django-authentication-removing-the-username
- https://stackoverflow.com/questions/64145745/create-user-missing-1-required-positional-argument-username?noredirect=1#64145844
- https://stackoverflow.com/questions/36059194/what-is-the-difference-between-json-dump-and-json-dumps-in-python
- https://stackoverflow.com/questions/64188313/django-can-i-delete-apps-static-files-after-running-collectstatic/64189244#64189244
- https://stackoverflow.com/questions/29416478/change-form-field-value-before-saving
- https://support.google.com/mail/thread/38519529?hl=en
- https://stackoverflow.com/questions/46155/how-to-validate-an-email-address-in-javascript
- https://stackoverflow.com/questions/3429084/why-do-i-get-an-object-is-not-iterable-error








