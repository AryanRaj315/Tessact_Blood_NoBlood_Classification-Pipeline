# Tessact_Blood_NoBlood Classification Pipeline
This repository contains the solution notebook to the problem asked in tessact.
### Models used
efficientnet-b0, efficientnet-b1
### Optimizer and Loss:
Over9000 and BCEWithLogits
### Ensembling:
Ensembled 10 models and predicted using 6 by applying alpha trimming. 5 models were of b0 trained on 5 different stratified split and 5 were of b1 trained on 5 different stratified split.
