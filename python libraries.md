Instructions for Setting Up a Python Virtual Environment
Download the Python 3.8.0 executable file from https://www.python.org/downloads/release/python-380/.
Open a command prompt or terminal window and navigate to the directory where you downloaded the file.
Run the command python-3.8.0.exe and follow the instructions to install Python.
Open a new command prompt or terminal window and create a new virtual environment with the command python -m venv <name_of_the_environment>.
To activate the virtual environment command to be used on Windows, run the command <name_of_the_environment>\Scripts\activate.
To activate the virtual environment command to be used on Mac, run the command source <name_of_the_environment>/bin/activate.
Installing Required Libraries
To install the required libraries for your project, activate your virtual environment and run the following commands:

OpenCV: pip3 install opencv-python
NumPy: pip3 install numpy
Object Detection Extension: pip install opencv-contrib-python==3.4.13.47 or pip install opencv-contrib-python
Mediapipe: pip install mediapipe
Virtual Keyboard and Mouse: pip install pynput and pip install pyautogui
Tensorflow: pip install tensorflow==2.5.0 or pip install tensorflow or pip install tensorflow_cpu. If you face any issues with long path names on Windows, enable long path in registry editor.
Pandas: pip install pandas
Flask: pip install flask
NLTK: pip install nltk
Upgrading TensorFlow
To upgrade TensorFlow, activate your virtual environment and run one of the following commands:

pip3 install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.0.0-py3-none-any.whl
python3 -m pip install --upgrade tensorflow
