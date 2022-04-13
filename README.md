# prometheus
django + vite + react + typescript = 😍

for dev:

pipenv shell
pipenv install
python manage.py migrate
npm install

terminal 1: python manage.py runserver
terminal 2: npm run dev

for prod: TBD, but debug = False, then remove "re_path(r"^static/(?P<path>.*)$", serve, {"document_root": settings.STATIC_ROOT})" from backend/urls and then do the collectstatic stuff
