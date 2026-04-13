# Coffee Leaf Disease Detection Using CNN

##  Overview
This project uses **Convolutional Neural Networks (CNN)** to detect diseases in coffee leaves. The model classifies leaves into four categories:
- **Cerscospora**
- **Healthy**
- **Leaf Rust**
- **Phoma**

## Dataset
- Training images: 10,800 images
- Test images: 1,200 images
- Image size: 224×224 pixels

##  Model Architecture
- 3 Convolutional layers + MaxPooling
- Dropout for regularization
- Dense layers for classification
- **Accuracy achieved: 84.7%**

##  Project Structure

├── data/

│ ├── train/

│ └── test/

├── saved_model/

│ └── coffee_leaf_disease_model.keras

├── notebooks/

├── requirements.txt

└── README.md


##  How to Run
```bash
# Install dependencies
pip install tensorflow numpy matplotlib opencv-python

# Run training
python train.py

# Test on single image
python predict.py --image path/to/leaf.jpg

 Results
Disease	Accuracy
Cerscospora	99.7%
Healthy	87.5%
Leaf Rust	53.4%
Phoma	89.7%
Overall Accuracy: 84.7%

Deployment

# Run Streamlit app
streamlit run app.py

Author
Kassahun Tigabu

Links
https://github.com/kassahun-tigabu/Coffee-Disease-Detection-Using-CNN
