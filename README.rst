=========
sleepless
=========

How to sleep less and better?

Requirements
============

1. Check out and install a version of ``python-fitbit`` compatible with API v1.2 (currently a PR) at a location of your choice and add this to your PYTHONPATH.

::

$git clone https://github.com/orcasgit/python-fitbit <desired_location>
$cd <desired_location>/python-fitbit
$git fetch origin pull/160/head:api-1_2
$git checkout api-1_2
$python setup.py install
$export PYTHONPATH=<desired_location>/python-fitbit

2. Register for a (fake) app on Fitbit. Go to the `Fitbit dev website <dev.fitbit.com >`_. Hover over "Manage" and click on "Register An App."" The OAuth 2.0 Application Type is "personal" and the Callback URL is ``http://127.0.0.1:8080/``. All other fields don't really matter. Take note of your ``CLIENT_ID`` and ``CLIENT_SECRET``.