---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Overview
======
My current research is as a member of the PEARLS and VENUS collaborations, searching and classifying high-redshift galaxies in deep optical and near-infrared data from both the Hubble Space Telescope (HST) and James Webb Space Telescope (JWST). In particular I am interested in the physics governing ionizing photon production and escape from the ISM, which has profound implications for the reionization history and topology. During my academic studies as a PhD student and postdoctoral researcher at the University of Manchester I have developed a highly modular and public cataloguing software, [galfind](https://github.com/duncanaustin98/galfind), for galaxy identification, classification, and sample selection. Using this photometric toolbox, I have identified several new high-redshift galaxy candidates from the first billion years of the Universe's history using state-of-the-art JWST/NIRCam photometric imaging, leading to the development of two high-redshift paper series.

Education
======
* **PDRA** — ERC funding provided by Chris Conselice, University of Manchester, 2025 - Onwards
  * Research interests: Reionization, UV luminosity functions, SED fitting, cataloguing and data reduction techniques for JWST/NIRCam, galaxy clustering and cosmic variance modelling
* **PhD Astrophysics** — STFC funded, University of Manchester, 2021 - 2025
  * Thesis title: *Inferring the properties of star forming galaxies in the Epoch of Reionization with JWST*
* **MPhys (Hons), 1st class** — University of Manchester, 2017 - 2021
  * Received outstanding achievement letter for obtaining an average grade > 80%, signed by Chief Examiner and Assessment Lead, Judith McGovern

Research Summary
======
* **EPOCHS-DR2 II: Blank field UV luminosity functions highlight an elevated and evolving star formation efficiency** — PDRA, University of Manchester, December 2025 - Ongoing (paper to be submitted within ~1-2 months)
  * UVLFs calculated using a unique 1/Vmax technique that incorporates non-uniform field depths to remove the bias towards flatter faint-end slopes found in regular studies
  * HOD framework used to estimate halo masses and provide contours in the UV luminosity–halo mass scatter vs star formation efficiency parameter space from joint UVLF + galaxy bias constraints

* **EPOCHS-DR2 I: Expanded data release and properties of 6.5 < z < 16.5 galaxies across NIRCam deep fields covering ~700 arcmin²** — PDRA, University of Manchester, December 2025 - Ongoing (paper in final internal review stage)
  * Presents a fiducial sample of ~2,500 galaxy candidates at 6.5 < z < 16.5 from HST/ACS_WFC and JWST/NIRCam data, cross matched to 292 NIRSpec/PRISM spectra from the DJA v4.4
  * Most comprehensive completeness/contamination estimates in the EoR to date using real spectra
  * KL-divergence analysis performed on the output Bagpipes SED fitting results, highlighting which parameters/hyperparameters are not adequately constrained as a function of redshift, including f<sub>esc</sub><sup>LyC</sup>
  * Includes a "gold" sample of z > 10.5 candidates with an increased SNR detection threshold; the estimated 60-75% contamination rate suggests 5-7 should be real high-redshift objects, in minor tension with McLeod+2026 and Weibel+2026. Two blue z ≃ 14 candidates have robust > 3σ F335M and F410M detections which merit single-slit NIRSpec follow-up

* **The galfind optical/NIR photometric toolbox** — PhD, University of Manchester, September 2022 - Ongoing [[galfind](https://github.com/duncanaustin98/galfind)]
  * Includes a cataloguing tool to perform source extraction, depth calculation, automasking, sample selection, SED fitting, photometric property calculation, luminosity/mass functions, and morphological fitting
  * Written in a flexible object-oriented framework, including ReadTheDocs documentation

* **Resolving the ionizing photon budget crisis with HII clumping constraints at z ≃ 6** — PhD, University of Manchester, July 2024 - July 2026
  * Calculates ionizing photon production rates and efficiencies as well as Lyman continuum escape fractions for a large sample of star forming and smouldering galaxies across a range of deep, blank field, photometric surveys
  * Clumping factor constraints required to match direct x<sub>HI</sub> measurements, solving the ionizing photon budget crisis

* **UV continuum slopes from wideband JWST/NIRCam photometry** — PhD, University of Manchester, July 2023 - October 2025
  * Used the galfind software to produce a sample of > 1000 star forming galaxies at 6.5 < z < 13 (the EPOCHS series)
  * Thorough analysis to outline (and partially correct for) UV continuum slope, β, biases associated with underestimated Lyα emission and damped Lyα absorption, as well as strong rest-frame UV emission lines
  * Reveals a lack of dust in star-forming galaxies at high redshift, in tension with simulations

* **High-redshift SFGs in the NGDEEP survey** — PhD, University of Manchester, February 2023 - July 2023
  * Performed source extraction, deblending, and forced photometry with SExtractor using a variety of photometric filters for selection
  * Calculated photometric redshifts using appropriate SFG templates within EAZY-py, and constructed a robust sample including various redshift PDF and SNR criteria

* **Galaxy clustering analysis in the UDS field** — PhD, University of Manchester, September 2021 - September 2022
  * Calculated galaxy biases and halo masses at z < 4 for a large sample of ~10,000 Lyman break galaxies over 0.8 deg² to investigate the redshift dependence of the angular galaxy clustering signal
  * Observed halo downsizing by performing analysis in a variety of stellar mass bins

* **Scale dependence of the linear HI bias approximation in semi-analytical models** — MPhys, University of Manchester, September 2020 - July 2021
  * Used the L-Galaxies, GAEA, and DARK SAGE semi-analytical models (SAMs) to explore baryonic feedback and cold gas partitioning via the HI mass function, HI-stellar, and HI-halo mass relations
  * Computed a basic HI power spectrum and investigated the scale dependence of the HI bias to determine the appropriateness of the linear bias approximation in the case of each SAM

Publications
======
{% assign sorted_pubs = site.publications | sort: "title" | sort: "date" | reverse %}
  <ul>{% for post in sorted_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Activity: Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching and Leadership Experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Scientific Outreach and Public Engagement
======
* **Science demonstrator** — Bluedot festival, July 2022, July 2023
  * Voluntary work for both the JBCA and JWST extragalactic astrophysics stands
  * Discussion of astrophysical principles to inspire the general public, including children. Hands-on demonstrations include VR headsets displaying the multi-wavelength night sky, an IR camera to showcase JWST/NIRCam photometry, and spectroscopy with fluid tubes using a diffraction grating

Additional Skills
======
* **Programming Languages:** Python, C++ (both object oriented and functional)
* **Software:** SAOImage DS9, TOPCAT, SExtractor, Photutils, EAZY-py, Bagpipes, GALFIT, pysersic, msaexp
* **Mathematical & Statistical Techniques:** Bootstrapping, 2-pt clustering statistics, Bayesian inference and Monte-Carlo Markov Chain sampling
* **DevOps & Version Control:** Continuous Integration (CI) with GitHub Actions, Sphinx + ReadTheDocs, pytest, ruff, pre-commit
