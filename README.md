# GENDER-DETECTION-using-FLASK
## Description:
Detect face in an image and to predict the gender of the person using a deep learning-based gender detection model.
## Algorithm Used
Deep Learning (Unsupervised)
## Python packages 
```python
import glob
import shutil
import uuid
import deepface.DeepFace
from flask import Flask, json, request, jsonify
import os
import urllib.request
from deepface import DeepFace
from werkzeug.utils import secure_filename
```
## How to install and run the package
### step 1: Install latest version of Python
Recommended version 3.10.0 or above.
### Step 2: Make sure pip is linked to Python(pip -V will display the info)
### Step 3: Install PyCharmIDE
### Step 4: Install the deepface package
![image](https://user-images.githubusercontent.com/80459102/193560518-efc317e4-7237-4c0b-b102-f74a5187aef9.png)
### Step 5: Similarly install other packages.
## Working
### Step 1: Run the flask project. 
![image](https://user-images.githubusercontent.com/80459102/193560592-af23eeb9-41fa-4d51-af7d-3f1cf0388426.png)
### Step 2: Open Postman
### Step 3: Add new request using Post method.
### Step 4: Enter request URL http://127.0.0.1:5000/upload?
### Step 5: Select [Body]-->[form-data]
### Step 6: Enter the key name: files[] 
### Step 7: Select the required image file 
### Step 8: Send the request. 
![image](https://user-images.githubusercontent.com/80459102/193560660-831cf698-4a7b-4f95-ba26-5aeac7c6fcc0.png)
## Output 
![image](https://user-images.githubusercontent.com/80459102/193560703-2b639b5b-9c00-44b8-8bda-925e5e7f3259.png)
## Credits
Sincere Thanks to [Sefik Ilkin Serengil](https://github.com/serengil) for deepface package.

