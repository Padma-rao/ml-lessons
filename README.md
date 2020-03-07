# Introductory lessons to deep learning for medical imaging by [MD.ai](https://www.md.ai)

The following are several Jupyter notebooks covering the basics of training deep learning models for medical imaging using data from <span>MD.ai</span>. They demonstrate how to download and parse annotation data from <span>MD.ai</span>, as well as train and evaluate different deep learning models for classification, segmentation, and object detection problems. The notebooks can be run on Google Colab with GPU (see instruction below).

| # | Name  | GitHub  | <span>MD.ai</span>  | Colab |
|---|---|---|---|---|
| 1  | Classification of chest vs. adominal X-rays using TensorFlow/Keras | [Link](https://github.com/mdai/ml-lessons/blob/master/lesson1-xray-images-classification.ipynb) | [Link](https://public.md.ai/annotator/project/PVq9raBJ) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdai/ml-lessons/blob/master/lesson1-xray-images-classification.ipynb) |
| 2  | Lung X-Rays Semantic Segmentation using U-Nets | [Link](https://github.com/mdai/ml-lessons/blob/master/lesson2-lung-xrays-segmentation.ipynb) | [Link](https://public.md.ai/annotator/project/aGq4k6NW) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdai/ml-lessons/blob/master/lesson2-lung-xrays-segmentation.ipynb) |
| 3a | RSNA Pneumonia detection using Kaggle data format | [Link](https://github.com/mdai/ml-lessons/blob/master/lesson3-rsna-pneumonia-detection-kaggle.ipynb) | [Link](https://public.md.ai/annotator/project/LxR6zdR2) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdai/ml-lessons/blob/master/lesson3-rsna-pneumonia-detection-kaggle.ipynb) |
| 3b | RSNA Pneumonia detection using the <span>MD.ai</span> python client library | [Link](https://github.com/mdai/ml-lessons/blob/master/lesson3-rsna-pneumonia-detection-mdai-client-lib.ipynb) | [Link](https://public.md.ai/annotator/project/LxR6zdR2) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdai/ml-lessons/blob/master/lesson3-rsna-pneumonia-detection-mdai-client-lib.ipynb) |

*Note that the mdai client requires an access token, which authenticates you as the user. To create a new token or select an existing token, to go a specific MD.ai domain (e.g., public.md.ai), register, then navigate to the "Personal Access Tokens" tab on your user settings page to create and obtain your access token.*

## <span>MD.ai</span> Annotator

<span>MD.ai</span> annotator is a web-based application to store, view, and collaboratively annotate medical images (e.g, DICOM) in the cloud. The <span>MD.ai</span> python client library can be used to download images and annotations, prepare the datasets, and then be used to train and evaluate deep learning models. Further documentation and videos are available at https://docs.md.ai/.

- <span>MD.ai</span> Annotator example project URL: https://public.md.ai/annotator/project/aGq4k6NW/workspace
- <span>MD.ai</span> python client libray URL: https://github.com/mdai/mdai-client-py

![MD.ai Annotator](https://docs.md.ai/img/annotator-homepage.png)

## Running Jupyter notebooks on Google Colab

It’s easy to run a Jupyter notebook on Google Colab with free GPU use within time-limited sessions. For example, add the Github Jupyter notebook path to https://colab.research.google.com/notebook:

Select the "GITHUB" tab, and add the Lesson 1 URL: https://github.com/mdai/ml-lessons/blob/master/lesson1-xray-images-classification.ipynb

To use the GPU, in the notebook menu, go to Runtime -> Change runtime type -> switch to Python 3, and turn on GPU. See more Colab tips and tricks [here](https://www.kdnuggets.com/2018/02/essential-google-colaboratory-tips-tricks.html).

---

&copy; 2020 MD.ai, Inc.
Licensed under the Apache License, Version 2.0
