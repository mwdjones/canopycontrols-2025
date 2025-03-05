Compiled codes, data, and figures for replicating the analysis and figures for Jones et al., 2025 (submitted to Hydrological Processes)

**Abstract**

In snow-dominated areas, runoff from winter precipitation can comprise up to 80% of the annual water budget. 
Warming winters are shifting snow precipitation to rain, shortening the snow accumulation and melt seasons, 
and increasing midwinter melt events and flooding during rain-on-snow events. At the same time, forests are
changing in species composition and geographical extent, and forest-dominated catchments can mediate the effects
of increased winter temperatures on snow dynamics. Here, we bring together climatic data and high-resolution forest 
and snow observations to investigate the complex relationships between forest canopy structure and below-canopy snow
depth in two low-relief Mississippi headwater catchments. To do so, this research complements a two-dimensional canopy
cover metric (i.e., leaf area index) with forest structure controls (e.g., canopy and understory surveys) and catchment
architecture (e.g., slope, aspect) to examine their joint influences on snow depth. Results show that (1) co-dominant tree
density better predicts peak snow depth over leaf area index, due to its ability to represent canopy overlap and
interception and (2) canopy structural diversity increases in peak snow depth. These results suggest that maintaining
structural diversity not only contributes to forest health but also builds a deeper snowpack, thereby increasing the potential
for water storage in snow-dominated watersheds.

**Contents**

_01_clean-grasshopper-data.ipynb_ - Compiles data from the text files in /data/modeloutput/rhino-data that came from the Rhino model 
into csv for numerical analysis. The Rhino model can be run using the layout files in /grasshopperfiles and the Rhino application (https://www.rhino3d.com/)

_02_plot-grasshopper-model.ipynb_ - Plots the data from the grasshopper model

_03_canopy-controls-analysis.ipynb_ - Tunes and runs the Random Forest SHAP variable importance analysis, calculates canopy structural diversity
metrics, and plots paper figures

For questions, contact Mariel Jones (jone3247@umn.edu)
