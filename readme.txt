*caffe framework should be installed and compiled first in the same folder as this repo will be installed in.
*activate the caffe env
*to convert yolov3 to caffe model run: 
python yolov3_darknet2caffe.py full_800.cfg full_800.weights full_800.prototxt full_800.caffemodel
*if you had any issues with protobuf lib consider installing this version: pip install protobuf==3.0.0-alpha-3
