# MCAP
For CADRE fellowship project Mapping Collaborations and Partnerships in SDG Research.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iuni-cadre/Fellow3-MCAP.git/master)
## Data Arrangement

TBD

## Code Summary

TBD

## Graphs

One of the outputs of the code in `MAG Institutional Network Graph (CADRE).ipynb`
is a Python NetworkX object `G` containing nodes and edges representing institutions involved with SDG research, and the connections between 
them. These connections were derived from co-authorships happening across the SDG literature found in MAG. Any two institutions affiliated with a pair of
co-authors is represented in the graph by an edge. All graphs are limited to *repeat* collaborations, that is connections between institutions that occured more than once; or in graphical terms have an edge value of greater than 1.

In the course of our study of SDG collaboration, we produced an array of network visualizations described below.

### Institutional

- All graph components, nodes colored by continent. [See graph](https://public.flourish.studio/visualisation/3820791/)
- Largest connected component, nodes colore by modularity class. [See graph](https://public.flourish.studio/visualisation/4449252/)
- Only modularity class 2; Highlighting prominence of regional connections. [See graph](https://public.flourish.studio/visualisation/4461554/)
- Largest connected component, 1999–2008, nodes colored by continent. [See graph](https://public.flourish.studio/visualisation/4321031/)
- Highlighting the 20 institutions with the highest degree, nodes colored by continent. [See graph](https://public.flourish.studio/visualisation/4461039/)
- Highlighting the 20 institutions with the highest degree, 2009–2018, nodes colored by continent. [See graph](https://public.flourish.studio/visualisation/4446921/)


### Author

- All graph components [See graph](https://public.flourish.studio/visualisation/4491303/)
- Largest connected components, nodes colored by modularity class. [See graph](https://public.flourish.studio/visualisation/4470016/)



