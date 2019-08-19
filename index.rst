The open-source QCArchive Infrastructure
========================================
The QCA project is designed from the start to be open-source and available to
the computational molecular sciences community. The entire code base is public
through GitHub repositories, and we are contributing back to other Open Source
projects as good members of the community. Rather than a monolithic piece of
software, the QCArchive software ecosystem is decomposed into several
components so that it can be used as a full ecosystem to build on top of or in
support of community software. See a full list of software components here.


A multilayered ecosystem
========================

The QCArchive ecosystem is made up of a series of layers to suit a variety of different use cases. The QCArchive ecosystem consists of the following:
Support libraries for quantum chemistry, from physical constants to abstract program execution engines.
A distributed task engine for running and organizing arbitrary computations.
The MolSSI QCArchive instance for the community to share and archive data.
High-level organizational layers known as Collections to compute and analyize commonly found operations.
See our getting started page for help on finding the right place to start:

We support software best practices
=================================

QCArchive's projects are all based on the same software best practices. Both users and developers can follow the code structure between all of the projects, and these practices are provided back to the community through the external projects like the CMS-Cookiecutter. This cookiecutter supports:

Continuous integration with automated testing and testing coverage
Automated versionsing and package distribution via Conda-Forge and PyPI
Code quality and linting checks for beutiful code
Automatic package organization and documentation setup

Code quality is of utmost importance
====================================

The quality of the QCArchive code is checked through rigorous continuous integration, code linters, and test coverage tools which help reduce the chance that bugs are introduced. We take data accuracy very seriously and all results and calculations are versioned, provenance tracked, and will be preserved over any updates of the database.

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Overview

   index.rst

.. toctree::
   :maxdepth: 1
   :caption: Basic Examples

   basic_examples/getting_started.ipynb
   basic_examples/reaction_datasets.ipynb
   basic_examples/torsiondrive_datasets.ipynb

