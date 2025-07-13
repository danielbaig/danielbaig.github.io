---
layout: page
title: Uncertainties on Parton Distributions
description: Final Year MSci Project - 2024
img: assets/img/ATLAS-Wboson-production.jpg
importance: 5
category: Internships and Undergraduate
related_publications: true
---

<i> Cover image credit {% cite atlas2024wboson %}.</i>


Parton distribution functions (PDFs) are instrumental to our understanding of the inner structure of hadrons and are essential for experiments that involve hadronic colliders. This project reviewed the applications of PDFs in deep inelastic scattering and Drell-Yan vector boson production. They were then used to explore W boson differential cross-sections with respect to W boson rapidity in addition to differential cross-sections with respect to electron rapidity at leading order (LO) and next-to-leading order (NLO). Then, we inspected the effect of applying a cut on the transverse momentum of the emitted positron (electron) and how this differs from also applying a cut to the (anti)electron-neutrino's transverse momentum. It was found that the disparity between the cut types can begin to elucidate our understanding of discrepancies between cross-sections obtained by ATLAS and LHCb collaborations for the 
\begin{equation}
	pp\rightarrow W^{\pm}\rightarrow e^{\pm}\overset{(-)}{\nu_e}
\end{equation}
interaction process.

To carry out this study we first generated the PDFs using the central set of MSHT2020 PDFs translated and adapted from an existing code written in Fortran {% cite harland2015parton %}. After the PDFs were determined they were retrieved using Python and combined with LO and NLO cross-sections to obtain total cross-section and differential cross-section distributions for various cuts on the transverse momentum of the emitted leptons in W boson production. The full process for generating the cross-section ratios between the different cut types is schematically depicted in Figure 1.

<div class="row justify-content-center">
  <div class="col-auto text-center mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/NLO_pT_cut_flowchart.png"
       title="NLO pT cut flowchart"
       class="img-fluid w-75 small-figure rounded z-depth-1 bg-white"
    %}
  </div>
</div>
<div class="caption">
    <i>Figure 1.</i> Flowchart showing the procedure to determine the variation of the ratio of the cross-sections with different cut types as the magnitude of the cut on the transverse momentum varies.
</div>






