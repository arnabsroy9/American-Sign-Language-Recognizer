# American Sign Language Recognizer (ASLR)
American Sign Language Recognizer is a system designed for recognizing American Sign Language gestures. 

## Installation 

Follow these steps to set up and install the ASLR system:

```

git clone https://github.com/arnabsroy9/American-Sign-Language-Recognizer.git
cd American-Sign-Language-Recognizer
pip install -r requirements.txt

```

Clone the repository from [ultralytics](https://github.com/ultralytics/yolov5). 

Copy aslr.pt from American-Sign-Language-Recognizer/model_weight and paste it into the yolov5 directory.

### You're ready to go...

## Inference 

To run the ASLR system, open a terminal in the yolov5 directory and execute the following command:
```
python detect.py --weights aslr.pt --source 0
```
## Output preview
![Output Preview](./assets/output.jpg)
