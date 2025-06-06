# About Martha's Vineyard Coastal Observatory

The Martha's Vineyard Coastal Observatory (MVCO) Air-Sea Interaction Tower (ASIT) is located at 41.325 N, 70.567 W. See https://mvco.whoi.edu/about/ for more site information. Discrete samples are collected in the vicinity of the tower.

# CTD Rosette Bottle and Bucket Sampling

Discrete water samples are collected at ASIT from the water column at multiple depths using Niskin bottles on a CTD rosette system and at the surface with a bucket. Some MVCO events are opportunistically collected on non-NES-LTER cruises, in which case, typically only a surface bucket sample is collected. Water analysis typically includes chlorophyll a, particulate absorption, colored dissolved organic matter, HPLC for pigments, particulate organic carbon and nitrogen, dissolved nutrients, and flow cytometry at all depths, and genetic sequencing at surface only.

# Bongo Net Tow Zooplankton Collection

A single oblique tow (down then up once through the water column) is conducted in the vicinity of ASIT with a bongo net, both sides of which are 61 cm in diameter and 3.2 m long. One net has 335 micron mesh, the other has 150 micron mesh, and they have similar porosity values, 45% and 46% respectively. A General Oceanics mechanical flowmeter is attached in the center of each net mouth to calculate volume filtered on a per-net basis. Attached to the bongo frame is a temperature-depth recorder (Star-Oddi DST centi-TD or Reefnet Sensus Ultra TDR) for later determining the depth and trajectory fished. During the tows, net depth is estimated using wire angle and wire out with a target net depth of 5 m off the bottom. Ship speed through the water is 1.5-2.0 kts into the current with a winch pay-out and haul-in speed of approximately 10 m/min (the slowest winch speed possible to operate in the shallow depths near MVCO). Samples are typically processed aboard the vessel with the whole 335 micron sample preserved in 5% buffered formalin-seawater and the whole 150 micron sample preserved in 95% ethanol.

# Ship-Provided Data
## Tioga cruises
Underway seawater data are sometimes collected on Tioga cruises and include surface seawater metrics such as temperature, salinity, and fluorometry. Underway ADCP data are sometimes collected for the duration of the day cruise. When CTD rosette casts are performed, water column CTD profiles were collected for temperature, salinity, fluorometry, and sometimes PAR, beam transmission, and sometimes dissolved oxygen.

## NES-LTER transect cruises
Underway seawater data and CTD water column profiles are always collected on transect cruises and include similar measurements to Tioga cruises. Underway ADCP data are always collected at multiple frequencies. Data for these cruises can be found by searching by cruise number at https://www.rvdata.us/data. 

More information on NES-LTER transect cruises can be found in the published events package on EDI: 

Northeast U.S. Shelf LTER, H.M. Sosik, and E.T. Crockford. 2025. Event logs from Northeast U.S. Shelf Long Term Ecological Research (NES-LTER) Transect cruises, ongoing since 2017 ver 2. Environmental Data Initiative. https://doi.org/10.6073/pasta/0cde75ba26923d87e107a1c440613209 (Accessed 2025-06-05).

# Quality assurance and data package assembly

The table of cruises to MVCO is compiled in a spreadsheet with validation for manual data entry. Data package assembly with metadata templates is completed in R, with documentation available at https://github.com/WHOIGit/nes-lter-events-mvco. 


## Differences From Previous Versions

In version 2, events with MVCO event ID from June 2022 to June 2025 cruises were added. NES-LTER transect cruises that sampled at MVCO were also added from 2018 to present. Tioga cruises in version 1 that did not have NES-LTER sampling were removed. Authorship was updated. Data table variable cruise_ID was updated to cruise. Project information was updated to include NES II and RAPID. 
