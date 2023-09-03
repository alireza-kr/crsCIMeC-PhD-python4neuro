# Python for (open) Neuroscience Course @ CIMeC

This is the final project of the Python for (open) Neuroscience Course held at [CIMeC](https://www.cimec.unitn.it/en) by [Luigi Petrucco](https://github.com/vigji/).

The project has THREE main parts:
1. It extracts activation of the last layer of AlexNet on a custom dataset using [THINGSvision toolbox](https://github.com/ViCCo-Group/thingsvision) and then creates an Representational Dissimilarity Matrix (RDM) from it.
2. It preprocess a MEG file from an anonymous subject that has undergone the same stimulus. The preprocess is done using [MNE-Python](https://mne.tools/). Then it creates an RDM using [rsatoolbox](https://github.com/rsagroup/rsatoolbox)
3. It compares the CNN's RDM with the MEG's RDM using Representational Similarity Analysis (RSA).
