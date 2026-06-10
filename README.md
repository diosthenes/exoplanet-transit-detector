# exoplanet-transit-detector
To detect an exoplanet transit from the available TESS data.

## description
The project features the usage of the lightkurve module, which makes use of the MAST archive to access flux-time data for stars under the observation of TESS and Kepler missions. The exoplanets are detected by using the transient method, where the flux-time data is analysed for dips. The inbuilt functiions in the Lightkurve module is used for the analysis of the lightcurves. Here, a star with a confirmed transit is analysed for demonstration. The project also showcases validation against known periods of exoplanet transits, for the values obtained from lightcurve analysis. The example target used here is WASP-18.

## result
The period was detected to be 0.942 days, against a published period of 0.941 days.

