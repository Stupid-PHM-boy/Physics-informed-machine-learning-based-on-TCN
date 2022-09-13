# Physics-informed-machine-learning-based-on-TCN
A hybrid approach using physical information (PI) lightweight temporal convolutional neural networks (PI-TCN) for remaining useful life (RUL) prediction of bearings under stiffness degradation. It consists of three PI hybrid models: a) PI feature model (PIFM) - constructs physical information health indicators (PIHI) to increase the feature space; b) PI layer model (PILM) - encodes the physics governing equations in a hidden layer; c) PI layer-based loss model (PILLM) - designs PI conflicting losses, taking into account the integration of the physics input-output relationship module into the differences before and after the loss function. I have provided the original model and basic methodology here and welcome further optimisation of the structure and associated training methods. Interestingly, it is not the number of layers of physics knowledge that is more useful; the right structure for the right physics knowledge is the key to success. Similar to pure DL tuning, to design neural networks based on full physical knowledge is a direction that I am very interested in and would like to discuss with you.

The idea is in this paper:
https://www.researchgate.net/publication/361741642_Physics-informed_Lightweight_Temporal_Convolution_Networks_for_Fault_Prognostics_Associated_to_Bearing_Stiffness_Degradation
