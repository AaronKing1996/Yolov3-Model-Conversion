# Yolov3.onnx To Yolov3.plan

**Table Of Contents**
- [Description](#description)
- [Prerequisites](#prerequisites)
- [Usage](#Usage)
- [License](#license)

## Description
This demo implements the conversion from yolov3.weights to yolov3.onnx, and the conversion from yolov3.onnx to yolov3.plan.

## Prerequisites
1. Install TensorRT-5.1.5.0

## Usage
- cd python
	- `python3 onnx_to_tensorrt.py`

- cd ../bin
	- `./trtexec --onnx=../models/yolov3.onnx --saveEngine=../models/yolov3.plan`

# License

For terms and conditions for use, reproduction, and distribution, see the [TensorRT Software License Agreement](https://docs.nvidia.com/deeplearning/sdk/tensorrt-sla/index.html) documentation.
