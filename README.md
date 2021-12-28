
# Djancommerce

[![codecov](https://codecov.io/gh/UlugbekMuslitdinov/djancommerce/branch/main/graph/badge.svg?token=OZDG0VYMEA)](https://codecov.io/gh/UlugbekMuslitdinov/djancommerce)
[![Django CI](https://github.com/UlugbekMuslitdinov/djancommerce/actions/workflows/django.yml/badge.svg)](https://github.com/UlugbekMuslitdinov/djancommerce/actions/workflows/django.yml)

The ready-to-use code for e-commerce applications based on Django framework.


## Contents

 - [Installation](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 

## Installation

To start using this project, you need to clone it or download the zip file

* Using HTTP
    ```bash
    git clone https://github.com/UlugbekMuslitdinov/djancommerce
    ```
* Using SSH 
    ```bash
    git@github.com:UlugbekMuslitdinov/djancommerce.git
    ```
After the cloning, install dependencies using Pipenv
* ```bash
    pipenv install pipenv && pipenv install --system
    ```

Migrate the database and run local server

```bash
python manage.py migrate
python manage.py runserver
```    


## Functionality
- Custom user model
  - User Login
  - User Registration