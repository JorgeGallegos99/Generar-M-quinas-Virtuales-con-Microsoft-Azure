# Generar máquinas virtuales en Microsof Azure

**Introducción**

Dentro del mundo de la informática los avances tecnologicos han llevado al desarrollo de muchos sistemas operativos y con estos varias actualizaciones para tratar de mejorarlos cada vez para que los usuarios tengan una experiencia satisfactoria al momento de usar dichos sistemas operativos.
Cada sistema operativo posee un propósito general y debido al gran número de sistemas operativos que existen, las personas que están encargadas de probar el correcto funcionamiento de estas actualizaciones, mejor conocidos como "beta testers", se ven obligados a instalar y desintalar los sitemas operativos para de esta forma poder detercar posibles fallas.

Esto sería un verdadero dolor de para los beta testes si no existieran las máquinas virtuales.

Por esta razón se crearon las máquinas virtuales que en el mundo de la informática es un software que emula a un ordenador y puede ejecutar programas como si fuese un ordenador real. En otras palabras, estaríamos teniendo un ordenador (virtual) dentro de nuestro ordenador y, en consecuencia, poder realizar esta actividad en los ordenadores trae un montón de beneficios como por ejemplo: 
No hay necesidad de tener otro ordenador (físico) para instalar o probar software, podemos ajustar las configuraciones de la máquina virtual a nuestras necesidades, se abre la posibilidad de tener distintos sistemas operativos sin necesidad de crear particiones o tener más discos duros o simplemente nos puede servir para provar software que aún estan en fase de pruebas(versiones beta, alfa, etc.) y tener la certeza que no afectara a nuestro sistema operativo base.
Microsoft Azure nos brinda el beneficio de generar máquinar virtuales y almacenarlas de forma segura en su nube. Con la ayuda de este programa aprenderemos a generar maquinas virtuales.

**Objetivos** 

**Objetivo General**

* Realizar un tutorial en Microsoft Azure para la generación de máquinas virtuales.

**Objetivos Específicos**

* Conocer qué es y para qué sirve Microsoft Azure

* Aprender y explicar cómo crear una máquina virtual en Microsoft Azure 

**Microsoft Azure**

Microsoft Azure o como era conocido antes Windows Azure, es una plataforma de computación en una nube pública de pago por uso que sirve para administrar, organizar, gestionar ciertas necesidades que están orientadas a actividades comerciales (Microsoft Azure, s.f.).

![f1](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f1.png)

Además, proporciona un cierto número de servicios entre los cuales están incluidos computación, analítica, almacenamiento y redes. Los usuarios registrados pueden acceder a estos servicios para crear nuevas aplicaciones o simplemente usar las que se encuentran en la nube pública. (Rouse, 2017).
Microsoft Azure fue lanzado en octubre del 2008 originalmente se llamaba Windows Azure, pero fue cambiada de marca a Microsoft Azure en abril de 2014. Azure compite con otras plataformas de nube pública, incluyendo Amazon Web Services (AWS) y Google Cloud Platform. (Parada, 2019)
La mayoría de empresas usan Microsoft Azure para poder respaldar y almacenar sus datos además de ejecutar sus aplicaciones para reducir los costos en vez de invertir en servidores y almacenamiento local (Parada, 2019). 

Al igual que con otras plataformas de nube pública, algunas organizaciones utilizan Azure para el respaldo de datos y la recuperación de desastres. Además, algunas organizaciones utilizan Azure como una alternativa a su propio centro de datos. En lugar de invertir en servidores y almacenamiento locales, estas organizaciones optan por ejecutar algunas o todas sus aplicaciones de negocio en Azure.

Para garantizar la disponibilidad, Microsoft tiene centros de datos de Azure ubicados en todo el mundo. A partir de enero de 2016, Microsoft dijo que los servicios de Azure están disponibles en 22 regiones de todo el mundo, incluyendo en los Estados Unidos, Europa, Asia, Australia y Brasil.

Al igual que ocurre con otros proveedores de nube pública, Azure utiliza principalmente un modelo de precios de pago ‘como va’, que se carga basado en el uso. Sin embargo, una sola aplicación puede utilizar múltiples servicios de Azure, por lo que los usuarios deben revisar y administrar el uso para minimizar los costos.

**Licencias**

**Licencia para estudiantes**

Azure para estudiantes le ayuda a comenzar con $100 en créditos de Azure que puede usar durante los 12 primeros meses junto con algunos servicios gratuitos (sujetos a cambios), sin necesidad de facilitar una tarjeta de crédito al suscribirse.

Azure para estudiantes está disponible para aquellos estudiantes que cumplan los siguientes requisitos. Debe confirmar que tiene 18 años o más y que asiste a una institución educativa acreditada que ofrece estudios de grado de dos o cuatro años, donde es alumno a tiempo completo. Debe acreditar su condición académica con la dirección de correo electrónico de la organización.

**Licencia Gratuita**

Con esta licencia tendremos acceso a todos los recursos mas populares de Microsoft Azure durante 12 meses, ademas, nos dan un credito de 170 para poder explorar a fondo la platafroma durante 30 dias y por ultimo nos ofrece mas de 25 servicios que siempre seran gratuitos.

**Licencia Pagada**

Cuando decidamos actualizar la licencia que tenemos por una Pagada podremos acceder a absolutamente todos los servicios que brinda microsoft Azure con precios de pago por uso. el costo dependera de los servicios que solicitemos y usemos a lo largo del mes

**Tutorial** 

Para la creación de maquinas virtuales se debe seguir los siguientes pasos:

1. Ingresar a la página principal de Microsoft Azure (https://azure.microsoft.com/es-es/)

![f2](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f2.png)

2.	Presionamos el botón “cuenta gratuita” que se encuentra ubicado en la parte superior derecha de la pantalla. 

![f3](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f3.png)

3.	Se desplegará una nueva página en la cual nos pregunta si queremos usar Microsoft Azure gratuitamente o si queremos adquirir una licencia para obtener más Beneficios.

![f4](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f4.png)

Si nos desplazamos un poco más hacia debajo de la página podremos ver los beneficios que Microsoft Azure nos ofrece con la cuenta gratuita que será la que usaremos para desarrollar este tutorial.

![f5](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f5.png)

4.	Seleccionamos la opcion “Empiece gratis” que nos direccionara hacia otra pagina en la cual debemos ingresar con nuestra cuenta de hotmail, outlook o con nuestra cuenta de Github en caso de tenerla. Para nuestro caso ingresaremos con una cuenta de hotmail.

![f6](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f6.png)

5.	Una vez iniciada sesion con nuestra cuenta de hotmail nos redireccionara a la siguiente pagina: 

![f7](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f7.png)

A continuacion debemos llenar todos los satos que nos soliciten.

6.	En la parte 2 de los datos que debemos llenar nos solicitará un número de teléfono para enviar un código de verificación, debemos asegurarnos que el número de teléfono que ingresemos sea el correcto, caso contrario no recibiremos el codigo de verificacion para la activación de nuestra cuenta de Microsoft Azure.

7.  En el punto 3 del registro nos pedirá que ingresemos una tarjeta de crédito para verificar nuestra identidad, cabe recalcalcar que no nos cobrarán nungún recargo por ingresar la tarjeta de crédito.

8.	Luego de leer los términos y condiciones marcamos el casillero aceptando que los hemos leido y para finalizar le damos clic en el botón “registrarse”. Asi finalizaremos el registro en microsoft Azure 

![f8](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f8.png)

9.	Se despliega la siguiente página

![f9](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f9.png)

Damos clic en el botón “ir al portal”.

10.	A continuación, nos aparecerá la siguiente pantalla.

 ![f10](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f10.png)

Aquí seleccionamos la opción que dice implementación de una máquina virtual.

11.	Como paso siguiente elegimos si queremos una maquinar virtual de Linux o de windows. en nuestro caso seleccionaremos una maquina virtual en el entorno de windows.

![f11](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f11.png)

12.	Damos clic en el botón “Crear” y se nos desplegará un cuadro de texto el cual nos indica que son las maquinas virtuales y para qué sirven. Nos dirigimos al final de ese cuadro de texto y volvemos a presionar el botón “crear”.

13.	En la página que se despliega llenamos todos los campos para nuestra máquina virtual sobre todo el nombre de nuestra máquina virtual y el sistema operativo que vayamos a usar.

![f12](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f12.png)

Seleccionamos el windows server 2016 , el tamaño se elige por defecto pero nosotros podemos cambiar el tamaño que usaremos dependiendo de la el uso que le vayas a dar a la maquina virtual, en esta ocacion dejaremos con el default.

14.	Le ponemos un nombre de ususario y contraseña que debemos recordar

![f13](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f13.png)

15.	Damos clic en revisar y crear

16.	La siguiente pantalla nos muestra las especificaciones de nuestra maquina virtual y el costo que tiene de uso por hora.

![f14](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f14.png)

17.	Damos clic en el botón crear. Esto podría tardar unos minutos.

18.	Cuando aparezca el siguiente mensaje sabremos que se creó correctamente nuestra máquina virtual.

![f15](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f15.png)

19.	Damos clic en el botón ir al recurso 

20.	Para abrir nuestra máquina virtual damos clic en el botón conectar

![f16](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f16.png)

21.	Seleccionamos la opción RDP

22.	Descargamos el archivo RPD

![f17](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f17.png)

23.	Le damos doble clic al archivo que se descargó.

24.	Aparecerá la siguiente ventana:

![f18](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f18.png)

25.	Damos clic en “conectar”.

26.	Escribirnos el usuario y contraseña de nuestra máquina virtual.

![f19](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f19.png)

27.	Damos clic en aceptar

28.	En la siguiente ventana damos clic en “si”

![f20](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f20.png)

Y listo! Habremos creado exitosamente la maquina virtual.

![f21](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f21.jpg)

**Conclusiones**

* Microsoft Azure es una plataforma que ofrece varios servicios gratuitos por determidado tiempo y podemos aceder completamente a ellos si compramos una licencia. Sin embargo, con el peridodo de prueba que nos dan se puede realizar varias pruebas con todos los servicios que ofrece, obiamente tedrán su limitaciones.
esta plataforma está orientada a las grandes empresas.

* La creacion de maquinas virtuales en relativamente sencilla, solo debemos tener en cuenta cierutos parametros que debemos elegir para crear adecuadamente nuestra maquina virtual y podamos ajustarla a nuestras necesidades.

**Bibliografía**

* Álvarez Vañó, J. M. (17 de Junio de 2019). Universisdad Politécnica de Valencia. Obtenido de Modelo Comparativo de Plataformas Cloud y Evaluación de Microsoft Azure, Google App Engine y Amazon EC2: https://riunet.upv.es/bitstream/handle/10251/101221/%c3%81LVAREZ%20-%20Modelo%20Comparativo%20de%20Plataformas%20Cloud%20y%20Evaluaci%c3%b3n%20de%20Microsoft%20Azure%2c%20Google%20App%20Eng....pdf?sequence=1&isAllowed=y

* Parada, M. (28 de Octubre de 2019). OpenWebinars. Obtenido de https://openwebinars.net/blog/que-es-azure/

* Ramírez, I. (25 de Julio de 2016). Xataka. Obtenido de https://www.xataka.com/especiales/maquinas-virtuales-que-son-como-funcionan-y-como-utilizarlas

* Rodríguez Meza, E., & Vargas Imbachi, D. R. (14 de Noviembre de 2019). Universidad EAN. Obtenido de Las ventajas de la utilización de Microsoft Azure en proyectos Open Source: https://repository.ean.edu.co/bitstream/handle/10882/9018/EstrategiasCompetitividad2016.pdf?sequence=1&isAllowed=y#page=6

* Rouse, M. (Marzo de 2017). Search Data Center en español. Obtenido de TechTarget: https://searchdatacenter.techtarget.com/es/definicion/Microsoft-Azure-Windows-Azure


