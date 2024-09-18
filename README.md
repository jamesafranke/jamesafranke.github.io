# Clouds 
Clouds represent the biggest source of uncertainty in climate response to CO$_2$ forcing. Of special concern are the stratocumulus decks found in the subtropics. Modeling their dynamics is challenging at scale, and so their behavior must be approximated in global models. Satellite observations provide an opportunity to learn about cloud physics, but represent a serious data challenge. 

## Temperature controls on low cloud morphology 
Using a self-supervised cloud classification system based on an auto-encoder applied to MODIS multi-spectral imagry, we can identify cloud types based on texture, which may diferentiate physical processes. When employed on 20 years of MODIS observations and co-located we reanalysis weather data. We find that low cloud texture in the subtropics is well-explained by the temperature structure of the lower tropopshere, specifically the estimated inversion strenght and the near surface temperature. In each temperature regime, you are most likely to find a certain class of clouds (boundaries are less clear).

<img src="clouds.png" width="500">
**[above]** A) AICCA cloud classes mapped to a meteorological domain of near-surface temperature and inversion strength, for all patches in the three main subtropical stratocumulus regions.  Regions of dominance are generally well-separated and coherent. The 10 most dominant classes are color-coded; all high clouds (mean cloud top pressure $>$680 hPa) are shown in light grey.  Nine of the 10 classes are stratocumulus; #20 is thinner and higher. Thumbnail images of typical class members are shown at bottom. (B) As in panel A but with dots scaled in size according to frequency of those meteorological conditions (for samples with clouds). The trade winds tend to move parcels on this diagram from upper left to lower right, i.e.\ from cold and stable to warmer and less stable, with clouds textures responding by becoming more open: #35 -> \#30 -> \#40.  (C) As in panel A but with dots scaled to represent the share of all clouds by the most dominant cloud class. Very high- or low-stability conditions produce more consistent textures. (D) The three stratocumulus regions color-coded by the most dominant cloud class in each location, using the same color code. Classes are distributed in understandable geographic patterns, following large-scale environmental gradients. As expected, zones of thick stratocumulus are in the subtropics.

See more details: https://github.com/jamesafranke/AICCA/blob/master/ms/low_marine_clouds_met_PNAS.pdf

## Data-driven cloud forecasting
Motivated by recent advances in data-driven weather forecasting

however, all recent transformer forecast models are trained on reanalysis model data, which does not contain all the revelant cloud phyisics to begin with.

We developed a new machine-learning ready cloud dataset based on the 5 main geostationary satelites we call CloudBench (following WeatherBench). Geostationary observations from 

<img src="cloudbench.png" width="700">
**[above]** CloudBench RGB mosaic constructed from 5 geostationary satellites with ``natural" color on the day side (high clouds in blue) and colorized IR clouds on the night side.

We employ a decoder-only transformer (GPT-like) to learn the relationship between two historical timesteps and one future timestep. Forecasts can in principle be rolled out indefinitely. Research is preliminary. 

<img src="forecast.png" width="700">
**[above]** 6-hour forecast rolled out at 30 min timestep for the Western Pacific. 

# Climate Interventions
Stratospheric aerosol injection may impact low clouds by changing the radiative cloud top cooling or vertical temperature structure of the atmosphere. 

<img src="rca.png" width="500">
[above] SAI may disrupt clouds more than CO$_2$. Left time series: net and cloud-only forcing following simulated volcanic eruptions for EC-Earth climate model. Right scatter: global mean rapid cloud adjustment to abrupt CO$_2$ forcing and volcanic SAI (averaged from 4 simulated historic eruptions) for the first three years post CO$_2$ forcing or eruption (the ratio of the integrals between the pink-blue line of the top and bottom time series plots). A value of 0.5 indicated the cloud radiative effect dampens the SAI forcing by half. (The CO$_2$ effect is opposite.) Dots represent individual CMIP-6 models averaged over all available realizations. Analysis not yet published.

# Food Security

## Heat stress for cattle
Cattle are by far the most economically important livestock species worldwide, with estimated over 1 billion animals. 

We employ a meta-analyis of published cattle heat stress studies. 

Crucially, land use forecasts of increased agricutual land are most dramatic in tropical rainforests. This drives a 

<img src="cattle.png" width="400">
**[above]**

See more details: 

## Shifting cropland under climate change

Without extensive growing season adaptations (and associated cultivar development), regions of peak yield do not shift 

<img src="latloss.png" width="500">
**[above]**

<img src="regions.png" width="700">
**[above]**

See more details: 

