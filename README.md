# Visual Novel Transcription from Video Files

## Overview
This project uses Optical Character Recognition (OCR) to extract text from frames of a visual novel gameplay video. The extracted text is then written to an HTML file. The project is designed to handle videos where many frames are identical, and it includes functionality to prevent the same frame from being processed multiple times.

## Dependencies
- OpenCV
- PyTesseract
- BeautifulSoup
- NumPy

## Setup
1. Install the required dependencies:

```bash
pip install opencv-python pytesseract beautifulsoup4 numpy
```

2. Download and install Tesseract OCR. Add the Tesseract path to your system’s PATH variable.

3. Download the necessary language data for Tesseract and place it in the `tessdata` directory where you installed Tesseract.

## Note
This script assumes that the text boxes are always in the same positions in the video frame.

## Example
![2024-03-03 15_35_08](https://github.com/girubato/video-text-extraction/assets/76228466/28ad079e-8269-448b-8f74-49f1696a121d)
