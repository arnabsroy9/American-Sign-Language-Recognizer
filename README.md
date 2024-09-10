# American Sign Language Recognizer (ASLR)
American Sign Language Recognizer is a system for sign language recognition. 

## Installation 

Clone repo and install required dependencies.

```

git clone https://github.com/arnabsroy9/American-Sign-Language-Recognizer.git
cd American-Sign-Language-Recognizer
pip install -r requirements.txt

```

Clone the repository from [ultralytics](https://github.com/ultralytics/yolov5). 

Copy aslr.pt from American-Sign-Language-Recognizer/model_weight and paste to yolov5

### You're ready to go...

## Inference 

Open terminal in yolov5 and execute: 
```
python detect.py --weights aslr.pt --source 0
```
## Output preview
![Output Preview](./assets/output.jpg)
