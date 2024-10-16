**Face Recognition using Principal Component Analysis**

Overview: This project involves creating a facial recognition system using Principal Component Analysis (PCA) to recognize and classify faces from the AT&T face dataset. The dataset contains images of 40 individuals, each having 10 different grayscale facial images taken under different conditions.

The PCA technique projects these images into a "face space" defined by the eigenvectors (Eigenfaces), and the system compares an input face image to this space to recognize the closest match.

Dataset
1) Dataset Used: AT&T Face Dataset
2) Dataset Details:
i) 40 subjects, 10 images per subject.
ii) Grayscale images of size 92x112 pixels
iii) Images vary in lighting, facial expressions, and details (e.g., glasses)
3) Dataset link: https://git-disl.github.io/GTDLBench/datasets/att_face_dataset/

Tasks

1) Load Dataset: Split the dataset into training and test sets.
2) Implement PCA from Scratch: Use PCA for dimensionality reduction.
3) Image Reconstruction: Reconstruct images from the eigen projections and visualize the differences by varying the number of components.
4) Visualize Mean (Eigenface): Generate and visualize the mean face.
5) Face Recognition: Implement a face recognition system and calculate accuracy by varying the number of principal components.

Dependencies

This project requires the following libraries:
i) numpy
ii) matplotlib
iii) os
iv) sys
v) cv2 (OpenCV)
vi) copy
vii) tqdm
viii) google.colab (if running in Colab)

You can install these dependencies via pip:
pip install numpy matplotlib opencv-python tqdm

Instructions to Run
Mount the Drive (for Google Colab):
The notebook is set up to mount Google Drive in Colab. If you are using Colab, make sure your dataset is stored in your Google Drive.

Dataset Loading:
Download the AT&T dataset and ensure it's placed in the appropriate directory for loading.

Execute the Notebook:
The notebook contains code for loading the dataset, implementing PCA from scratch, and visualizing results. Step through each section to perform PCA, reconstruct images, and evaluate the recognition system's accuracy.

Results
PCA Image Reconstruction: Visualization of the effect of different numbers of principal components on image reconstruction.
Face Recognition Accuracy: Evaluates the recognition accuracy for varying numbers of principal components.
References
Eigenfaces for Recognition Paper: https://sites.cs.ucsb.edu/~mturk/Papers/mturk-CVPR91.pdf

This README provides an overview and sufficient instructions for users who want to understand and execute the notebook. Let me know if you'd like to add or modify any sections! 
