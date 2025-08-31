# Astrophysics Undergraduate Student

## Table of Contents
- [Education](#education)
- [Work Experience](#work-experience)
- [Research Experience](#research-experience)
  - [Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT](#globular-clusters-ngc)
  - [Variable Star Analysis Pipeline](#variable-star-pipeline)
  - [SCIE 507: Hawai'i Maunakea Observatories 2024](#maunakea-2024)
  - [Exoplanet Observations](#exoplanet-observations)
  - [Stellar Evolution Laboratory](#stellar-evolution-lab)
  - [WASP-12b Exoplanet Analysis](#wasp-12b-analysis)
  - [Spectra Studies with the RAO Echelle Spectrograph](#echelle-spectrograph)
  - [Jupiter Size Measurement Laboratory](#jupiter-size-lab)
- [Successful Observing Proposals](#observing-proposals)
- [Talks & Lectures](#talks-lectures)
- [Conferences](#conferences)
- [Awards & Grants](#awards-grants)
- [Volunteer Experience](#volunteering)
- [Astrophotography at the Rothney Astrophysical Observatory](#rothney-observatory-photography)

## Education {#education} 			        		
- **B.S., Astrophysics & Physics** | University of Calgary (_Expected May 2026_)
- Science Internship Program
- Participated in the inaugural Maunakea Observatories Study Abroad Program (May 2024)

### Relevant Coursework
- Undergraduate Thesis Project, Galactic Astrophysics, Stellar Astrophysics, High Energy Astrophysics, Interstellar Medium, Hawai'i Maunakea Observatories, Quantum Mechanics 1/2, Electromagnetic Theory 1/2/3, Statistical Mechanics 1/2, Experimental Physics 1/2.

#### Technical Skills: Python, LaTeX, Mira, Source Extractor, Scamp, SWarp, Maxim DL, telescope operation, image processing, Microsoft Suite
#### Soft Skills: Critical Thinking, Problem Solving, Teamwork, Leadership, Digital Literacy, Public Outreach

## Work Experience {#work-experience}
**Coordinator of Volunteers, Rothney Astrophysical Observatory** (_Aug 2024 - Present_)
- In this position, I coordinate 100+ student volunteers from the Physics and Astronomy Department at the University of Calgary to assist with outreach events at the Rothney Astrophysical Observatory. As part of the job, I organize individuals attending an event, assign tasks, coordinate carpools, and train new volunteers in telescope operation and public speaking.

**Intern, Rothney Astrophysical Observatory** (_May 2024 - Aug 2025_)
- Operated the 1.8m A.R. Cross Telescope (ARCT), 0.5m Kaylie Green Memorial Telescope (KGMT), and 0.4m Clark-Milone Telescope (CMT) to observe exoplanets, eclipsing binaries, galaxies, nebulae, supernova remnants, and more.
- Identified and resolved several software and mechanical issues in telescope operation.
- Participated in disassembling the KGMT in summer 2024 to access the camera for repair.
- Developed Python-based data processing pipelines to automate the reduction of photometric datasets, reducing analysis time [Variable Star Analysis Pipeline](#variable-star-pipeline).
- Gathered exoplanet transit data that verified published exoplanet transit parameters, such as planet radius and impact parameter, using the ARCT, KGMT, and CMT [Exoplanet Observations](#exoplanet-observations).
- Developed observing schedules for RAO telescopes to optimize observation time.
- Delivered public lectures on exoplanetary science, stellar evolution, galactic structure, globular clusters, galaxy interaction, and astrophotography to audiences of 150+ participants, ranging from grade 4 students to high schoolers and the general public.

## Research Experience {#research-experience}
### Undergraduate Thesis Project - Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT {#globular-clusters-ngc}

**Supervisors:** Dr. Matthew Taylor and Dr. Phil Langill

**Abstract:**
The spatial distribution of globular clusters (GCs) in galactic halos offers critical insights into the formation and evolution of their host galaxies. We combine new CFHT/WIRCam Ks-band imaging with archival CFHT/MegaCam optical data to identify GCs around the giant lenticular galaxy NGC 7332 and its spiral companion NGC 7339 using a uiKs colour-colour diagram. Given their close proximity to each other (35.2 kpc, assuming a shared distance of 20.5 Mpc), we investigate potential gravitational interaction by analyzing the spatial and colour distributions of their GC systems. The Ks-band data were obtained with CFHT/WIRCam as part of a proposal written for an inaugural undergraduate international learning experience provided by the University of Calgary in Spring 2024, led by Dr. Langill and Dr. Taylor. As part of this program, twelve students participated in writing proposals for CFHT and Gemini North, visited each observatory’s base facilities, and toured the telescopes at the summit of Maunakea. The uiKs diagram is a powerful tool to separate GCs from background galaxies and foreground stars by their magnitude variations across three filters. Early results identified 90 GC candidates orbiting NGC 7332 and NGC 7339, providing key insights into their potential interaction and evolutionary histories.

View my [Final Physics 599 Report](/assets/img/Phys599_FinalReport_HLenz(2).pdf). Note that after completing this class in the Fall 2024 semester, I continued work on the project during my internship and eventually improved my analysis of the data to find more concrete results, as presented in <a href="/assets/img/HLenz-CASCAPoster.pdf" type="application/pdf" target="_blank">my poster</a> presented at CASCA 2025 and the CFHT Users Meeting 2025.

![NGC 7332 & NGC 7339 With Found Globular Clusters](/assets/img/NGC7332-7339withgc.png)
*Image of NGC 7332 (right) and NGC 7339 (left) with 139 newly identified globular clusters.*

**This project had three goals:**
1. Identify globular clusters (GCs) based on their magnitude in u, i, and Ks filters using a uiKs colour-colour diagram. With new Ks-band data, this method of GC detection is now possible.
2. Determine host galaxy interactions; the spatial distribution of GCs can indicate whether these two galaxies are in the early stages of galactic interaction.
3. Study galactic history from the bimodal blue-red colour distribution of GCs.

These galaxies were chosen because they are edge-on, in close proximity (35.2 kpc) to each other, and had catalogue data in the u and i filters observed by MegaCam/CFHT but no Ks data. A proposal was written to CFHT for WIRCam to observe these galaxies in the Ks-band as part of an inaugural undergraduate international learning experience led by Dr. Langill and Dr. Taylor in May 2024.

![uiKs diagram used to identify globular clusters](/assets/img/uiks_cc_diagram_w_labbles.png)
*The uiKs colour-colour diagram characterizing objects using magnitude measurements of sources around NGC 7332 and NGC 7339 in near-ultraviolet (u), optical (i), and near-infrared (Ks). Using the normalized colours (u−i)_0 and (i−Ks)_0, GCs can be separated, a method first used in 2014 by Dr. Muñoz.*

The globular clusters were selected from the central region of the uiKs diagram, as seen in the figure above. Candidates were then filtered using photometric measurements made by Source Extractor, such as magnitude, flux radius, and ellipticity. Image cutouts of the globular clusters were made to confirm GC-like appearance and proximity to their host galaxy (within 5 effective radii) for them to be considered gravitationally bound.

![distribution study of globular clusters](/assets/img/distributions_and_ptest.png)
*The observed distribution of globular clusters versus a random distribution of globular clusters around NGC 7332 and NGC 7339, compared using the Kolmogorov-Smirnov test to show a p-value of 1.7 × 10^-4.*

To test whether the observed globular cluster distribution results from the overlap of two globular cluster systems or gravitational interaction, random globular cluster distributions were generated based on observed distances of globular clusters. The figure above shows that the randomly generated distribution produced a relatively even globular cluster density, while the observed data shows a central concentration. A Kolmogorov-Smirnov test confirms a statistically significant (p=1.7 × 10^-4) difference between the distributions, supporting the case for non-random structure and possible interaction.

![uiKs diagram used to identify globular clusters](/assets/img/histogram.png)
*u-Ks histogram reveals a blue-red globular cluster bimodality with more red globular clusters, suggesting these galaxies formed through mergers with fewer larger galaxies rather than many smaller galaxies. Note that after studying the distribution of red and blue globular clusters, no meaningful pattern was found, with either globular cluster type mainly being around either galaxy; it was an even distribution.*

**Conclusions for my three goals:**
1. Using a uiKs colour-colour diagram, I identified 139 GC candidates surrounding NGC 7332 and NGC 7339. This method combines near-UV (u), optical (i), and near-infrared (Ks) photometry to effectively isolate globular clusters in colour space. Although the candidates match expected photometric and structural properties of globular clusters, spectroscopic confirmation is needed to verify their identities and association with their host galaxies.
2. A Kolmogorov-Smirnov (KS) test compared the cumulative radial distributions of observed and randomly generated globular cluster positions. The resulting p-value (p=1.7 × 10^-4) indicates a statistically significant difference, rejecting the null hypothesis that the observed distribution is random. This supports the presence of a non-random spatial structure, consistent with gravitational interaction between NGC 7332 and NGC 7339.
3. The u-Ks colour histogram of the identified globular clusters shows a larger population of red globular clusters, indicating that these two galaxies were formed through mergers with fewer larger galaxies rather than many smaller galaxies.

### Variable Star Analysis Pipeline {#variable-star-pipeline}

As a major project during my internship at the Rothney Astrophysical Observatory (RAO), I developed a **Python-based pipeline** for detecting variable stars from raw astronomical images. The code automates the entire process: starting with input raw images, darks, biases, and flats, it performs bias, dark, and flat corrections. It then uploads the corrected images to **astrometry.net** to obtain World Coordinate System (WCS) information, followed by running **Source Extractor** for photometry to generate catalogs. A tracking script automatically follows stars across the image set, producing check plots for verification. The pipeline queries **SIMBAD** for star classifications, flagging known variables, and performs differential photometry by selecting a user-specified number of nearby non-variable comparison stars. It iteratively detects new variables from the initial photometry run, flags them, and reruns differential photometry to refine results, ensuring comparison stars are stable. Finally, it generates detailed plots and analysis logs highlighting potential new variable stars in the field. I adapted this pipeline to handle data from all RAO telescopes, including the CMT, ARCT, and KGMT.

This project significantly enhanced my programming skills in **Python**, image processing, and astronomical data analysis. At RAO, I applied it to real telescope data, improving efficiency in variable star detection for outreach and research. It also integrated techniques from my globular cluster research with the **Canada France Hawaii Telescope**, such as photometry using Source Extractor and tracking, preparing me for graduate-level work in stellar variability and time-series analysis with large datasets in Python.

The videos embedded below show a timelapse of two stars as analyzed by my script. The first video shows the exoplanet light curve for **WASP-12b**, an exoplanet transit observed many times at the RAO with the KGMT; the second video shows the timelapse for one of the comparison stars used in the differential photometry of WASP-12b.

<video controls width="100%" height="auto">
  <source src="/assets/img/var/star_timelapse_Wasp12b_star10017_differential_mag.mp4" type="video/mp4">
  Your browser does not support the video tag. [Download Video](/assets/img/var/star_timelapse_Wasp12b_star10017_differential_mag.mp4)
</video>
*Differential light curve timelapse for the exoplanet WASP-12b found by my code.*

<video controls width="100%" height="auto">
  <source src="/assets/img/var/star_timelapse_Wasp12b_star10058_differential_mag.mp4" type="video/mp4">
  Your browser does not support the video tag. [Download Video](/assets/img/var/star_timelapse_Wasp12b_star10058_differential_mag.mp4)
</video>
*Differential light curve timelapse for a non-variable star found by my code.*

After further data cleaning and detrending, I created the following as my final processed light curve for WASP-12b.

![final processed light curve for WASP-12b](/assets/img/wasp_light_curve.png)
*The final processed light curve for WASP-12b as generated by my variable star analysis code.*

### SCIE 507: Hawai'i Maunakea Observatories 2024 {#maunakea-2024}

This was an inaugural global learning class at the University of Calgary, led by two exceptional professors, Dr. Langill and Dr. Taylor. During this class, we simulated the work of a professional astrophysicist by developing a research idea, writing proposals for both the **Canada France Hawaii Telescope (CFHT)** and **Gemini North Telescope**, and receiving data back. Before the trip, we decided a suitable project for CFHT would be to observe NGC 7332 and NGC 7339 in the Ks band with WIRCam to identify globular clusters; for Gemini, we proposed to study the globular cluster M5, reported to have an abnormally high rotation rate, using the GNIRS instrument to confirm these results. After submitting these proposals and securing time on both telescopes, 12 students and two professors traveled to the Big Island of Hawai'i. While there, we toured the base facilities of both CFHT and Gemini, engaging with staff about telescope operations and instrument functionalities. We were fortunate to observe the telescopes in action at night and visit the summit of Maunakea, where we received tours and spoke with engineers, an unforgettable experience. Unfortunately, Gemini was unable to collect data for us. Upon receiving the CFHT data, we began reducing it as a group, but ran out of time in the semester. I then requested to continue this work as my undergraduate thesis project, using new WIRCam Ks-band CFHT data alongside catalogued CFHT MegaCam data.

![Me at the Gemini North Telescope](/assets/img/atGEMINI.jpg)
*Getting a tour of the Gemini North Telescope at the summit of Maunakea.*

### Exoplanet Observations {#exoplanet-observations}

During my internship at the Rothney Astrophysical Observatory (RAO), I collaborated with another intern to observe over 50 exoplanet transits, often coordinating multiple telescopes, including the **CMT**, **ARCT**, **KGMT**, and Plaskett, to simultaneously target the same transit event in different filters. This multi-telescope approach allowed us to capture high-quality light curves by pointing all instruments at a single exoplanet target, mitigating issues such as weather or instrumental variability while maximizing signal-to-noise ratios. I personally collected exoplanet data using the CMT, ARCT, and KGMT telescopes, focusing on transit photometry to measure planetary parameters such as radius, orbital period, and impact parameter.

These observations built on my prior coursework in Astrophysics 307, where I analyzed WASP-12b transits, refining my skills in telescope coordination, real-time data acquisition, and multi-instrument synchronization. At RAO, this experience directly informed my work on outreach programs and contributed to the adaptation of my **variable star analysis detection pipeline**, incorporating transit detection algorithms for identifying periodic variability in exoplanet host stars and improving automated photometry for time-series datasets.

![cmt webcams](/assets/img/cmt_webcam.png)
*Screenshot of the webcams for the Clark-Milone Telescope at the Rothney Astrophysical Observatory in operation collecting exoplanet data.*

![example of an exoplanet target found using Swarthmore](/assets/img/swarthmore_target.png)
*Screenshot of an example exoplanet target found using Swarthmore, then observed with the ARCT and CMT.*

### Stellar Evolution Laboratory {#stellar-evolution-lab}

As part of my Astrophysics 403 term project at the University of Calgary, I collaborated with Andrea Luhar to model the evolution of a 1.1 solar mass star using **MESA (Modules for Experiments in Stellar Astrophysics)** software, tracing its lifecycle from pre-main sequence to white dwarf stages. We generated HR diagrams and analyzed luminosity changes, finding that the proton-proton (PP) chain dominated hydrogen burning, maintaining a stable ~1 L⊙ after 10^7 years, while the triple-alpha process triggered a helium flash peaking at ~10^7 L⊙ around 8.7 billion years for higher metallicity (Z=0.02). We also plotted stellar radius, core temperature, and elemental abundances (H, He, C), revealing sharp transitions in core composition and density during hydrogen and helium burning phases, with a notable “switchback” maneuver in the horizontal branch.

Re-simulating with low metallicity (Z=0.0001), we discovered a halved main sequence lifetime (4.3 billion years for helium flash) and a smoother HR diagram path without the switchback, with the second luminosity peak during helium burning 100 times brighter (10^7 L⊙) than the solar metallicity model. The low metallicity star exhibited more gradual density and temperature transitions between shells, with faster core hydrogen depletion and extended white dwarf cooling. These results deepened my expertise in stellar evolution modeling and data analysis, complementing my research with the Canada France Hawaii Telescope and internship at Rothney Astrophysical Observatory.

![Star evolution high metallicity](/assets/img/ASPH403/HRdiagram2(1).png)
*Our first MESA simulation of a 1.1 M⊙ star with high metallicity.*

![Star evolution low metallicity](/assets/img/ASPH403/HRdiagram2.png)
*Star evolution of a 1.1 M⊙ star MESA simulation with lower metallicity, showing a relatively shorter time spent in the main sequence and the second luminosity peak during helium burning to be 100 times brighter.*

### WASP-12b Exoplanet Analysis {#wasp-12b-analysis}

This was my final project in Astrophysics 307, Observational Astrophysics, at the University of Calgary. Using data from the Rothney Astrophysical Observatory, I reduced transit data and obtained results consistent with published values for the size, orbital period, and mass of **WASP-12b**.

As part of my Astrophysics 307 group project at the University of Calgary, I collaborated with peers to study the exoplanet transit of **WASP-12b** across its host star **WASP-12a**. Using software tools like **Mira** and **Tycho**, we pre-processed astronomical images by subtracting darks and biases, dividing by flats, and performing photometry to measure instrumental magnitudes. We analyzed atmospheric extinction, determining coefficients around 0.6 for our target and reference stars, and generated light curves with up to 20 comparison stars to reveal a clear transit dip. From this, we calculated a magnitude difference of ~0.012 during transit, flux ratios indicating a ~1% brightness drop, and estimated the planet's radius at approximately 12 Earth radii, consistent with published values.

This project honed my skills in image processing, photometry, and light curve analysis, which I later applied during my internship at the Rothney Astrophysical Observatory (RAO), where I operated telescopes and coordinated outreach. It also laid the foundation for developing my variable star analysis detection pipeline, enhancing my proficiency in handling variable astronomical data and preparing me for advanced research in stellar and exoplanet studies.

### Spectra Studies with the RAO Echelle Spectrograph {#echelle-spectrograph}

As part of my Astrophysics 307, Observational Astrophysics, group project at the University of Calgary, I collaborated with peers to analyze stellar spectra obtained from the Rothney Astrophysical Observatory's (RAO) **Echelle Spectrograph** using **Visual Spec** software. We measured Earth's orbital speed by examining Doppler shifts in the 34th and 35th orders of spectra from **β Gem** (sunset, K0 III) and **α Ser** (sunrise, K2 III), calculating an average velocity of approximately 23 km/s, which deviated slightly from the theoretical 29.78 km/s due to potential instrumental errors. The second part of the project involved qualitative analysis of spectral profiles for stars of decreasing temperatures (A1.5 IV at 9185 K, F5 IV at 6700 K, G9.5 III at 5480 K, M0.5 III at 3630 K), identifying elements like Ti, Zr, Cr, and Fe, and noting trends such as increasing noise, wider absorption lines, and more lines in cooler stars due to atmospheric density differences. Part C explored the spectrograph's mechanics, including trends in plate factors decreasing with higher orders for better resolution (up to ~10,000), enabling radial velocity measurements down to ~30 km/s, with a slit angular size of ~2.5" and effective focal length of ~4.125 m.

This project enhanced my expertise in spectral rectification, Gaussian fitting, and Doppler analysis, skills I directly applied during my internship at the RAO, where I operated telescopes and processed spectroscopic data for outreach and research. It also built foundational knowledge in handling wavelength shifts and absorption features, which informed the development of my variable star analysis detection pipeline by improving techniques for identifying variability in stellar spectra and light curves.

![comparison of two spectra](/assets/img/comparison_spectra.png)
*Comparison of rectified spectral profiles of 34-β Gem (top) and 34-α Ser (bottom).*

### Jupiter Size Measurement Laboratory {#jupiter-size-lab}

As part of my Astrophysics 305 lab at the University of Calgary, I collaborated with fellow students to measure the physical size of **Jupiter** and its atmospheric bands using ground-based observations. On October 3, 2022, we used a **Celestron 8-inch telescope** with a **Neximage 5 CCD camera** on the University of Calgary campus, capturing AVI videos under clear skies. After processing images in **Registax 6.1** (stacking 55% of frames, applying wavelet transforms, and RGB balancing), we analyzed them in **SAOImage** to determine pixel sizes, calculating Jupiter's angular diameter (43.9") and physical diameter (1.26 × 10^8 m, close to the actual 1.43 × 10^8 m). We also measured the upper band's size (9.22 × 10^6 m), lower band's size (9.88 × 10^6 m), and distance between bands (3.18 × 10^7 m), with errors (1.09 × 10^6 m) derived from Gaussian FWHM analysis, noting discrepancies possibly due to atmospheric seeing or instrumental factors.

This lab sharpened my skills in telescope operation, image processing with Registax and SAOImage, and trigonometric calculations for angular measurements, which I directly applied during my internship at the Rothney Astrophysical Observatory (RAO), where I handled similar CCD imaging and data reduction for planetary and stellar observations. It also provided foundational experience in analyzing variable features like planetary bands, influencing the development of my variable star analysis detection pipeline by improving techniques for frame stacking, noise reduction, and precise photometric measurements in dynamic astronomical datasets.

![jupiter zoom in](/assets/img/jupiter_zoom_in.png)
*Zoom-in of Jupiter to measure its diameter.*

## Successful Observing Proposals {#observing-proposals}
- **Co-Investigator, Gemini North Observatory**, 2.83 hours (2024)
  - **Project:** "Seeing Stars! Measuring the Dizzying Spin of the Galactic Globular Cluster M5"
  - **Goal:** To use the Gemini Near-Infrared Spectrograph (GNIRS) to measure the rotational velocity of the globular cluster M5. This globular cluster was important to observe as a previous paper reported it to have an abnormally high spin rate; therefore, by observing M5 with GNIRS, we could confirm this measurement.
- **Co-Investigator, Canada-France-Hawaii Telescope**, 3 hours (2024)
  - **Project:** “Searching for Globular Clusters in NGC 7332 & NGC 7339”
  - **Goal:** To observe the galaxies NGC 7332 and NGC 7339 using WIRCam. With this new Ks-band data and catalogue u- and i-band data from the MegaCam instrument, we could use the uiKs colour-colour plot method to identify globular clusters around NGC 7332 and NGC 7339. This was important because these galaxies are 35.2 kpc apart from each other, suggesting they may be in the early stages of galactic interaction; therefore, based on the distribution of the globular clusters, we could determine if this is so.

## Talks & Lectures {#talks-lectures}
- **Guest Speaker:** Update on the Rothney Astrophysical Observatory - Physics and Astrophysics Student Association Research Night, Nov 2024
- **Guest Lecture:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - Rothney Astrophysical Observatory Space Night, May 2025
- **Speaker:** Globular Cluster Science - Rothney Astrophysical Observatory School Groups, 2024-2025
- **Poster:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - CFHT Users Meeting, June 2025
- **Poster Flash Talk:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - CASCA, June 2025
- **Guest Speaker:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - Canadian Conference for Undergraduate Women and Gender Minorities in Physics (CCUW*iP), February 2025

## Conferences {#conferences}
- **CASCA 2025** - Presented a poster on my undergraduate thesis project; I also had the opportunity to give a poster flash talk. <a href="/assets/img/HLenz-CASCAPoster.pdf" type="application/pdf" target="_blank">View my poster</a>
- **CFHT Users Meeting 2025** - Presented a poster on my undergraduate thesis project. <a href="/assets/img/HLenz-CASCAPoster.pdf" type="application/pdf" target="_blank">View my poster</a>
- **CASTOR Small Teams Meeting 2025** - I was allowed to sit in on this meeting as I am very interested in the CASTOR project.
- **Graduate Student Workshop, CASCA 2025** - This meeting was held just before CASCA 2025, where graduate students from across the country collaborated and shared various helpful insights.
- **Canadian Conference for Undergraduate Women and Gender Minorities in Physics (CCUW*iP) 2025** - I presented a PowerPoint on my undergraduate thesis project.

![Me at CASCA 2025 presenting my poster](/assets/img/atCASCA.jpg)
*Me at CASCA 2025 presenting my poster.*

![Me giving a talk at Space Night](/assets/img/atspacenight.jpg)
*Me giving a talk at Space Night.*

## Awards & Grants {#awards-grants}
- **Kaylie Green Memorial Fund Scholarship**, Green Family (2024-2025)
- **Alexander Rutherford High School Achievement Scholarship**, Government of Alberta (2021)

## Volunteer Experience {#volunteering}
- **Team Astro Member**, University of Calgary (_Mar 2024 - Present_)
  - As a member of Team Astro, I volunteer once a month at the Rothney Astrophysical Observatory, where I have operated the **A.R. Cross Telescope (ARCT)**, **Kaylie Green Memorial Telescope (KGMT)**, and **Clark-Milone Telescope (CMT)** while informing the public about the objects we observe, the instrumentation of the telescopes, and the history of the observatory. I have helped guide groups of up to 400 people on tours around the observatory. I am also one of two volunteer coordinators for Team Astro [Work Experience](#work-experience).
- **Open House**, University of Calgary (_Oct 2024_)
  - During this event, I was one of the volunteers at the Faculty of Science booth during the University of Calgary Open House. I spoke with numerous prospective university students and informed them about our programs.
- **Earth Sciences Fair**, University of Calgary (_Mar 2025_)
  - During this event, I was one of the volunteers at the Rothney Astrophysical Observatory booth during the University of Calgary Earth Sciences Fair.
- **Observing Night**, Maunakea Observatories (_May 2024_)
  - During this event, I volunteered at an observing night organized by the Maunakea Observatories, assisting with public engagement and telescope operations.

## Astrophotography at the Rothney Astrophysical Observatory {#rothney-observatory-photography}
Below are some of my best astrophotography images created from data I collected with the Kaylie Green Memorial Telescope (KGMT) and Clark-Milone Telescope (CMT).

![Bubble Nebula - CMT](/assets/img/astro/Bubble_Stacked_GraXpert.png)
*NGC 7635 - Bubble Nebula - CMT*

![Flame Nebula - CMT](/assets/img/astro/Flame_stretched_GraXpert_stack_V1.png)
*NGC 2024 - Flame Nebula - CMT*

![Whirlpool Galaxy - CMT](/assets/img/astro/M51_stack_V1.png)
*M51 - Whirlpool Galaxy - CMT*

![Horsehead Nebula - CMT](/assets/img/astro/Horsehead_GraXpert_V1.png)
*IC 434 - Horsehead Nebula - CMT*

![Horsehead Nebula and Flame Nebula - KGMT](/assets/img/astro/IC434_V1.png)
*IC 434 - Horsehead Nebula and Flame Nebula - KGMT*

![Orion Nebula - KGMT](/assets/img/astro/M42_V1.png)
*M42 - Orion Nebula - KGMT*

![Orion Nebula - CMT](/assets/img/astro/M42_stretched_GraXpert_stacked.png)
*M42 - Orion Nebula - CMT*

![Pinwheel Galaxy - CMT](/assets/img/astro/M101_GraXpert_Stack_V1.png)
*M101 - Pinwheel Galaxy - CMT*

![Andromeda Galaxy - KGMT](/assets/img/astro/M31_V1.png)
*M31 - Andromeda Galaxy - KGMT*

![Triangulum Galaxy - KGMT](/assets/img/astro/M33-V3.png)
*M33 - Triangulum Galaxy - KGMT*

![Triangulum Galaxy - CMT](/assets/img/astro/M33_60s_stack_V1.png)
*M33 - Triangulum Galaxy - CMT*

![California Nebula - CMT](/assets/img/astro/NGC1499_120s_stack_V1.png)
*NGC 1499 - California Nebula - CMT*
