---
title: "Software"
permalink: /software/
---

Here's a list of the software I've written, all of it is open-source.

[Waveplot](https://www.waveplot.com/)
--------

An online wavefunction viewer which demonstrates simple concepts in quantum chemistry. Waveplot is built with students in mind and features the model quantum systems they encounter in introductory quantum chemistry. Students can manipulate input variables, plots, and download raw data to use in their own work.

[AtomAccess](https://pypi.org/project/atom-access)
-----------------

A python package which quantifies steric hindrance at chemical centres using raytracing. I wrote AtomAccess to be fast and user-friendly through either its simple [web-interface](https://magnetism-tools.manchester.ac.uk/apps/atom_access_app), or through command-line and scripting.

[ccfit2](https://pypi.org/project/ccfit2/)
-------

A python package for working with experimental magnetometry data. Users can input a magnetometer output file and obtain a fitted plot of their data using a single command and an interactive interface. Thanks to its modular design and rich documentation, `ccfit2` can be included in users own python code with ease. 

Tau
---

A C++/Fortan90 program for the simulation of magnetic relaxation rates. Tau uses ab initio spin-phonon coupling data to accurately simulate magnetic relaxation under a range of conditions using a semi-classical master equation.

FIRMS_SIM
---------

A Fortran90 program for simulating far-infrared magnetospectroscopy spectra. I wrote `FIRMS_SIM` during the latter half of my PhD. You can see the results [here](https://www.nature.com/articles/s41467-022-28352-2).


*_suite
---------

The `*_suite` codes are used by the Chilton group to work with various computational chemistry software packages. I wrote varying amounts of these with other members of the Chilton Group
(Jakob Staab, Dr Letitia Birnoschi), and I personally wrote the entire CI/CD pipeline for all packages. I no longer contribute to these projects.