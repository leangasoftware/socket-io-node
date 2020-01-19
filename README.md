# Entrevista Socket.io-Node

![](https://miro.medium.com/max/2792/1*tWm33yhceKIL22QqOORu2w.png)

Bienvenido a tu prueba de __Socket.io-Node__, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
- Pensamiento lógico.
- Resolución de problema.
- Tiempo de desarrollo.
- Entre otros.


Finalizada la prueba recuerda enviar link del proyecto o tu repositorio a [desarrollo@leangasoftware.es](mailto:desarrollo@leangasoftware.es) con tu información de contacto y en el asunto colocar: 
__SOCKET-NODE-INTERVIEW__


> Recomendación: No importa terminar todos los ejercicios, lo más importante es la funcionalidad del ejercicio resuelto(s).

### Contexto:
En algunos casos necesitamos compartir código con nuestros compañeros, profesores, etc. Necesitamos una herramienta en la cual haciendo uso de Socket y Node establecer una "Sala" en la cual con una URL única se pueda compartir, y editar por cada uno de los participantes  sin necesidad de logearse ni registrarse solo compartiendo la URL se puedan unir de 1 a 3 personas y poder colaborar en tiempo real.

![](https://cdn.loom.com/sessions/thumbnails/e435231a4b564b20ac3c8cde5dcd2f9a-00001.gif)
> __Atención__ La imagen es referencial, pero se quiere representar la idea, no debe ser exactamente igual.

# Ejercicios

### Antes de empezar:
- Para el front se debe hacer uso de alguna de estas tecnologías
    - Angular
    - AngularJS
    - ReactJS
- Se debe desplegar en un servidor propio o heroku para poder probar exitosamente el proyecto

### 1. Home.
![](https://i.imgur.com/iNPMkzQ.png)

__REQUERIMIENTO:__
Se requiere en home, pedir un "N" limite de usuarios y tu nick de usuario luego retornara una URL de link único.
Ejemplo: 'http://compartocodigo.demo/96puo'

- Vista __404__
	- RUTA: `/404`
	- HTML: A tu gusto.
	- __NOTA:__ Debes poder re-direccionar rutas que no existan a `404`

___
### 2. Unirse a Sala.
![](https://i.imgur.com/QoaPE8u.png)

__REQUERIMIENTO:__
Se requiere que se pueda unirse a la sala ingresando un "Nick" y siempre que exista cupo para unirse.

- Vista __JOIN__
	- RUTA: `/{unique_code}`
	- HTML: A tu gusto.
	- __NOTA:__ Debes poder re-direccionar rutas que no existan a `404`
___

### 3. Participación
![](https://i.imgur.com/5lU1Xg2.png)

__REQUERIMIENTO:__
Se debe poder editar código o texto en tiempo real por todos los participantes unidos a la sala.

### 4. Style y Export

![](https://i.imgur.com/vW20VPl.png)

__REQUERIMIENTO:__
Se debe implementar un "rich-text" el cual le de un estilo de colores al código, por otro parte se debe agregar un botón para poder descargar el código en un archivo.

Gracias por participar! 
