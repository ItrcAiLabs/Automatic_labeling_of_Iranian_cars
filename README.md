# Car Detection and Labeling

## Overview
This project automates the detection and labeling of cars in images using YOLO models. It extracts key attributes such as car color, model, and license plate details, then saves the information in an XML file.

## Features
- **Car Color Detection** using YOLO.
- **Car Model and Bounding Box Detection** using YOLO.
- **License Plate Recognition and Parsing** using YOLO.
- **XML Output** containing detected details and coordinates.

## Requirements
- Python 3.x
- Required libraries (install using `pip install -r requirements.txt`)

## Usage
1. git clone :

```bash
git clone https://github.com/ItrcAiLabs/Automatic_labeling_of_Iranian_cars
cd Automatic_labeling_of_Iranian_cars
```

2. Run the script:
   ```bash
   python automatic_labeling.py
   ```

## Output
Each processed image generates an XML file with details like:
- Car model
- Car color
- License plate details (parsed)
- Bounding box coordinates for the car and plate



## License
This project is for personal and research use.

