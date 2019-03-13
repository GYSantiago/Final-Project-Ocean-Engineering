# Final-Project-Ocean-Engineering
Final Project for Ocean Engineering at University of Washington Bothell
This repository is a summary of my Final Project for Ocean Engineering.
The goal was to find out how Washington's inshore ocean temperatures varied with depth during our snowstorm in February. 
OOI CTD data was used from the Coastal Endurance Array. Links for the Washington Inshore Surface Mooring instruments are provided below.
1.) CE06ISSM-SBD17-06-CTDBPC000 (Surface Buoy)
2.) CE06ISSM-RID16-03-CTDBPC000 (Near Surface Instrument Frame)
3.) CE06ISSM-MFD37-03-CTDBPC000 (Seafloor Multi-Function Node) 
https://ooinet.oceanobservatories.org/platformnav?id=Q0UwNklTU00=&array=PHNwYW4+Q29hc3RhbCBFbmR1cmFuY2U8L3NwYW4+&lat=NDcuMTM0NzU=&lng=LTEyNC4yNzExNQ==
A figure that visually shows where the Inshore Surface Mooring is located is included in this repository.
With the three CTD instruments, the ocean temperature was plotted at three different depths over the course of February 2019. 
The three depths recorded were 1m, 7m, and 29m.
These depths are relatively shallow in comparison to ocean depths further from the shore. I wanted to see if there was a significant change at the ocean surface and seafloor.
In order to compare each depth side by side, I plotted the temperature vs time in Python on the same axis. It takes place from the beginning to the end of February. However, I was unable to convert the arbitrary CTD time values to the date and time.
The code and results are shown in the attached notebook. 
The plot shows that there was a significant change in temperature at the 1 meter and 7 meter depths. This drop in temperature occurs towards the beginning of the month, which is consistent with when the snowstorm arrived.
From analyzing the plot, it can be seen that the seafloor maintained roughly 10.5 degrees Celsius while the upper depths dropped down by nearly 2 degrees Celsius.
I was curious why the shallow seafloor managed to retain its heat so well, looked for more information on the area.
Washington's inshore surface mooring location is a hotspot for upwelling.
According to the National Oceanic and Atmospheric Administration (NOAA), when upwelling occurs, high winds cause surface waters to be replaced by cold, nutrient-rich water that “wells up” from below.
The winds from the snow storm seem to have caused a drastic form of upwelling as well as directly cooling the surface.
This is very different than the common trend of water getting colder as depth increases.
It can clearly be seen when the effects of the storm occur.
