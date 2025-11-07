---
title: 'Modelling the progress of reionization'
date: 2025-11-08
permalink: /posts/2025/11/modelling_reionization/
tags: [Physics, Reionization]
math: true
---

Following the dark ages in the Universe's history, the gravitational collapse of baryons formed the first stars and galaxies around 250 Myr after the Big Bang at redshifts $z\gtrsim14-20. The onset of nuclear fusion within Population III stars produced copious amounts of photons to reionize the Universe from mainly neutral hydrogen (HI) to ionized hydrogen (HII). Although the precise nature of this process is not well known, it is believed to have ended by $z\simeq5-6$. This period of time is known as the Epoch of Reionization.

We have several pieces of observational evidence which have aided us in this discovery:
- Estimates of the optical depth to reionization from Planck and WMAP measurements of the Cosmic Microwave Background
- The decline in observed Ly$\alpha$ emission in galaxies at high redshift within the EoR
- Total absorption of the Ly$\alpha$ forest in quasar spectra by the Gunn Peterson trough at rest-frame wavelengths $\lambda_{\rm rest}<1216~\mathrm{\AA}$

<!-- - Redshifted observations of the 21cm spin-flip transition in neutral hydrogen -->


The reionization ODE
====================

$$
    \dot{Q}_{\rm HII} = \frac{\dot{n}_{\rm ion}}{\langle n_{\rm H}\rangle} - \frac{Q_{\rm HII}}{\langle t_{\rm rec}\rangle}
$$


Source term
-----------

$\dot{n}_{\rm ion}$: Rate of ionizing photons produced and escaping the ISM surrounding the source galaxies/AGN and into the IGM

$\langle n_{\rm H} \rangle$: Volume-averaged hydrogen density


Sink term
---------

$Q_{\rm HII}$: Ionized hydrogen volume-filling factor

$\langle t_{\rm rec} \rangle$: Mean recombination timescale for ionized hydrogen in the IGM



Optical depth to reionization
=============================
