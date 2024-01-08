# SSPs Decomposition

## Introduction
This repository contains the scripts that accompany the paper
> Al Khourdajie, A., J. Skea & R. Green (Accepted). “Climate ambition, background scenario or the model? Attribution of the variance of energy-related indicators in global scenarios.” Energy and Climate Change

Below we provide details on preparing the data, implementing the Shapley-Owen decompostion method, generating and visualising the results, generating the supplementary results.      

## Data
The data used in this paper: SSP Database (Shared Socioeconomic Pathways) - Version 2.0

Available from: https://tntcat.iiasa.ac.at/SspDb/dsd?Action=htmlpage&page=10

Citation:
> Keywan Riahi, Detlef P. van Vuuren, Elmar Kriegler, Jae Edmonds, Brian C. O’Neill, Shinichiro Fujimori, Nico Bauer, Katherine Calvin, Rob Dellink, Oliver Fricko, Wolfgang Lutz, Alexander Popp, Jesus Crespo Cuaresma, Samir KC, Marian Leimbach, Leiwen Jiang, Tom Kram, Shilpa Rao, Johannes Emmerling, Kristie Ebi, Tomoko Hasegawa, Petr Havlík, Florian Humpenöder, Lara Aleluia Da Silva, Steve Smith, Elke Stehfest, Valentina Bosetti, Jiyong Eom, David Gernaat, Toshihiko Masui, Joeri Rogelj, Jessica Strefler, Laurent Drouet, Volker Krey, Gunnar Luderer, Mathijs Harmsen, Kiyoshi Takahashi, Lavinia Baumstark, Jonathan C. Doelman, Mikiko Kainuma, Zbigniew Klimont, Giacomo Marangoni, Hermann Lotze-Campen, Michael Obersteiner, Andrzej Tabeau, Massimo Tavoni. The Shared Socioeconomic Pathways and their energy, land use, and greenhouse gas emissions implications: An overview, Global Environmental Change, Volume 42, Pages 153-168, 2017, ISSN 0959-3780, DOI:110.1016/j.gloenvcha.2016.05.009

Details on data preparation and downselection are available in folder *01_input_data_prep* above. The code also produces *Figure B.1* and *Table B.3*, Appendix B in the paper.

## Methods and Results
We utilise the Shapley-Owen decomposition method, and apply it on the SSPs datafile prepared in *01_input_data_prep*.

The implementation of the Shapley-Owen decomposition method in Python is available in folder *02_decomposition_analysis_figures*. Check the paper for further details. The folder includes the script that implement the Shapley-Owen methodolgy and generat the results for both the main body of the paper, as well as the diagnostic analysis presented in Appendix E. 

Figures provided here are the decomposition figures only for the main body of the paper, as well as Figure D.1 (Appendix D), and Figures E.1 - E.6 (Appendix E) 

The ternay results and plots in the main body of the paper can be found in folder *03_ternary_plots*

The remainder of all results and plots can be found in folder *04_appendix_c_supplementary_figures*

All results should be reproducible by following the sequence of the scripts in this repo. 

For any question or feedback on the Python implementation of the analysis, please do get in touch.

## Data
All input data files and results are available in folder *05_data*.

## Citation
If you find our work useful, please cite our paper. Please do so also in case you make use of the code or variation of it. 

## Acknowledgments
Alaa Al Khourdajie and Jim Skea were supported by the Engineering and Physical Sciences Research Council, United Kingdom, grant/award no. EP/P022820/1. 
