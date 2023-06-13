# Trafficsign_Detection_YoloV5

This repository contains a Python project that uses YOLO v5 to detect traffic signs in images and videos.

## Requirements

* Python 3.6+
* PyTorch 1.10+
* YOLO v5

## Installation

1. Clone this repository.
2. Install the required dependencies.


```
pip install -r requirements.txt
```

## Usage

To detect traffic signs in an image, run the following command:

```
python detect_traffic_signs.py <image_path>
```

To detect traffic signs in a video, run the following command:

```
python detect_traffic_signs.py <video_path>
```

The output of the script will be a list of detected traffic signs, along with their bounding boxes and confidence scores.


The output of the script is as follows:

```
[
  {
    "class": "stop",
    "confidence": 0.99,
    "bounding_box": [
      0.1, 0.1, 0.8, 0.8
    ]
  },
  {
    "class": "speed limit 30",
    "confidence": 0.95,
    "bounding_box": [
      0.2, 0.2, 0.6, 0.6
    ]
  }
]
```

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests.
