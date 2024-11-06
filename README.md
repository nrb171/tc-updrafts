# Overview
This is the data repository for submitted Barron et al., 2024. 

Each of the CSV files in this repository are data collected from updrafts in the TC-RADAR dataset, and two high-resolution WRF-EnKF simulations of Hurricanes Matthew (2016) and Harvey (2017). 

# Details
The columns of each file are as follows:


| Shear-Relative Angle                                | Low-Level Mean Flow-Relative Angle                 | Updraft Depth                          | Updraft Bottom Altitude                        | Updraft Top Altitude                        | Updraft Vertical Velocity                                         | Circulation Classification                                               | Updraft Radial Position                               | Normalized Updraft Radial Position                                                          |
| --------------------------------------------------- | -------------------------------------------------- | -------------------------------------- | ---------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------ | ----------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| degrees to the right of the 200-850 mb shear vector | degrees to the right of the 850 mb windward vector | Total depth of updraft, recorded in km | Bottommost altitude of updraft, recorded in km | Topmost altitude of updraft, recorded in km | Average of vertical velocities in updraft, recorded in m s$^{-1}$ | Classification of circulation around updraft. 1=IuI, 2=OuO, 3=IuO, 4=OuI | Distance from storm center to updraft, recorded in km | Distance from storm center to updraft divided by the location of the radius of maximum wind |

