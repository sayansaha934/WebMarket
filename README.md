
## Analysis of images of retail shelf displays and detection the object on shelf



https://user-images.githubusercontent.com/87168504/184640588-4cd36942-c9bc-4f41-bf53-f64e9d885e57.mp4

## Dataset
https://www.kaggle.com/datasets/manikchitralwar/webmarket-dataset

## How to use this repo
- `git clone https://github.com/sayansaha934/WebMarket.git`
-  change directory to `WebMarket`
- `conda create -n WebMarket python==3.6.9`
- `conda activate WebMarket`
- `pip install -r requirements.txt`
- install pytorch
- Run `python detect.py --weights weights/best.pt --source images --img 416 --conf 0.4`, output images will be saved in `runs/detect/exp`
- Run `Training.ipynb` for training and keep the model weight (`.pt` file) inside `weights`

We have used [roboflow](https://roboflow.com/) to create labels
