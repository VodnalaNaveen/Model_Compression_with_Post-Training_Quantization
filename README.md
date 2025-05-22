# Model_Compression_with_Post-Training_Quantization


This project demonstrates how to compress a trained Keras model using TensorFlow Lite post-training quantization. By converting weights and activations to lower precision (e.g., float16 or int8), it significantly reduces the model size and speeds up inference, especially on edge devices. This method balances compression and performance with minimal impact on model accuracy.

## What Can a Quantized Model (Compression) Do for Me?
  * Significantly reduces model size by converting weights and activations to lower precision (int8)
  * Speeds up model loading
  * Lower memory and power usage
  * Maintains high prediction accuracy

## Getting Started
### 1. Create an Environment
``` conda create -n compressed_model python==3.12 ```
### 2.Activate the Environment
``` conda activate compressed_model ```
### 3.Install Project Dependencies
``` pip install -r requirements.txt ```
## Run the code
```
python .\run1.py --weights_path "C:\Users\vodna\OneDrive\Desktop\QUANTIZATION\Elite28_PQT\normal.h5" --quantized_compressed_model_path 'C:\Users\vodna\OneDrive\Desktop\compresed_model'
```
#### Parser Arguments

 * --weights_path	         :-	Path of your original .h5 model
 * --quantized_compressed_model_path	:-	Folder path to save quantized_compressed model
