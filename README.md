# Ex02 Django ORM Web Application
# Date: 20.09.2024
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM

![image](https://github.com/user-attachments/assets/240a9f48-df89-46ac-98f8-49714eb8919a)


## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
models.py
```
from django.db import models
from django.contrib import admin
class bankloan(models.Model):
    customer_name=models.CharField(max_length=100,primary_key=True)
    customer_id=models.CharField(max_length=100)
    loan_no=models.IntegerField()
    loan_amount=models.IntegerField()
    email=models.EmailField()
 
class userAdmin(admin.ModelAdmin):
    list_display=('customer_name','customer_id','loan_no','loan_amount','email')
# Create your models here.
```
admin.py
```
from django.contrib import admin
from .models import bankloan,userAdmin
admin.site.register(bankloan,userAdmin)
```

# OUTPUT

![image](https://github.com/user-attachments/assets/6d4847fd-d5b9-4c91-bca9-3ba925345302)

![image](https://github.com/user-attachments/assets/9e230503-d629-4536-beaf-090eb5237999)


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
