# MCAP
For CADRE fellowship project Mapping Collaborations and Partnerships in SDG Research.

## Data Arrangement

Info to be added once data is approved in current format(s)

## Code Summary

TBD

## Graph

One of the outputs of the code in `MAG Institutional Network Graph (CADRE).ipynb`
is a Python NetworkX object `G` containing nodes and edges representing institutions involved with SDG research, and the connections between 
them. These connections were derived from co-authorships happening across the SDG literature found in MAG. Any two institutions affiliated with a pair of
co-authors is represented in the graph by an edge. Any 1 paper contributes to as many edges between institutions as there are possible institutional combinations among
the co-authors' affiliations. While a paper with 2 authors could only ever connect 2 institutions, a paper with 30 authors and 30 different 
affiliated institutions would contribute to 435 different edges. Thus a single many-authored paper may have outsize influence on the shape of the graph.

The [nodes](mag_output_inst/mag_inst_nodes.csv) and [edges](mag_output_inst/mag_inst_edges.tsv) have been rendered in visual form using Flourish.Studio:

https://public.flourish.studio/visualisation/3820791/

