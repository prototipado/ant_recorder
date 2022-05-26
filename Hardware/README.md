# Ant Project

### MATERIALES

- Tornillos autoroscantes M2.5 x10mm de largo (o similar): 3 para cerrar el gabinete del sensor de luz, 2 para el montaje del sensor de luz.
- Tornillos autoroscantes M1.5 x5mm de largo (o similar): 1 para fijar el sensor de humedad y temperatura.
- Tornillo M4 o M5, de 20 a 25mm, con su tuerca, para el tornillo de fijación (o similar).
- Ventana de vidrio de 15x15mm a 19x19mm.
- Cable de 4 hilos.
- Módulo sensor de luz Bh1750 (GY-302).
- Módulo sensor de HyT HTU21D.
- Silicona para sellado.

### IMPRESIÓN DE PARTES

*Imprimir en tecnología FDM las siguientes partes:*
- HT_sensor_holder.stl
- ligth_sensor_holder.stl
- sunshield_dish_top.stl
- support.stl
- ss_dish_interm.stl  x3

### MONTAJE

1. Soldar cables al módulo de luz.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_1.jpeg"> </p>

2. Colocar el módulo de sensado de luz dentro de su soporte.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_2.jpeg" > </p>

3. Sellar la periferia del cable con silicona.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_3.jpeg" > </p>

4. Agregar sellador de silicona en la ranura donde encastra el holder del sensor de luz.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_4.jpeg" > </p>

5. Una vez que el sellador de silicona haya endurecido, colocar el holder con tornillos.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_5.jpeg" > </p>

6. Soldar cables al módulo sensor de HyT y colcarlo en su holder utilizanbdo el tornillo.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_6.jpeg" > </p>

7. Petar el vidrio con sellador de silicona sobre la apertura para el sesnor de luz.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_10.jpeg"  </p>

8. Atornillar las distintas partes para ensamblar el dispositivo. Tener en cuenta que las aperturas en los laterales de las piezas queden alineadas entre sí de manera de permitir el flujo de aire.
El ensamble se raliza en el siguiente orden:
- sunshield_dish_top (con ligth_sensor_holder)
- ss_dish_interm
- ss_dish_interm
- ss_dish_interm
- HT_sensor_holder
- support




<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_8.jpeg"> </p>

9. Soldar los cables de ambos sensores entre sí y a una sección de cable que le permita llegar hasta la Raspberry Pi.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_7.jpeg" > </p>

10. Sostenga los cables sobre el brazo del soporte utilizando precintos.

<p align="center"> <img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_9.jpeg" > </p>

### CONEXIÓN
Conecte el cable armado a la Raspberry de forma de alimentar ambas placas (3.3V [PIN 1] y GND [PIN 6]) y luego conecte SCL [PIN 5] y SDA [PIN 3].
