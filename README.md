# Pothole Detection Project

## Overview
This project explores various methods for pothole detection using convolutional neural networks (CNNs). We evaluate the performance of three different models: CNN with Fully Connected Layer Model, CNN with Global Average Pooling Model, and YOLO v4. The aim is to find an efficient and accurate method for detecting potholes in road images.

## Table of Contents
- Overview
- Conclusion
- Installation
- Usage
- Dataset
- Models
- Results
- Contributing
- License

## Conclusion
we developed innovative methods for pothole detection using three different models: CNN with Fully Connected Layer Model, CNN with Global Average Pooling Model, and YOLO v4. We collected a substantial amount of data containing images of potholes under various conditions and weather. After implementing augmentation techniques on the data, all three models were trained and their accuracy was evaluated. The results indicate the following accuracies:
- CNN VGG16 with Fully Connected Layer Model: 94.07%
- CNN VGG16 with Global Average Pooling Model: 93%
- YOLO v4: 92%
A comparison between the convolutional neural model and YOLO v4 was conducted, showing that the images were correctly identified with the best accuracy using one of the pre-trained convolutional neural networks.

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/your_username/pothole-detection.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```
   jupyter notebook pothole_detection.ipynb
   ```
2. Follow the instructions in the notebook to run and evaluate the models.

## Dataset
The dataset used for training and testing the models contains images of potholes under various conditions and weather. Due to copyright restrictions, the dataset is not included in this repository. However, you can find similar datasets online or collect your own.

## Models
1. CNN with Fully Connected Layer Model
2. CNN with Global Average Pooling Model
3. YOLO v4

**Results**
After training the models, the following accuracies were achieved:
- CNN VGG16 with Fully Connected Layer Model: 94.07%
- CNN VGG16 with Global Average Pooling Model: 93%
- YOLO v4: 92%

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```