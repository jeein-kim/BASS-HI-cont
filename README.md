
## The L-band continuum images of 40 **BASS-HI** targets

These datasets were obtained from two projects ([_VLA/20A-123_](https://library.nrao.edu/proposals/?utf8=✓&search_field=all_fields&q=20A-123) and [_VLA/23B-079_](https://library.nrao.edu/proposals/catalog/20265)) observed with the Karl G. Jansky Very Large Array (VLA).  
The observations were conducted in the C- and D-configurations, targeting 38 and 2 sources, respectively.  
The L-band broadband covers 1–2 GHz, resulting in a typical bandwidth of 1 GHz.  
The data were processed and reduced using <span style="color:green"><i>CASA 6.5.4-9 CASAtools:v1.0.0</i></span>.


The measurement files include BAT IDs, beam information, measured fluxes with uncertainties, measured radii, and RMS values.  
RMS values were derived from the imaging residual FITS files.
The continuum flux and uncertainty were measured via the CASA task "[_imfit_](https://casadocs.readthedocs.io/en/latest/api/tt/casatasks.analysis.imfit.html)" within the coverage radius.  

The columns in the `measurements.csv` file are listed below:


| Column Name               | Description |
|----------------------------|-------------|
| BAT                        | BAT ID |
| TELESCOP                   | Telescope name |
| DATE-OBS                   | Observation date |
| BMAJ                       | Beam major axis (arcsec) |
| BMIN                       | Beam minor axis (arcsec) |
| BPA                        | Beam position angle (deg) |
| IntFlux[Jy]                | Integrated flux (Jy) |
| Err[Jy]                    | Flux uncertainty (Jy) |
| Peak[Jy/beam]              | Peak flux (Jy/beam) |
| Err[Jy/beam]               | Peak flux uncertainty (Jy/beam) |
| IntFlux[mJy]               | Integrated flux (mJy) |
| Err[mJy]                   | Flux uncertainty (mJy) |
| MeasureRadius[arcsec]      | Measurement radius (arcsec) |
| Name                       | Source name |
| Cname                      | Counterpart name |
| Project_Code               | Project code |
| VLA_config                 | VLA configuration |
| measured_RMS_uJy/beam      | Measured RMS (μJy/beam) |
| RAJ2000                    | Right ascension (J2000) |
| DEJ2000                    | Declination (J2000) |
| Dist                       | BASS Distance (Mpc) |
| cont_base                  | Contour base flux for PNG plotting |



---

- #### 20A-123 (C-configuration) PI: A.Chung
A total of 38 datasets are included.  
The average beam size is ~12–16 arcsec.  
The mean RMS is 64.4 ± 70 μJy/beam.  
For 31 datasets with RMS < 100 μJy/beam, the mean RMS is 39.65 ± 23.79 μJy/beam.  
For 7 datasets with RMS > 100 μJy/beam, the mean RMS is 173.98 ± 104.65 μJy/beam.  

- #### 23B-079 (D-configuration) PI: J.Kim
A total of 2 datasets are included.  
The average beam size is ~30–40 arcsec.  
The mean RMS is 20 μJy/beam.


---




_This GitHub page is intended for internal sharing within the [**BASS project**](https://www.bass-survey.com) only.  
If you are interested in this data, please contact us individually._

