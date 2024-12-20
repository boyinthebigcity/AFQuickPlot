# AFQuickPlot
Ready-to-go Jupyter notebook toolbox for plotting AlphaFold-generated MSAs, per-residue pLDDT, and PAE. 

## Pre-requisites:
- Output files from AlphaFold
- Python with the following packages:
  - os
  - glob
  - pickle
  - json
  - numpy
  - matplotlib.pyplot
  - pandas

## How to use:
1. Run your AlphaFold (AF) prediction on your preferred system (e.g. on a HPC)
2. Download the output folder to your local drive
3. Copy the pathname from the downloaded folder and open the correct notebook for your AF version:
  
  |[Version 3 (beta)](https://alphafoldserver.com/)|Version 2.3.2        |
  |---------------------|--------------------|
  |AF3Plot.ipynb       |AFQuickPlot.ipynb (or AFParser.ipynb)|
  | |*_Other AlphaFold2 versions may work, but haven't been tested._*|
4. Run all cells, and paste in the pathname and write in your protein name when prompted.
    - (V2.3.2) If the notebook takes too long or the kernal dies, use AFParser.ipynb to create the pLDDT .csv file and go to step 6.
5. The plots will be saved inside the output folder as .pdf files, and pLDDT scores as a .csv file
6. Use the AFRePlot.ipynb notebook to re-plot pLDDT scores with your choice of nº top-ranked predictions and range of positions shown.

## Acknowledgements
Thank you to Sébastien Lemal PhD for writing the blog post that heavily inspired this Jupyter notebook toolbox: https://blog.biostrand.ai/explained-how-to-plot-the-prediction-quality-metrics-with-alphafold2 
A big thank you to the ITS Research Team at QMUL for helping me get my AlphaFold predictions working on our HPC.
