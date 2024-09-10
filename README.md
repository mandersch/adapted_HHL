# Master's Thesis - Adaptation of the HHL algorithm for unitary inversion

This repository contains all code used in my master's thesis on black box unitary inversion through an adapted HHL algorithm.

## adapted_HHL.ipynb 
> contains all scripts directly related to the algorithm, its preprocessing and analysis

**Declaration** defines all necessary matrices, vectors and constants

**Main Algorithm** runs the adapted HHL algorithm without error mitigaion

**QCL-QPE** runs the phase estimation of the preprocessing step

**Post Selection** performs the calssical selection of eigenseries

**f_l(p)** calculates the maximum error to a given series length

**Series Prob** calculates the probability of finding eigenseries under given circumstances

