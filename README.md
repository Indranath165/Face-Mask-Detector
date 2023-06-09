<h1>Face-Mask-Detector</h1>
Real time face-mask detection using Deep Learning and OpenCV. This project aims to detect whether a person is wearing a face mask or not. The implementation is based on the VGG16 architecture and utilizes the power of deep learning to achieve accurate results. The system can be integrated into existing security systems or used as a standalone solution.
<h2>Dataset</h2>
The face mask dataset used in this project was obtained from <a href="https://universe.roboflow.com/pyimagesearch/covid-19-pis/dataset/2" target="_blank">here</a>. This publicly available dataset provides a diverse collection of images capturing individuals with and without face masks in various scenarios and backgrounds.
<h2>Dataset Description</h2>
<ul>
    <li>Number of images: 1279</li>
    <li>Image resolution: Image resolutions vary across the dataset.</li>
    <li>Categories: The dataset is organized into two categories:</li>
    <ul>
        <li>with Mask: This category contains images of individuals wearing face masks.</li>
        <li>without Mask: This category includes images of individuals without face masks.</li>
    </ul>
</ul>
<h2>Installation</h2>
<ol>
  <li>Clone or download this repository to your local machine.<br></li>
  <li>Navigate to the project directory: <code>cd Face-Mask-Detector</code> <br></li>
  <li>Install the required dependencies: <code>pip install -r requirements.txt</code> <br></li>
  <li>In this machine learning project, i have used Jupyter Notebook for the development. Using pip python package manager you can install Jupyter notebook. <br></li>
  <li>Run the face mask detector script: face_detection.ipynb <br></li></li>
  <li>The script will access your webcam and display the live feed with face mask predictions. You can close the window at any time by pressing the 'x' button.</li>
</ol>
<h2>Technologies Used</h2>
<ul>
    <li><b>Python</b>: The programming language used for implementing the face mask detector. Python offers simplicity, readability, and a wide range of libraries and frameworks for machine learning tasks.</li>
    <li><b>Keras</b>: A high-level deep learning framework that provides an intuitive interface for building and training neural networks. Keras simplifies the implementation of complex architectures like VGG16 and enables efficient experimentation.</li>
    <li><b>TensorFlow</b>: An open-source machine learning framework that provides a comprehensive ecosystem of tools, libraries, and resources for developing and deploying machine learning models. TensorFlow is used as the backend for Keras and offers excellent performance for deep learning computations.</li>
    <li><b>OpenCV</b>: A powerful computer vision library that provides a wide range of functions and algorithms for image and video processing tasks. OpenCV is utilized in this project for capturing video from the webcam, performing real-time face detection, and manipulating image data.</li>
    <li><b>VGG16</b>: A popular deep convolutional neural network architecture that has shown outstanding performance in various computer vision tasks, including image classification. VGG16 is used as the base model for the face mask detector, leveraging its ability to extract meaningful features from images.</li>
</ul>
These technologies, combined together, provide a strong foundation for developing an accurate and efficient face mask detection system. They enable the implementation of deep learning models, image processing operations, and real-time webcam integration, ultimately leading to the successful identification of individuals wearing or not wearing face masks.
<h2>Contributions</h2>
Contributions are welcome! We value your input and encourage you to actively participate in the project. If you have any ideas, suggestions, bug reports, or feature requests, please don't hesitate to open an issue on GitHub. Additionally, we appreciate any code contributions you may have. If you'd like to contribute code, please submit a pull request, and we will review it as soon as possible. Thank you for your support!
