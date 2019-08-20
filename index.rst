QCArchive Infrastructure
========================
The infrastructure that powers the MolSSI QCArchive is made up of a series of
open-source layers that can be used for a variety of projects and use cases.
Every piece of software that we develop is available on GitHub and supported by
the MolSSI team.

At the outer most scope the QCArchive infrastructure allows you to generate
data precisely as we do in QCArchive and run the same statistical and visual
analysis without interacting with the MolSSI servers and instead, hold the data
privately. In addition, at a later data if you would like to upload your data
to the MolSSI servers it is a very quick and easy process!

.. image:: media/boxology_private.png
   :width: 80%
   :alt: QCArchive ecosystem
   :align: center

Layered Infrastructure
----------------------

While the infrastructure can be used as a single unit to manage data at scale
each library that we support can be used individually for many uses outside of
data management.  The capabilities of each library are as follows:

- |qcelemental_docs|_ - Periodic table information, version-controlled physical constants, molecule parsing, testing infrastructure, and MolSSI QCSchema models.
- |qcengine_docs|_ - Quantum chemistry program executor and IO standardizer (QCSchema).
- |qcfractal_docs|_ - Distributed task scheduler and executor, database store for chemistry results, and organization of results at scale.
- |qcportal_docs|_ - Visualization, organization, and statistical data for chemistry-related results and a front-end client for QCFractal.



Project Highlights
------------------
A few projects in which the QCArchive infrastructure is being implemented are as follows:

- `Psi4 <http://psicode.org>`_ - A quantum chemistry packages which uses QCElemental for physical constants and QCEngine to compute addititive properties such as DFTD3.
- `geometric <https://github.com/leeping/geomeTRIC>`_ - A backend agnostic geometry optimizer which uses QCEngine to evaluate gradients for a variety of different quantum chemistry-like packages.
- `MultirefPredict <https://github.com/hjkgrp/MultirefPredict>`_ - Multireference character prediction using QCElemental for model implementations and QCEngine to harness many backends simultaneously.

Project Demos
-------------
To highlight the capabailities of each project, short demoss were created.
Full details can be found by going to each projects Documentation page which
can be found in the dropdown at the top of this page.

- `QCElemental <basic_examples/QCElemental.html>`_
- `QCEngine <basic_examples/QCEngine.html>`_

Supported by
------------
The QCArchive infrastructure is supported by the `Molecular Science Software Institute <https://molssi.org>`_ and the `National Science Foundation <https://www.nsf.gov>`_

.. raw:: html
    
    <div style="width: 50%; margin: auto; padding: 10px">
    <style scoped type="text/css">
    
    img.logo-row {
        display: inline-block;
        margin-left: auto;
        margin-right: auto;
        width: 150px;
        passing: 10px;
    }
    </style>
    
    <a href="https://molssi.org"><img class="logo-row" src="_static/images/molssi-logo.png" alt="MolSSI"></a>
    <a href="https://www.nsf.gov"><img class="logo-row" src="_static/images/nsf.png" alt="NSF"></a>
    </div>


Additional features are sponsored by our partners:

- `Open Force Field Initiative <https://openforcefield.org>`_

Consider becoming a feature sponsor `today <community.html#work-with-us>`_!

.. toctree::
   :maxdepth: 1
   :caption: Overview
   :hidden:

   philosophy
   community


.. toctree::
   :maxdepth: 1
   :caption: Module Demos
   :hidden:

   basic_examples/QCElemental.ipynb
   basic_examples/QCEngine.ipynb

