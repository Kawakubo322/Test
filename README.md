# Import a flow file (or files) and store in a db

### Virtual Environment

You'll activate virtual environment at 'challenge' directory.

```
source myvenv/bin/activate
```

### Install Django

```
pip install -r requirements.txt
```

## Import a flow file

```
python manage.py meter_point 'filepath'
```

## Check it out

```
python manage.py runserver
```

Visit 'http://127.0.0.1:8000/admin'
Username: ola
Password: kawakubo
