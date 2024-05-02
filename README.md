# objectDetection
Object Detection using supervision and yolo v8

# create a virtual environment
python3.8 -m venv ob_env
source ob_env/bin/activate

# install all the packages from the requirement text file
pip install -r requirement.txt

# Run the following command to detect the prediction
yolo detect predict model=yolov8l.pt source=0 show=true

