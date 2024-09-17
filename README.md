# Clouds 
Clouds represent the biggest source of uncertainty in climate response to CO$_2$ forcing. Of special concern are the stratocumulus decks found in the subtropics. Modeling their dynamics is challenging at scale, and so their behavior must be approximated in global models. Satellite observations provide an opportunity to learn about cloud physics, but represent a serious data challenge. 

## Temperature controls on low cloud morphology 
Using a self-supervised cloud classification system based on an auto-encoder, we can track cloud population dynamics. 

<img src="clouds.png" width="500">
[above] Self-supervised low cloud classes in the subtropics map to temperature stability space. (Classes contain no temperature information to begin with.)

See more details: 

## Data-driven cloud forecasting
Motivated by recent advances in data-driven weather forecasting

We developed a new machine-learning ready cloud dataset based on the 5 main geostationary satelites.

<img src="cloudbench.png" width="700">
[above] CloudBench RGB mosaic constructed from 5 geostationary satellites with ``natural" color on the day side (high clouds in blue) and colorized IR clouds on the night side.

We employ a decoder-only transformer (GPT-like) to learn the relationship between two historical timesteps and one future timestep. Forecasts can in principle be rolled out indefinitely. Research is preliminary. 

<img src="forecast.png" width="700">
[above] 6-hour forecast rolled out at 30 min timestep for the Western Pacific. 

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
[above] 

See more details: 

## Shifting cropland under climate change

Without extensive growing season adaptations (and associated cultivar development), regions of peak yield do not shift 

<img src="latloss.png" width="500">
[above]

<img src="regions.png" width="700">
[above]

See more details: 

