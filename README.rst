==============
Guake 3 README
==============

|actions-badge|_ |bountysource-badge|_ |docs-badge|_ |translation-badge|_

.. |actions-badge| image:: https://github.com/Guake/guake/actions/workflows/ci.yml/badge.svg
.. _actions-badge: https://github.com/Guake/guake/actions

.. |bountysource-badge| image:: https://img.shields.io/bountysource/team/guake/activity.svg
.. _bountysource-badge: https://www.bountysource.com/teams/guake

.. |docs-badge| image:: https://readthedocs.org/projects/guake/badge/?version=stable
.. _docs-badge: https://guake.readthedocs.io/en/stable/?badge=stable

.. |translation-badge| image:: https://hosted.weblate.org/widgets/guake/-/guake/svg-badge.svg
.. _translation-badge: https://hosted.weblate.org/projects/guake/guake/

Introduction
============

Guake is a python based dropdown terminal made for the GNOME desktop environment. Guake's style of window is
based on an FPS game, and one of its goals is to be easy to reach.

Quick Installation Guide
------------------------

Please refer to `Installation Guide <https://guake.readthedocs.io/en/latest/user/installing.html#system-wide-installation>`_

What it looks like ?
--------------------

.. image:: https://i.ibb.co/s97cJWZ/guake.png
    :alt: Guake Screenshot
    :class: with-shadow

Drop down terminal on pressing <F12>

Features Request
----------------

Please vote for feature on `FeatHub <http://feathub.com/Guake/guake>`_.
Open Issues on GitHub only for bug reports.

Most requested features list for Guake:

|feathub-badge|_

.. |feathub-badge| image:: http://feathub.com/Guake/guake?format=svg
.. _feathub-badge: http://feathub.com/Guake/guake

There is also a Bountysource opened here for those willing to pay a certain amount of money for a
really needed feature.
`See our Bountysource page here <https://www.bountysource.com/teams/guake>`_.

Note when compiling from source
-------------------------------

Do **NOT** use the Tarball packages automatically generated by GitHub on the Release pages. They
won't work because one of the main components of Guake build system, PBR, requires the full Git
history to be available when building from source. Note this does not impact source distribution
packages you can download from Pypi.

Build from sources instructions are described on
`this page of the Online Documentation <http://guake.readthedocs.io/en/latest/user/installing.html#install-from-source>`_.
Please read this carefully before opening an issue!

Bugs? Information?
------------------

- Source Code available on `GitHub <https://github.com/Guake/guake/>`_.
- Official Homepage: http://guake-project.org
- Online Documentation is hosted on `ReadTheDocs <http://guake.readthedocs.io/>`_.
- If you are not a developer, you can still contribute to Guake by
  `improving its translations in your language <https://hosted.weblate.org/projects/guake/guake/>`_.
  Guake users are welcome `to support Weblate <https://weblate.org/donate/>`_ in providing this
  service for free for OpenSource Projects.

**Important note**: Do **NOT** use the domain guake.org, it has been registered by someone outside
the team. We cannot be held responsible for the content on that web site.

This project was originally created by Gabriel Falcão, see: https://sourceforge.net/projects/guake-gnome-vte/
