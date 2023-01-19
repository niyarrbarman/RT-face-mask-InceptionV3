# Real-time Face Mask Detection

A deep learning model for real-time face mask detection using transfer learning on the InceptionV3 model pre-trained on the ImageNet dataset.

## Overview

The model is able to detect whether a person is wearing a face mask or not in real-time. The model has been trained on a dataset collected from [Kaggle](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset), and fine-tuned on the InceptionV3 model pre-trained on the ImageNet dataset.

## Requirements
<code></code>

## Usage

1. Clone the repository<br>
<code>git clone https://github.com/niyarrbarman/RT-face-mask-InceptionV3.git</code>
2. Install the required packages<br>
<code>pip3 install -r requirements.txt</code>
3. Run the script<br>
<code>python3 main.py</code>

The script will open up your webcam and display the live video feed with mask detection.

## Evaluation

The model has been trained and evaluated on a dataset of around 12k images, The model has achieved an accuracy of 94% on the validation set.

