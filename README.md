
# 🤖 Hand Gesture Recognition using Machine Learning

This project demonstrates hand gesture recognition using Machine Learning and image processing. It enables collecting gesture images, training a model, and recognizing gestures in real-time using a webcam.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `app.py` | Launches the real-time gesture recognition application. |
| `collect-data.py` | Captures hand gesture images from webcam for dataset creation. |
| `image_processing.py` | Contains functions for preprocessing and enhancing gesture images. |
| `preprocessing.py` | Performs additional preprocessing steps before training. |
| `train.py` | Trains a machine learning model on the collected gesture dataset. |
| `requirements_pip.txt` | Lists dependencies to install via `pip`. |
| `requiremnets_conda.txt` | Lists dependencies for `conda` environment setup. |
| `signs.png` | Reference image for the different hand gesture classes. |
| `README.md` | Project documentation file. |

---

## 🚀 Features

- Capture and label hand gestures from a webcam.
- Preprocess and clean gesture data.
- Train a custom machine learning model.
- Real-time gesture detection and classification.



## 📦 Installation

1. **Clone the Repository:**
  
   git clone https://github.com/your-username/Hand-Gesture-Recognition-using-ML.git
   cd Hand-Gesture-Recognition-using-ML


2. **Create and Activate Virtual Environment:**

   Using pip:

  
   pip install -r requirements_pip.txt


   Or using conda:

  
   conda create --name gesture_env --file requirements_conda.txt
   conda activate gesture_env




## 🧠 How to Use

1. **Collect Data:**

  
   python collect-data.py


2. **Preprocess Collected Images:**

  
   python preprocessing.py


3. **Train the Model:**

  
   python train.py


4. **Run Gesture Recognition:**

  
   python app.py





