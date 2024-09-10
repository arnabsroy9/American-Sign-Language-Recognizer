# American Sign Language Recognizer (ASLR)
isearch is for searching images that are similar or nearly similar to a query image or text. We use CLIP-japanese model, which we have quantized for efficiency. Our optimization has made it 30 times faster than the CLIP-japanese model. To store and manage the image embeddings, we use Qdrant as vector database.

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
