# OPC_DEMO
Simulate a photolithography machine to process OPC and ILT data. Use this data to train a UNet to perform ILT. 

The two jupyter notebooks are include.

1) Litho_Sim.ipynb -> This simulated a photolithography machine and also produces the optimised masks in "train_masks".
2) UNet_training.ipynb -> The use the pairs of data from "train_layout" and "train_masks" to train the Unet to perform ILT.

Three datasets are also include:

1) random patterns -> This is the full random patterns dataset
2) train_layout -> This is the layouts selected to produce their optimised masks
3) train_masks -> These are the optimised masks produced by Litho_Sim.ipynb



