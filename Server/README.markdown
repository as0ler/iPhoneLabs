b Server
==========

Setup
-----

You'll need to install:

* blinker 
* cherrypy
* flask
* flask-sqlalchemy
* simplejson

Install PIP on MacOS X:
	brew install pip

With PIP Run:
    pip install blinker flask simplejson
    sudo pip install flask-sqlalchemy

Install CherryPy 3.2.3
    cd Dependencies/CherryPy-3.2.3
    sudo pip install cherrypy 

Using
-----

To run the HTTPS server on port 8443

    python app.py 
