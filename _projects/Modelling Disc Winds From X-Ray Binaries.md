---
layout: page
title:  Modelling Disc Winds From X-Ray Binaries
description: Astrophysics Internship - 2023
img: assets/img/Rob_Hynes_BinSim_XRB.jpeg
importance: 2
category: Internships and Undergraduate
related_publications: true
---

<i> Cover image produced with BinSim by Rob Hynes {% cite hynes2010binsim %}.</i>

Often black holes will be a part of a binary system, where its companion is a star in an earlier stage of its life. X-ray binaries (XRBs) are examples of such systems. In these systems, matter from the companion star can by attracted by the black hole and form an accretion disk around it. These accretion discs eject material due to thermal and/or magnetic processes. Disc winds also carry away some material and are identified by P-Cygni profiles in spectra. These are characterised by an emission due to the deexcitation of atoms in the accretion disk combined with a blueshifted absorption at a lower wavelength as can be seen in Figure 1.

<div class="row justify-content-center">
  <div class="col-auto text-center mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/P-Cygni.png"
       title="P-Cygni Profile"
       class="img-fluid small-figure rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    <i>Figure 1.</i> Prominent features of a P-Cygni profile. Adapted from Figure 12.17 of {% cite carroll2006introduction %}.
</div>

This has been seen in data for XRBs in the optical region, but not in simulations. Using the Monte Carlo radiative transfer code: PYTHON, we explored the system's parameter space to find the conditions under which such a profile arises. By analysing the data using a variety of techniques, we successfully found the conditions to simulate P-Cygni profiles for XRBs in the optical spectrum for the first time.







