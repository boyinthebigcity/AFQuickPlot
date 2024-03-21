# AFQuickPlot
Ready-to-go Jupyter notebook for plotting AlphaFold-generated MSAs, per-residue pLDDT, and PAE. 

1. Pre-requisites:
- AlphaFold output files
- Python with the following packages:
  - os
  - glob
  - pickle
  - json
  - numpy
  - matplotlib.pyplot

2. How to use:
- Run your AlphaFold prediction on your preferred system (e.g. on a HPC)
- Download the output folder to your local drive
- Copy the pathname from the downloaded folder and open the AFQuickPlot.ipynb notebook
- Run all cells, and paste in the pathname and write in your protein name when prompted.
- The plots will be saved inside the output folder as PDFs

3. Acknowledgements
- This notebook was based on the code by Sébastien Lemal PhD: https://blog.biostrand.ai/explained-how-to-plot-the-prediction-quality-metrics-with-alphafold2 
