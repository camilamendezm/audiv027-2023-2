#### Contenidos de este repositorio

* carpeta [imagenes/](imagenes/):
   * archivo [arduino_01.png](/imagenes/arduino_01.png)
   * archivo [arduino_02.png](/imagenes/arduino_02.png)
   * archivo [google_colab_01.png](/imagenes/google_colab_01.png)
   * archivo [google_colab_02.png](/imagenes/google_colab_02.png)
   * archivo [google_colab_03.png](/imagenes/google_colab_03.png)
   * archivo [arduino_01.png](/imagenes/arduino_01.png)
   * archivo [arduino_02.png](/imagenes/arduino_02.png)
* archivo [README.md](README.md)
  
# Sobre reconocimiento de bebidas y sus colorantes

Los colores brillantes atraen a las personas como las flores atraen abejas, esta ha sido una estrategia para vender distintos articulos desde siempre, utilizando diseños con colores fuertes y paquetes brillantes para que un producto llame mas la atencion que la competencia. Pero cuando utilizamos estos colores para teñir alimentos ¿Estamos seguros de lo que consumimos? ¿Que es lo que crea estos brillantes colores en nuestras bebidas favoritas?.

En este proyecto utilizaremos Arduino para que sea capaz de reconocer los colores fuertes de las bebidas e informarnos cual es el colorante que se utiliza para teñirlas de esa forma, de esta manera podemos saber que es realmente lo que provoca el color de la bebida y como esto puede afectar a nuestros cuerpos.

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

* #### Instalar la libreria de TensorFlow Lite.
Para comenzar a trabajar utilizamos como base el codigo de el ejercicio "FruitToEmoji", Principalmente el codigo existente en "object_color_recognition" y tambien "object_color_classify" el que editaremos como sea necesario para permitir nuestro trabajo.
  
* #### Crear base de datos en Arduino con los colores de las bebidas reconociendo los colores Amarillo, Azul, Naranja y Rojo.
Para la creacion de esta libreria utilizamos "object_color_recognition" y las bebidas Kem piña (Amarillo), Gatorade Cool blue (Azul), Fanta (Naranja) y finalmente Bilz (Rojo), reconociendo sus colores con luz natural, luz tenue y luego alumbrando las botellas con una linterna, de manera que la libreria contara con una amplia variedad de tonos para cada bebida y asi reconocerlas con mas facilidad en distintos ambientes.
  
* #### Ingresar base de datos al código en [Google Colab](https://colab.research.google.com/github/arduino/ArduinoTensorFlowLiteTutorials/blob/master/FruitToEmoji/FruitToEmoji.ipynb)
Al entrenar el modelo nos encontramos con un problema, puesto que el Google Colab no esta preparado para trabajar con 4 colores, para poder hacerlo funcionar tubimos que encontrar cual era la parte del proceso que impedia la produccion del archivo "model.h" 

* #### Eliminar la sección “Run with Test Data”.
Finalmente encontramos cual era el problema que impedia la realizacion de este archivo, y logramos resolverlo simplemente eliminando el paso "Run with Test Data" que solo permitia el analisis de 3 colores. (foto)

* #### Descargar carpeta model.h (foto) 

* #### Ingresar los resultados en Arduino IDE.

* Modificar código en Arduino IDE, añadiendo una variable, cambiando los nombres y otorgarles un carácter (captura).

**Proccesing**
  
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
