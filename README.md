# Curvetopia

![image](https://github.com/user-attachments/assets/c1693620-e27c-4664-8427-43013f268720)


This project focuses on advanced image processing techniques to analyze and manipulate images containing regular geometric shapes. The primary goals are to classify shapes, regularize their forms, detect symmetry, and complete occluded shapes. By leveraging a range of image processing and machine learning techniques, the project aims to provide a comprehensive solution for handling shapes in various states of distortion or occlusion.

Shape Classification is achieved by employing a Random Forest Classifier, trained on features extracted from geometric shapes. These features include curvature and distance to the centroid, which are computed from the curves' data. The classifier distinguishes between different shape categories such as circles, squares, and triangles. The project includes preprocessing steps for loading and cleaning data, followed by feature extraction to ensure uniformity and accuracy in classification.

Shape Regularization involves adjusting and aligning shapes to match their ideal geometric forms. This step applies algorithms to smooth edges and correct distortions, enhancing the visual and geometric accuracy of the shapes.

Symmetry Detection plays a crucial role in identifying symmetrical axes within shapes. The project uses symmetry to complete partially occluded shapes, reconstructing missing parts based on detected symmetry. This helps in accurately analyzing shapes even when they are partially hidden.

Shape Completion is tackled by detecting and filling occluded parts of shapes. The project uses symmetry and advanced image processing techniques to reconstruct incomplete shapes, providing a more complete representation of the original forms.

The project is implemented using Python, utilizing libraries such as OpenCV for image processing, NumPy for numerical operations, and Matplotlib for visualization. The code is developed and tested in a Jupyter Notebook environment, allowing for interactive exploration and refinement of the algorithms.

Overall, this project provides a robust framework for analyzing, regularizing, and completing images of geometric shapes, offering valuable tools for various applications in image analysis and computer vision.

# Demo Link
[https://youtu.be/OOdWjGRL9yY]
