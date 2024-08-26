# Test task for UpTrader (tree-menu in Django)

1. Clone this repo to your local machine/server.
2. Make sure Django and Python both are installed
3. Go to the my_test/test_menu and execute the following:
```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```
4. Enter the login and password for admin panel
5. Run the following:
```
python manage.py runserver
```
6. Open your browser and proceed to `http://127.0.0.1:8000/` (or you can Ctrl+click the link in the terminal after starting the server)
7. Add `/admin` to URL to access admin panel and add/edit the menus
