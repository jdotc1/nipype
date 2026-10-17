.. rubric:: About this fork

This is a development fork of `nipy/nipype <https://github.com/nipy/nipype>`__. Nipype provides a common Python interface to neuroimaging tools such as FSL, FreeSurfer, AFNI, ANTs, and SPM, so processing steps from different packages can be composed into one workflow. It is useful for making those connections explicit and sharing processing pipelines.

The fork's `upstream PR #3784 <https://github.com/nipy/nipype/pull/3784>`__ proposes inspecting executable dependencies without shell parsing. It was open on 17 October 2026 and is tracked on its linked feature branch.

Start with the `official documentation <https://nipype.readthedocs.org/en/latest/>`__ for installation, interfaces, and workflow examples; individual tools have their own requirements. `Compare the default branch with upstream <https://github.com/jdotc1/nipype/compare/nipy:master...jdotc1:master>`__. The upstream README and its community and contribution links are preserved below.

.. rubric:: Upstream README

.. image:: https://raw.githubusercontent.com/nipy/nipype/master/doc/_static/nipype-banner-bg.png
   :target: https://nipy.org/nipype
   :alt: Nipype logo

.. list-table::
   :widths: 20 80
   :header-rows: 0

   * - Code
     -
      .. image:: https://img.shields.io/pypi/pyversions/nipype.svg
         :target: https://pypi.python.org/pypi/nipype/
         :alt: Supported Python versions

   * - Tests
     -
      .. image:: https://codecov.io/gh/nipy/nipype/branch/master/graph/badge.svg
         :target: https://codecov.io/gh/nipy/nipype
         :alt: codecov badge
      .. image:: https://travis-ci.org/nipy/nipype.svg?branch=master
         :target: https://travis-ci.org/nipy/nipype
         :alt: Travis CI badge
      .. image:: https://circleci.com/gh/nipy/nipype/tree/master.svg?style=svg
         :target: https://circleci.com/gh/nipy/nipype/tree/master
         :alt: CircleCI badge

   * - PyPI
     -
      .. image:: https://img.shields.io/pypi/v/nipype.svg
         :target: https://pypi.python.org/pypi/nipype/
         :alt: PyPI version
      .. image:: https://img.shields.io/pypi/status/nipype.svg
         :target: https://pypi.python.org/pypi/nipype/
         :alt: Development Status
      .. image:: https://img.shields.io/pypi/dm/nipype.svg
         :target: https://pypistats.org/packages/nipype
         :alt: PyPI - Downloads

   * - Packages
     -
      .. image:: https://img.shields.io/conda/vn/conda-forge/nipype
         :target: https://anaconda.org/conda-forge/nipype
         :alt: Conda package

   * - License & DOI
     -
      .. image:: https://img.shields.io/pypi/l/nipype.svg
         :target: https://pypi.python.org/pypi/nipype/
         :alt: License
      .. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.596855.svg
         :target: https://doi.org/10.5281/zenodo.596855
         :alt: Citable DOI

   * - Community
     -
      .. image:: https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg?style=flat
         :target: http://gitter.im/nipy/nipype
         :alt: Chat

Current neuroimaging software offer users an incredible opportunity to
analyze data using a variety of different algorithms. However, this has
resulted in a heterogeneous collection of specialized applications
without transparent interoperability or a uniform operating interface.

*Nipype*, an open-source, community-developed initiative under the
umbrella of `NiPy <http://nipy.org>`_, is a Python project that provides a
uniform interface to existing neuroimaging software and facilitates interaction
between these packages within a single workflow. Nipype provides an environment
that encourages interactive exploration of algorithms from different
packages (e.g., AFNI, ANTS, BRAINS, BrainSuite, Camino, FreeSurfer, FSL, MNE,
MRtrix, Nipy, Slicer, SPM), eases the design of workflows within and
between packages, and reduces the learning curve necessary to use different
packages. Nipype is creating a collaborative platform for neuroimaging
software development in a high-level language and addressing limitations of
existing pipeline systems.

*Nipype* allows you to:

* easily interact with tools from different software packages
* combine processing steps from different software packages
* develop new workflows faster by reusing common steps from old ones
* process data faster by running it in parallel on many cores/machines
* make your research easily reproducible
* share your processing workflows with the community

Documentation
-------------

Please see `nipy.org/nipype <http://nipy.org/nipype>`_ for the Nipype
documentation.

Python 2 Statement
------------------

Python 2.7 reaches its end-of-life in January 2020, which means it will
*no longer be maintained* by Python developers. `Many projects
<https://python3statement.org/>`__ are removing support in advance of this
deadline, which will make it increasingly untenable to try to support
Python 2, even if we wanted to.

The final series with 2.7 support is 1.3.x. If you have a package using
Python 2 and are unable or unwilling to upgrade to Python 3, then you
should use the following `dependency
<https://www.python.org/dev/peps/pep-0440/#version-specifiers>`__ for
Nipype::

    nipype<1.4

Bug fixes will be accepted against the ``maint/1.3.x`` branch.

Support and Communication
-------------------------

If you have a problem or would like to ask a question about how to do something in Nipype please open an issue to
`NeuroStars.org <http://neurostars.org>`_ with a *nipype* tag. `NeuroStars.org <http://neurostars.org>`_  is a
platform similar to StackOverflow but dedicated to neuroinformatics.

To participate in the Nipype development related discussions please use the `neuroimaging mailing list <http://mail.python.org/mailman/listinfo/neuroimaging>`_.

Please add *[nipype]* to the subject line when posting on the mailing list.

You can even hangout with the Nipype developers in their
`Gitter <https://gitter.im/nipy/nipype>`_ channel or in the BrainHack `Slack <https://brainhack.slack.com/messages/C1FR76RAL>`_ channel. (Click `here <https://brainhack-slack-invite.herokuapp.com>`_ to join the Slack workspace.)


Contributing to the project
---------------------------

If you'd like to contribute to the project please read our `guidelines <https://github.com/nipy/nipype/blob/master/CONTRIBUTING.md>`_. Please also read through our `code of conduct <https://github.com/nipy/nipype/blob/master/CODE_OF_CONDUCT.md>`_.
