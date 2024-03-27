# sign-language-detector-python

Sign language detector with Python, OpenCV and Mediapipe !

## Installation 🛠

- clone the repository: `git clone https://github.com/Mayank9001/Sign-Language-Detection`
- run `pip install -r requirements.txt` in cmd to install the requirements
- Execute files in this order :
  - `collect_imgs.py` (to collect images of hand signs)
  - `create_dataset.py` (to create a dataset on which our model will train and test)
  - `train_classifier.py` (to train the classifier using Random Forrest Classifier)
  - `inference_classifier.py` (for real time inference using trained classifier)

Note: Before running any file make sure you have installed all packages mentioned in requirement.
