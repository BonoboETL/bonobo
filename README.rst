==========
🐵  bonobo
==========

Data-processing for humans.

** Actively maintained fork for Bonobo ETL **

In an effor to support the Bonobo community, we hav forked the original 'bonobo-project' to continue
active maintenance. Much thanks to the original developers and maintainers, your hard work is
greatly appreciated!

Our initial goal is to finalize 0.7.0 based on the existing release candidate rc3 along with
changes needed to address the end-of-life of python 3.5 & 3.6 and soon to be end-of-lifed 3.7.

As we pick up the mantle of moving towards a full 1.0 release, please stay tuned for a roadmap
to address updating dependencies, remaining feature functionality and stability improvements.

Documentation can now be found at: http://bonoboetl.github.io/bonobo/

?.. image:: https://img.shields.io/pypi/v/bonobo.svg
?    :target: https://pypi.python.org/pypi/bonobo
?    :alt: PyPI

?.. image:: https://img.shields.io/pypi/pyversions/bonobo.svg
?    :target: https://pypi.python.org/pypi/bonobo
?    :alt: Versions

?.. image:: https://readthedocs.org/projects/bonobo/badge/?version=master
?    :target: http://docs.bonobo-project.org/
?    :alt: Documentation

?.. image:: https://travis-ci.org/python-bonobo/bonobo.svg?branch=master
?    :target: https://travis-ci.org/python-bonobo/bonobo
?    :alt: Continuous Integration (Linux)

?.. image:: https://ci.appveyor.com/api/projects/status/github/python-bonobo/bonobo?retina=true&branch=master&svg=true
?    :target: https://ci.appveyor.com/project/hartym/bonobo?branch=master
?    :alt: Continuous Integration (Windows)

?.. image:: https://codeclimate.com/github/python-bonobo/bonobo/badges/gpa.svg
?   :target: https://codeclimate.com/github/python-bonobo/bonobo
?   :alt: Code Climate

?.. image:: https://img.shields.io/coveralls/python-bonobo/bonobo/master.svg
?    :target: https://coveralls.io/github/python-bonobo/bonobo?branch=master
?    :alt: Coverage

Bonobo is an extract-transform-load framework for python 3.8+ (see comparisons with other data tools).

Bonobo uses plain old python objects (functions, generators and iterators), allows them to be linked together in a directed graph, and then executed using a parallelized strategy, without having to worry about the underlying complexity.

Developers can focus on writing simple and atomic operations, that are easy to unit-test by-design, while the focus of the
framework is to apply them concurrently to rows of data.

One thing to note: write pure transformations and you'll be safe.

Bonobo is a young rewrite of an old python2.7 tool that ran millions of transformations per day for years on production.

----

*Bonobo project has been forked and is, once again, moving forward towards full 1.0 release. Help in testing release candidates is greatly apprecaited)*

----

Homepage: https://bonoboetl.github.io/ (`Roadmap <https://www.bonobo-project.org/roadmap>`_)

Documentation: http://bonoboetl.github.io/docs/

Contributing guide: *tbd*

Issues: https://github.com/bonoboetl/bonobo/issues

Community: *tbd*

Release announcements: http://eepurl.com/csHFKL

----

Made with ♥ by `Romain Dorgueil <https://twitter.com/rdorgueil>`_ and `contributors <https://github.com/python-bonobo/bonobo/graphs/contributors>`_.

Carrying the torch forward by the Bonobo ETL community.

.. image:: https://img.shields.io/pypi/l/bonobo.svg
    :target: https://pypi.python.org/pypi/bonoboETL
    :alt: License


