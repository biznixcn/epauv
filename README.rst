EPAUV
=====

This is a project started by a few FOSS@RIT hackers in Rochester, NY for the
first-ever National Day of Civic Hacking. We hope to expose publicly-available
UV index data provided by the Environmental Protection Agency to create an
attractive, interesting interface to this data.


Front Page
==========

The front page is a simple 3 column view that gives a quick description,
provides a form for inputting your Zipcode, and links to the project source and
license.

.. image:: /epauv/static/images/zipform.png
   :height: 100px
   :width: 200 px
   :align: center


Desktop View
============

This is a screenshot of what the results look like from a desktop view. The
index shown at the top is calculated by checking the time the page was visited
against the hourly index. The colors are mapped to the severity levels listed
on the EPA informational website.

.. image:: /epauv/static/images/result-desktop.png
   :height: 100px
   :width: 200 px
   :align: center


Mobile View
===========

As the page was designed using Unresponsive CSS, we get a fluid page that
scales with the size of the viewport (aka we get mobile friendly pages without
having to write separate code just for mobile devices.)

.. image:: /epauv/static/images/result-mobile.png
   :height: 100px
   :width: 200 px
   :align: center


Hourly Results
==============

Hourly results for the day are colored based on UV Index severity, and include
tips and advice based on EPA information, such as time until skin damage, and
precautions to take based on UV Levels.

.. image:: /epauv/static/images/result-list.png
   :height: 100px
   :width: 200 px
   :align: center


License
-------

This software is released under the GNU GPL version 3 or later.

Getting Started
---------------

We hack on this project in a virtualenv, and you should, too!

EPAUV requires that you have the ``python-lxml`` package installed.
This is used by pygal to generate coolio SVG diagrams.

-   cd <directory containing this file>

-   $venv/bin/python setup.py develop

-   $venv/bin/initialize_EPAUV_db development.ini

-   $venv/bin/pserve development.ini

Contributors
------------

-   Nate Case

-   Remy DeCausemaker

-   David Gay

