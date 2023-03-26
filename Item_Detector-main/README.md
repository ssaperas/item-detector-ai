# Stock Detector 

### **👾👾👾 Welcome 👾👾👾**
### **Introduction**

This project aims to facilitate the detection of out-of-stock products in supermarkets or stores by adding QR codes under the products. When there is a shortage of stock, the QR code is exposed and the camera can analyze it to determine which product is missing.

There are two modes of use in our application: the first is through images and the second is through video. In both modes, the frames are analyzed by a pre-trained deep learning model specialized in QR code detection, making it easy to detect and process them to a QR code scanning library to obtain the corresponding product.

To initialize the project, clone this repository and follow the instructions below.

Installation of Libraries:
bash
Copy code
pip3 install opencv-python
pip3 install pyzbar
pip3 install PyQt5
pip3 install tempfile
Installation of Application on Mobile Device
This is probably the most complicated part of the set-up, but basically you need to install a third-party application to communicate the mobile device with the computer. In our case, we used MacOS with iOS through the EpocCam Pro application.

Execution of Python3 Program
Simply enter the command python3 Detector_Stock.py in the terminal

Feel free to fork or improve the current project :)

<img width="1295" alt="Captura de Pantalla 2022-07-02 a las 4 44 27" src="https://user-images.githubusercontent.com/62452212/176983835-da43187d-02b1-4d92-a565-43c82f5e87b2.png">
Project carried out by Sergi Saperas and Carlos Martin
