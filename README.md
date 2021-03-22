# Medical-4D-Image-Analysis
## Visulization of the MRI 4D images of Prostate Glands affected by Prostate Cancer.

* Utilized the publically available data on the Prostate Cancer MRI scans provided by the [Medical Segmentation Decathlon Challenge](https://decathlon-10.grand-challenge.org/).
* MRI images have been extracted and visualized using the [Nibabel](https://nipy.org/nibabel/) library of the python, which is used in Neuroimaging.
* Dataset is differentiated into categorical features and labels using the Keras library from the TensorFlow module.
* The 4D images are visualized using three planes - Coronal Plane, Transverse Plane and Saggital Plane which are denoted in the notebook as Planes - 1,2, and 3 respectively.

![human-anatomy-planes](https://user-images.githubusercontent.com/58086070/111982555-1eb78700-8b2f-11eb-88d5-60e35c2597ff.jpg)

* Images visualized are color coded for specific cancer detection in the planes.
* Random sub volumes also specified for a more accurately visualized patch of the Cancer effected Prostate gland.
