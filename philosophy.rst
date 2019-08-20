Software Philosophy
===================
The QCArchive is an open community sponsored by `The Molecular Sciences
Software Institute <https://molssi.org>`_. However, this is a community-driven
project which requires feature requests, user feedback, and code support.
There are a variety of ways to help support the QCArchive project as seen
below.

Open-source infrastructure
--------------------------

The QCArchive project is designed from the start to be open-source and available to
the computational molecular sciences community. The entire code base is public
through GitHub repositories, and we are contributing back to other Open Source
projects as good members of the community. Rather than a monolithic piece of
software, the QCArchive software infrastructure is decomposed into several
components so that it can be used as a full ecosystem to build on top of or in
support of community software.

We support software best practices
----------------------------------

QCArchive's projects are all based on the same software best practices. Both
users and developers can follow the code structure between all of the projects,
and these practices are provided back to the community through the external
projects like the CMS-Cookiecutter. This cookiecutter supports:

- Continuous integration with automated testing and testing coverage.
- Automated versionsing and package distribution via Conda-Forge and PyPI.
- Code quality and linting checks for beutiful code.
- Automatic package organization and documentation setup.

The cookiecutter is available for all Python projects! Check it out `here <https://github.com/MolSSI/cookiecutter-cms>`_!

Code quality is of utmost importance
------------------------------------

The quality of the QCArchive code is checked through rigorous continuous
integration, code linters, and test coverage tools which help reduce the chance
that bugs are introduced. We take data accuracy very seriously and all results
and calculations are versioned, provenance tracked, and will be preserved over
any updates of the database.


.. image:: media/covlgtm.png
   :width: 400px
   :alt: CodeCoverage
   :align: center
