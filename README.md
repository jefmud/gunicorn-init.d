# gunicorn-init.d
a simple Gunicorn init.d script

This is a minimalist SystemV approach to a script to start/stop Gunicorn.  This should work on various SystemV type Linux distros like Ubuntu, CentOS, Raspbian, etc.

Gunicorn is a Pythonic WSGI server that works very well by itself, but even better running proxied through Nginx.

https://gunicorn.org/

If you configure it properly, Gunicorn is excellent at serving Python frameworks.  Personally I've tested it with Django, Flask, and Bottle Frameworks.

You will need to change the variables to match that of your app!

Good luck!
