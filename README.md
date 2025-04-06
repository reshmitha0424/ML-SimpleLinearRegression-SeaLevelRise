# ML-SimpleLinearRegression-SeaLevelRise

### ***Overview:***

**Sea level rise** refers to the **increase in the average height of the world's oceans** over time. This phenomenon is primarily driven by two major factors related to global warming:

1. **Thermal Expansion**: As ocean water warms, it expands. Even a small increase in temperature can cause large volumes of water to expand significantly.
2. **Melting Ice**: Glaciers and polar ice sheets are melting at accelerated rates, adding more water to the oceans.

While sea levels naturally fluctuate due to tides and weather, the long-term **upward trend** observed over the past century is a direct consequence of human-induced climate change. This rise threatens coastal cities, ecosystems, and millions of lives globally, as it can lead to:
- Increased coastal flooding and storm surges
- Erosion of shorelines
- Submersion of low-lying islands and coastal cities
- Displacement of populations

So, it is necessary for us to understand how the rise is happening — particularly the slope of the trend — to evaluate the urgency of the issue and take the necessary actions. By analyzing the rate at which sea levels are rising, we can better predict future scenarios and support evidence-based policy and adaptation strategies.


<hr>

### ***Background:***

Good data science (and data analysis more generally) as well as the appropriate application of machine learning algorithms depends on a clear understanding of the underlying problem/situation, the methods by which the data you are about to analyze are collected, and the situational context in which that data sits. To that end:

Read through the following resources (including links within) regarding the Sea Level Rise and its impacts across the globe.

1. NASA Sea Level Change Portal: Offers comprehensive data, visualizations, and tools to explore global sea level changes. 
[https://sealevel.nasa.gov/]
2. NOAA Sea Level Rise Viewer: An interactive tool that allows users to visualize potential impacts of sea level rise on coastal communities in the U.S. 
[https://coast.noaa.gov/slr/]
3. NRDC's Sea Level Rise 101: Provides an overview of the causes, effects, and responses to sea level rise. 
[https://www.nrdc.org/stories/sea-level-rise-101]
4. NOAA's National Ocean Service on Sea Level Rise: Explains the science behind sea level rise and its implications for coastal areas. 
[]https://oceanservice.noaa.gov/hazards/sealevelrise/]
5. NASA's Climate Change: Vital Signs of the Planet: Presents key indicators of climate change, including detailed information on sea level trends. 
[https://climate.nasa.gov/vital-signs/sea-level/?intent=121]

<hr>

### ***Dataset:***

The data used in this analysis was sourced from the NOAA STAR (Center for Satellite Applications and Research) website.

**Google Link to the Source** - https://www.star.nesdis.noaa.gov/socd/lsa/SeaLevelRise/

Select the global mean sea level from the Products tab in the left. The dataset chosen was the "Seasonal signals removed" CSV file under the "TOPEX, Jason-1, -2, -3, and Sentinel-6MF" column. This version of the dataset has had seasonal variations (like annual cycles) filtered out to focus on the long-term sea level trend. The measurements, derived from satellite altimetry missions like TOPEX/Poseidon, Jason-1 through Jason-3, and Sentinel-6 Michael Freilich, represent global changes in mean sea level from 1992 to the present.
