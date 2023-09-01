# Fit of Fermi data for the SEDs in the SIN IV paper

We provide the output files of the fit of Fermi data used in the SIN IV paper. The folders contain the fermi model and fit results for the respective source (as in the folder name). 

`llh.npy` is the state of region of interest (ROI) as was calculated with the fit (see also [the fermipy documentation](https://fermipy.readthedocs.io/en/latest/output.html)).

The output for the SED fit itself is in `SED.npy`, detailed information on each entry is available [here](https://fermipy.readthedocs.io/en/latest/advanced/sed.html?highlight=sed#sed-dictionary). 

For plotting, `bowtie.npy` contains the shape of the bowtie for the fitted model (power law or log-parabola) for the SED. 
