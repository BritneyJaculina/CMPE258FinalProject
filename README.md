# CMPE258_Wildlife_Animals
Android Studio Project app can be downloaded at the following link: https://drive.google.com/file/d/185E39ogpjtF-QCEN_I4ugOsQfOvCJHOh/view?usp=sharing

Requirements:
- Python 3.10
- IDE, ideally Visual Studio which was used for this project
- YOLO dependencies: pip install ultralytics on command line

To run the test script, download the subset folder and subset.ipynb from GitHub. Additionally, you will need to navigate to: https://drive.google.com/drive/folders/1aBJwrUWtbxX4z5XRAGC1bOragIZ-XrqQ?usp=sharing. Go to runs/detect/round3train and download the folder. This will contain the best trained model. Continue to extract the folders and change the paths according to your machine in the subset.ipynb script. The script will run the model through the subset of images and produce annotated images in subset/results. It will also output the name of the animal, confidence score, and determine if the animal is harmful or harmless in the notebook.
