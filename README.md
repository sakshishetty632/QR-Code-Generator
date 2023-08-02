# QR Code Generator
This repository contains the source code for a QR Code Generator web application built with Flask. The application allows users to generate QR codes for links they provide. The QR code is displayed on the web page in real-time.

## How to Use
1. Clone the repository to your local machine using git clone https://github.com/sakshishetty632/QR-Code-Generator.
2. Make sure you have Python installed on your system.
3. Install the required dependencies using 
```
pip install Flask
```
```
pip install qrcode
```
io & base64 (Included with Python, no separate installation needed).

4. Run the application using
```
python main.py
```
5. Open your web browser and go to
```
http://127.0.0.1:5000/
```
6. Enter the link you want to encode as a QR code in the input field.
7. Click the "Generate QR Code" button.
8. The generated QR code will be displayed below the input field.

## Files
main.py: The main Python script that runs the Flask web application. It includes two routes: the default '/' route, which displays the home page, and the '/ route with the POST method, which generates the QR code and displays it on the page.

index.html: The HTML template used to render the web page. It contains a simple form with an input field to enter the link and a button to submit the form. The generated QR code is displayed below the form.

## Dependencies
The application requires the following Python libraries:

Flask: A micro web framework used to create the web application.
qrcode: A library to generate QR codes.
io: A library to handle I/O operations.
base64: A library to encode and decode data in Base64 format.
These dependencies are listed in the requirements.txt file, which you can use to install them using pip install -r requirements.txt.


## Acknowledgments
The QR code generation functionality is implemented using the qrcode library.
The web application is built using the Flask framework.
