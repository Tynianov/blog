# django-blog

My personal blog, built with Python's Django framework.

## Requirements
- python 3.5 or higher
- pip
- MySQL

## Configuration

Use `.env` file to configure environment configuration such as database URL etc.

## Installation
1. Create virtualenv
```
cd /path/to/target/folder && virtualenv ENV
```
2. Install pip packages

```
pip -r requirements.txt
```
3. Create database in MySQL

4. Create .env file and fill with required information (db name, username & password)

5. Run migration
```
./manage.py migrate
```

6. Run server

```
./manage.py runserver
```
