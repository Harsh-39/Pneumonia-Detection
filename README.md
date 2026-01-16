# Pneumonia-Detection
The model is trained to detect  whether the victim/patient is suffering from Pneumonia or not just by analysing his/her chest X-ray Image uploaded on web application .



## Pneumonia Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images.
Model trained separately and loaded into Flask web application.

### How to Run

pip install -r requirements.txt  
python app.py  

### Download Model
Model is too large for GitHub. Download from Google Drive:
Contact on email(given in bio ) for model link. 

Contact E-mail = harshlavaniya11@gmail.com

STEPS TO RUN THE MODEL (ON ANY SYSTEM USING VS CODE)

1. Download or clone the GitHub repository.
   - Option A: Click on "Code" → "Download ZIP" → Extract it
   - Option B: git clone <repository-link>

2. Open VS Code.
   - Go to File → Open Folder
   - Select the project folder

3. Download the trained model file (.h5) from Google Drive.( Link given above and in Bio)
   - File name must be: pneumonia_detection_model.h5
   - Place this file inside the main project folder (same level as app.py)

4. Open terminal in VS Code.

5. Install all required dependencies by running:
   pip install -r requirements.txt

6. Run the Flask application using:
   python app.py

7. If the server starts successfully, you will see:
   Running on http://127.0.0.1:5000/

8. Open any web browser and go to:
   http://127.0.0.1:5000/

9. Upload a chest X-ray image and click on Predict.

10. The model will classify the image as:
    - Pneumonia
    - Normal
