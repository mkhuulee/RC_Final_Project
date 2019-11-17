# **Research Computing: Final Project**
Michelle Lee\
Fall 2019

## Research Question
Are there deep earthquakes associated with the 2015 Axial Seamount Eruption and are these deep earthquakes located at the depths and locations of the magma imaged beneath the caldera?

## Motivation
For this project, we define deep earthquakes at Axial Seamount as earthquakes located beneath the main axial melt lens (AML), which is located at around 1.5km below the seafloor. At other volcanic systems, deep earthquakes associated with eruptions of the volcano have been detected and located beneath the main magma reservoir. These deep earthquakes are typically located where deep magma reservoirs are located (Iceland). For this project, we want to determine if the ocean bottom seismometers(OBS) at the seamount were able to detect deep earthquakes at Axial Seamount during the time of the 2015 eruptions and where these deep earthquakes are located in relativity to known magma reservoirs beneath Axial Seamount. 

## Data Set(s)
Axial Seamount Earthquake Catalog from Felix Waldhauser:\
Downloaded Files:\
[Axial Earthquake Event Catalog (Up to 2017)](https://ocean.pangeo.io/user/0000-0002-4169-7049/files/RC_Final_Project/Data/Axial-DD.v201701.1?_xsrf=2%7C9067c149%7C0183faafdefadf55411b510d66dad02a%7C1573496896)\
[Phase File](https://ocean.pangeo.io/user/0000-0002-4169-7049/files/RC_Final_Project/Axial-DD.phases.v201701.1?_xsrf=2%7C9067c149%7C0183faafdefadf55411b510d66dad02a%7C1573496896)\
Online:\
[Axial Earthquake Recent Catalog*](https://www.ldeo.columbia.edu/~felixw/Axial/)

*Most recent compilation of earthquakes detected from the OBS stations at Axial Seamount from OOI (Ocean Observatories Initiative) cabled array: continually updated with any addtional events detected

Magma Reservoir:\
I will create an array with the interpreted location of the magma reservoirs from Arnulf et al. (2014, 2018)

## Analysis
First, I will load both the event catalog text file and the phase file, which contains the P and S-wave for each of the event and select the events that are within the timeframe and location of interest. Then I will take the S-wave and subtract the P-wave and plot these relocated depth values with the estimated depths from the catalog for comparison.This information will allow me to determine how well the velocity model used works with relocating the depth of deeper earthquake events. From that I will select the events that are deeper than 1.5km and plot those to look at the locations of these events and compare them to the location of previously mapped magma reservoirs locations. 