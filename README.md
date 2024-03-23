# Real-Time Text Detection with Python, OpenCV, and Tesseract

**Prerequisites:**

Before running the project, make sure you have the following dependencies installed:

- Python
- OpenCV (cv2)
- Tesseract OCR
- NumPy
- Pillow (PIL)

Ensure that you download and install Tesseract OCR and set the path to the Tesseract executable in the code.

**How to Run:**

1. Clone this repository or download the project files.

2. Open the Python script in your preferred code editor.

3. Set the path to the Tesseract executable (`pytesseract.pytesseract.tesseract_cmd`) to the location of your Tesseract installation.

4. Customize any other settings, such as webcam resolution, blur parameters, or text display position in the code as needed.

5. Run the Python script:

   ```bash
   python real_time_text_detection.py
   ```

The webcam or screen video feed will be displayed, and the recognized text will be overlaid in green color. Press 'q' to exit the program.
