# Detector de Stock 

### **👾👾👾 Bienvenido 👾👾👾**
### **Introducción**

Este proyecto tiene como objetivo poder facilitar la detección de falta de stock en supermercados o tiendas, mediante la adición de codigos QR debajo de los productos, de modo que cuando hay falta de material, el propio QR queda al descubierto y la camara puede analizar este QR y saber que producto falta. 

Existen dos modos de uso en nuestra aplicación, el primero es mediante imagenes y el segundo es mediante video. En ambos modos, los frames son analizados mediante un modelo preentrenado de Deep Learning especializado en detección de codigos QR, haciendo que se detecten con facilidad y puedan ser procesados a una libreria de escaneo de codigos QR y asi obtener el producto correspondiente.


Para inicializar el proyecto, clona este repositorio y sigue las instrucciones que hay a continuación.
## Instalación de Librerias :
```bash
pip3 install opencv-python
pip3 install pyzbar
pip3 install PyQt5
pip3 install tempfile
```
## Instalación de aplicación en dispositivo Movil
Probablemente esta sea la parte más complicada del set up, pero basicamente debes instalar una aplicación de terceros 
para comunicar el Movil con el Ordenador. En nuestro caso hemos utilizado MacOS con iOS a través de la aplicación EpocCam Pro.
    
## Ejecución del programa Python3 
    
Simplemente debes introducir la instrucción `python3 Detector_Stock.py`en la terminal

Sientete libre de realizar fork o mejorar el proyecto actual :) 



<img width="1295" alt="Captura de Pantalla 2022-07-02 a las 4 44 27" src="https://user-images.githubusercontent.com/62452212/176983835-da43187d-02b1-4d92-a565-43c82f5e87b2.png">


Proyecto realizado por Sergi Saperas y Carlos Martin 
