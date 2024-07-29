# SharkNet-X
An Explainable Convolutional Neural Network Approach to Fossil Shark Tooth Identification

The files "VGG16-DA180_8Luglio24.h5 2.7z.001", "VGG16-DA180_8Luglio24.h5 2.7z.002" and "VGG16-DA180_8Luglio24.h5 2.7z.002" must be dowloaded together and decompressed in order to obtain the model.

This model refers to the VGG16 architecture trained with transfer learning and using data augmentation with rotation angles up to 180 degree.


For reference please cite the paper:
Barucci, Andrea, Giulia Ciacci, Pietro Liò, Tiago Azevedo, Andrea Di Cencio, Marco Merella, Giovanni Bianucci, Giulia Bosio, Simone Casati, and Alberto Collareta. "Artificial Intelligence-powered fossil shark tooth identification: Unleashing the potential of Convolutional Neural Networks." arXiv preprint arXiv:2405.04189 (2024).

https://arxiv.org/abs/2405.04189


Another paper is going to be published.


###################################################################################################################
DATASET

Some images used duting the training and test of the CNNs described in our works can be found in this repository.
Images were splitted in subfolders, were you can find the following species/taxa:
- Alopias
- Carcharhinus
- Carcharias Taurus
- Carcharodon Carcharias
- Chlamydselachus Lawleyi
- Cosmopolitodus hastalis
- Echinorhinus
- Galeocerdo
- Hexanchus griseus
- Isurus oxyrinchus
- Notorynchus lawleyi
- Odontaspis ferox
- Prionace glauca
- Squatina




Please consider that in order to train our networks we performed data pre-precessing, removing the background from the images and uniforming their size.
In this repository you can then find some images belonging to our dataset, which was developed thanks to the pictures taken from the GAMPS collection.
GAMPS is located in Scandicci (Firenze, Italy) and it has an extraordinary collection of the tuscany pliocene, in particular part of the collection is devoted to sharks.
Here you can find probably the largest collection in the world of Chlamydoselachus lawleyi teeth (https://it.wikipedia.org/wiki/Chlamydoselachus_lawleyi).

Here the link to the collection:
https://www.gamps.org

A special thanks to A. M. Addabbo, S. Taruffi and to all the students from the “Istituto di Istruzione Superiore Tecnica e Liceale Russell Newton” (Scandicci, Italy), who supported the G.A.M.P.S. dataset creation.

#########################################################################################################################################################################
If you are considerring to use our dataset please add the citation and the acknolodgments to the GAMPS.
Please consider to inform the GAMPS and the authors of this study that you are using the dataset.

For more details please contact the authors of the paper, in particular a.barucci@ifac.cnr.it
