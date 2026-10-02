The Triaxial Polymer Ejection System

A Bio-Inspired Multiaxial Extrusion System for Synthetic Silk Strands
DOI: https://doi.org/10.5281/zenodo.23104622
Developed by Satronic Labs / Satronic Group
Lead Researcher: Bellam Sri Sathwik Reddy
Project Status: Open-Source Theoretical / Hobbyist Specification

Project Overview
This repository contains the hardware documentation, 3D schematics, fluid dynamics principles, and chemical frameworks for a portable, user-operated Triaxial Polymer Ejection System (conceptually a real-world, functional "Spider-Man web shooter"). Inspired by the 2024 Tufts University Boston SilkLab experiment, this system explores the rapid, pneumatic deployment of high-tensile, immediate-adhesive synthetic structural strands capable of item retrieval.

System Architecture

1. Mechanical and Fluid Delivery
Triaxial Extrusion Nozzle: Features a nested three-channel system designed for simultaneous polymer delivery, solvent-driven curing, and pneumatic alignment:
Inner Channel (20-gauge): Houses the active liquid polymer fluid.
Middle Channel (16-gauge): Feeds 100% pure acetone for instantaneous chemical solidification.
Outer Channel (12-gauge): Directs compressed CO2 gas.
Pneumatic Booster: An automated carbon fiber pressure chamber reinforced with an outer titanium shell. It seals both exits upon intake and releases internal CO2 gas up to a maximum peak of ~100 PSI.
Aerodynamics: The outer pneumatic ring exploits the Venturi effect to optimize mechanical strand alignment and extend delivery range.

2. Theoretical Chemical Formula

An 11% (w/w) concentrated fluid solution optimized for immediate cross-linking and extreme load-bearing strength:
4g Silk Fibroin: Derived from silk cocoons via boiling sodium bicarbonate followed by Ajisawa's reagent dissolution.
3g Chitosan: Incorporated into the matrix to scale load-bearing capacity up to 800x the strand's weight.
3g Tannic Acid: Replaces scarce dopamine, acting as the primary mussel-biochemistry adhesive agent.
1g Borate Buffer: Complements the primary catechol group adhesive, increasing surface tackiness 18-fold.
89mL H2O: Universal carrier solvent.
Valve Shutdown Timing and Safety

To completely prevent catastrophic fluid backflow or high-pressure nozzle clogging, the system relies on an asynchronous milliseconds-based valve shutdown sequence upon releasing the activation lever:

0 ms: Close Inner Channel (Polymer Stops)
1 ms: Close Middle Channel (Acetone Solvent Stops)
200 ms: Close Outer Channel (CO2 Purge Ends)
