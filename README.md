Transfer Learning for Arabic Alphabet Sign Language Classification
==================================================================

This repository showcases a project using transfer learning with the ResNet50V2 architecture to classify Arabic alphabet sign language gestures. The approach leverages a pre-trained deep learning model for robust and efficient gesture recognition, aiming to enhance accessibility for the deaf and hard of hearing community.

* * *

Dataset Used
------------

**RGB Arabic Alphabets Sign Language Dataset**

*   **Source:** [Kaggle](https://www.kaggle.com/datasets/muhammadalbrham/rgb-arabic-alphabets-sign-language-dataset)
*   **Description:** A dataset containing RGB images representing gestures for Arabic alphabet characters.

* * *

Model and Approach
------------------

**Pre-trained Model:**

*   **ResNet50V2:** A convolutional neural network pre-trained on ImageNet, fine-tuned on the Arabic sign language dataset to extract features and classify gestures efficiently.

**Performance:**

*   **Training Accuracy:** 94.29%
*   **Test Accuracy:** 90.45%

* * *

Features
--------

*   **Transfer Learning:** Utilized ResNet50V2 to reduce training time and improve feature extraction.
*   **Dataset Preprocessing:** Resized, normalized, and augmented images to improve generalization and reduce overfitting.
*   **Scalability:** Built a modular framework using TensorFlow and Keras for future enhancements.

* * *

Technology Stack
----------------

*   **Programming Language:** Python
*   **Libraries:**
    *   TensorFlow
    *   Keras
    *   NumPy
    *   Matplotlib (for visualization)

* * *

Usage
-----

1.  **Clone the repository:**
    
    ```bash
    git clone https://github.com/your-username/your-repo-name.git  
    ```
    
2.  **Run the notebook:**  
    Open and execute the Jupyter notebook provided to train and test the model on the dataset.
    

* * *




