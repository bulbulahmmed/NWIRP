# NWIRP
This github directory contains required model and PEST input files that has been explained on the draft of NWIRP article written by Ahmmed et. al. Anybody is encouraged to run the model and verify the work. 
# Model input files
nwirp directory is for model input and accessory files
# Initial PEST input and record files
1. nwirp_reg.pst 
2. nwirp_reg.rec
# Pest file with calibrated parameters
nwirp_cal.pst
# Nonlinear uncertainty analyses data
1. randpar_existing_val_mean.txt is for random realizations that were generated using randpar utility of PEST
2. nsmc_existing_val_mean.txt is nullspace projection over random realizations that were generated by pnulpar utility of PEST
3. schur_rands_from_pyemu.txt contains parameters of schur realizations
4. nsmc_real.txt contains parameters of NSMC realizations
5. record.dat has total model calls by each NSMC simulation run for 1,000 realization (total model calls: 60,531)
