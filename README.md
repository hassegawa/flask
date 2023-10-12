pip install flash
pip install pyjwt
pip install datetime
pip install uuid
pip install Flask-SQLAlchemy


apt update
apt install sqlite3

doc https://www.bacancytechnology.com/blog/flask-jwt-authentication


flask --app app run --host=0.0.0.0 --port=8080

# login
https://pt.linux-console.net/?p=5089
CSS = https://cdnjs.com/libraries/bulma

Em um terminal, você pode definir os valores FLASK_APP e FLASK_DEBUG:

export FLASK_APP=project
export FLASK_DEBUG=1

## db
  python
  from project import db, create_app, models
  app=create_app()
  app.app_context().push()
  db.create_all()