RTP: Reproducible Tract Profiles===================================

**RTP** comprises a set of methods to manage and analyze diffusion weighted imaging (DWI) data for reproducible tractography. The tools take MRI data from the scanner and process them through a series of analysis implemented as Docker containers that are integrated into a modern neuroinformatics platform (Flywheel, Docker, Singularity). The platform guarantees that the entire pipeline can be re-executed, using the same data and computational parameters. We describe the DWI analysis tools that are used to identify the positions of a user-defined number of tracts and their diffusion profiles. The combination of these three components defines a system that transforms raw data into reproducible tract profiles for publication.

Although this repository is only for the tracking part, the whole solution is comprised of three main parts from nifti to tractography (each one implemented in a different container): Anatomical ROI creation, diffusion preprocessing, and tracking/metric derivation pipeline.

Check out the :doc:`How to use` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   How to use
   Installation
