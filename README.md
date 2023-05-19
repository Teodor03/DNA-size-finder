# DNA-size-finder

## Overview:
DNA size finder is a lightweight Java application that automates the analysis of microscopic images of DNA fiber data. It comes bundled with the BioFormats library, which allows it to open most of the available image formats. It provides an easy to use environment with different modes for analysis. It was developed in the Institute of Molecular Biology of the Bulgarian Academy of Sciences.

## How to setup:
The application DNA size finder is easy to setup. The only requirement is that there is a **Java SE Version 8 or higher** installed on the computer. The required JRE can be downloaded from here:

https://www.java.com/en/download/manual.jsp

After this step is complete and the repository is cloned, the jar file is ready to launch. In the folder where the jar file is located there is also a settings folder where pre-created settings for the program to use are stored. DNASizeFinder creates folders where settings and data exporting is handled in the directory where the jar is located, so it is **recommended to keep the jar file in a separate folder**. In the folder "exampleImages" there are several microscopic images for testing the program.

## Dependencies:
The following third-party libraries are being used in this project: (They come together bundled in the jar file.)

1. The BioFormats library for IO (Only the "format-gpl" package is being used.).
2. Logback classic as an implementation of the logging framework.

## Cite us:
This project is currently published at the following link, where a detailed explanation is given, so when using our software please cite us:

https://doi.org/10.1080/13102818.2023.2206488

## Contact us:
If you are having any questions about the software or want to give a feedback, you can send an email to the following address.

teokirilov@gmail.com
