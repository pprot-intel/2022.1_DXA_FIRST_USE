# ONNX Inference - Style transfer (Pointilism)

## Tasks

### Find out more about OpenVINO Toolkit
Try to get a general idea about OpenVINO:
- what are example use cases
- where can you learn how to use it
- where can you download it from

### Installation
When you're done exploring, we'll move to installation. Go to https://pypi.org/project/openvino-dev/ and follow the installation instructions 2022.1 release

Next, use OpenVINO to run inference on [Pointilism-9.onnx](https://media.githubusercontent.com/media/onnx/models/main/vision/style_transfer/fast_neural_style/model/pointilism-9.onnx) model, using example [coco_square.jpg](https://raw.githubusercontent.com/openvinotoolkit/openvino_notebooks/main/notebooks/212-onnx-style-transfer/data/coco_square.jpg) image as input for the model

**Note**: if you use Conda, run PIP command with Anaconda Prompt. On Windows, you might need to add [OpenVINO library to your PATH]( https://github.com/openvinotoolkit/openvino_notebooks/wiki/Conda#step-6-conda-add-the-openvino-library-to-your-path)
 
**Goal:**
- load and compile model with OpenVINO
- run inference with example image
- display inference results as a new, style-transfered image

### Model and Image

- Fast Neural Style Transfer ONNX model repository: https://github.com/onnx/models/tree/main/vision/style_transfer/fast_neural_style
- Pointilism model: https://media.githubusercontent.com/media/onnx/models/main/vision/style_transfer/fast_neural_style/model/pointilism-9.onnx
- Image: https://raw.githubusercontent.com/openvinotoolkit/openvino_notebooks/main/notebooks/212-onnx-style-transfer/data/coco_square.jpg

