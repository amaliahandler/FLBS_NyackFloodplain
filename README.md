# FLBS_NyackFloodplain

Last updated: September 11, 2020

Nyack Floodplain Data Compilation and Data Archiving Project

This repo is used for data compilation, cleaning, EDI data package formation and updating, and analysis of Nyack Floodplain RiverNet data, a project created and maintained by Flathead Lake Biological Station.

The following scripts are used to compile data from FLBS data files
- Nyack_Floodplain_Data_Compilation.Rmd
- Nyack_Floodplain_Data_Compilation_PackageUpdate2020.Rmd

The following script was created to clean water data spanning from project inception to June 2019
- Nyack_Floodplain_Water_QAQC.Rmd

The following scripts was created to assemble the metadata into the EML language used for EDI repository data packages
- Nyack_Floodplain_Water_EML_Assembly.Rmd
- Nyack_Floodplain_Met_EML_Assembly.Rmd

The following scripts are part of ongoing analysis of the data produced from this project
- Nyack_Floodplain_FloodGW_Time_Lag.Rmd
- Nyack_Floodplain_Flood_Dynamics.Rmd
- Nyack_Floodplain_Flood_Finder.Rmd

The Data folder contains all data tables that are used and produced by these scripts

Nyack_Met_EML is the file structure used to create, edit, and compile the EDI data package for the met data
Nyack_Water_EML is the file structure used to create, edit, and compile the EDI data package for the water data

The EDI data packages can be view here

Met data: https://doi.org/10.6073/pasta/d06570e3c746c4f516fac28be5200c64
Water data: https://doi.org/10.6073/pasta/d41a8f4cc4174e36b71a3f79e4e5618d

