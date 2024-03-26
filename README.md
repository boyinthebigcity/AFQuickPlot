# AFQuickPlot
Ready-to-go Jupyter notebook for plotting AlphaFold-generated MSAs, per-residue pLDDT, and PAE. 

## Pre-requisites:
- AlphaFold output files
- Python with the following packages:
  - os
  - glob
  - pickle
  - json
  - numpy
  - matplotlib.pyplot
  - pandas

## How to use:
- Run your AlphaFold prediction on your preferred system (e.g. on a HPC)
- Download the output folder to your local drive
- Copy the pathname from the downloaded folder and open the AFQuickPlot.ipynb notebook
- Run all cells, and paste in the pathname and write in your protein name when prompted.
- The plots will be saved inside the output folder as .pdf files, and pLDDT scores as a .csv file
- Use the AFRePlot.ipynb notebook to re-plot pLDDT scores with your choice of nº top-ranked predictions and range of positions shown.

## Acknowledgements
- This notebook was based on the code by Sébastien Lemal PhD: https://blog.biostrand.ai/explained-how-to-plot-the-prediction-quality-metrics-with-alphafold2 
