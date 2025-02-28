# FACE DETECTION AND ANALYSIS USING DEEPFACE 
# Face Insight

## Overview
**Face Insight** is a Python-based AI Model created for extracting and analyzing faces from PDF documents. It converts PDFs to images, detects faces using MTCNN, and analyzes age, gender, and race using DeepFace. The extracted data is saved into a CSV file for further analysis.The input that was did to develop this model was adevertisements form various print magazines.
## Features
- 🖼️ Converts PDFs into images
- 🔍 Detects faces using MTCNN
- 🧑‍🤖 Analyzes age, gender, and race with DeepFace
- 📊 Saves extracted data into a CSV file
- ⚡ Ideal for advertisement analysis and AI-powered document processing

## Installation
To use Face Insight, install the required dependencies:
```sh
pip install opencv-python numpy pandas pdf2image deepface mtcnn pillow
```

## Usage
Run the script by specifying the folder containing PDFs:
```sh
python script.py
```

## CSV Output Format
The processed face data is stored in a CSV file with the following columns:
```
AD ID, Faces on Image, Age, Gender, Race, Image Path
```

### Sample CSV Data
```
AD_001, 2, 25, Man, Asian, output_faces/AD_001_1_face_0.jpg
AD_002, 1, 30, Woman, Caucasian, output_faces/AD_002_1_face_0.jpg
```
Here is an example of sample csv data.
![Image Alt](https://github.com/Littajosethottam/FaceAnalysis/blob/main/csv%20file.png?raw=true)
the code successfully detects multiple images and lists it in excel,easy for comparsion especially for large datsets.

## Contributing
Feel free to fork this repository, submit issues, or suggest improvements.



---
## Citations:

For Facial Recognition:

@article{serengil2024lightface,
  title     = {A Benchmark of Facial Recognition Pipelines and Co-Usability Performances of Modules},
  author    = {Serengil, Sefik Ilkin and Ozpinar, Alper},
  journal   = {Journal of Information Technologies},
  volume    = {17},
  number    = {2},
  pages     = {95-107},
  year      = {2024},
  doi       = {10.17671/gazibtd.1399077},
  url       = {https://dergipark.org.tr/en/pub/gazibtd/issue/84331/1399077},
  publisher = {Gazi University}
}

@inproceedings{serengil2020lightface,
  title        = {LightFace: A Hybrid Deep Face Recognition Framework},
  author       = {Serengil, Sefik Ilkin and Ozpinar, Alper},
  booktitle    = {2020 Innovations in Intelligent Systems and Applications Conference (ASYU)},
  pages        = {23-27},
  year         = {2020},
  doi          = {10.1109/ASYU50717.2020.9259802},
  url          = {https://ieeexplore.ieee.org/document/9259802},
  organization = {IEEE}
}

For Facial Attribute Analysis:

@inproceedings{serengil2021lightface,
  title        = {HyperExtended LightFace: A Facial Attribute Analysis Framework},
  author       = {Serengil, Sefik Ilkin and Ozpinar, Alper},
  booktitle    = {2021 International Conference on Engineering and Emerging Technologies (ICEET)},
  pages        = {1-4},
  year         = {2021},
  doi          = {10.1109/ICEET53442.2021.9659697},
  url          = {https://ieeexplore.ieee.org/document/9659697},
  organization = {IEEE}
}


For OpenCV:
@article{opencv_library,
  author = {Bradski, Gary},
  title = {The OpenCV Library},
  year = {2000},
  journal

 
