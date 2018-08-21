# Chitra ma k chha? - What's in the picture?
A minimal object detection system that recognizes everyday objects in the picture.

## How to install?

Clone the repo
```
git clone https://github.com/akashadhikari/chitra-ma-k-chha.git
cd chitra-ma-k-chha
```

Create a virtual environment. <br>
```
python3 -m venv detection
source detection/bin/activate
````
Install the requirements
```
pip3 install -r requirements.txt
```
Go to src folder
```
cd src
```
Download this file: https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5<br>
Place the file inside the 'src' folder<br>
Copy and paste any jpg image you'd like to detect (inside the 'src' folder) and rename it to '<b>image.jpg</b>'<br>
Run
```
python3 detection.py
```
