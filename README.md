# Simple scikit learn classifier example

* ``classifier``: Directory containing simple Jupyter notebook to train a news classifier and pickled version fo the classifier
* ``swagger.yaml``: REST API Swagger definition
* ``app.py``: basic rest endpoints
* ``requirements.txt``: list of required Python libraries
* ``test.sh``: shell script to execute example HTTP requests against the pet shop API


Running Locally
===============

You can run the Python application directly on your local operating system:

```bash
    $ sudo pip3 install -r requirements.txt
    $ ./app.py # start the HTTP server
```


 - Connexion: https://pypi.python.org/pypi/connexion
 - Flask: http://flask.pocoo.org/
 - Swagger 2.0 Specification: https://github.com/swagger-api/swagger-spec/blob/master/versions/2.0.md
 - /ui/: http://localhost:8080/ui/
