This project is designed to detect face masks in real-time using a live webcam feed or by uploading images. The model used is YOLOv8, which has been trained to detect faces and classify whether they are wearing a mask or not. The frontend of the application is built using Streamlit, allowing users to interact with the system easily.
## Requirements
To run this project locally, you need to have the following Python libraries installed:

Streamlit: For building the frontend application
YOLOv8: For the face mask detection model
OpenCV: For handling video streams
Torch: PyTorch framework for YOLOv8
## Clone the Repository
git clone https://github.com/MananAli05/Face-Mask-Detection.git
 ##  Install Dependencies
 pip install -r requirements.txt
 ## How To Run
 streamlit run face2.py