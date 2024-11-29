# Spam Message Classification using SVM

## Description

This project applies the **Support Vector Machine (SVM)** algorithm to classify text messages as **spam** or **non-spam (ham)**. To make the data easier to visualize and interpret, we first use **Principal Component Analysis (PCA)** to reduce the dimensionality of the feature space. The dataset consists of text messages, and the goal is to classify each message as spam or non-spam.

### Key Features:
- **Data Preprocessing**: Includes text vectorization (converting text messages into numerical features).
- **Dimensionality Reduction**: PCA reduces the feature space from high dimensions (e.g., 384 features) to 2 dimensions for easier visualization.
- **Model Training**: An SVM classifier is trained to distinguish between spam and ham messages.
- **Visualization**: A 2D scatter plot is used to visualize how well the spam and ham messages are separated in the reduced feature space.
