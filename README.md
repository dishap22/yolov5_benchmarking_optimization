# YOLOv5 Benchmarking and Optimization

## Running

First, create a virtual environment

`python venv -m venv`

Next, clone the YOLOv5 repo and install dependencies:

```plaintext
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
```

Now, download the COCO 128 mini dataset

```plaintext
cd ..
mkdir -p datasets && cd datasets
wget https://ultralytics.com/assets/coco128.zip
unzip coco128.zip
```

Now, run install the Jupyter notebook dependencies

```plaintext
cd ..
pip install -r  requirements.txt
```

Now you can run the Jupyter notebook.
