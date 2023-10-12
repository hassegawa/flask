## git clone

  * https://github.com/hassegawa/flask.git

  * docker run --rm -it -v ./flask:/app -p 8080:8080 python:3.11-slim-bullseye /bin/bash

  * cd /app

### install python pakage
  * pip install -r requirements.txt

### instal SqLite3
  * apt update
  * apt install sqlite3
  * sqlite3 user.db
  * .quit

### to create database
  * python3 migration.py

### RUN
  * flask --app app run --host=0.0.0.0 --port=8080

  #### No navegador
    * localhost:8080
