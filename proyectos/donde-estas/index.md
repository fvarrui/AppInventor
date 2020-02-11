# ¿Dónde estás?

La app que vamos a desarrollar en este proyecto permite localizar y compartir en tiempo real una ubicación en un plano (p.ej.: el plano del instituto, de nuestra casa, de un edificio, ...).

Para compartir información entre las apps se ha utilizado el componente **FirebaseDB**, que permite notificar a los dispositivos conectados cualquier cambio realizado a la información almacenada.

Firebase Token: 

```
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJkIjp7InVpZCI6IjU4NjQ1NTAzLTM3NzctNGI4ZS05ZmZkLTQ2YWE2ZjhhODg2ZSIsInByb2plY3QiOiJEb25kZUVzdGFzMiIsImRldmVsb3BlciI6ImZ2YXJydWlAaWVzZG9taW5nb3BlcmV6bWluaWs6ZXMifSwidiI6MCwiZXhwIjoxNjcyODgzNzUwOCwiaWF0IjoxNTgxNDQ4NzA4fQ.6LNn31dZ8N8Y8a_ZIdQk8Mj5ncvhoiLCcJMuwSufRkM
```

Project Bucket: `DondeEstas2`

[Descargar APK](DondeEstas2.apk)

## Medios

* Icono de la aplicación: [location.png](location.png).
* Plano: [mapa.jpg](mapa.jpg).
* Sonido: [picked.wav](picked.wav).

## Diseñar la interfaz

La interfaz de la pantalla principal será la siguiente:

![](interfaz.png)

## Comportamiento de la aplicación

### Variable global para almacenar la lista de colores disponibles

![](inicializar-global-colores.png)

### Cuando se toca el lienzo (plano)

![](cuando-lienzo1-tocar.png)

### Cuando se pulsa el botón de quitar el pin

![](cuando-quitarpin-clic.png)

### Cuando seleccionamos un color en el desplegable

![](cuando-desplegable1-despuesdeseleccionar.png)

### Cuando cambiamos los datos almacenados en FirebaseDB

![](cuando-firebasedb1-datachanged.png)

## Probar la aplicación

![](prueba.jpg)