=====
Usage
=====

To use two_scoops in a project, add it to your `INSTALLED_APPS`:

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
