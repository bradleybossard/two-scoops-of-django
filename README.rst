=============================
two_scoops
=============================

.. image:: https://badge.fury.io/py/two_scoops.png
    :target: https://badge.fury.io/py/two_scoops

.. image:: https://travis-ci.org/bradleybossard/two_scoops.png?branch=master
    :target: https://travis-ci.org/bradleybossard/two_scoops

Following along with two scoops of Django

Documentation
-------------

The full documentation is at https://two_scoops.readthedocs.io.

Quickstart
----------

Install two_scoops::

    pip install two_scoops

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'two_scoops',
        ...
    )

Add two_scoops's URL patterns:

.. code-block:: python

    from two_scoops import urls as two_scoops_urls


    urlpatterns = [
        ...
        url(r'^', include(two_scoops_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
