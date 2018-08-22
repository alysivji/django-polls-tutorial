# Django Notes

## DB Migrations

Change your models (in models.py).
Run python manage.py makemigrations to create migrations for those changes
Run python manage.py migrate to apply those changes to the database.

## Better Shell

SHELL_PLUS = "ipython"
python manage.py shell_plus
