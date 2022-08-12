# Cleansea CNN Model (Read below)

Our CNN model for the Cleansea Mobile App. It classifies four of the most common and critical types of trash, debris, etc. from the TACO Custom dataset, which we adapted/sourced from the original Taco dataset. This original Taco dataset was created for object detection, so we modified it to be used for classification. See original Taco dataset (1.6K images) here: http://tacodataset.org/ <br>

Our Cleansea Model was trained and optimized to reach >95% accuracy consistently on Taco Custom 1.0 and ~90% accuracy consistently on Taco Custom 2.0 (bigger dataset). Of course, due to the time-consuming work of relabeling data and adding augmentations to increase dataset size, our custom Taco datasets are smaller than the original Taco dataset.

*Model and adapted dataset were developed by Julia Huang and mobile app was developed by Arushi Gupta from Team cloud9 - Deep Learning Track.

# What's In This Repository:
<li> Materials Used to Develop Dataset + Model </li>
<li> Our Dataset We Used (see below) </li>
<li> Model Architecture </li>
<li> Model Classification Results </li>
<li> Model Code (3 Google Colab Notebook versions in surreal_version folder) :)</li>
<li> Saved Model in .h5 format (only 500K parameters!) - lightweight enough for easy mobile app deployment, such as using Flutter </li>
<li> Cleansea App User Journey Diagram  </li>
<li> Machine Learning Process Flow Diagram  </li>

# Our Google Colab Notebook
includes process from dataset loading, processing, to model training (also linked in this github repo)
https://colab.research.google.com/drive/14dzlJOXXuSqTsd5M4WJco5ubBpb7OxO_?usp=sharing

# About Our Taco Custom Dataset (version 1.0 and 2.0)
TACO Custom dataset in Google Drive: https://drive.google.com/drive/folders/1MMX_i6e6GTondUnDtLiPjdbqegihMAVU?usp=sharing <br>
TACO Custom dataset published on Kaggle: https://www.kaggle.com/datasets/julesh7/taco-dataset-revised-230-imgs <br>
TACO Custom 2.0 dataset in Google Drive: [https://drive.google.com/drive/folders/1MMX_i6e6GTondUnDtLiPjdbqegihMAVU?usp=sharing](https://drive.google.com/drive/folders/1tk_5IRaRoEP2BY9vrjVV9yZKpxQ3w9jL?usp=sharing) <br>
TACO Custom 2.0 dataset published on Kaggle: https://www.kaggle.com/datasets/julesh7/taco-dataset-revised-230-imgs <br>


To create these 2 datasets, I labeled images of 4 important debris types and placed original TACO dataset files into four folders - cans, bottles, plastics, containers. Images were resized and rescaled to match our tasks. In addition, we performed data cleaning due to noisy images and images that contained two classes.
Note: there are not many publicly available ocean debris datasets - the most comprehensive one we could find was TACO.

# Canva Slides Presentation for Cleansea ML Mobile App
https://www.canva.com/design/DAFIGOsvodM/QWxmbrADZLBg_JPwwZjQmg/view?utm_content=DAFIGOsvodM&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
