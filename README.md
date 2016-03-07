Fcgi module with corrections that allow run a django project,
when he is within an application on IIS server (Windows).

Configuration:

`PYTHONPATH` - The base directory django project.

`WSGI_APP` - Variable that defines the module wsgi (app.wsgi).

Configure the wsgi prefix in the variable `django.root` with the value `%APPL_VIRTUAL_PATH%`