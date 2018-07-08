# Chitra ma k chha? - What's in the picture?
A very basic object detection system that recognizes everyday objects in the picture.

## How to install?
Create a virtual environment. <br>
```
python3 -m venv image-detection
cd image-detection
source bin/activate
````
Go back to project root and
```
pip3 install -r requirements.txt
```
Go to src folder
```
cd src
```
Download this file: https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5<br>
Place the file inside the 'src' folder<br>
Copy and paste any jpg image you'd like to detect (inside the 'src' folder) and rename it to 'image.jpg'<br>
Run
```
python3 detection.py
```

