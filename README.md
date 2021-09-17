
UNIVERSIDAD DE LAS FUERZAS ARMADAS (ESPE)     ![image](https://user-images.githubusercontent.com/88467497/133656171-c0eee408-9fc0-4a82-81dc-2aaeab0e7787.png)
========================

## Datos 

- Nombre: César Garnica
- Nrc: 5416
- Carrera: Ingeniera en Telecomunicaciones 
- Materia: Fundamentos de circuitos eléctricos 

## Tema 
 - Ejemplo para simular una red IoT con Packet Tracer

## Objetivo

     Objetivo General:
     
     - Realizar un estudio que permita establecer una propuesta de aplicación de Internet de
     las Cosas en la solución o mejora de los procesos de interacción que realiza una persona en
     diferentes entornos simulados como son hogar, laboral y académico.
     
     Ojetivos Especificos:
     
     - Investigar qué dispositivos IoT se podrían encontrar el entorno hogar, laboral o
     académico.
     - Buscar los ejes cruciales de funcionamiento y posibles usos o configuraciones en
     el entorno hogar, laboral y académico.
     - Realizar una propuesta por cada uno de los entornos para enriquecer la
     experiencia con los usuarios y mejorar su calidad de vida.
     
## Desarrollo 

**Instalacion Del Programa**

Paso 1. Ir a Cisco Networking Academy, arriba a la derecha clic en Log In, Login. Ingresar con tu usuario o bien darte de alta si es que aún no tenés una cuenta (requerido).

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%201.PNG)

Una vez iniciamos sesión podemos ir directamente a la zona de descarga de Cisco Packet Tracer.

A mitad de página aproximadamente podrás encontrar la link para descarga; Windows Desktop Version 7.3.1 English en nuestro caso.

Clic en la versión que requieras para tu equipo y guardar el archivo.

Paso 2. Instalar Cisco Packet Tracer
Doble clic al instalador.

Aceptamos el contrato de licencia y clic a Next.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%202.PNG)

Paso 3. Indicamos carpeta de instalación o aceptamos la sugerida y clic a Next.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%203.PNG)

Paso 4. Aceptamos nombre de carpeta de menú sugerida o modificamos y clic en Next.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%204.PNG)

Paso 5. Revisamos opciones de accesos directos y clic en Next.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%205.PNG)

Paso 6. Todo listo! Clic en Install.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%206.PNG)

Paso 7. Si todo va bien un ratito después veremos la pantalla de finalización, clic en Finish.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%207.PNG)

Paso 8. En esta instancia se abre la aplicación. Es probable que nos pida nuevamente las credenciales de nuestra cuenta de Cisco Networking Academy.

Y listo, nuestra herramienta de simulación lista para utilizarse.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Paso%208.PNG)

**Una red IoT**

Es la agrupación e interconexión de dispositivos y objetos a través de una red (bien sea privada o Internet, la red de redes), dónde todos ellos podrían ser visibles e interaccionar. Respecto al tipo de objetos o dispositivos podrían ser cualquiera, desde sensores y dispositivos mecánicos hasta objetos cotidianos como pueden ser el frigorífico, el calzado o la ropa.
Como se puede ver, IoT está ya aquí y es una realidad, su ámbito de aplicación es muy amplio y cada día surgen más y más dispositivos que hacen posible esta tecnología. Dicha tecnología asociada al IoT permite recoger datos y mandarlos a la red para su análisis o incluso realizar un análisis previo y después mandarlos a la red.

**IoT empresarial**

Las soluciones de IoT para empresas les permiten mejorar los modelos comerciales actuales y entablar nuevas relaciones con los clientes y los partners. No obstante, su implementación presenta ciertos desafíos.El volumen de datos que genera un sistema de dispositivos inteligentes (lo cual se conoce como big data) puede volverse abrumador.Integrar el big data a los sistemas actuales y configurar el análisis de datos para poder utilizarlos puede resultar complicado.

**10 Tendencias del Intenert de las cosas para 2020**

- CRECIMIENTO EN DATOS Y DISPOSITIVOS CON MÁS INTERACCIÓN HUMANO-DISPOSITIVO.
- LA INTELIGENCIA ARTIFICIAL, CLAVE EN EL IoT (DE NUEVO).
- VUI: LAS INTERFACES DE USUARIO POR VOZ (VOICE USER INTERFACE) SERÁN UNA REALIDAD.
- MÁS INVERSIONES EN IoT.
- FINALMENTE, LA EXPANSIÓN REAL DEL IOT PEQUEÑO.

**Pantalla Principal de Cisco Packet Tracer**

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/menus-principales-en-packet-tracer.png)

A continución prodecemos a explicar un ejemplo para simular una red IoT con Packet Tracer.

El ejemplo que a continuacion va hacer presentado, es de una red que esta siendo conectada en un plano de una casa. Esta red IoT, es una red sencilla que usamos para las cosas que no pueden ser conectadas o nunca han sido conectadas. Hare una breve explicación de como fueron conectados lo utilizado en dicho ejemplo.

1. Como primera parte, esta el haber agregado la imagen de fondo de un plano de una casa y tomar como referencia donde poder ubicar nuestras cosas que van hacer conectadas.
2. Como segundo, agregramos las conexiones que que vamos a ocupar, en este caso la que vamos a ocupar es una conexion de Wireless Divices, con el nombre mas específico que es la de Home Gateway. Esta conexión es un muy facil de usarla, ya que no nesecitamos usar algun tipo de lengauje o que sea progrmable lo antes mencionado.
![](https://github.com/cagarnica/Imagenes-IoT/blob/main/HomeGateway.PNG)

3. Como tercero, hacemos la ubicacion de las cosas que vamos a querer que se conecten al HomeGateway, que en este caso ocupamos varias cosas para poder observar de como se hace una conexión. En este caso, ocupamos lo que es una lámpara, un ventilador, una cafetera, ventenas y un equipo de sonido. Como antes indique, este dispositivo inalámbrico es un poco sencillo para que se hagan las conexeciones, solo tenemos que tomar en cuenta ciertos parámetros, que son los siguientes. El rato que nosotros agregamos los objetos que desea utilizar, hay que hacer algunas configuraciones dentro de este dispositivo. Sin embargo, lo único que tenemos que tomar en cuenta, es que tengamos en la opcion de IoT Server activado la opcion del HomeGateway. Tambien vamos a tener que cambiarle el nombre en la parte de Wirelesss, exactamente en la opcion de SSDI con el nombre del dispositivo que estamos ocupando, en este caso es el de HomeGateway, para que asi se nos haga la conexión directa. A continuación indicare en las siguientes imagenes, como debemos de tener en cada unas de nuestras cosas que estan ubicadas en nuestro plano

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Conexion.PNG)

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/SSID.PNG)

4. Como cuarto punto, tendremos que ubicar los dispositvos por el cual vamos hacer el manejo de las cosas que estan ubicadas en el plano. Para esto, ocupamos lo que es un smartphone y una lapto. Tenemos mas opciones con las cuales podemos trabajar, pero estas son las más utilizadas por los usuarios. Cada dispositivo tiene su propia configuración.  En este caso se podria decir que la mas compleja en ser utilizada es la laptop. Ya que tenemos que hacer un cambio de tarjeta con la cual estamos trabajando las cosas que hemos utilizado, y hacer casi una misma configuración como las cosas que están en el plano. De igual manera, a continuación voy a presentar en una imagen lo que tenemos que hacer.

Laptop:

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Laptop.png)

Lo que tenemos que hacer aquí es, apagar al computador para poder sacar la tarjeta, y asi poder tener una misma conexión con lo que sera el dispositivo inalámbrico.

Una vez hecho estos pasos tendremos la conexión establecida.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionLaptop.PNG)

Smartphone:

En este dispositivo es algo mas sencillo de hacer, ya que solo tenemos que hacer el cambio de nombre en la parte de Wirless, SSDI.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/SSID.PNG)

Una vez hecho estos pasos tendremos la conexión establecida.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionSmartphone.PNG)

5. Como quinto y ultimo paso, tenemos que hacer la comprobación de que cada dispositivo nos funcione de manera correcta. A continuación, indicaré como es la funcionalidad de cada una de las cosas. Tendren que entra en cada dispositivo, entrar en la parte de desktop y ahi ver las cosas que tenemos conectadas.

Laptop:

En lo que es la cuestión de la laptop, podemos observar que nos aparece con un botón verde, esto nos está indicando que todas las cosas están conectadas correctamente. Pero para antes de pasar a la parte de ver las cosas conectadas, tenemos que inciar sesión con usuario y contraseña que nos estan proporcionando.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/Login.PNG)

Una vez hecho esto, procedemos a ver las conexiones. Aquí, podemos observar que, tenemos unos botones donde podremos interactuar para que cada cosa cumpla su función.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionM.PNG)

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionM.1.PNG)

Smartphone:

En lo que es la cuestión del smartphone, podemos observar que nos aparece con un botón verde, esto nos está indicando que todas las cosas están conectadas correctamente. Pero para antes de pasar a la parte de ver las cosas conectadas, tenemos que inciar sesión con usuario y contraseña que nos estan proporcionando. Es lo mismo proceso que de la laptop.

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionM.PNG)

![](https://github.com/cagarnica/Imagenes-IoT/blob/main/ConexionM.1.PNG)
 
Con esto finalizamos la explicación de dicho ejemplo.

## VIDEO
- https://www.youtube.com/watch?v=DqSF19PrQUM

## Conclusiones

- Se realizó el diseño de una red casera de Internet de las cosas IoT, la cual se puede acceder y administrar desde cualquier dispositivo o desde un dispositivo de escritorio, es decir, que de manera remota se pueda abrir una puerta o ver quien ha ingresado a través de la misma.
- Se estableció cuáles son los requerimientos mínimos para diseñar una red de Internet de las cosas IoT en un hogar, siendo una tecnología muy fácil de implementar teniendo todos los dispositivos y requerimientos ya establecidos.
- Se esquematizó y se probó una red de IoT por medio del simulador de Packet Tracer obteniendo resultados satisfactorios.

## Bibliografia 

- https://www2.deloitte.com/es/es/pages/technology/articles/IoT-internet-of-things.html
- https://www.telcel.com/empresas/tendencias/notas/como-funciona-iot#
- https://www.redhat.com/es/topics/internet-of-things/what-is-iot
- https://www.bbvaopenmind.com/tecnologia/mundo-digital/diez-tendencias-del-internet-de-las-cosas-en-2020/
- https://www.netacad.com/es/courses/packet-tracer
