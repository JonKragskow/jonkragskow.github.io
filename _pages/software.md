---
title: "Software"
permalink: /software/
---

Here's a home for all the software I've written. Unless stated otherwise, assume I'm the one who wrote it.

[Waveplot](https://www.waveplot.com/)
--------

An interactive wavefunction viewer made to demonstrate some simple concepts in quantum chemistry. Waveplot is written in python using Dash.

[Magnetism-Tools](https://magnetism-tools.manchester.ac.uk/apps/atom_access_app)
-----------------

A home for web-interfaces to software developed by the Chilton Group at the University of Manchester. Currently, Magnetism-Tools contains
an interactive Tanabe-Sugano diagaram viewer, and AtomAccess; a ray-tracing program which quantifies the steric hindrance of reactive centres.
Magnetism-Tools is written in python using Dash, and is hosted on a custom Apache web server (which I set up) at the University of Manchester.

[`ccfit2`](https://pypi.org/project/ccfit2/)
-------

A python package which makes processing magnetometry data easy. Currently, `ccfit2` can work with AC susceptibility, DC decay, and DC Waveform data.
`ccfit2` also has the capability to fit magnetic reversal rate data to various phenomenological models. There is a user-friendly command line interface available,
along with a slimmed down executable version for users who don't want to use a terminal. Dr Daniel Reta originally wrote `ccfit2` while in the Chilton Group,
and I have subsequently rewritten the entire code as a more modular python package, and added proper semantic versioning.

`Tau`
---

A C++/Fortran90-95 program for calculating magnetic reversal rates in single molecule magnets using ab initio spin-phonon coupling data. I wrote `Tau` using some initial code
written by Prof. Nicholas Chilton, and it is now worked on by other members of the Chilton Group.

`*_suite`
-------

The `*_suite` codes are used by the Chilton group to work with various computational chemistry software packages. I wrote varying amounts of these with other members of the Chilton Group
(Jakob Staab, Dr Letitia Birnoschi), and I personally wrote the entire CI/CD pipeline for all packages.