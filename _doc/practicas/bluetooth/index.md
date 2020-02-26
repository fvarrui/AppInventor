---
layout: practica
title: Bluetooth
excerpt: Envío de mensajes desde un cliente a un servidor mediante bluetooth.
icon:
  type: fa
  name: fa-bluetooth
color: blue
---

La siguiente aplicación permite la comunicación por Bluetooth de dos dispositivos. Un dispositivo desempeñará el rol de Servidor, que recibirá mensajes desde otro dispositivo, que hará de Cliente.

Desde la pantalla principal de la aplicación se podrá elegir si actuar como servidor o como cliente.

> :warning: Los dispositivos deben ser vinculados previamente desde los `Ajustes` del dispositivo.

## Medios

- No necesarios para este proyecto.

## Interfaz

La app contará con dos pantallas: 

- **Screen1**: Pantalla principal donde se podrá seleccionar entre Servidor o Cliente.
- **Cliente**: Pantalla desde la que se podrá conectar a un servidor y enviarle mensajes.
- **Servidor**: Pantalla desde la que se visualizarán los mensajes recibidos desde otro dispositivo.

### Screen1

![](screen1-interfaz.png)

### Cliente

![](cliente-interfaz.png)

## Servidor

![](servidor-interfaz.png)

## Comportamiento

### Screen1

#### Cambiar a la pantalla Cliente

Al pulsar el botón `Cliente` se abrirá la pantalla `Cliente`:

![](cuando-cliente-clic.png)

#### Cambiar a la pantalla Servidor

Al pulsar el botón `Servidor` se abrirá la pantalla `Servidor`:

![](cuando-servidor-clic.png)

### Cliente

#### Inicializar la pantalla `Cliente`

![](cuando-cliente-inicializar.png)

#### Seleccionar el servidor al que conectarse

![](cuando-conectar-antesdeseleccion.png)

#### Después de seleccionar el servidor

![](cuando-conectar-despuesdeseleccion.png)

#### Enviar un mensaje

![](cuando-enviar-clic.png)

#### Cerrar la pantalla actual y volver a  `Screen1`

![](cuando-volver-clic.png)

### Servidor

#### Inicializar la pantalla `Servidor`

![](cuando-servidor-inicializar.png)

#### Aceptar conexiones

![](cuando-aceptarconexion-clic.png)

#### Cuando se ha aceptado una conexión

![](cuando-servidorbluetooth1-conexionaceptada.png)

#### Comproabr si se han recibido datos

![](cuando-reloj1-temporizador.png)

#### Cerrar la conexión

![](cuando-desconectar-click.png)

#### Cerrar la pantalla y volver a `Screen1`

![](cuando-volver-clic.png)


## Prueba

![](prueba.png)