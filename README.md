# BrainTumorClassification
Project for the Computional Intelligence and Deep Learning exam on my Master Degree in Artificial Intelligence and Data Engineering at the University of Pisa.
# Introduction
A brain tumor is a collection, or mass, of abnormal cells in your brain. The skull, which encloses the brain, is very rigid. Any growth inside such a restricted space can cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening. Early detection and classification of brain tumors is an important research domain in the field of medical imaging and accordingly helps in selecting the most convenient treatment method to save patients life therefore. 

The best technique to detect brain tumors is Magnetic Resonance Imaging (MRI). A huge amount of image data is generated through the scans. These images are examined by the radiologist. A manual examination can be error-prone due to the level of complexities involved in brain tumors and their properties.
Application of automated classification techniques using Machine Learning(ML) and Artificial Intelligence(AI) has consistently shown higher accuracy than manual classification. Hence, proposing a system performing detection and classification by using Deep Learning Algorithms using ConvolutionNeural Network (CNN), Artificial Neural Network (ANN), and TransferLearning (TL) would be helpful to doctors all around the world.
# Results
In this work we tested from scratch CNN, pre-trained CNNs and vision transformer for the classification of brain tumors. We discuss the differences of these models and then we ensembled them improving their performances.
We saw how the differents techniques to find the weights are important in order to maximize the results of our model. 

In terms of accuracy we obtained a model with about 97.6\% of accuracy, which is totally comparable to the results discussed in the Related Work chapter. An important result we have to be proud about is that we reached an almost perfect precision on no tumor, which will led to avoid the most unpleasant consequences for the patient.

