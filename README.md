# Environmental and Structural Drivers of Hurricane Edouard (2014) Intensification

Undergraduate honors research — University at Albany, SUNY, Department of Atmospheric and Environmental Sciences.
**Author:** EB Smith · **Advisors:** Prof. Kristen Corbosiero and Prof. Brian Tang

## Overview
Hurricane Edouard (2014) was one of the best-observed Atlantic hurricanes, sampled by NOAA P-3 Hurricane Hunter aircraft, NASA's Hurricane and Severe Storm Sentinel (HS3) Global Hawk, and NCAR/NOAA AVAPS dropsondes. This project combines those observations with satellite infrared imagery and WWLLN lightning data to examine what supported, and what hindered, Edouard's intensification.

## Key findings
- A lightning outbreak on 12–13 September preceded intensification (lead–lag relationship); outer-core lightning led in flashes per 3 h in most periods.
- Vortex tilt stayed small (< 40 km) through most of development, with a coherent circulation center in P-3 tail Doppler radar.
- Higher surface θe downshear, consistent with intensifying tropical cyclones (Wadler et al. 2022).
- Tangential winds increased and the radius of maximum wind contracted.
- Hindrance: mid-level dry air on the east side created a thermodynamic asymmetry and suppressed convection there.

## Repository layout
| Folder | Contents |
|---|---|
| `notebooks/1_lightning_ir` | WWLLN lightning radius–time Hovmöller, IR brightness temperature vs. shear-relative azimuth |
| `notebooks/2_radar` | P-3 tail Doppler radar loading, reflectivity, vortex tilt, tangential winds / RMW |
| `notebooks/3_dropsondes` | Dropsonde RH and θe cross-sections (14 Sep), dropsondes overlaid on satellite imagery |
| `notebooks/4_satellite` | Retrieval and animation of 4-km merged IR imagery |
| `exploratory/` | Earlier work: IR animations, HRD dropsonde plotting, TC-PRIMED/LIS experiments |
| `figures/` | Selected final figures |

## Data
Raw data are **not** included (several GB of radar, dropsonde, satellite, and lightning files). The notebooks reference paths on the UAlbany `tcdynasty` lab server; update those paths to run elsewhere. Sources:
- NOAA/AOML Hurricane Research Division — P-3 tail Doppler radar and dropsondes
- NASA HS3 / NCAR EOL — AVAPS dropsondes
- NASA GES DISC — NCEP/CPC 4-km merged IR (MERGIR)
- World Wide Lightning Location Network (WWLLN)

Notebook outputs were cleared to keep the repository small.

## References
- Rogers, R. F., et al., 2016: Observations of the Structure and Evolution of Hurricane Edouard (2014) during Intensity Change. Part II. *Mon. Wea. Rev.*, 144, 3355–3376. https://doi.org/10.1175/MWR-D-16-0017.1
- Zawislak, J., et al., 2016: Observations of the Structure and Evolution of Hurricane Edouard (2014) during Intensity Change. Part I. *Mon. Wea. Rev.*, 144, 3333–3354. https://doi.org/10.1175/MWR-D-16-0018.1
- Fischer, M. S., R. F. Rogers, P. D. Reasor, and J. P. Dunion, 2023: An Observational Analysis of the Relationship between Tropical Cyclone Vortex Tilt, Precipitation Structure, and Intensity Change. *Mon. Wea. Rev.*, 152, 203–225. https://doi.org/10.1175/MWR-D-23-0089.1
- Wadler, J. B., et al., 2022: The Effects of Environmental Wind Shear Direction on Tropical Cyclone Boundary Layer Thermodynamics and Intensity Change from Multiple Observational Datasets. *Mon. Wea. Rev.*, 150, 115–134. https://doi.org/10.1175/MWR-D-21-0022.1
