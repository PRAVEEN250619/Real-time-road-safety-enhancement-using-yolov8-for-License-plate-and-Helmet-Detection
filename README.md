Real time road safety enhancement using yolov8 for license plate and helmet detection
Motorcycle Accidents have been rapidly growing throughout the years in many countries. The helmet is the main safety equipment of motorcyclists. There was need to propose an automated system that monitors motorcycles and detects the persons wearing helmet or not and a system to detect number plates.

This system proposes an automated system for detecting motorcyclists who do not wear a helmet and a system for retrieving motorcycle number plates.So, our model detects the helmet of the rider. If the two-wheeler rider does not wear the helmet, it detects the number plate of the vehicle.To detect the objects, this deep learning algorithm uses CNN (Convolutional Neural Network) that recognizes specific objects in videos, live images or feeds.

This project is a Streamlit-based application for detecting helmets, bikes, and recognizing number plates in a video stream. It uses the YOLOv8 object detection model for detecting bikes and helmets and a CNN model for helmet detection. Additionally, it recognizes number plates in real-time video.

Installation
Clone the Repository

Clone this repository to your local machine.

Install Dependencies :

Navigate to the project directory and install the required dependencies listed in the requirements.txt file using pip :

 pip install -r requirements.txt

Download Helmet Detection Model :

Download the helmet detection model (helmet-nonhelmet_cnn.h5) and place it in the project directory. You can train this model using your dataset or use a pre-trained one.

Usage
Run the Streamlit App
To run the Streamlit app, use the following command:

streamlit run source.py
This will start the Streamlit development server and open the app in your default web browser.

Upload a Video File
On the Streamlit app, use the file uploader to select a video file (e.g., MP4 or AVI) that you want to process.

View the Detection and Recognition Results
The app will display the video with real-time detections of bikes and helmets. If a helmet is detected, it will be labeled as "Helmet" or "No Helmet" based on the helmet detection model's prediction. Number plates, if present, will also be recognized and displayed.

Interact with the App
You can pause, resume, and navigate through the video using the app's interface. Observe the real-time results as the video plays.

File Structure
source.py: The main Streamlit app code for helmet, bike, and number plate detection and recognition.
requirements.txt: A list of required Python packages and their versions.

ScreenShots
Screenshot (235) Screenshot (237) Screenshot (236)
Acknowledgements
This project uses YOLOv8 for object detection. You can find more information about YOLOv8 here.
