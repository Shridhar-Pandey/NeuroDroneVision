# NeuroDroneVision

An AI-powered system utilizing neural network architectures for precise and real-time drone detection and tracking.

## Description
**Drone Detection System**

### Output Video with Detections
You can check the sample output video with detections [here](https://github.com/Shridhar-Pandey/NeuroDroneVision/blob/main/output_video_with_detections.mp4).

![Drone Detection](https://github.com/Shridhar-Pandey/NeuroDroneVision/blob/main/Output%20photos/Readme_output.png)![Drone Detection](https://github.com/Shridhar-Pandey/NeuroDroneVision/blob/main/Output%20photos/output_3.png)


### Importing Libraries
- Imported essential libraries such as `TensorFlow`, `Keras`, and `scikit-learn` for building, training, and evaluating the machine learning model.
- Imported `OpenCV` and `PIL` for image processing tasks.
- Used `matplotlib` and `seaborn` for data visualization and plotting.

### Setup Environment:
- `%matplotlib inline` is used to display plots inline in the Notebook.
- Suppressed warnings using `warnings.filterwarnings('ignore')` to keep the output clean.

### Loading and Pre-processing the Data
- Used `glob` to find all `.jpg` images in the specified directory and loaded them using `PIL`.
- Converted images to RGB format and resized them to 256x256 pixels for consistent input size.
- Parsed corresponding annotation files (`.txt`) for each image to extract bounding box coordinates.

### Visualize Training Images:
- Displayed the first 15 training images in a 5x5 grid using `matplotlib` to verify correct loading and preprocessing.
- Printed the total number of loaded images to confirm the dataset size.

### Data Preparation:
- Converted image data and annotations to numpy arrays and normalized pixel values.
- Used `train_test_split` to split the dataset into training (90%) and testing (10%) subsets.

### Model Architecture:
- Implemented YOLO and VGG16 models for drone detection.

## Installation
To install the necessary dependencies, run:


## Usage
1. Clone the repository:
    ```
    git clone https://github.com/your-username/NeuroDroneVision.git
    ```
2. Navigate to the project directory:
    ```
    cd NeuroDroneVision
    ```
3. Run the main script:
    ```
    python main.py
    ```

## Results
The system uses neural network models to accurately detect drones in various environments and scenarios, providing real-time feedback and alerts.

## Contributing
Feel free to fork this repository, make your changes, and submit a pull request.
![Drone Detection](https://github.com/Shridhar-Pandey/NeuroDroneVision/blob/main/Output%20photos/output_2.png)
## License
This project is licensed under the MIT License.
