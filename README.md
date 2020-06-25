# Generar máquinas virtuales en Microsof Azure

1. Planteamiento del Problema

Dentro del mundo de la informática los avances tecnologicos han llevado al desarrollo de muchos sistemas operativos varias actualizaciones para tratar de mejorarlos cada vez y que los usuarios tengas una experincia satisfactoria al momento de usar dichos sistemas operativos.
Cada sistema operativo posee un propósito general y debido al gran número de sistemas operativos que existen, las personas que estan encargadas de probar el correcto funcionamiento de estos actualizaciones, mejor conocidos como "beta testers", se ven obligados a instalar y desintalar los sitemas operativos para de esta forma poder detercar posibles fallas.

Esto seria un verdadero dolor de para los beta testes si no existieran las maquinas virtuales por esta razon se crearon las máquinas virtuales que en el mundo de la informática es un software que emula a un ordenador y puede ejecutar programas como si fuese un ordenador real. En otras palabras, estaríamos teniendo un ordenador (virtual) dentro de nuestro ordenador y, en consecuencia, poder realizar esta actividad en los ordenadores trae un montón de beneficios como por ejemplo: 
No hay necesidad de tener otro ordenador (físico) para instalar o probar software, podemos ajustar las configuraciones de la máquina virtual a nuestras necesidades, se abre la posibilidad de tener distintos sistemas operativos sin necesidad de crear particiones o tener más discos duros o simplemente nos puede servir para provar software que aún estan en fase de pruebas(versiones beta, alfa, etc.) y tener la certeza que no afectara a nuestro sistema operativo base.
Microsoft Azure nos brinda el beneficio de generar máquinar virtuales y almacenarlas de forma segura en su nube. Con la ayuda de este programa aprenderemos a generar maquinas virtuales.

2. Objetivos 

2.1. Objetivo General

* Realizar un tutorial en Microsoft Azure para la generación de máquinas virtuales.

2.2. Objetivos Específicos

* Conocer qué es y para qué sirve Microsoft Azure

* Aprender y explicar cómo crear una máquina virtual en Microsoft Azure 

3. Estado del Arte 

**Modelo Comparativo de Plataformas Cloud y Evaluación de Microsoft Azure, Google App Engine y Amazon EC2**

La computación en la nube es un modelo de prestación y consumo de servicios que ofrece muchas ventajas a las empresas (alta disponibilidad, elasticidad, máximo aprovechamiento de recursos, etc.) que se traducen en requisitos de calidad que deben ser cumplidos por el servicio. Sin embargo, la elección de una plataforma de cloud computing puede ser
complicada desde el punto de vista del usuario, ya que no está claro las ventajas y limitaciones de cada una de ellas y por lo tanto hay cierta incertidumbre a la hora de realizar esta selección. Dentro del cloud computing existen distintos roles, en este proyecto hablaremos de los 3 más reconocidos. El consumidor, persona que contrata los servicios de un proveedor y utiliza sus servicios. El proveedor, entidad que proporciona los servicios cloud computing. Y, por último, el bróker o intermediario, entidad que media entre el consumidor y el proveedor, velando por el cumplimiento del contrato entre ambos. Existen varios proveedores de servicios en la nube, siendo Microsoft, Google y
Amazon los más importantes. Otros proveedores relevantes son Rackspace, IBM, Oracle, Salesforce, etc. Por lo tanto, existe una alta competencia de proveedores de servicios en la nube, basada en los precios a los que ofertan los recursos. Sin embargo, los proveedores deben considerar otro factor diferenciador más allá del precio de oferta: la calidad de sus servicios.

**Autor**

José Miguel Álvarez Vañó

**Lugar y Fecha de Publicación**

Valencia, España

17 de Junio de 2019

Este artículo tiene como propósito guiar o explicar los beneficios que se obtienen al utizar software que permiten almacenar datos en su nube. Además, hace comparación entre varias plataformas mostrando todas las ventajas que poseen.

**Las ventajas de la utilización de Microsoft Azure en proyectos Open Source**

El semillero de investigación CLOIT de la Universidad EAN, durante el primer periodo académico de 2016, presenta el producto de investigación acerca de la utilización de tecnologías de código abierto soportadas en Microsoft Azure, que reflejan el resultado de divulgación y aplicación del conocimiento para la implementación de aplicativos de software, incorporando sistemas operativos Linux sin importar la distribución, paquetes y servicios, que serán configurados para su funcionamiento en contextos empresariales y académicos. Dentro del proceso de investigación se realizó una prueba de concepto implementado en un sitio web con Microsoft Azure, que usa el sistema operativo Linux y tecnologías de código abierto, utilizando una máquina virtual en la modalidad de infraestructura como servicio o IaaS.

**Autores**

* Edy Rodríguez Meza 

* Daniel Rodrigo Vargas Imbachi

**Lugar y Fecha de Publicación**

Bogotá, Colombia

14 de Noviembre del 2019

4. Marco Teórico 

Microsoft Azure

Microsoft Azure o como era conocido antes Windows Azure, es una plataforma de computación en una nube pública de pago por uso que sirve para administrar, organizar, gestionar ciertas necesidades que están orientadas a actividades comerciales (Microsoft Azure, s.f.).

![f1](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f1.png)

Además, proporciona un cierto número de servicios entre los cuales están incluidos computación, analítica, almacenamiento y redes. Los usuarios registrados pueden acceder a estos servicios para crear nuevas aplicaciones o simplemente usar las que se encuentran en la nube pública. (Rouse, 2017).
Microsoft Azure fue lanzado en octubre del 2008 originalmente se llamaba Windows Azure, pero fue cambiada de marca a Microsoft Azure en abril de 2014. Azure compite con otras plataformas de nube pública, incluyendo Amazon Web Services (AWS) y Google Cloud Platform. (Parada, 2019)
La mayoría de empresas usan Microsoft Azure para poder respaldar y almacenar sus datos además de ejecutar sus aplicaciones para reducir los costos en vez de invertir en servidores y almacenamiento local (Parada, 2019). 

5. Tutorial 

Para la creación de maquinas virtuales se debe seguir los siguientes pasos:

5.1.	Ingresar a la página principal de Microsoft Azure (https://azure.microsoft.com/es-es/)

![f2](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f2.png)

5.2.	Presionamos el botón “cuenta gratuita” que se encuentra ubicado en la parte superior derecha de la pantalla. 

![f3](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f3.png)

5.3.	Se desplegará una nueva página en la cual nos pregunta si queremos usar Microsoft Azure gratuitamente o si queremos adquirir una licencia para obtener más Beneficios.

![f4](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f4.png)

Si nos desplazamos un poco más hacia debajo de la página podremos ver los beneficios que Microsoft Azure nos ofrece con la cuenta gratuita que será la que usaremos para desarrollar este tutorial.

![f5](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f5.png)

5.4.	Seleccionamos la opcion “Empiece gratis” que nos direccionara hacia otra pagina en la cual debemos ingresar con nuestra cuenta de hotmail, outlook o con nuestra cuenta de Github en caso de tenerla. Para nuestro caso ingresaremos con una cuenta de hotmail.

![f6](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f6.png)

5.5.	Una vez iniciada sesion con nuestra cuenta de hotmail nos redireccionara a la siguiente pagina: 

![f7](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f7.png)

A continuacion debemos llenar todos los satos que nos soliciten.

5.6.	En la parte 2 de los datos que debemos llenar nos solicitara un número de teléfono para enviar un código de verificación, debemos asegurarnos que el número de teléfono que ingresemos sea el correcto, caso contrario no recibiremos el codigo de verificacion para la activación de nuestra cuenta de Microsoft Azure.

5.7.  En el punto 3 del registro nos pedirá que ingresemos una tarjeta de crédito para verificar nuestra identidad, cabe recalcalcar que no nos cobrarán nungún recargo por ingresar la tarjeta de crédito.

5.8.	Luego de leer los términos y condiciones marcamos el casillero aceptando que los hemos leido y para finalizar le damos clic en el botón “registrarse”. Asi finalizaremos el registro en microsoft Azure 

![f8](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f8.png)

5.9.	Se despliega la siguiente página

![f9](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f9.png)

Damos clic en el botón “ir al portal”.

5.10.	A continuación, nos aparecerá la siguiente pantalla.

 ![f10](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f10.png)

Aquí seleccionamos la opción que dice implementación de una máquina virtual.

5.11.	Como paso siguiente elegimos si queremos una maquinar virtual de Linux o de windows. en nuestro caso seleccionaremos una maquina virtual en el entorno de windows.

![f11](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f11.png)

5.12.	Damos clic en el botón “Crear” y se nos desplegará un cuadro de texto el cual nos indica que son las maquinas virtuales y para qué sirven. Nos dirigimos al final de ese cuadro de texto y volvemos a presionar el botón “crear”.

5.13.	En la página que se despliega llenamos todos los campos para nuestra máquina virtual sobre todo el nombre de nuestra máquina virtual y el sistema operativo que vayamos a usar.

![f12](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f12.png)

Seleccionamos el windows server 2016 , el tamaño se elige por defecto pero nosotros podemos cambiar el tamaño que usaremos dependiendo de la el uso que le vayas a dar a la maquina virtual, en esta ocacion dejaremos con el default.

5.14.	Le ponemos un nombre de ususario y contraseña que debemos recordar

![f13](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f13.png)

5.15.	Damos clic en revisar y crear

5.16.	La siguiente pantalla nos muestra las especificaciones de nuestra maquina virtual y el costo que tiene de uso por hora.

![f14](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f14.png)

5.17.	Damos clic en el botón crear. Esto podría tardar unos minutos.

5.18.	Cuando aparezca el siguiente mensaje sabremos que se creó correctamente nuestra máquina virtual.

![f15](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f15.png)

5.19.	Damos clic en el botón ir al recurso 

5.20.	Para abrir nuestra máquina virtual damos clic en el botón conectar

![f16](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f16.png)

5.21.	Seleccionamos la opción RDP

5.22.	Descargamos el archivo RPD

![f17](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f17.png)

5.23.	Le damos doble clic al archivo que se descargó.

5.24.	Aparecerá la siguiente ventana:

![f18](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f18.png)

5.25.	Damos clic en “conectar”.

5.26.	Escribirnos el usuario y contraseña de nuestra máquina virtual.

![f19](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f19.png)

5.27.	Damos clic en aceptar

5.28.	En la siguiente ventana damos clic en “si”

![f20](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f20.png)

Y listo! Habremos creado exitosamente la maquina virtual.

![f21](https://github.com/JorgeGallegos99/Trabajo-Extra-/blob/master/Img/f21.jpg)
