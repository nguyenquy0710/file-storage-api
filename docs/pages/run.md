# run

## Installing GuniCorn

Installing gunicorn [from source](http://docs.gunicorn.org/en/stable/install.html#from-source) saved me after 2 hours trying!

- https://stackoverflow.com/questions/29679963/why-gunicorn-command-not-found-with-gunicorn-installed
  - pip3 install git+https://github.com/benoitc/gunicorn.git

## Start Apps

```bash
pip install -r /tmp/requirements.txt

sh scripts/migrate.sh

# on server
sh scripts/run.sh
# on local
sh scripts/run-local.sh
```

## Running from source

```sh
$ git clone git@github.com:struckchure/file_storage_api.git
$ cd file_storage_api
$ pip3 install -r requirements.txt
$ python3 manage.py runserver 1276
```
