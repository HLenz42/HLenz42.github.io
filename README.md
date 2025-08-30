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
  - [Spectra Stidies with the RAO Echelle Spectrograph](#echelle-spectrograph)
  - [Jupiter Size Measurement Laboratory](#observing-lab)
- [Successful Observiong Proposals](#observing-proposals)
- [Talks & Lectures](#talks-lectures)
- [Conferences](#conferences)
- [Awards & Grants](#awards-grants)
- [Volunteer Experiance](#volunteering)
- [Working at the Rothney Astrophysical Observatory](#rothney-observatory)



## Education {#education} 			        		
- B.S., Astrophysics & Physics | University of Calgary (_Expected May 2026_)
- Science Internship Program
- Participated in the Maunakea Observatories Study Abroad Program (May 2024

### Relavent Courcework
- Undergraduate Thesis Project, Galactic Astrophysics, Stellar Astrophysics, High Energy Astrophysics, Interstellar Medium, Hawai'i Maunakea Observatories, Quantum Mechanics 1/2, Electromagnetic Theory 1/2/3, Statistical Mechanics 1/2, Experimental Physics 1/2.

#### Technical Skills: Python, Latex, Mira, Source-Extractor, Scamp, SWarp, Maxim DL, Microsoft suit
#### Soft Skills: Critical thinking, Problem solving, Teamwork, Leadorship, Digital literacy, Public outreach
## Work Experience {#work-experience}
**Coordinator of Volunteers @ Rothney Astrophysical Observatory (_Aug 2024 - Present_)**
- In this position I coordinate 100+ student volunteers from the Physics and Astronomy department at the University of Calgary to help out with outreach events at the Rothney Astrophysical Observatory. As part of the job I have to organize individuals coming to an event, give them tasks, organize carpools, and train new volunteers in telescope operation and public speaking.

**Intern @ Rothney Astrophysical Observatory (_May 2024 - Aug 2025_)**
- I have operated the 1.8m A.R. Cross Telescope (ARCT), 0.5m Kaylie Green Memorial Telescope (KGMT), and 0.4m Clark-Milone Telescope (CMT) to observe exoplanets, eclipsing binaries, galaxies, nebulas, super nova reminants, and more!
- While operating telescpes I have found several bugs in there operation both softwere and mechanical related and have fixed the problems.
- During the summer of 2024 partispated in dissasembling the KGMT in order to gain access to the camera for repair.
- Developed Python-based data processing pipelines,to automate the reduction of photometric datasets and reduce analysis time [Variable Star Analysis Pipeline](#variable-star-pipeline).
- Gathered exoplanet transit data that verified published exoplanit transit parametsrs such as planet radiuse and impact parameter using the ARCT, KGMT, and CMT [Exoplanet Observations](#exoplanet-observations).
- Developed observing scheduals for the RAO telescopes to optimise observation time.
- Delivered public lectures on exoplanetary science, stellar evolution, galactic structure, globular clusters, galaxy interaction, and astrophotography to audiences of 150+ participants. I gave thes talks to audiances of all ages from grad 4 to high school to the general public.

## Research Experiance {#research-experience}
### Undergraduate Thesis Project - Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT {#globular-clusters-ngc}
<!--[Publication](https://www.mdpi.com/1424-8220/22/8/3048) -->

The spatial distribution of globular clusters (GCs) in galactic halos offers critical insights into the formation and evolution of their host galaxies. We combine new CFHT/WIRCam Ks-band imaging with archival CFHT/MegaCam optical data to identify GCs around the giant lenticular galaxy NGC 7332 and its spiral companion NGC 7339 using a uiKs colour-colour diagram. Given their close proximity to each other (35.2kpc assuming a shared distance of 20.5Mpc), we investigate the potential gravitational interaction by analyzing the spatial and colour distributions of their GC systems. The Ks-band data was obtained with CFHT/WIRCam as part of a proposal written for an inaugural undergraduate international learning experience provided by the University of Calgary in Spring 2024, led by Dr. Langill and Dr. Taylor. As part of this program, twelve students participated in writing proposals for CFHT and Gemini North, visited each observatory’s base facilities, and toured the telescopes at the summit of Maunakea. The uiKs diagram is a powerful tool to separate GCs from background galaxies and foreground stars by their magnitude variations across three filters. Early results have identified 90 GC candidates orbiting NGC 7332 and NGC 7339, providing key insights into their potential interaction and evolutionary histories.

[Final Report](/assets/img/Phys599_FinalReport_HLenz(2).pdf)

![NGC 7332 & NGC 7339 With Found Globular Clusters](/assets/img/NGC7332-7339withgc.png)
*Image of NGC 7332 and NGC 7339 with 139 newly identified globular clusters.*

![uiKs diagram used to idetifiy globular clusters](/assets/img/uiks_cc_diagram_w_labbles.png)
*uiKs coulour colour diagram used to identify globular clusters by usilizing near ultraviolet, optical, and near infaread photometry.*
<!--![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)-->

### Variable Star Analysis Pipeline {#variable-star-pipeline}
<!--[Publication](https://www.mdpi.com/1424-8220/22/11/4240)-->

As a major project during my internship at the Rothney Astrophysical Observatory (RAO), I developed a Python-based pipeline for detecting variable stars from raw astronomical images. The code automates the entire process: starting with input raw images, darks, biases, and flats, it performs bias, dark, and flat corrections. It then uploads the corrected images to astrometry.net to obtain World Coordinate System (WCS) information, followed by running Source Extractor for photometry to generate catalogs. A tracking script automatically follows stars across the image set, producing check plots for verification. The pipeline queries SIMBAD for star classifications, flagging known variables, and performs differential photometry by selecting a user-specified number of nearby non-variable comparison stars. It iteratively detects new variables from the initial photometry run, flags them, and reruns differential photometry to refine results, ensuring comparison stars are stable. Finally, it generates detailed plots and analysis logs highlighting potential new variable stars in the field. I adapted this pipeline to handle data from all RAO telescopes, including the CMT, ARCT, and KGMT.

This project significantly enhanced my programming skills in Python, image processing, and astronomical data analysis. At RAO, I applied it to real telescope data, improving efficiency in variable star detection for outreach and research. It also integrated techniques from my globular cluster research with the Canada France Hawaii Telescope, such as photometry using [Source Extractor]([https://www.mdpi.com/1424-8220/22/11/4240](https://www.astromatic.net/software/sextractor/)) and tracking, preparing me for graduate-level work in stellar variability and time-series analysis with large data sets in python.


<video controls width="100%" height="auto">
  <source src="/assets/img/var/star_timelapse_Wasp12b_star10017_differential_mag.mp4" type="video/mp4">
  Your browser does not support the video tag. [Download Video](/assets/img/var/star_timelapse_Wasp12b_star10017_differential_mag.mp4)
</video>
*Differential light curve for WASP-12b found by my code.*
<video controls width="100%" height="auto">
  <source src="/assets/img/var/star_timelapse_Wasp12b_star10058_differential_mag.mp4" type="video/mp4">
  Your browser does not support the video tag. [Download Video](/assets/img/var/star_timelapse_Wasp12b_star10058_differential_mag.mp4)
</video>
*Differential light curve for a non variable star found by my code.*

### SCIE 507: Hawai'i Maunakea Observatories 2024 {#maunakea-2024}

This was a inagral global learning class at the University of Calgary set up by two amazing proffesors Dr. Langill and Dr. Taylor. During this class we simulated what it is like to be a proffesional astrophysisit, we came up with a research idea, wrote proposals to both the Canada France Hawaii Telescope (CFHT) and Gemini North Telescope, and recived data back. Before we went on the trip we desided a good project for CFHT would be to observe NGC 7332 and NGC 7339 in the Ks band with WIRcam such that we could identify globular clusters, for Gemini we proposed to look at a globular cluster, M5, that has been reported to be rotating at an abnormaly fast rate, utilizing the GENRES instrument we wanted to confirm theese results. After submiting these proposals and getting time on both telescopes, 12 students and 2 proffessors went to the big island of Hawai'i. While at Hawai'i we toured the base facilities of both CFHT and Gemini and talked to the people working there who told us about the operation of the telecopes and the diffrent instruments used. We were lucky to be at both base facilites at night to see the telescopes in action and the variouse programs and procedurse used to control them. We were then even more luck to visit the telescopes at the sumit where we recived tours and talked to the Enginers currently working there, which was a truly incredible experiance. Unfortently Gemini was not able to collect data for us. When recived the data back from CFHT we started reducing it as a group, however we ran out of time in the semester. This is when I asked my supervisors to continue this work as my undergraduate thesis project, using new WIRcam Ks band CFHT data along with cataloge CFHT MegaCam data. 

### Exoplanet Observations {#exoplanet-observations} 
<!--[Publication](https://www.mdpi.com/1424-8220/22/11/4240)-->

This was one of the projects I worked on as a Intern at the Rothney Astrophysical Observatory. I was assisting a fellow student in collecting data for ∼40 Exoplanets with the Clark-Milone Telescope, A.R. Cross Telescope and the Plaskett Telescope.


### Stellar Evolution Laboratory {#stellar-evolution-lab}
<!--[Publication](https://www.mdpi.com/1424-8220/22/11/4240)-->

As part of my Astrophysics 403 term project at the University of Calgary, I collaborated with Andrea Luhar to model the evolution of a 1.1 solar mass star using MESA (Modules for Experiments in Stellar Astrophysics) software, tracing its lifecycle from pre-main sequence to white dwarf stages. We generated HR diagrams and analyzed luminosity changes, finding that the proton-proton (PP) chain dominated hydrogen burning, maintaining a stable ~1 L⊙ after 10^7 years, while the triple-alpha process triggered a helium flash peaking at ~10^7 L⊙ around 8.7 billion years for higher metallicity (Z=0.02). We also plotted stellar radius, core temperature, and elemental abundances (H, He, C), revealing sharp transitions in core composition and density during hydrogen and helium burning phases, with a notable “switchback” maneuver in the horizontal branch.

Re-simulating with low metallicity (Z=0.0001), we discovered a halved main sequence lifetime (4.3 billion years for helium flash) and a smoother HR diagram path without the switchback, with the second luminosity peak during helium burning 100 times brighter (10^7 L⊙) than the solar metallicity model. The low metallicity star exhibited more gradual density and temperature transitions between shells, with faster core hydrogen depletion and extended white dwarf cooling. These results deepened my expertise in stellar evolution modeling and data analysis, complementing my research with the Canada France Hawaii Telescope and internship at Rothney Astrophysical Observatory.

![Star evolution high metalisity](/assets/img/ASPH403/HRdiagram2(1).png)
*Our first MESA simulation of 1.1 M⊙ star with high metalisity.*

![Star evolution low metalisity](/assets/img/ASPH403/HRdiagram2.png)
*Star evolution of a 1.1 M⊙ star MESA simulation with lower metalisity showing a shorter time spent in the main sequence. This simulation showed a relatifly shorter time spent in the main sequence and the second luminosity peak during helim burning to be 100 times brighter.*

### WASP-12b Exoplanet Analysis {#wasp-12b-analysis}
<!--[Publication](https://www.mdpi.com/1424-8220/22/11/4240)-->

This was my final project in ASPH 307, Observational Astrophysis, at the university of Calgary. In this lab using data from the Rothney Astrophysical Observatory I was able to reduce the transit data and fine a result consitant with published values for the size, orbital speed, and mass of WASP-12b.


As part of my Astrophysics 307, Observational Astrophysis, group project at the University of Calgary, I worked in a group to study the exoplanet transit of WASP-12b across its host star WASP-12a. Using software tools like Mira and Tycho, we pre-processed astronomical images by subtracting darks and biases, dividing by flats, and performing photometry to measure instrumental magnitudes. We analyzed atmospheric extinction, determining coefficients around 0.6 for our target and reference stars, and generated light curves with up to 20 comparison stars to reveal a clear transit dip. From this, we calculated a magnitude difference of ~0.012 during transit, flux ratios indicating a ~1% brightness drop, and estimated the planet's radius at approximately 12 Earth radii which is consistant with published values. 

This project honed my skills in image processing, photometry, and light curve analysis, which I later applied during my internship at the Rothney Astrophysical Observatory (RAO), where I operated telescopes and coordinated outreach. It also laid the foundation for developing my variable star analysis detection pipeline, enhancing my proficiency in handling variable astronomical data and preparing me for advanced research in stellar and exoplanet studies.

### Spectra Stidies with the RAO Echelle Spectrograph {#echelle-spectrograph}

As part of my Astrophysics 307, Observational Astrophysis, group project at the University of Calgary, I worked in a group to analyze stellar spectra obtained from the Rothney Astrophysical Observatory's (RAO) Echelle Spectrograph using Visual Spec software. We measured Earth's orbital speed by examining Doppler shifts in the 34th and 35th orders of spectra from β Gem (sunset, K0 III) and α Ser (sunrise, K2 III), calculating an average velocity of approximately 23 km/s, which deviated slightly from the theoretical 29.78 km/s due to potential instrumental errors. The second part of the project involved qualitative analysis of spectral profiles for stars of decreasing temperatures (A1.5 IV at 9185 K, F5 IV at 6700 K, G9.5 III at 5480 K, M0.5 III at 3630 K), identifying elements like Ti, Zr, Cr, and Fe, and noting trends such as increasing noise, wider absorption lines, and more lines in cooler stars due to atmospheric density differences. Part C explored the spectrograph's mechanics, including trends in plate factors decreasing with higher orders for better resolution (up to ~10,000), enabling radial velocity measurements down to ~30 km/s, with a slit angular size of ~2.5" and effective focal length of ~4.125 m.

This project enhanced my expertise in spectral rectification, Gaussian fitting, and Doppler analysis, skills I directly applied during my internship at the RAO, where I operated telescopes and processed spectroscopic data for outreach and research. It also built foundational knowledge in handling wavelength shifts and absorption features, which informed the development of my variable star analysis detection pipeline by improving techniques for identifying variability in stellar spectra and light curves.






### Jupiter Size Measurement Laboratory {#observing-lab}
<!--[Publication](https://www.mdpi.com/1424-8220/22/11/4240)-->

As part of my Astrophysics 305 lab at the University of Calgary, I collaborated with fellow students to measure the physical size of Jupiter and its atmospheric bands using ground-based observations. On October 3, 2022, we used a Celestron 8-inch telescope with a Neximage 5 CCD camera on the University of Calgary campus, capturing AVI videos under clear skies. After processing images in Registax 6.1 (stacking 55% of frames, applying wavelet transforms, and RGB balancing), we analyzed them in SAOImage to determine pixel sizes, calculating Jupiter's angular diameter (43.9") and physical diameter (1.26 × 10^8 m, close to the actual 1.43 × 10^8 m). We also measured the upper band's size (9.22 × 10^6 m), lower band's size (9.88 × 10^6 m), and distance between bands (3.18 × 10^7 m), with errors (1.09 × 10^6 m) derived from Gaussian FWHM analysis, noting discrepancies possibly due to atmospheric seeing or instrumental factors. 

This lab sharpened my skills in telescope operation, image processing with Registax and SAOImage, and trigonometric calculations for angular measurements, which I directly applied during my internship at the Rothney Astrophysical Observatory (RAO), where I handled similar CCD imaging and data reduction for planetary and stellar observations. It also provided foundational experience in analyzing variable features like planetary bands, influencing the development of my variable star analysis detection pipeline by improving techniques for frame stacking, noise reduction, and precise photometric measurements in dynamic astronomical datasets.





<!--![Bike Study](/assets/img/bike_study.jpeg)-->
## Successful Observing Proposals {#observing-proposals}
- Co-I, Gemini North Observatory, 2.83 hours (2024)
  - **Project:** "Seeing Stars! Measuring the dizzying spin of the Galactic globular cluster M5"
  - **Goal:** To use the Gemini Near-InfraRead Spectrograph (GNIRS) to measure the rotational velocity of the globular cluster M5. This globular cluster was important to observe as a previouse paper reported it to have an abnoraly high spin rate, therfore by observing M5 with GNIRS we could confirm this measurment.
- Co-I, Canada-France-Hawaii Telescope, 3 hours (2024)
  - **Project:** “Searching for Globular Clusters in NGC 7332 & NGC 7339”
  - **Goal:** To observe the galaxies NGC 7332 and NGC 7339 using WIRcam. With this new Ks band data and catalogue u and i band data from the Megacam instrument we could use the uiKs colour coluor plot method to identify globular clusters around NGC 7332 and NGC 7339. This was important because these galaxise are 35.2kpc apart from eachother therefore should be in the early stages of galactic interaction, therfore based on the distribution of the globular cluster we can determine if this is so. 
 
## Talks & Lectures {#talks-lectures}
- **Guest Speaker:** Update on the Rothney Astrophysical Observatory  - Physics and Astrophysics Student Assosiation Reasearch Night, Nov 2024
- **Guest Lecture:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - Rothney Astrophysical Observatory Space Night, May 2025
- **Speaker:** Globular Cluster Science - Rothney Astrophysical Observatory School Groups, 2024-2025
- **Poster:**  Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - CFHT UM, June 2025
- **Poster Flash Talk:**  Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - CASCA, June 2025
- **Guest Speaker:** Searching For Globular Clusters in NGC 7332 and NGC 7339 using CFHT - Canadian Conference for Undergraduate Women and Gender Minorities in Physics (CCUW*iP), Febuary 2025

<!--- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)-->

## Confrences {#conferences}
- **CASCA 2025** - Presended a poster on my undergraduate thesis project, I also had the opportunity to do a poster flash talk. <a href="/assets/img/HLenz-CASCAPoster.pdf" type="application/pdf" target="_blank">View my poster</a>
- **CFHT Users Meeting 2025** - Presended a poster on my undergraduate thesis project <a href="/assets/img/HLenz-CASCAPoster.pdf" type="application/pdf" target="_blank">View my poster</a>
- **CASTOR Small Teams Meeting 2025** - I was allowed to sit in on this meeting as I have been very intrested in the CASTOR porject.
- **Graduate Student Wrokshop CASCA 2025** - 
- **Canadian Conference for Undergraduate Women and Gender Minorities in Physics (CCUW*iP) 2025** - I presented a power point on my undergraduate thesis project.

## Awards & Grants {#awards-grants}
- **Kaylie Green Memorial Fund Scholarship**, Green Family (2024-2025)
- **Alaxander Rutherford High School Achievement Scholarship**, Government of Alberta (2021)

## Volunteer Experiance {#volunteering}
- Team Astro Member | University of Calgary | (_Mar 2024 - Present_)
  - As a member of Team Astro I volunteer once a month at the Rothney Astrophysical Observatory where I have operated the A.R. Cross Telescope (ARCT), Kaylie Green Memorial Telescope (KGMT), and Clark-Milone Telescope (CMT) while informing the public about the objects we are observing, the instrumentation of the telescopes, and history of the observatory. I have helped guide goups of the public up to 400 people tour around the observatory. I am also one of two voulunter coordinators for Team Astro [Work Experience](#work-experience).
- Open House | University of Calgary | (_Oct 2024_)
  - During this even I was one of the volunteers at the Fabulty of Science booth during the Univerity of calgary open house. I taked to numorus future university students and informed them about our programs. 
  
## Working at the Rothney Astrophysical Observatory {#rothney-observatory}
![Instructing a group of students](/assets/img/grade9_activity.jpg)
*A example of one of our activities done with the school groups that come to the RAO. This is our Grade 9 parralax activity where we have two levels and get students to measure a distant object.*

<!---## Publications
1. Talebi S., Lary D.J., Wijeratne L. OH., and Lary, T. Modeling Autonomic Pupillary Responses from External Stimuli Using Machine Learning (2019). DOI: 10.26717/BJSTR.2019.20.003446
2. Wijeratne, L.O.; Kiv, D.R.; Aker, A.R.; Talebi, S.; Lary, D.J. Using Machine Learning for the Calibration of Airborne Particulate Sensors. Sensors 2020, 20, 99.
3. Lary, D.J.; Schaefer, D.; Waczak, J.; Aker, A.; Barbosa, A.; Wijeratne, L.O.H.; Talebi, S.; Fernando, B.; Sadler, J.; Lary, T.; Lary, M.D. Autonomous Learning of New Environments with a Robotic Team Employing Hyper-Spectral Remote Sensing, Comprehensive In-Situ Sensing and Machine Learning. Sensors 2021, 21, 2240. https://doi.org/10.3390/s21062240
4. Zhang, Y.; Wijeratne, L.O.H.; Talebi, S.; Lary, D.J. Machine Learning for Light Sensor Calibration. Sensors 2021, 21, 6259. https://doi.org/10.3390/s21186259
5. Talebi, S.; Waczak, J.; Fernando, B.; Sridhar, A.; Lary, D.J. Data-Driven EEG Band Discovery with Decision Trees. Preprints 2022, 2022030145 (doi: 10.20944/preprints202203.0145.v1).
6. Fernando, B.A.; Sridhar, A.; Talebi, S.; Waczak, J.; Lary, D.J. Unsupervised Blink Detection Using Eye Aspect Ratio Values. Preprints 2022, 2022030200 (doi: 10.20944/preprints202203.0200.v1).
7. Talebi, S. et al. Decoding Physical and Cognitive Impacts of PM Concentrations at Ultra-fine Scales, 29 March 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-1499191/v1]
8. Lary, D.J. et al. (2022). Machine Learning, Big Data, and Spatial Tools: A Combination to Reveal Complex Facts That Impact Environmental Health. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_12
9. Wijerante, L.O.H. et al. (2022). Advancement in Airborne Particulate Estimation Using Machine Learning. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_13-->

<!-- - [Data Science Blog](https://medium.com/@shawhin)-->
