Running tests
=============

Currently RTD isn't well tested. This is a problem, and it is being worked on. However, we do have a basic test suite. To run the tests, you need simply need to run::

    ./manage.py test rtd_tests

This should spit out a bunch of info, build a couple projects, and eventually pass.

Continuous Integration
----------------------

The RTD test suite is exercised by Travis CI on every push to our repo at
GitHub. You can check out the current build status:
https://travis-ci.org/rtfd/readthedocs.org
