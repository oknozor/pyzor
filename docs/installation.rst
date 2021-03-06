Getting Pyzor
==============

Installing
-----------
The recommended and easiest way to install Pyzor is with ``pip``::

    pip install pyzor
    
In order to upgrade your Pyzor version run::
 
    pip install --upgrade pyzor


Compatibility
-------------

Pyzor is compatible with the following Python versions and implementations:

   - Python 2.6
   - Python 2.7
   - Python 3.2+
   - PyPy
   - PyPy3

Pyzor will also work on Windows. 

Downloading
------------

If you don't want to or cannot use ``pip`` to download and install Pyzor. You
can do so directly from the source::

    python setup.py install
    
You can find the latest and older versions of Pyzor on 
`PyPI <https://pypi.python.org/pypi/pyzor>`_.

Dependencies
-------------

Pyzor Client
^^^^^^^^^^^^^

If you plan on only using Pyzor to check message against our public server,
then there are no required dependencies.

Pyzor Server
^^^^^^^^^^^^^

If you want to host your own Pyzor Server then you will need an appropriate 
back-end engine. Depending on what engine you want to use you will also need 
to install the required python dependecies. Please see :ref:`server-engines`
for more details.

The Pyzor also support the `gevent library <http://www.gevent.org/>`_. If you 
want to use this feature then you will need to first install it. 

