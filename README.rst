Barebone DjangoCMS 4 project
============================

This is an experimental attempt to study DjangoCMS 4 using the official documentation:

https://docs.django-cms.org/en/latest/introduction/01-install.html#installing-django-cms-by-hand

We keep it drastically simple to avoid messing with other concerns, this is
a first approach of DjangoCMS 4 goal only.

Generated project has been done from template ``cms-template==4.1`` and some minor
architecture changes:

* A Makefile has been added with helpful tasks;
* Requirements has been moved in ``requirements/`` with some additional requirements
  for further usage;
* Readme file has been changed to a ReStructuredText format;
* ``.gitignore`` has been improved;
