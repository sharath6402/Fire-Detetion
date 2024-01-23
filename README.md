# Fire-Detetion using yolov8

# Fire Detection using YOLOv8

## Overview

This repository contains the code and resources for detecting fires in images and videos using YOLOv8, a state-of-the-art object detection algorithm. The project aims to provide an accurate and efficient solution for identifying fire incidents in various scenarios.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Training](#training)
- [Inference](#inference)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

To set up the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/sharath6402/fire-detection-yolov.git
   cd fire-detection-yolov8
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained YOLOv8 weights:

   ```bash
   wget https://github.com/ultralytics/yolov5/releases/download/v5.0/yolov5s.pt -O weights/yolov5s.pt
   ```

## Usage

Describe how to use the project. Include any configuration settings, command-line arguments, or environment variables that users need to be aware of.

```bash
python detect_fire.py --image input.jpg
```

## Dataset

Provide information about the dataset used for training and testing the model. Include details such as the source of the dataset, number of images, and any preprocessing steps applied.

## Training

If users want to train the model on their own dataset, provide instructions on how to do so. Include information about creating a custom configuration file, data augmentation, and training command.

```bash
python train.py --config custom_config.yaml
```

## Inference

Explain how to perform inference on new images or videos using the trained model.

```bash
python detect_fire.py --image input.jpg --weights trained_model.pt
```

## Results

Share the performance metrics, evaluation results, or visualizations to showcase the effectiveness of the model. Include example images with bounding boxes around detected fires.

## Contributing

Provide guidelines for contributors. Explain how they can report issues, submit feature requests, or contribute to the development of the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Mention and thank any individuals, organizations, or projects that have contributed to or inspired your work.
```

Remember to replace placeholders such as `your-username` with your actual GitHub username, and update the commands and details based on your specific project structure and requirements.
