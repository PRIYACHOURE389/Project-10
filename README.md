# Project-10

Custom-OCR/
│
├── data/
│   └── Dataset_OCR/                     # Dataset for YOLOv3 training
│
├── model/
│   └── yolov3.weights                   # Trained YOLOv3 model weights
│
├── output/
│   └── results/                         # Folder for OCR outputs (CSV, images, etc.)
│
├── scripts/
│   ├── train_yolov3.py                  # Script for training YOLOv3 on SageMaker
│   ├── inference.py                     # Script for running inference and post-processing
│   └── sagemaker_pipeline.py            # Script to create an automated SageMaker pipeline
│
├── Custom_OCR.py                        # Main script to trigger OCR process
│
├── requirements.txt                     # List of dependencies
│
└── README.md                            # Documentation of the project
