# beehive_simulation_data_release

## Description
This repository contains all originally produced COMSOL simulation data contained in \<INSERT DOI WHEN AVAILABLE\>. The data is organized by figure; the caption of the figure and the paper text provide more information. 

## Reading File Names
File names include a relevant cavity parameters, followed by their associated values. All values are counts or in mm, as appropriate. The letter d is used for cell separation rather than $\ell$. For figures where multiple .dxf files were generated and simulated per geometric configuration the tag \_rev# is used to differentiate results obtained by simulating associted .dxf files.  

Example: /beehive_haloscope_simulation_public_data/Figure_12/n169_R19.5_d38.5_r7.00_rerrormax0.01_x0_y0_rev0.txt describes a cavity with 169 cells, cell radii of 19.5 mm, cell separation of 38.5 mm, ideal rod radius of 7.00 mm, maximum rod radius variation of 0.01 mm, and rod position (0 mm, 0 mm). It is a simulation of the first .dxf generated for this geometric configuration. 

Figures without data fall into four categories:

1. The figure is a drawing or sketch with no associated data (Figs. 1 and 5).
2. The figure shows a COMSOL-generated E-field; in case the image contained in the figure is the simulated data (Figs. 2, 6, 8, 14 [E-field insets], 18).
3. The figure is an experiment summary; all associated data can be found by reading the referenced papers (Figs. 24, 25).
4. The figure describes a calculation using data from other figures (Figs. 27, 28).

## License
This work is licensed under a Creative Commons Attribution 4.0 International License

![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
