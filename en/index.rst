QField - your mobile [Q]GIS solution
====================================
QField allows you to efficiently work on your GIS data outdoor.

QField's optimized user interface for Android devices hides the full power of `QGIS <https://qgis.org>`_ under the hood.


.. container::

  .. vimeo:: 376372805

Concepts
--------

QField was designed with a few key concepts in mind.

Keep it simple
..............

The requirements on the field are not the same as on a desktop. The screen is
smaller, the input devices are different and the tasks are different.

QField aims to help the user to perform the tasks he needs to do without
cluttering the user interface. This means, that only tasks which need to be
done on the field are availble from the interface. Everything else is not.

This means that everything like layer styling, form definitions and other
project setup steps should be done on a computer with QGIS installed first.

Be compatible with QGIS
.......................

QField is based on QGIS. It is not a rebuild of QGIS it really *does* use QGIS
libraries. The rendering engine is exactly the same as in QGIS for desktop and
your project will therefore look exactly the same on your mobile device as it
does on your computer.

If something is already available as a configuration option in a QGIS project,
it should not be re-invented. QField therefore uses the same edit widgets as
QGIS desktop does. If a project is already configured for the desktop, it
should just run on mobile as well.

Remember, this is just the *concept*. This is what we have in mind when we
develop QField. It does not mean that it is already completely there yet.

Mode based
..........

QField is built around *modes*. Modes are similar to a *map tool* in QGIS
desktop. A mode defines the task which a user is currently doing. Either a user
is *browsing* through the data or he is *digitizing* something new.


Contents
--------

.. toctree::
   :maxdepth: 1
   :glob:

   installation-guide/index
   project-management/index
   user-guide/index
   development/index
   qfieldsync/index
   case-studies/index

Translations
============

The documentation is available in several languages

`Català </docs/ca>`_

`Deutsch </docs/de>`_

`English </docs/en>`_

`Castellano </docs/es>`_

`Eesti </docs/et>`_

`Suomalainen </docs/fi>`_

`Français </docs/fr>`_

`Galego </docs/gl>`_

`עברי </docs/he>`_

`Magyar </docs/hu>`_

`Italiano </docs/it>`_

`Lietuvos </docs/lt>`_

`Nederlands </docs/nl>`_

`Português </docs/pt>`_

`Română </docs/ro>`_

`Українська </docs/uk>`_

`日本語 </docs/ja>`_

If there is an error with a translation, please `help to improve it <https://www.transifex.com/opengisch/qfield-documentation/>`_.


Indices and tables
------------------

* :ref:`genindex`
* :ref:`search`

