
.. The State of members.python.or.id slides file, created by
   hieroglyph-quickstart on Sat Aug  9 11:39:25 2014.

=================================
The State of members.python.or.id
=================================

| @akbargumbira
| @iromli

Did You Know?
=============

| Python Indonesia community maps: `members.python.or.id`_.

.. figure:: /_static/homepage.png

.. _members.python.or.id: http://members.python.or.id

It's Open Source!
=================

Forked from `github.com/kartoza/flask_user_map`_.

* @timlinux
* @akbargumbira

Development at `github.com/id-python/members`_.

.. _github.com/kartoza/flask_user_map: https://github.com/kartoza/flask_user_map
.. _github.com/id-python/members: https://github.com/id-python/members

Goals
=====

Quotes from Zaki Akhmad (@za):

    Ide awal berangkat dari proyek direktori yang berusaha mendata Pythonista Indonesia.

    Lalu, bagaimana jika bisa dilihat dalam peta? Tentunya akan lebih menarik. Hal ini bisa membuat interaksi antar Pythonista Indonesia lebih baik. Termasuk jika ada pemula yang ingin belajar.

Goals (1)
---------

| Web-based interface for `github.com/id-python/direktori`_.

.. figure:: /_static/direktori.png

.. _github.com/id-python/direktori: https://github.com/id-python/direktori

Goals (2)
---------

| Interaction — local/regional meetups, social media, etc.

.. figure:: /_static/meetup.png

Goals (3)
---------

See **The Future** section!

Current State
=============

As per August 23rd, 2014:

* Hosting provided by Fahri Reza (@dozymoe)
* Basic functionality: add, edit, delete user
* Mailer problem

  * might be detected as spam
  * not delivered

The Future
==========

* Basic functionality:

  * add, edit, delete user's projects
  * avatars
  * tags/specialization

* Advanced features:

  * search users and projects

* Marketplace e.g. https://djangogigs.com/ (?)

* Et Cetera™

The Tech Stack
===============

.. figure:: /_static/tech_stack.png
   :scale: 130 %
   :align: center

Technical Stuff
===============

* Flask_
* Leaflet_
* SQLAlchemy_

.. _Flask: http://flask.pocoo.org/
.. _Leaflet: http://leafletjs.com/
.. _SQLALchemy: http://www.sqlalchemy.org/


Technical Stuff (1)
-------------------

Why Flask?

* Minimalism and Simplicity - We don't want too much overhead for such simple
  requirement
* Some said, `who likes ORM?`_
* Some others said `Lovely Routing`_

.. _who likes ORM?:  http://www.butenas.com/blog/why-flask/
.. _Lovely Routing: http://www.reddit.com/r/Python/comments/1yr8v5/django_vs_flask/

Technical Stuff (2)
-------------------

Why Leaflet?

* What's the option? `Google vs Leaflet vs OpenLayers`_
* We want to use OpenStreetMap
* Speed of development, flexibility, efficiency (OpenLayers ~ 1M is too much for
  such requirement)

.. _Google vs Leaflet vs OpenLayers: http://robinlovelace.net/software/2014/03/05/webmap-test.html

Technical Stuff (3)
-------------------

Why SQLAlchemy?

* Database engine abstraction — we are using Postgres engine
* Connection pooling, ORM, extensions
* Easy schema migration through Alembic — except when using SQLite

Help Us, Please!
================

* Spread the words
* Feedback
* Donate — http://www.python.or.id/p/donasi.html
* Submit bugs reports and fixes (GitHub PR)
* New features (GitHub PR)
* Code sprint

Thanks!
=======

Questions?

| @akbargumbira
| @iromli
