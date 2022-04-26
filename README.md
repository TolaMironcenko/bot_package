=====
tgb
=====

Polls is a Django app to conduct web-based polls. For each question,
visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "tgb" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'tgb',
    ]
    ...
    TOKEN = 'your telegram bot token'

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/.