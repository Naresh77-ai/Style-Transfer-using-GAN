## Problem Statement
Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. Imaging procedures in the medical field requires an expert radiologist’s opinion since interpreting them is not a simple binary process ( Normal or Abnormal). Even so, one radiologist may see something that another does not. This can lead to conflicting reports and make it difficult to effectively recommend treatment options to the patient. One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding. But to have access to different imaging is difficult and expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

## Objective
The objective of this project is to build a Generative adversarial model(modified U-Net) which can generate artificial MRI images of different contrast levels from existing MRI scans. Using GANs we will create T2 weighted images from T1 weighted MRI image and vice-versa.

## Data Understanding
The dataset consists of T1 and T2 MRI Images in two different folders "TrainT1" and "TrainT2" respectively and are not related in any way since we have an unpaired dataset.

## Pipeline
The Sequence of the Project:
- Importing Libraries
- Data Loading and Visualization
- Data Preprocessing
- Model Building
- Model Training
- Generating a GIF

## ✅ Final Insights & Conclusion

After training the GAN-based style transfer model for 300 epochs, the generated outputs show that the model successfully learned to translate images into the target style while preserving the core anatomical structure. The generated images retain key spatial patterns from the inputs (overall brain shape and major intensity regions) while adopting the target-domain texture/contrast characteristics—indicating stable convergence and effective feature mapping between the two domains.
