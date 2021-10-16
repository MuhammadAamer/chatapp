First of all open the Chatapp Directory.
then open cmd in the same directory.
Then run the following command.

pip install -r requirements. txt



Then setup your postgres sql with the following credentials

    'NAME': 'new_databas',
        'USER': 'postgres',
        'PASSWORD': 'aaamir5175',
        'HOST': '127.0.0.1',
        'PORT': '5432',

            OR


change the database sitting CHATSERVERPLAYGROUND/sittings.py according to your database.
Then run the following command.


python manage.py makemigrations


and then run the following command


python manage.py migrate


and for testing purpose run the folowing command


python manage.py runserver
