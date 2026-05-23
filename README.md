# Badminton-Analysis using Computer Vision

## Introduction
This project is a real-time badminton tracking system built using computer vision and deep learning techniques. It processes live or recorded single-camera footage to detect and track gameplay dynamics, generating accurate match analytics and performance insights for players and coaching analysis.",

## Result

<p align="center">
  <img src="outputvideo.gif" alt="Demo video">
</p>

<p align="center"><em>Result</em></p> 

## Installation
1. Clone this repository:
    ```
    git clone ~
    cd ~
    ```

2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Download pre-trained models:
    - Download the necessary pre-trained models for player and shuttlecock detection and place them in the `models/` directory.

## Usage
1. Prepare your dataset:
    - Ensure your dataset contains videos or images of badminton matches with annotated player and shuttlecock positions.
    - Organize the dataset into appropriate directories, such as 'train' and 'val' for training and validation data.

2. Train the model:
    - Modify the training configuration in the train.py file according to your dataset.

3. Analyze new videos or images:
    - Use the trained model to detect players and shuttlecocks in badminton matches

4. Result

![Result](train/player_output/models/results.png)
![Result](train/player_output/models/confusion_matrix_normalized.png)
![Result](train/shuttle_output/models/results.png)
![Result](train/shuttle_output/models/confusion_matrix_normalized.png)

## Dataset Preparation
Ensure your dataset contains diverse videos or images of badminton matches, depicting various players, courts, and lighting conditions. Annotated bounding boxes should accurately enclose the players and shuttlecock in the frames.

## Model Configuration
Experiment with different model configurations and adjust parameters such as input image size, batch size, and training epochs to optimize performance based on your specific requirements and computational resources.

## Contributing
Contributions to this project are welcome. Feel free to submit pull requests for bug fixes, enhancements, or additional features.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

