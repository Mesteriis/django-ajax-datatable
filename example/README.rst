
Install
=======

In your virtualenv, install Django dependencies:

.. code-block:: bash

    pip install -r requirements.txt

Initialize database tables:

.. code-block:: bash

    python manage.py migrate

Create a super-user for the admin:

.. code-block:: bash

    python manage.py createsuperuser

Download js packages:

.. code-block:: bash

    npm install

Run
===

.. code-block:: bash

    python manage.py runserver

Then visit http://127.0.0.1:8000/.
