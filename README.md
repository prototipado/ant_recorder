# Ant Recorder

### CLONAR REPOSITORIO

*Desde la Rpi abrir la consola (Ctrl+Alt+T) y escribir:*
```
cd Desktop
git clone https://github.com/prototipado/ant_recorder.git
```
*Nota: Luego de clonar debe instalar las librerias y dependencias, ir a la sección de requisitos !!!*

### EJECUTAR LA APLICACION

*El archivo AntP (dentro de ant_project) es una acceso directo, por lo tanto puede moverlo al escritorio y ejecuta la aplicacion. Otra opción es es realizar:*
```
cd ant_recorder
python3 main_original.py
```

## REQUISITOS
### LIBRERIAS NECESARIAS
```
sudo apt-get install python3-pyqt5
sudo apt-get install python3-rpi.gpio
sudo apt install python3-smbus
pip3 install tomlkit
pip3 install htu21df
```

### HABILITAR I2C y cámara
```
sudo raspi-config 
INTERFACE OPTIONS ---> I2C ---> yes
INTERFACE OPTIONS ---> Camera ---> yes
```

---

## CONTACTO 


---

