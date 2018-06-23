The boofuzz of Protocol Fuzzing for Healthcare
============================================

.. image:: https://travis-ci.org/jtpereyda/boofuzz.svg?branch=master
    :target: https://travis-ci.org/jtpereyda/boofuzz
.. image:: https://readthedocs.org/projects/boofuzz/badge/?version=latest
    :target: http://boofuzz.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status
.. image:: https://img.shields.io/pypi/v/boofuzz.svg
    :target: https://pypi.python.org/pypi/boofuzz
.. image:: https://badges.gitter.im/jtpereyda/boofuzz.svg
    :alt: Join the chat at https://gitter.im/jtpereyda/boofuzz
    :target: https://gitter.im/jtpereyda/boofuzz?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge

SulleyBooMikefuzz is a fork of boofuzz_ and booFuzz is the successor to the venerable `Sulley`_ fuzzing
framework. 

The goal: To fuzz 3 major Healthcare related protocols such as DICOM, HL7 and Web services.

Why?
----

Boo Fuzz is very vast, customization would take a lot of time especially while creating models for 3 core Healthcare realted protocols

Features
--------

Like Sulley & boofuzz, SulleyBooMikeFuzz incorporates all the critical elements of a fuzzer:

-  Easy and quick data generation.
-  Instrumentation – AKA failure detection.
-  Target reset after failure.
-  Recording of test data.

SulleyBooMikefuzz also features:

-  Built-in support for fuzzing Helathcare specific datamodels for such as DICOM, HL7 and Web services
-  Better recording of test data.
-  Test result CSV export.
-  *Extensible* instrumentation/failure detection.
-  Easier install experience!

Sulley is affectionately named after the giant teal and purple creature
from Monsters Inc. due to his fuzziness. Boofuzz is likewise named after
the only creature known to have scared Sulley himself: Boo! And SulleyBooMikeFuzz is named after the combination of 3 of the major challenging fuzzing aspects in healthcare.

.. figure:: _static/sulley_boo_mike.JPG
   :alt: Boo Sulley and Mike from Monsters Inc

Installation
------------
::

    pip install sbmfuzz


SulleyBooMikefuzz installs as a Python library used to build fuzzer scripts. See
`INSTALL.rst`_ for advanced and detailed instructions.


Contributions
-------------

Pull requests are welcome, as boofuzz is actively maintained (at the
time of this writing ;)). See `CONTRIBUTING.rst`_.

Community
---------

For questions that take the form of “How do I… with boofuzz?” or “I got
this error with boofuzz, why?”, consider posting your question on Stack
Overflow. Make sure to use the ``fuzzing`` tag.

If you’ve found a bug, or have an idea/suggestion/request, file an issue
here on GitHub.

For other questions, check out boofuzz on `gitter`_ or `Google Groups`_.

For updates, follow `@fuzztheplanet`_ on Twitter.

.. _Sulley: https://github.com/OpenRCE/sulley
.. _Google Groups: https://groups.google.com/d/forum/boofuzz
.. _gitter: https://gitter.im/jtpereyda/boofuzz
.. _@fuzztheplanet: https://twitter.com/fuzztheplanet
.. _documentation: http://boofuzz.readthedocs.io/
.. _INSTALL.rst: INSTALL.rst
.. _CONTRIBUTING.rst: CONTRIBUTING.rst
