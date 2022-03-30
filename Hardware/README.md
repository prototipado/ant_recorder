# Ant Project

### MATERIALES

- Tornillos autoroscantes M2.5 x10mm de largo: 4 para cerrar el gabinete, 2 para el montaje del sensor de luz.
- Tornillos autoroscantes M1.5 x5mm de largo: 2 para fijar el sensor de humedad y temperatura.
- Tornillo M4 o M5, de 20 a 25mm, con su tuerca, para el tornillo de fijación.
- Ventana de vidrio de 15x15mm a 19x19mm.
- Cable de 4 hilos.
- Módulo sensor de luz Bh1750 (GY-302).
- Módulo sensor de HyT HTU21D.
- Silicona para sellado.

### IMPRESIÓN DE PARTES

*Imprimir en tecnología FDM las siguientes partes:*
- bottom_v2_boards.stl
- top_boards.stl
- tuerca.stl

### MONTAJE

1. Soldar cables a los módulos.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_10.jpeg" width="400" height="600">

2. Colocar las placas en el gabinete y soldar el cable de comunicación con la Raspoberry a las placas.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_7.jpeg" width="400" height="600">

3. Sellar la periferia del sensor de HyT con silicona.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_6.jpeg" width="400" height="500">

4. Pegar el vidrio y sellar toda la periferia del mismo.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_4.jpeg" width="500" height="500">

5. Agregar sellador de silicona a lo largo de toda la ranura de cierre del gabiente.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_3.jpeg" width="400" height="500">

6. Cerrar el gabinete y colcoar el tornillo de fijación.

<img src="https://github.com/prototipado/ant_recorder/blob/main/Hardware/Imagenes/img_2.jpeg" width="600" height="500">

### CONEXIÓN
Conecte el cable armado a la Raspberry de forma de alimentar ambas placas (3.3V [PIN 1] y GND [PIN 6]) y luego conecte SCL [PIN 5] y SDA [PIN 3].
