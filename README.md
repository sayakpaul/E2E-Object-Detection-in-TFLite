# E2E-Object-Detection-in-TFLite
This repository shows how to train a custom detection model with the [TFOD API](https://github.com/tensorflow/models/tree/master/research/object_detection) (TF2), optimize it with TFLite, and perform inference with the optimized model.

<div align="center"><img src="https://i.ibb.co/ZXW6N1q/image.png"></img></div>

## About the notebooks
- `Training_a_pets_detector_model_within_minutes_with_TFOD_API.ipynb`: Shows how to train a custom object detection model on the Pets dataset (non-eager mode).
- `Running_inference_with_a_custom_TFOD_API_model.ipynb`: Shows how to export a `SavedModel` graph from the trained checkpoint files, and run inference. 
- `Object_Detection_in_TFLite.ipynb`: Shows how to quantize the original model, generate a TFLite model, and run inference. 

## TFLite model files
Available [here](https://github.com/sayakpaul/E2E-Object-Detection-in-TFLite/releases/tag/v0.1.0) (currently available in dynamic-range only).
