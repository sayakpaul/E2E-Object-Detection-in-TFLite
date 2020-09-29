## About the notebooks
- `Fruits_Detection_Data_Prep.ipynb`: Shows how to prepare a object detection dataset in order to train it with the TFOD API in non-eager mode.
- `Training_MobileDet_Custom_Dataset.ipynb`: Shows how to fine-tune a MobileDet model to detect localize and detect fruits. It also shows how to optimize the fine-tuned model with TensorFlow Lite and run inference with the optimized model. 

Please note that the dataset used here is faulty. So, expect some discrepencies in the inference results. 

You are encouraged to follow this tutorial ([Optimizing MobileDet for Mobile Deployments](https://sayak.dev/mobiledet-optimization/)) that shows how to effectively convert MobileDet models for mobile deployments. 
