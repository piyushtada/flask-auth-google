# flask-oauth-example

for google setup you need to put in

## Authorized JavaScript origins

> http://127.0.0.1:5000

> http://localhost:5000

## Authorized redirect URIs

> http://127.0.0.1:5000/callback/google

> http://localhost:5000/callback/google

we are puting both because the url depends on how you run your flask app.

things you need

```bash
pip install flask
pip install Flask-Login
pip install -U Flask_SQLAlchemy
pip install requests
pip install python-dotenv
```
