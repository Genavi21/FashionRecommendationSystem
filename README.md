# Fashion Recommendation System

This project is a machine learning-powered web application designed to recommend visually similar fashion items based on uploaded images. It uses a pre-trained ResNet50 model for feature extraction and a user-friendly interface built with **Streamlit**.

---

## Features

- **Image Upload**: Users can upload an image of a fashion item to receive recommendations of similar items.
- **Image Recommendation**: Displays the top 5 most similar fashion images.
- **Interactive UI**: Designed with Streamlit for an intuitive and responsive experience.

---

## Tech Stack

### **Frontend**
- **Streamlit**: Provides the web interface.

### **Backend**
- **Python**: Core programming language.
- **TensorFlow/Keras**: Used for feature extraction with ResNet50.
- **scikit-learn**: Implements the Nearest Neighbors algorithm.
- **NumPy & Pickle**: Data handling and model persistence.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fashion-recommendation-system.git
   cd fashion-recommendation-system
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the precomputed `Image_features.pkl` and `filenames.pkl` files.

---

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Upload a fashion image using the interface.

3. View the recommended similar images.

---

## Model Details

- **Feature Extractor**: ResNet50 pre-trained on ImageNet with a `GlobalMaxPool2D` layer.
- **Feature Normalization**: L2 normalization applied to feature vectors.
- **Nearest Neighbor Search**: Finds top similar images using Euclidean distance.

---

## Contributing

Contributions are welcome! Please submit issues or pull requests to improve the system.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Fashion dataset used for generating recommendations.
- Frameworks and libraries: TensorFlow, scikit-learn, Streamlit.

