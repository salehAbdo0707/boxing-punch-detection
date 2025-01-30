# Boxing Punch Detection

## Overview
This project uses computer vision and deep learning to detect and classify punches in a boxing match. The model processes video frames, identifies punches, and classifies them into different categories.

## Features
- Detects punches in real-time or from pre-recorded videos.
- Classifies different types of punches (e.g., jab, hook, uppercut).
- Uses YOLO for object detection and a custom model for punch classification.
- Can be integrated into mobile or web applications.

## Tech Stack
- **Programming Language**: Python
- **Deep Learning Frameworks**: TensorFlow / PyTorch
- **Computer Vision**: OpenCV
- **Object Detection**: YOLO (You Only Look Once)
- **Model Deployment**: Flask / FastAPI (optional for serving predictions)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/boxing-punch-detection.git
   cd boxing-punch-detection
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Download the trained model (if available) and place it in the `models/` directory.

## Usage
### Running on Video
```bash
python detect.py --video path/to/video.mp4
```

### Running on Webcam
```bash
python detect.py --webcam
```

## Dataset & Training
- The dataset consists of labeled boxing match videos with frame annotations.
- The model is trained using supervised learning with augmentation techniques.
- To train a custom model, run:
  ```bash
  python train.py --epochs 50 --batch_size 16
  ```

## Results
- **Model Accuracy**: 82%


## Future Improvements
- Improve model accuracy with more training data.
- Optimize for real-time performance.
- Deploy as a mobile or web application.

## Contributing
Feel free to open issues or submit pull requests!

## License
MIT License

## Contact
For questions, reach out at [saleh070703@gmail.com.com] or open an issue on GitHub.

