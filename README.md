# Transfer-learning-SOLAR-ENERGY-MATERIALS

We build a 3-layer network with dropout rate 0.2 for the first 2 layers. We first trained the model with the pretraindataset, using MSELoss as our criterion and Adam as our optimiser. Then we freeze the the parameters and train the model with training data for 2000 epochs. Afterwards, we pause training, unfreeze the body, and continue training, but with a very small learning rate for 2000 epochs.
