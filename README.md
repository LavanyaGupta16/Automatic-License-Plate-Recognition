
<h1 align="center"> Number-plate-recognition:car: </h1>
Number Plate recognition, also called License Plate recognition using image processing methods is a potential research area in smart cities and the Internet of Things. An exponential increase in the number of vehicles necessitates the use of automated systems to maintain vehicle information for various purposes.

## Functionalities

* It detect the number plate in a given image or video 
* Identifies the text in the detected number plate

### Prerequisites 
The project code utilizes the following library:
*    Python 
*    OpenCV  
*    pytesseract 
*    Pillow
*    Streamlit
*    imutils 
*    numpy
*    Tesseract-OCR (This is NOT installed through pip but with the Windows installer)

## Folder Structure
1.  **Images** ---> Contains Few image to try on
2.  **Videos** ---> Contains a video to try on
3.  **app.py** ---> This contain all the python code for detection of license plate

## Instructions to run
* To install Streamlit and other dependencies, use the given pip command.
```bash
pip install -r requirements.txt
```

```bash
pip install -r packages.txt
```

* Running Streamlit scripts is incredibly easy. All you need to do is enter the following line in your terminal.

```bash
streamlit run app.py
```
