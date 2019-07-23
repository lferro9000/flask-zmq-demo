flask-zmq-demo
==============

Demo for adding ZMQ support to your Flask application.

To run it, create a virtual environment and activate it:

```
python -m venv .venv
. .venv/bin/activate
```

Install the dependencies:

```
pip install -r requirements
```

Then run in two terminals:

```
python server/server.py
```

and

```
python web/demo.py
```

Then open a browser in:

```
http://localhost:5000
```

You will see in your browser "Hello world!" and in the server terminal "value".


Note:
* Windows users will need to use ".venv/Scripts/activate.bat" to activate the environment
* Default port 5000 used in the demo.py. Check Flask documentation if you need to use a different port: https://flask.palletsprojects.com
