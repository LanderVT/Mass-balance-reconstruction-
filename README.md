# Mass-balance-reconstruction
Reconstruction of the mass balance of different glaciers in the Kyrgyz Tien Shan

In this repository, the climatic data for the two main meteorological stations can be found:

Kumtor-Tien Shan (3659 m)
Chon-Kyzyl-Suu (2571 m)

The data is provided in timesteps of 3-hours.

1) Temperature measured at 2m above the ground (Temp)
2) Precipitation (Prec)
3) Yearly (1 Oct - 30 Sept) precipitation (Pter)

The provided .matlab file can be used to interpolate the 3-hourly meteorological data to hourly data. 

In addition, the outlines of the glaciers are provided via a .shapefile.

Other data can be requested via lander.van.tricht@vub.be

Concerning new data for CKS:
* Temperature: Data from Kumtor is downloaded and scaled to CKS
* Precipitation: Daily data from CKS is spread into intervals of 1h
