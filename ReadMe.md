# **Research Computing: Final Project**
Michelle Lee\
Fall 2019

## Research Question
Are there deep earthquakes associated with the 2015 Axial Seamount Eruption and are these deep earthquakes located below the main magma reservoir beneath the caldera?

## Motivation
For this project, we define deep earthquakes at Axial Seamount as earthquakes located beneath the main axial melt lens (AML), which is located at around 3km below the seafloor. At other volcanic systems, deep earthquakes associated with eruptions of the volcano have been detected and located beneath the main magma reservoir. These deep earthquakes are typically located where magma sills have been imaged beneath the main AML and have been correlated with the magma transport between the sills. For this project, we want to determine if the ocean bottom seismometers(OBS) at the seamount were able to detect deep earthquakes at Axial Seamount during the time of the 2015 eruptions. Then for these deep earthquakes, we want to compare their depths and locations with the location the main AML to see if any are located below it. Our main goal is to determine if the deep earthquakes from eruptions at Axial Seamount can tell us about the magma transport during the 2015 eruption.

## Data Set(s)
Axial Seamount Earthquake Catalog from Felix Waldhauser:\
Downloaded Files:\
[Axial Earthquake Event Catalog (Up to 2017)](https://ocean.pangeo.io/user/0000-0002-4169-7049/lab/tree/RC_Final_Project/Axial-DD.v201701.1)\
[Phase File](https://ocean.pangeo.io/user/0000-0002-4169-7049/lab/tree/RC_Final_Project/Axial-DD.phases.truncate.1)\
Online:\
[Axial Earthquake Recent Catalog*](https://www.ldeo.columbia.edu/~felixw/Axial/)

*Most recent compilation of earthquakes detected from the OBS stations at Axial Seamount from OOI (Ocean Observatories Initiative) cabled array: continually updated with any addtional events detected

Magma Reservoir:\
Lat/Lon Locations of the magma reservoirs from Arnulf et al. (2014, 2018)\
[Main Magma Reservoir](https://ocean.pangeo.io/user/0000-0002-4169-7049/lab/tree/RC_Final_Project/Axial_Seamount_MMR.ll)\
-Depth will need to be estimated as a range since data with depth (3-4 kmbsf) is not available but within the text 

## Analysis
First, I will load both the event catalog text file and the phase file, which contains the P and S-wave for each of the event and select the events that are within the timeframe and location of interest. Then I will take the S-wave and subtract the P-wave and plot these relocated depth values with the estimated depths from the catalog for comparison.This information will allow me to determine how well the velocity model used works with relocating the depth of deeper earthquake events. From that I will select the events that are deeper than 4km and plot those to look at the locations of these events and compare them to the location of previously mapped magma reservoirs locations. 

## Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mkhuulee/RC_Final_Project/master)
