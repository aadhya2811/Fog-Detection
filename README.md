# Fog-Detection
This project focuses on developing a fog detection system for self-driving vehicles using the CARLA simulator. The objective is to enhance autonomous navigation safety by identifying and classifying foggy weather conditions in real-time. Foggy environments pose significant challenges to computer vision systems due to reduced visibility, which can affect object detection, lane following, and decision-making algorithms.

Using image data captured from an ego vehicle within CARLA under various fog densities, we trained a deep learning model to classify images as clear, light fog, or dense fog. The dataset includes synthetic foggy scenes generated by manipulating CARLA's weather parameters. Preprocessing techniques such as resizing, normalization, and optionally contrast enhancement were applied to improve model performance.

We utilized a Convolutional Neural Network (CNN) architecture for classification, and implemented denoising techniques to improve visibility and robustness under heavy fog. The trained model was then tested on real-time image feeds from CARLA to evaluate its accuracy and responsiveness in dynamic driving scenarios.

The system can be integrated into larger self-driving stacks to trigger adaptive responses (e.g., speed reduction or sensor switching) based on fog severity. This project demonstrates the potential of AI-driven environmental awareness to increase the reliability of autonomous driving systems in adverse weather conditions.
