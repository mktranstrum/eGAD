This repository has the data and code for generating the data for the paper _Generalized Aliasing Explains Double Descent and Informs Model Design._

Most of the data files can be read (and were generated) using the code in the jupyter notebook `GADExperiments.ipynb`.
* The random feature models were all generated and plotted using the jupyter notebook `GADExperiments.ipynb`.  
Results are saved as .npz files in this directory.
* Collocation data is in a separate subdirectory, stored as .csv files, and was plotted with `GADExperiments.ipynb`.
* Cluster expansion data is in the two files `CEdata-physicist-order.csv` and `CEdata-random-order.csv` in this directory, and was plotted with `GADExperiments.ipynb`.

The remaining data files are for the "adding points" experiment: `Legendre_leggauss400.npz` and `Legendre_random400.npz`.  These can be accessed (and were generated) using the jupyter notebook `AddingTrainingPoints.ipynb`.

pdf plots of the data are included.
