# DoGNet
A Deep Architecture for Synapse Detection in Multiplexed Fluorescence Images

![Alt text](images/pipeline.png?raw=true "DoGNet Pipeline")

We propose DoGNet, a neural architecture, that closes the gap between classical computer vision blob detectors, such as Difference of Gaussians (DoG) filters, and modern convolutional networks. DoGNet is optimized to take in highly multiplexed microscopy data. Due to small number of trainable parameters, DoGNet can be trained with only few examples, which facilitates application of the tool to new datasets and prevents overfitting. We evaluate our method on multiplexed fluorescence imaging data in both primary mouse neuronal cultures and mouse cortex tissue slices. We show that DoGNet outperforms convolutional networks with a low to moderate number of training examples. DoGNet synapse localizations are then used to guide the segmentation of individual synaptic protein locations and extent, revealing the spatial organization of proteins within synapses and their abundances.

# Acknowledgements
This work is supported by Skoltech NGP Program (Skoltech-MIT joint project)