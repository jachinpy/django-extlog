django-extlog
=============

.. image:: https://pypip.in/v/django-extlog/badge.png
    :target: https://crate.io/packages/django-extlog/
    :alt: Latest PyPI version

.. image:: https://pypip.in/d/django-extlog/badge.png
    :target: https://crate.io/packages/django-extlog/
    :alt: Number of PyPI downloads


Extended log for Django, tracks changes in values of fields.


Installation
------------

Installing from pypi (using pip):

    pip install django-extlog

Installing from github:

    pip install -e git://github.com/AxiaCore/django-extlog.git#egg=django-extlog


Quick Setup
-----------

1. Add ``django_extlog`` to your ``INSTALLED_APPS`` setting like this::

    INSTALLED_APPS = (
        ...
        'django_extlog',
    )

2. Add ``AuditLoggingMiddleware`` to your ``MIDDLEWARE_CLASSES`` setting::

    MIDDLEWARE_CLASSES = (
        ...
        'django_extlog.middleware.AuditLoggingMiddleware',
    )


Screenshots
-----------

.. image:: http://axiacore.github.io/public/img/docs/extlog-admin-list.png


.. image:: http://axiacore.github.io/public/img/docs/extlog-admin-detail.png
