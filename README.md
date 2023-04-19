# DNA-size-finder
## Overview
DNA size finder is a lightweight Java application that automates the analysis of microscopic images of DNA fiber data. It provides an easy to use environment with many different modes for analysis. It was developed in the Institute of Molecular Biology of the Bulgarian Academy of Sciences.
## How to setup for users
The application DNA size finder is easy to setup. The only requirement is that there is a **Java SE Version 8 or higher** installed on the computer. If only a compiled version is  needed to be used, the required JRE can be downloaded from here:

https://www.java.com/en/download/manual.jsp

After this step is complete the folder "DNASizeFinderAlpha21.1" needs to be downloaded. In this folder there is the jar file that can be launched and a settings folder where pre-created settings for the program to use are stored. DNASizeFinder creates folders where settings and data exporting is handled in the directory where it is located, so it is **recommended to keep the jar file in a separate folder**. In the folder "exampleImages" there are several microscopic images for testing the program.
## Dependencies
Currently in this branch is included the experimental feature of loading images with the BioFormats library:

https://www.openmicroscopy.org/bio-formats/
