
# HIV-1B Trees

HIV Trees and log files for the PDA 500-taxa dataset from ([Hong et al., 2020](http://dx.doi.org/10.3390/v12020182))

The trees and log files correspond to the outputs of a BEAST analysis of 500 HIV-1B sequences performed with a strict molecular clock, a GTR+G4 nucleotide substitution model, a logistic growth coalescent prior and an informative normally distributed root-height prior centered at 44 years with a standard deviation of 2 (following [Worobey et al., 2016](https://doi.org/10.1038/nature19827)). 

See ([Hong et al., 2020](http://dx.doi.org/10.3390/v12020182)) for more info.

The following files have been included in this repository:
* `nogeo_pda_500_1_1_run1.log`: Log files with samples from the first BEAST MCMC replicate
* `nogeo_pda_500_1_1_run2.log`: Log files with samples from the first BEAST MCMC replicate
* `nogeo_pda_500_1_1.combined.log`: Concatenated log file with both runs without burn-in
* `nogeo_pda_500_renamed.combined.trees`: Concatenated trees files without burnin. Taxa names have been renamed to preserve anonymity.
* `nogeo_pda_500_renamed.combined.downsampled.trees`: Downsampled empirical tree distribution of 1000-posterior trees (sampled every 2.5M states).Taxa names have been renamed to preserve anonymity.
* `tree_run_mapping.csv`: CSV file mapping each tree in the empirical tree distribution to its corresponding run.
