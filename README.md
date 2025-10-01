# Emotion_AI

## step1 
Created Repo and Cloned to local. Next, template.py file contains file structure and setup.py save custom package. Also, will create virtual env specific for this project. Using commands,
```bash
python -m venv emotion
emotion\Scripts\activate
```

## step2
Via requirement.txt, will list all required packages for this project. Will execute and verify using commands,
```bash
pip install -r requirements.txt
pip list
```

## step3
Here we now ellaborated steps which we performed as a process on data.
### task 1
UNDERSTAND THE PROBLEM STATEMENT AND BUSINESS CASE : Two parts actually, Part 1 is to predict facial expression and part 2 is to predict key facial points.
### task 2
IMPORT LIBRARIES AND DATASETS 
### task 3
PERFORM IMAGE VISUALIZATION : Ploted images and corresponding faical points and verified on grid structure of images. 
### task 4
PERFORM IMAGE AUGMENTATION : First, we flip the images as a part of image augmentation and concatenated in data. Secondly, we incresed briteness of images at different levels to tain model and added those pixel data to original.