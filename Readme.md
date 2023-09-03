# Custom Module Odoo Python

A simple projects to create a custom module on Odoo Python

## Requirements 
    1. PostgreSQL
    2. Python IDE (this projects developed in PyCharm)

## How To Run

    1. Clone this Repo and Mount the Folder
    2. Clone Odoo 16 Repo on Project's root Folder
```
git clone https://github.com/odoo/odoo --branch 16.0 --depth 1
```
    3. mount Odoo Folder and install the requirements
```
pip install -r requirements.txt
```
    4. Create a new Directory named conf in project's root folder and create a new file with name odoo.conf and setup like below:
```
[options]
db_host = localhost
db_port = 5432
db_user = your_db_user
db_password = your_db_password
http_port = 8069
```
    5. setup run/debug environtment like below :
- Scripts directory
- ```
  projects-root/odoo/odoo-bin
    ```
- Config
- ```
  -c projects-root/conf/odoo.conf
  ```
    
6. Run The Projects