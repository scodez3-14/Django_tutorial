

## Projects and how to run

Each part contains its own `manage.py`. To run a part, `cd` into the part folder and run the dev server.

### Part 1

```bash
cd part1
python manage.py runserver
# visit http://127.0.0.1:8000/
```

### Part 2 (has static demo)

This part contains `static/styles.css` and `templates/home.html` (demo). Important notes:

- `part2/mysite/settings.py` should include `django.contrib.staticfiles` in `INSTALLED_APPS` and have `DEBUG = True` for the dev server to serve static files automatically.
- `STATIC_URL` should be set to `/static/` and `STATICFILES_DIRS` should include the project `static/` folder.

Run:

```bash
cd part2
python manage.py runserver
# visit http://127.0.0.1:8000/
```

### Part 3

```bash
cd part3
python manage.py runserver
# visit http://127.0.0.1:8000/
```

Part 3 contains additional migrations and `polls` templates under `templates/polls/`.