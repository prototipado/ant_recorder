# Ant Project

### MATERIALES

- Tornillos autoroscantes M2.5 x10mm de largo: 4 para cerrar el gabinete, 2 para el montaje del sensor de luz.
- Tornillos autoroscantes M1.5 x5mm de largo: 2 para fijar el sensor de humedad y temperatura.
- Tornillo M4 o M5, de 20 o 25mm, con su tuerca, para el tornillo de fijación
- Ventana de vidrio de 20x20mm
- Cable de 4 hilos
- Módulo sensor de luz Bh1750 (GY-302)
- Módulo sensor de HyT HTU21D
- Silicona para sellado

### IMPRESIÓN DE PARTES

*Imprimir en tecnología FDM las siguientes partes:*
- bottom_v2_boards.stl
- top_boards.stl
- tuerca.stl

### MONTAJE

1. Soldar cables a los módulos.

![alt text](Imagenes/img_10.jpg)

2. Soldar el cable de comunicación con la Raspoberry a las placas

![alt text](Imagenes/img_10.jpg)

3. Pegar el vidrio y sellar toda la periferia del mismo

![alt text](Imagenes/img_4.jpg)

4. Agregar sellador de silicona a lo largo de toda la ranura de cierre del gabiente.

![alt text](Imagenes/img_3.jpg)

### CONEXIÓN
Conecte el cable armado a la Raspberry de forma de alimentar ambas placas (3.3V [PIN 1] y GND [PIN 6]) y luego conecte SCL [PIN 5] y SDA [PIN 3].
