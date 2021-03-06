[Tutorial](https://indico.cern.ch/event/1019958/contributions/4420290/) given at PyHEP21 on July 6th, 14:30 CEST.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/b-fontana/PyHEP21BokehPresentation/HEAD?urlpath=lab/tree/Motivation.ipynb) [![DOI](https://zenodo.org/badge/380001262.svg)](https://zenodo.org/badge/latestdoi/380001262)

<!---  # [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/b-fontana/PyHEP21BokehPresentation/HEAD) --->

Description: *We discuss and justify the application of Python's Bokeh library to non-interactive and interactive visualization. A comparison between Bokeh and some widely used alternatives is made. We include a tutorial covering the key aspects necessary to create virtually any interactive plot needed in HEP, and provide custom examples and code.*

The material includes three notebooks:
- ```Motivation.ipynb```: why ```bokeh``` is very competitive
- ```InteractivePlotting.ipynb```: how to perform interactions with ```bokeh```
- ```CustomExample1.ipynb```: example of exploratory data analysis

-------

**Plot embedding**

```bokeh``` plots can be easily embedded into websites (check the [```gh-pages```](https://github.com/b-fontana/PyHEP21BokehPresentation/tree/gh-pages) branch):

 - see the tutorial example [here](https://b-fontana.github.io/PyHEP21BokehPresentation/ExploreData/).
 - an additional example (```CustomExample2.py```, referring to astrophysical spectra generation) is provided in pure ```python``` format only given its large size. To visualize its output click [here](https://b-fontana.github.io/PyHEP21BokehPresentation/SpectraGeneration/).
 - many great examples by the [active ```bokeh``` community](https://discourse.bokeh.org/):
     - [Bioinformatics](https://pirovc.github.io/grimer-reports/others/placenta_wgs.html)
     - [COVID interactive paper](https://jacob-barhak.github.io/COVID19_Ensemble_2021.html)
     - [Fitness](https://hnagib.com/)
     - [Mortality rates](https://cjdixon.s3-ap-southeast-2.amazonaws.com/bokeh/mortality_rates.html)
     - [Simple simulation](https://polyas-urn.herokuapp.com/app)