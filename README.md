#Fashion Recommendation System
This project is a machine learning-powered web application designed to provide fashion image recommendations. The application uses a pre-trained ResNet50 model for feature extraction and is deployed using Streamlit to deliver an intuitive and interactive user interface.

#Features
Image Upload: Users can upload an image of a fashion item to find visually similar items.
Image Recommendation: The system retrieves and displays top similar fashion items based on image content.
User-Friendly Interface: Developed with Streamlit for a clean and responsive user experience.
#Tech Stack
#Frontend
Streamlit: Provides an interactive web interface.
#Backend
Python: Core programming language.
TensorFlow/Keras: Utilized for ResNet50-based feature extraction.
scikit-learn: Implements the Nearest Neighbors algorithm.
NumPy & Pickle: Data handling and model persistence.
#Installation
Clone the repository and navigate to the project directory.
Ensure TensorFlow, scikit-learn, Streamlit, and other dependencies are installed.
Precompute image features using the provided script and save them as .pkl files.
#Usage
Run the Streamlit application using streamlit run app.py.
Upload an image through the interface.
View the recommended similar fashion items displayed.
#Model Details
Feature Extractor: ResNet50 pre-trained on ImageNet, with a GlobalMaxPool2D layer for dimensionality reduction.
Image Features: Extracted and normalized for similarity searches.
Nearest Neighbor Search: Finds the top 5 most similar images using Euclidean distance.
#Contributing
Contributions are welcome! Report issues or submit pull requests to enhance the system.

#License
This project is licensed under the MIT License.

#Acknowledgements
Fashion dataset sourced for training and testing.
Frameworks and libraries: TensorFlow, scikit-learn, Streamlit.
