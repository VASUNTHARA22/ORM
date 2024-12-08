# Ex02 Django ORM Web Application
# Date:
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bank Loan List</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f8f9fa;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .loan-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .loan-item {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .loan-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .loan-title {
            font-size: 18px;
            color: #007BFF;
            margin-bottom: 10px;
        }
        .loan-details {
            font-size: 14px;
            color: #555;
        }
        .apply-btn {
            display: inline-block;
            margin-top: 10px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 5px;
            text-align: center;
        }
        .apply-btn:hover {
            background-color: #218838;
        }
    </style>
</head>
<body style="background-color: yellow;">
    <h1>Bank Loan Options</h1>
    <div class="loan-list">
        <div class="loan-item">
            <div class="loan-title">Home Loan</div>
            <div class="loan-details">
                <p><strong>Interest Rate:</strong> 7.5% p.a.</p>
                <p><strong>Maximum Amount:</strong> $500,000</p>
                <p><strong>Tenure:</strong> Up to 20 years</p>
            </div>
            <a href="/apply-home-loan" class="apply-btn">Apply Now</a>
        </div>
        <div class="loan-item">
            <div class="loan-title">Personal Loan</div>
            <div class="loan-details">
                <p><strong>Interest Rate:</strong> 10.5% p.a.</p>
                <p><strong>Maximum Amount:</strong> $50,000</p>
                <p><strong>Tenure:</strong> Up to 5 years</p>
            </div>
            <a href="/apply-personal-loan" class="apply-btn">Apply Now</a>
        </div>
        <div class="loan-item">
            <div class="loan-title">Car Loan</div>
            <div class="loan-details">
                <p><strong>Interest Rate:</strong> 8.5% p.a.</p>
                <p><strong>Maximum Amount:</strong> $100,000</p>
                <p><strong>Tenure:</strong> Up to 7 years</p>
            </div>
            <a href="/apply-car-loan" class="apply-btn">Apply Now</a>
        </div>
        <div class="loan-item">
            <div class="loan-title">Education Loan</div>
            <div class="loan-details">
                <p><strong>Interest Rate:</strong> 6.5% p.a.</p>
                <p><strong>Maximum Amount:</strong> $200,000</p>
                <p><strong>Tenure:</strong> Up to 15 years</p>
            </div>
            <a href="/apply-education-loan" class="apply-btn">Apply Now</a>
        </div>
    </div>
</body>
</html>

```
# OUTPUT

![image](https://github.com/user-attachments/assets/b1257faa-07ed-40e7-a653-4a48d28f6c1c)



# RESULT
Thus the program for creating a database using ORM hass been executed successfully
