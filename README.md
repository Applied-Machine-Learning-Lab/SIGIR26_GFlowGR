# Code for GFlowGR

## Data 

Data can be downloaded from https://github.com/HonghuiBao2000/LETTER/tree/master/data 

## Implementation

1. Key components of GFGR are included in *modeling_letter.py*:
- ***forward_prob*** to compute forward probability;
- ***in_batch_negative_sampling_new*** to conduct trajectory sampling and reward attribution;
- ***gfn_loss*** to calculate the loss value for GFlowNet (DB or TB);

2. Hyperparameters: Default values within *utils.py*

3. The running script is in *run_train_gfn.sh* (including the training and test).
