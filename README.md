# PyGlm
Python scripts to generate GridLAB-D Modeling (.glm) files for power distribution network simulation.

Dependent files:

(1) topology.json

The lines of different areas, e.g. mv area (7.2kV transmission network) and lv areas (120V distribution network).
All the transformers that connect areas of different voltage levels (under "tr"). 

(2) config.json

measure_id: maps node to its meter

fixed_measurement: fixed measurement for transmission level nodes.

area2transformer: maps area to its transformer

area2phase: maps area to its power phase

(3) measurement.csv

The measurement of the meters at different times.
