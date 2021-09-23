=====
Usage
=====

To use Nobinobi Observation in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'nobinobi_observation.apps.NobinobiObservationConfig',
        ...
    )

Add Nobinobi Observation's URL patterns:

.. code-block:: python

    from nobinobi_observation import urls as nobinobi_observation_urls


    urlpatterns = [
        ...
        url(r'^', include(nobinobi_observation_urls)),
        ...
    ]
