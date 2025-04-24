# Development of a Surface Plasmon Resonance Sensor for Predicting Airborne Contaminants and Their Cumulative Impact on Human Health

## Overview
This repository contains my Bachelor's final qualification work in Optical Engineering (12.03.02) completed at Bauman Moscow State Technical University in collaboration with Russian Academy of Science in 2023. Under the supervision of I.Sh. Khasanov and V.I. Batshev, the project focuses on the development of a Surface Plasmon Resonance (SPR) sensor aimed at predicting airborne contaminants and assessing their cumulative impact on human health. The work includes the principal development of the sensor's optical design, computational simulation and optimization processes and a detailed experimental study.

## Principal Development
The core of this project is the design and implementation of an SPR sensor based on the following principles:

- **SPR Principle & Optical Scheme:**  
  The sensor operates using the Kretschmann configuration, where a thin silver nanofilm is deposited on a glass prism. When illuminated by a He-Ne laser (λ = 632.8 nm) through a prismatic input method, the sensor excites surface plasmon polaritons (SPPs) on the metal film. The resonance condition is monitored by tracking changes in the reflectivity function R(θ).

- **Sensor Architecture:**  
  The optical layout comprises:
  - A **He-Ne laser** as the light source.
  - **Polarizers** and a **mirror system** to control and direct the beam.
  - **Telescopic systems** to expand the laser beam.
  - A **diaphragm** and **collecting lens** to shape and focus the beam.
  - A **glass prism** coated with a silver nanofilm, which is the active element for SPR excitation.
  - A **camera** that records the reflected beam and captures the resonance images.

- **Optimization Approach:**  
  In addition to the basic sensor design, an adaptive Monte Carlo method was applied to optimize key parameters—such as the thickness of the silver film, resonance angle, and wavelength—to achieve a reflectance coefficient R below 10⁻². This optimization enhances the sensitivity of the sensor, ensuring reliable detection of low concentrations of toxic substances.

## Experiment
The experimental phase validated the sensor's performance under controlled conditions:

- **Experimental Setup:**  
  The sensor was integrated into an experimental setup consisting of:
  1. **He-Ne Laser (λ = 632.8 nm):** Provides the coherent light necessary for SPR excitation.
  2. **Polarizer and Mirror System:** Shape and direct the laser beam.
  3. **Telescopic Beam Expanders:** Increase the beam diameter for uniform illumination.
  4. **Diaphragm and Collecting Lens:** Precisely control the beam profile.
  5. **Glass Prism with Silver Nanofilm:** The core component where SPR occurs.
  6. **Camera:** Captures sequential images of the reflected beam, recording changes in the resonance curve over time.

- **Experiment Details:**  
  - **Duration:** The experiment was conducted over a period of 13 hours.
  - **Conditions:** The sensor was exposed to a controlled chlorine atmosphere (0.005% concentration) at 20°C.
  - **Observations:**  
    - Initial images captured the pristine state of the silver nanofilm.
    - Subsequent images, recorded after 2 hours and beyond, showed gradual changes in the resonance curves, indicating the onset and progression of corrosion due to chlorine exposure.
    - The evolution of the SPR images and reflectivity data enabled a quantitative analysis of the sensor's response to the corrosive process.
    
- **Significance:**  
  The experiment demonstrated the sensor's capability to detect low concentrations of toxic substances by monitoring subtle changes in the SPR signal. The results provide a basis for developing a cost-effective and durable air quality indicator suitable for continuous environmental monitoring.

## Repository Contents
- **Bachelors_Diploma.pptx:** The presentation file detailing the project's theoretical background, sensor design, principal development, experimental setup, and key results.
- **SPR Sensor Optimization Paper:** Documentation of the adaptive Monte Carlo optimization process used to enhance sensor sensitivity.

## Acknowledgments
- **Author:** Ivanchenko A.M.  
- **Supervisor:** Batshev V.I.  
- **Institution:** Bauman Moscow State Technical University, Faculty of Radioelectronics and Laser Technology, Department RL2 "Laser and Optoelectronic Systems".  
- **Collaborators:** STC UI RAS (in collaboration with I.S. Khasanov).  
- **Year:** 2023
