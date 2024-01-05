---
title: "Software"
permalink: /software/
---

Here's a list of the software I've written, nearly all of it is open-source.

[Waveplot](https://www.waveplot.com/)
--------

An interactive wavefunction viewer made to demonstrate some simple concepts in quantum chemistry. Waveplot is written in python using Dash.

[AtomAccess](https://pypi.org/project/atom-access)
-----------------

A python ray-tracing program which quantifies the steric hindrance of reactive centres. I rewrote AtomAccess from an initial version by Dr Gemma Gransbury,
making the code considerably faster and much more modular. You can read more about the AtomAccess code and Gemma's results from using it [here](https://pubs.acs.org/doi/10.1021/jacs.3c08841). I also wrote a [web interface](https://magnetism-tools.manchester.ac.uk/apps/atom_access_app) for AtomAccess in python using Dash, and this is hosted on a custom Apache web server (which I set up) at the University of Manchester.

[ccfit2](https://pypi.org/project/ccfit2/)
-------

A python package which makes processing magnetometry data easy. Currently, `ccfit2` can work with AC susceptibility, DC decay, and DC Waveform data.
`ccfit2` also has the capability to fit magnetic reversal rate data to various phenomenological models. There is a user-friendly command line interface available,
along with a slimmed down executable version for users who don't want to use a terminal. Dr Daniel Reta originally wrote `ccfit2` while in the Chilton Group. I completely rewrote `ccfit2` from scratch in version `5.0.0` and it is now a modular python package which can be either used through its command line interface, or imported into other python scripts and programs.

Tau
---

A C++/Fortran90-95 program for calculating magnetic reversal rates in single molecule magnets using ab initio spin-phonon coupling data. I wrote `Tau` using some initial code
written by Prof. Nicholas Chilton. I no longer contribute to this project.

FIRMS_SIM
---------

A Fortran90-95 program for simulating far-infrared magnetospectroscopy spectra. I wrote `FIRMS_SIM` during the latter half of my PhD. You can see the results [here](https://www.nature.com/articles/s41467-022-28352-2).


*_suite
---------

The `*_suite` codes are used by the Chilton group to work with various computational chemistry software packages. I wrote varying amounts of these with other members of the Chilton Group
(Jakob Staab, Dr Letitia Birnoschi), and I personally wrote the entire CI/CD pipeline for all packages. I no longer contribute to these projects.