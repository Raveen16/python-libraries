## Downloading Python in Local Environment

1. Download the Python 3.8.0 x86-64 executable installer file from https://www.python.org/downloads/release/python-380
2. Run the exe file that was donwloaded `python-3.8.0.exe` install Python.
3. Add Python 3.8 to path and click on customize installation.
4. Select all optional features.
5. Select first 5 options from the advance options screen.
6. Click on install.
7. Click yes and provide permission to install python.


## Setting Up a Python Virtual Environment

1. Open a command prompt or terminal window in current working directory and create a new virtual environment with the command `python -m venv <name_of_the_environment>`
2. To activate the virtual environment command to be used on Windows, run the command `<name_of_the_environment>\Scripts\activate`
3. To activate the virtual environment command to be used on Mac, run the command `source <name_of_the_environment>/bin/activate`

## Installing Required Packages

Use the following commands to install the necessary packages:

- **Watchdog:** `pip install watchdog`
- **Observer:** `pip install observer`
- **Events:** `pip install events`
- **OPENCV:** `pip3 install opencv-python`
- **Numpy:** `pip3 install numpy`
- **Object Detection Extension:** `pip install opencv-contrib-python==3.4.13.47` or `pip install opencv-contrib-python`
- **Mediapipe:** `pip install mediapipe`
- **Virtual Keyboard and Mouse:** `pip install pynput`  and `pip install pyautogui` 
- **Pandas:** `pip install pandas`
- **Flask:** `pip install flask`
- **NLTK:** `pip install nltk`


- **Tensorflow(enable long path in registory editor if facing any issues for tensorflow):** `pip install tensorflow==2.5.0`  or `pip install tensorflow` or `or pip install tensorflow_cpu` or `pip3 install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.0.0-py3-none-any.whl` or `python3 -m pip install --upgrade tensorflow`
