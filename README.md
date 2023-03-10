# Proyecto-3-Mini Amplificador De Audio Casero
![espe](https://user-images.githubusercontent.com/117187676/204173965-f5741989-1012-4150-a4ec-1722212ee733.png)
# INTEGRANTES
* Kevin Mauricio Viteri
* Dennis Stalin Jaguaco Veloso
* Alexis Omar Grijalva Nacevilla
# 1. OBJETIVOS
## OBJETIVO GENERAL
Comprender y analizar el funcionamiento y utilidad del circuito de un mini amplificador de sonido, mediante la correcta aplicacion del algoritmo y pasos explicados en el video proporcionado por el docente, para lograr conocer su adaptacion en parlantes de uso convencional.
## OBJETIVOS ESPECIFICOS
* Armar el circuito de un mini amplificador de sonido mediante el implemento de los componentes mencionados en el material audiovisual proporcionado.
* Visualizar y poner a prueba el resultado obtenido, mediante el uso correcto de los componentes involucrados, para comprobar su buen funcionamiento.
# 2. MARCO TEORICO
LM386
El integrado LM386 también se lo llama como JRC386. Es un circuito integrado formado por un amplificador y requiere bajas tensiones tanto en la entrada de audio como en la fuente de alimentación. Se utiliza habitualmente en altavoces de ordenador (amplificadores), radios, amplificadores de guitarra, entre otros.
Éste es un amplificador de audio sencillo que se puede utilizar para amplificar señales de dispositivos portátiles tales como radios, reproductores de mp3, altavoces de ordenador, etc. No se requiere gran potencia de salida. Puede alimentarse con una fuente de tensión de 9 V en el pin 8 ofrece 0,5 vatios de potencia y sólo 0,2% ÷en este caso de distorsión.

![image](https://user-images.githubusercontent.com/117187676/222359091-2dbe1896-9190-44dc-8321-6efbcd12777d.png)

PROTOBOARD
El protoboard está lleno de orificios que se encuentran metalizados donde los contactos están a presión, en estos orificios van insertados los componentes para construir el circuito. Además, es una herramienta útil para conectar diversidad de dispositivos sin la necesidad de estar soldados.

![image](https://user-images.githubusercontent.com/117187676/222359164-5e48dc76-6a92-410a-9923-f7e65efc431c.png)

POTENCIÓMETRO
Va actuar un potenciómetro como una resistencia, pero en este caso el valor puede ser variable, ajustándose según las necesidades, por tanto de igual forma limita la corriente, teniendo caídas de tensión tal y como sucede en una resistencia con valor fijo. De esta forma un potenciómetro de 100 kΩ, puede tener valores desde 0 a 100 000 Ω.

![image](https://user-images.githubusercontent.com/117187676/222359598-65a12b12-f398-42af-a6b5-7b788eeed262.png)

BATERÍA
Las baterías o acumulador eléctrico, es un artefacto formado por celdas electroquímicas que tienen la capacidad de convertir la energía química contenida en ella en energía eléctrica. Por lo tanto, las baterías generan corriente continua y, por lo tanto, se utilizan para alimentar varios circuitos según su tamaño y potencia.  Las baterías 
 Tienen una capacidad de carga que viene determinada por las características de su composición y  se mide en amperios-hora (Ah), lo que significa que la batería puede suministrar un amperio de corriente durante una hora continua. Cuanto mayor sea su capacidad de carga, más electricidad podrá almacenar en su interior.

![image](https://user-images.githubusercontent.com/117187676/222359652-734eeee8-c144-4b3f-adc7-bb1e165463a4.png)

CABLE PLUG
El cable plug de señales analógicas, se emplea para conectar micrófonos, auriculares y otros sistemas de señal analógica a dispositivos electrónicos, sin embargo en su mayoría se usa para audio. Para reconocer cada tipo se aplica un código de colores que son: verde, azul, rosa / rojo, gris, negro, naranja.

![image](https://user-images.githubusercontent.com/117187676/222359743-8dbcfb18-30f1-4c9d-bd90-b7bfc556275b.png)

CONDENSADOR
El condensador es un dispositivo eléctrico que cuenta con dos terminales, su principal característica es de almacenar energía eléctrica. Se encuentra construido con dos superficies conductoras y está separada por un aislante, estos dispositivos cuentan con cierta cantidad de carga eléctrica acumulan de manera proporcional al tamaño de sus superficies y a su vez inversamente proporcional a la separación de las mismas. Para medir  esta carga eléctrica que almacenan se mide en Faradios (F).

![image](https://user-images.githubusercontent.com/117187676/222359793-c97378ed-f5e8-486d-b310-3871efac68c4.png)

* # 3. PROCEDIMIENTO Y ESQUEMAS
Prara este circuito se requerira de los siguentes componentes:
* Una protoboard 
* Circuito integrado lm 386 
* Protoboard, o lo pueden armar soldando con cables
* Un potenciometro de 10k
* Varios cables
* Batería desde 5v / 12v
* Un plug cable
* Un condensador de 220uF a 16v
* Parlante de 8 ohm 2 watts

Se procedera a especificar de manera practica el procedimiento de armado e instalacion del circuito:
* en la protoboard en un nodo conectaremos el positivo del circuito y en otro nodo el negativo, colocamos el integrado con la pequeña ranura viendo hacia la izquierda.
* Hacer un puente desde la pata 2 hasta la pata 4 del integrado.
* Conectamos la pata positiva del condensador a la pata 5 del integrado a la pata 5 y la pata negativa del condensador hacia un punto colocamos el potenciómetro lo colocamos en esta parte.
* conectamos un cable desde la pata 2 del integrado hasta la pata izquierda del potenciómetro desde la pata 2 hasta la pata izquierda.
*  Conectamos otro cable desde la pata 3 del integrado hasta la pata central del potenciometro.
*  La pata derecha del potenciómetro y la pata 4 del integrado serán la entrada de señal de audio conectamos el club cable y a la pata 4 y a la pata derecha del potenciómetro.
* El plug lo conectaremos a un reproductor de audio, hacemos un puente desde la pata 2 del integrado hasta el lado negativo de la protoboard.
* Conectamos los parlantes un cable del parlante a la pata negativa del condensador y el otro cable del parlante a la pata 4 del integrado.
* Finalmente conectar la batería y probar nuestro amplificador de sonido conectaremos positivo de la batería al positivo del circuito y negativo al negativo y conectamos un reproductor de audio.

 ## ESQUEMA E IMAGENES
 
 ![IMG-20230301-WA0757 (2)](https://user-images.githubusercontent.com/117187676/222335681-2e8c4410-3bfb-452b-9ef6-81790556b925.jpg)

![IMG-20230301-WA0755](https://user-images.githubusercontent.com/117187676/222335888-1235a5b0-dd8d-4146-887c-6b770051eb5f.jpg)

![IMG-20230301-WA0756](https://user-images.githubusercontent.com/117187676/222335899-a3a1b1d0-d2e4-4ea5-94f9-873941044cba.jpg)

# 4. VIDEO

https://youtu.be/Y-xJzV0yY6k

# 5. CONCLUSIONES

* Se puede concluir que, gracias a el seguimiento de las instrucciones y los pasos mostrados en el video proporcionado, se pudo lograr un resultado efectivo, demostrando asi el funcionaciemto y proposito del circuito.

* En conclusion, el uso de los diferentes compnentes electronicos empleados en la realizacion del circuito, se basa en las distintas funciones de cada uno de ellos, por lo que con una investigacion cinetifica y empirica se logro los resultados esperados.


# 6. BIBLIOGRAFIA

* Martín Pereda, J. A., & Rodríguez Rodríguez, T. (1978). Componentes electrónicos. Departamento de Publicaciones, Escuela Técnica Superior de Ingenieros de Telecomunicación.



