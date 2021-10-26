# PROYECTO MEDIDOR DE AMOR


## Resumen

Este es un programa que mide temperatura y enciende LEDs.

setup:

Serial.begin (9600);

Incia la comunicacion por via USB 

for: sirve para repetir cosas 

loop:

primero declara una variable 

int sensorVal = analogRead (sensorpin)

Lee el voltage que teiene el pin

SensorPin ( en este caso A0= y lo magca a valoes entre 0 y 1023. 0 significa 0V o GND y 1023 significa SV.

Serial.print (" sensor valve: ",);

Serial,print (sensor val);

( sensor valve: ,); a esto se le llama STRING o cadena de caracteres.

float voltage = (sensorVal/124.0) * 5.0;

temperatura: float temperature = (voltage - 0.5) * 100;

LOOP:
Leer sensores
Tratar los datos del sensor
Pasamos de 0-023 a una temperatura 
Decidir que leds se encienden

if (temperature <baselineTemp){



## Introduccion teoria


# Proceso de montaje

-Materiales necesarios

 [-Circuito:](https://github.com/Ainhoa0512/ARDUINO/blob/main/love_o_meter.ino)

-Foto circuito:


![Captura de pantalla de 2021-10-26 13-48-02](https://user-images.githubusercontent.com/90753279/138871619-b5ecc928-3e10-4e5e-9f1e-46c0a70fec44.png)


## Código

-Explicar ""explicar codigo""

-Enlace al código utilizado

- Foto - Video - Funciona o no -

## Variaciones

