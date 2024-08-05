# Python API Automation Framework

Hybrid Cusomter API Automation Framework include the proper folder structure

![Screenshot 2024-08-05 at 08 18 38](https://github.com/user-attachments/assets/3c7d5fe5-207a-42e7-84fe-f4d53354d987)

### Tech Stack
- Python 3.12
- Requests - HTTP Requests
- PyTest - Testing Framework
- Reporting - Allure Report, PyTest HTML
- Test Data - CSV, Excel, JSON,  Faker
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)

### Allure Report

![Screenshot 2024-08-05 at 08 19 43](https://github.com/user-attachments/assets/da1ee5e1-81ef-4317-a0ba-d5788d779657)


### How to Install Packages

``` pip install requests pytest pytest-html faker allure-pytest jsonschema```

### How to run your Testcase Parallel

```pip install pytest-xdist```

### How to add the .gitignore File?

Copy the content from this to .gitignore file
https://www.toptal.com/developers/gitignore/api/pycharm+all

### How to run the Basic Test with Allure report

``` pytest tests/tests/crud/test_create_booking.py  --alluredir=allure_result -s```

