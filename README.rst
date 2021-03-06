===================
Access2base Typings
===================

This project is Type Support (typings) for `LibreOffice`_ `Access2base <https://github.com/LibreOffice/core/tree/master/wizards/source/access2base>`_

At the time of this writing there is no `PyPI.org`_ packaing for **access2base**.
It is not necessary to have a  **access2base** package to take advantage of
**access2base** typings.

This project leverages `types-unopy <https://github.com/Amourspirit/python-types-unopy>`_ that gives
full typing support for `LibreOffice API <https://api.libreoffice.org/>`_.
This allows full type support for `access2base <https://github.com/LibreOffice/core/tree/master/wizards/source/access2base>`_
and `LibreOffice API <https://api.libreoffice.org/>`_.


These Typings are created for `LibreOffice`_ ``7.1``, ``7.2``, and ``7.3``.

Installation
============

PIP
---

types-access2base `PyPI <https://pypi.org/project/types-access2base/>`_

.. code-block:: bash

    $ pip install types-access2base

Access2Base.py
--------------

**Access2base** lives inside of `LibreOffice`_. Using these typings in an modern code editor
will give type Support for the **access2base** library.

There are exceptions on Linux when *access2base.py* may not be installed.
This will depend on part how `LibreOffice`_ is installed.
If `LibreOffice`_ is installed via `flatpak <https://flathub.org/apps/details/org.libreoffice.LibreOffice>`_ or `snaps <https://snapcraft.io/libreoffice>`_
then *access2base.py* should already be installed.

If `LibreOffice`_ is installed with apt-get then you may need to install ``python3-access2base``.
This may also require setting up `LibreOffice ppa <https://www.ubuntuupdates.org/ppa/libreoffice>`_ for your distro.

.. code-block:: bash

    $ sudo apt-get update
    $ sudo apt-get install python3-access2base

Other
=====

**Figure 1:** access2base typings example

.. figure:: https://user-images.githubusercontent.com/4193389/164977724-779af9be-0227-44e3-8e27-316b14e1d337.gif
   :alt: types-access2base example gif.

.. _PyPi.org: https://pypi.org/
.. _LibreOffice: https://www.libreoffice.org/