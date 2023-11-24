#### Contenidos de este repositorio

* carpeta [imagenes/](imagenes/):
   * archivo [google_colab_01.png](/imagenes/google_colab_01.png)
   * archivo [google_colab_02.png](/imagenes/google_colab_02.png)
   * archivo [google_colab_03.png](/imagenes/google_colab_03.png)
   * archivo [google_colab_04.png](/imagenes/google_colab_04.png)
   * archivo [google_colab_05.png](/imagenes/google_colab_05.png)
   * archivo [google_colab_06.png](/imagenes/google_colab_06.png)
   * archivo [google_colab_07.png](/imagenes/google_colab_07.png)
   * archivo [google_colab_08.png](/imagenes/google_colab_08.png)
* archivo [README.md](README.md)
  
# Sobre reconocimiento de bebidas y sus colorantes

Nuestro objetivo con este proyecto es .

<sub> [**Gloria Herrera**](https://github.com/gloriaherrera), [**Amelia López**](https://github.com/Ax0lMar) y [**Camila Méndez**](https://github.com/camilamendezm) para audiv027-2023-2. Electivo Ambas Menciones: Inteligencia Artificial  
DOCENTE: [**Aaron Montoya Moraga**](https://github.com/montoyamoraga) - FAU.UCHILE -  </sub>

#### Proyecto funcionando

#### Materiales

* Arduino Nano 33ble sense
* Computador
* [Arduino IDE](https://www.arduino.cc/en/software)
* [Processing](https://processing.org/download)
* TensorFlow

### Proceso

* Crear base de datos en Arduino con los colores de las bebidas.
* Ingresar base de datos al código en [Google Colab](https://colab.research.google.com/github/arduino/ArduinoTensorFlowLiteTutorials/blob/master/FruitToEmoji/FruitToEmoji.ipynb)
* Eliminar la sección “Run with Test Data”. (foto)

* Descargar carpeta model.h (foto) 

* Ingresar los resultados en Arduino IDE.
* Instalar la libreria de TensorFlow Lite.
* Modificar código en Arduino IDE, añadiendo una variable, cambiando los nombres y otorgarles un carácter (captura).

**proccesing**
  
* Colocar el ejemplo SimpleRead en Processing (Archivo - Ejemplos - Bibliotecas - Serial - SimpleRead).
* Cambiar línea 22 del codigo para saber el puerto que está ocupando nuestro Arduino (captura)
* En processing, agregar valores y asignarles colores en RGB a cada uno. (captura)

(video funcionando)




### Referentes

[Fruit identification using Arduino and TensorFlow](https://blog.arduino.cc/2019/11/07/fruit-identification-using-arduino-and-tensorflow)

## Conclusiones

Aprendizajes:

Dificultades:
* Processing
* Modificar códigos
