# Bachelor's Thesis: Design of an Implantable Antenna for Microwave Hyperthermia (Part II)

Welcome to the GitHub repository for the second part of the Bachelor's Thesis. This project focuses on the design of an implantable antenna for microwave hyperthermia. 

This repository contains the second phase of the project, discussing the methodology and analysis undertaken. The initial steps involved verifying the thermal analysis conducted in the previous phase, followed by the design of a prototype antenna for variable frequency heating. Due to encountered limitations, a transition was made to a miniaturized antenna design.

## Methodology

The adopted methodology was a sequential process, starting with the prototype antenna design, followed by the miniaturized antenna design and measurement setup. The subsequent steps involved phantom development and culminated in thermal measurements.

The critical aspect of this methodology was the identification of the optimal operating frequency for the antenna, resulting in ideal SAR distribution - a process also known as heating optimization.

## Prototype Antenna Design

A circular slot antenna served as the prototype design. The design aimed to function at varying frequencies, enabled by changing the size of the slot - the diameter of the inner circle and the width of the slot. Limitations were encountered when testing various frequencies in this setup.

## Miniaturized Antenna Design

The limitations from the prototype antenna prompted a transition to a more intricate miniaturized antenna design. Despite its complexity, this antenna offered the flexibility needed for testing across different frequencies.

## Measurement Setup

The measurement setup phase involved consideration of measurements post-antenna production. The material switched from human bone cortical to human fat for easier phantom production. The antenna was then redesigned in the simulation program to fit into the measurement cup, and a feeding structure was added.

## Phantom Development

Phantom development followed an [article](https://ieeexplore.ieee.org/document/7152875) outlining the creation of an artificial breast phantom replicating the dielectric and thermal properties of human fat. After adjusting the ratios of gelatin, water, and oil, the dielectric properties of the produced phantom proved satisfactory.

## Antenna Production

An LPKF device, an in-house printed circuit board prototyping tool, was used for antenna production. The designed antenna's gerber files were introduced to the LPKF device, after which the feeding structure was soldered onto the antenna.

## Thermal Measurement

At an input power of 6dbm, the heating provided was unobservable due to insufficient measuring equipment. This issue prompted an increase in input power, utilizing a signal generator from another lab. The resultant data were both intriguing and satisfactory.

## Conclusion

Despite a few challenges, a successful development and simulation of an implantable antenna operating at a frequency of 2.45 GHz was accomplished. This project offered invaluable learning opportunities and highlighted areas for potential improvements and further research.

## Cost Analysis

This project necessitated a workstation for simulation implementation and a vector network analyzer (VNA), a rotary stage, and absorbers for the creation of the measurement setup. 

## Repository Structure

This repository holds significant resources and documents pertinent to the project:

- `./scripts` : Contains MATLAB scripts for testing the dielectric properties of the phantom.
- `./designs/` : Holds ANSYS Electronics Desktop (AEDT) files used for various antenna designs throughout the project.
- `./VNA/` : Presents the results from the Vector Network Analyzer.
- `./manufacturing/` : Houses design files used in the fabrication of antennas, boards, etc. 
- `./thermal_photo/` : Features thermal camera screenshots to examine the heat generated by the fabricated antenna.
- `./photos/` : Provides an inside look into the manufacturing and measuring processes through photos.
- `after_graduation.zip` : Contains documents created post-graduation, furthering the work on this project for approximately 3-4 months until the onset of the pandemic.
- `Project_proposal.pdf`: Initial proposal for the project.
- `Midterm_report.pdf`: Midterm report, submitted on 20.11.2019.
- `Presentation.pdf`: Final presentation for this part of the thesis.
- `Bachelor's_Thesis.pdf`: Final bachelor's thesis, submitted on 4th January 2020.
- `./figs/`: Features a collection of screenshots taken during the simulation phase of the research.