---
title: "Surfing Wing: Aerodynamic Forces in a Two-Dimensional Vortex Wake"
excerpt: "An instrumented airfoil surfing a controlled vortex street, and a model that predicts its lift (2022&ndash;2025) <br/><img src='/images/SurfingWing.jpg'>"
collection: portfolio
---

If a flapping flyer gains something from another's wake, the effect should be measurable on a *rigid* wing too &mdash; without the confounding variability of a live animal. This project is the engineering counterpart to the [Surfing on Vortices](/portfolio/02-surfing-birds/) bird experiments.

A servo-driven wake generator pitches a flat plate sinusoidally upstream; a NACA 0012 wing mounted 350 mm downstream on a six-axis load cell measures forces at 5 kHz over 100 cycles, while 2D2C PIV captures the vortex dynamics in the same plane. The whole setup is automated in MATLAB with synchronized acquisition, which is what makes a sweep across Strouhal number, reduced frequency and flapping amplitude tractable.

<img src='/images/SurfingWing.jpg' alt="The surfing wing and upstream wake generator under laser illumination in the test section">

Two results drive the work:

* The wing's lift response **locks to the wake-generating frequency**, and cycle-level lift fluctuations scale with Strouhal number &mdash; 58&ndash;99% of the spectral energy sits in the primary peak.
* Classical unsteady aerodynamics predicts the phase-resolved lift well when the right tool is used: **Wagner's function with Duhamel's integral** tracks the measured lift closely, while a quasi-steady approach massively over-predicts it.

Presented at the 77th APS-DFD Annual Meeting (2024); manuscript under review at the *Journal of Fluid Mechanics*.

[Download the DFD 2024 poster (PDF, 11 MB)](/images/Poster_DFD2024_lessword.pdf)
