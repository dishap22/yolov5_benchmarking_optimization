# YOLOv5 Benchmarking and Optimization

## Running

Start off in the `yolov5_benchmarking_optimization` directory.

First, create a virtual environment

`conda create -n yolo-benchmark python=3.11` and activate it `conda activate yolo-benchmark`.

Next, clone the YOLOv5 repo and install dependencies:

```plaintext
git clone https://github.com/ultralytics/yolov5
cd yolov5
python -m pip install -r requirements.txt
```

Now, download the COCO 128 mini dataset

```plaintext
cd ..
mkdir -p datasets && cd datasets
wget https://ultralytics.com/assets/coco128.zip
unzip coco128.zip
```

Now, run install for the Jupyter notebook dependencies

```plaintext
cd ..
python -m pip install -r requirements.txt
```

Now you can run the Jupyter notebook.

File structure should look like this:

```plaintext
yolov5_benchmarking_optimization/
  |_ datasets/
  |_ yolov5/
  |_ benchmarking.ipynb
  |_ README.md
  |_ requirements.txt
```