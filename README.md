# Django Notes

## DB Migrations

Change your models (in models.py).
Run python manage.py makemigrations to create migrations for those changes
Run python manage.py migrate to apply those changes to the database.

## Better Shell

SHELL_PLUS = "ipython"
python manage.py shell_plus

## Testing

```text
As long as your tests are sensibly arranged, they won’t become unmanageable. Good rules-of-thumb include having:
    * a separate TestClass for each model or view
    * a separate test method for each set of conditions you want to test
    * test method names that describe their function
```
