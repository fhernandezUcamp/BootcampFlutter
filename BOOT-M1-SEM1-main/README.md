
![Banner](imagenes/banner.png)

# M1S1: Introducción al desarrollo de apps multiplataforma

> #### **¡Hola, damos inicio al módulo 1!**
> #### Espero te encuentres muy bien y con mucha motivación para continuar el recorrido del diseño y creación de Apps multiplataforma, en la presente sesión conoceremos los inicios del desarrollo de una App de forma nativa y multiplataforma, no te preocupes entenderás todos estos conceptos muy pronto, así mismo se te ayuda a configurar tu entorno para poder crear Apps ya sea en Windows, Mac o Linux.
> #### **Continuemos...**

# Objetivo por semana 
> ### Al término de esta semana el participante, conocerá los términos teóricos sobre el desarrollo de aplicaciones multiplataforma, nos adentraremos en cómo utlizar Flutter como plataforma tecnologica para desarrollo de apps para móviles Android y iOS, y otros dispositivos y el participante configurará su entorno de desarrollo en Flutter.


# ÍNDICE

- [El desarrollo de aplicaciones nativas (Móviles,Web, Escritorio)](https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/README.md#el-desarrollo-de-aplicaciones-nativas-m%C3%B3vilesweb-escritorio)
- [La actualidad sobre el desarrollo de aplicaciones multiplataforma](https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/README.md#la-actualidad-sobre-el-desarrollo-de-aplicaciones-multiplataforma)
- [Qué es Flutter y por qué usarlo](https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/README.md#herramientas-lowcodenocode-para-flutter)
- [Herramientas LowCode/NoCode para Flutter](https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/README.md#herramientas-lowcodenocode-para-flutter)
- [Los requisitos previos para crear aplicaciones con Flutter] (https://github.com/BootcampFlutter/BOOT-M1-SEM1#atributos-html)
- [La configuración del entorno de desarrollo en Windows](https://github.com/BootcampFlutter/BOOT-M1-SEM1#atributos-html)      
- [La configuración del entorno de desarrollo en MacOS](https://github.com/BootcampFlutter/BOOT-M1-SEM1#im%C3%A1genes-svg)
- [El primer programa realizado en Flutter (Hola mundo desde Flutter!)](https://github.com/BootcampFlutter/BOOT-M1-SEM1#im%C3%A1genes-svg)
- [La anatomía de una aplicación en Flutter!)](https://github.com/BootcampFlutter/BOOT-M1-SEM1#im%C3%A1genes-svg)

# El desarrollo de aplicaciones nativas (Móviles,Web, Escritorio)

El desarrollo de las aplicaciones nativas hace alusión a que emplea el lenguaje nativo de la plataforma para la construcción de la misma, por ejemplo, el desarrollo de aplicaciones en el sistema operativo en Android que serian en los lenguajes tales como Java, Kotlin, en el caso del sistema operativo de Apple -iOS serian en los siguientes lenguajes y el último framework  tales como Objective-C, Swift y SwiftUI y un último ejemplo sería el desarrollo de aplicaciones en Windows que puede ser con el lenguaje de C#, Visual Basic Net esto por decir algunos de los principales lenguajes. 

Ahora, considerando varias ventajas al utilizar el desarrollo de aplicaciones nativas, se enumeran las siguientes.

 - Se trabaja directamente con las funciones y el SDK (Software Development Kit) oficial del sistema operativo, lo cual se puede utilizar toda función sin límites.
 - Se puede acceder a los sensores y hardware del dispositivo.
 - La experiencia de diseño y desarrollo al 100% en rendimiento de cada sistema ofrece.


Aunado a lo anterior, también no encontramos con desventajas las cuales varios autores en libros y expertos en la material nos relatan.
- Se ocupa un equipo multidisciplinario que tenga el conocimiento de varios lenguajes de programación para cada plataforma o sistema operativo.
- El tema de dar mantenimiento a cada desarrollo que se vaya haciendo y tener la gente adecuada con el nivel de expertís para llevarlo a cabo.

En ningún momento se demerita el desarrollo nativo, sino que se debe de tomar en cuenta para la toma de decisiones para la creación de una App o un sistema.


<p align="center">
<img style="margin: 0px auto;" src="https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/imagenes/desarrollo-nativo-de-apps.png?raw=true" />
<br/>
  Figura 1.- Las plataformas con su propio lenguaje de programación
</p>


 Puede ser que tengas varias preguntas en este primer tema, se habla de varias tecnologías y tecnicismos como lenguajes de programación, en este apartado te va a ayudar a entender todos estos términos.
- Lenguaje de programación: Muchos lo pueden definir de la siguiente de la siguiente manera, es una forma de comunicarnos con una computadora, tablet o celular e indicarle qué queremos hacer.
- Framework: Muchos lo pueden definir de la siguiente de la siguiente manera, es un esquema o marco de trabajo que ofrece una estructura base para elaborar un proyecto con objetivos específicos, una especie de plantilla que sirve como punto de partida para la organización y desarrollo de software.
 Hay varias clasificaciones de estos lenguajes como alto nivel y bajo nivel, compilados e interpretados, pero ondearemos más adelante sobre este y otros términos.
> #### **Continuemos...**

**Ejemplo de desarrollo de una App en Ios y Android.**

A continuación de deja un video como realizar una aplicación de en iOS el sistema operativo de Apple utilizando el lenguaje de programación Swift y por último se desarrolla otra aplicación para Android utilizando kotlin como lenguaje de programación, esto para poner en contexto como se realizaría con tecnología nativa, posterior a ello en próximas lecciones de la presente sesión se observara como se lleva a cabo empleando Flutter.


<p align="center">
 Dar clic para ver el video
 <br/>
<a target="_blank" href="https://www.youtube.com/watch?v=jE3rqNWTWDs">
    <img src="https://img.youtube.com/vi/jE3rqNWTWDs/0.jpg" width="300px" />
</a>
</p>

# La actualidad sobre el desarrollo de aplicaciones multiplataforma

El desarrollo multiplataforma se puede definir como un proceso mediante el cual se desarrolla una aplicación independiente al sistema operativo, ya sea móvil o escritorio con un mismo lenguaje de programación, que esto a su vez facilita su exportación y visualización en cualquier dispositivo de los sistemas operativos citados anteriormente. 

Aunado a lo anterior todo se lleva a cabo con un mismo lenguaje de programación, puede desarrollar Apps multiplataforma que típicamente de manera nativa se ocuparía saber uno a 3 lenguajes de programación.

Algunos expertos como la Universidad Europea cita lo siguiente, "Aunque las aplicaciones nativas tienen un buen rendimiento y un elevado nivel de personalización, el desarrollo de aplicaciones multiplataforma se está imponiendo porque permite ahorrar tiempo, energía y recursos a las empresas, ya que no es necesario programar diferentes apps."

El desarrollo móvil multiplataforma es una tendencia que crece año tras año y que permite, a partir de un código común, generar aplicaciones para los sistemas operativos móviles más usados actualmente: Android y iOS.

Esto permite a una empresa, especialmente a las que son relativamente pequeñas, desarrollar su aplicación móvil y publicarla en la tienda de aplicaciones de ambos sistemas operativos sin la necesidad de dos equipos distintos, cada uno especializado en una de las plataformas, reduciendo así los costes. Además, se reduce también el tiempo de desarrollo necesario y se reduce la cantidad de código duplicado, dado que las funciones sólo se programan una vez y funcionan en ambas plataformas.

No obstante, optar por un desarrollo móvil multiplataforma también tiene dos desventajas principales: el rendimiento, el cual en la mayoría de los casos se ve afectado por el uso de componentes no nativos, dado que la comunicación de éstos con los distintos componentes nativos de cada plataforma suele ser inconsistente; y la experiencia de usuario, dado que los componentes de la interfaz no pueden aprovechar el potencial que podrían al no ser componentes nativos de la propia plataforma.

Actualmente, algunos de los frameworks de desarrollo móvil multiplataforma más utilizados son React Native y Xamarin. A este conjunto se ha unido recientemente Flutter, que soluciona los principales problemas del resto de frameworks de desarrollo móvil multiplataforma y el cual se analizará más adelante.

<p align="center">
<img style="margin: 0px auto;" src="https://github.com/fhernandezUcamp/BootcampFlutter/blob/main/BOOT-M1-SEM1-main/imagenes/Flutter-el-SDK-de-Google-para-desarrollar-apps-nativas-multiplataforma.png?raw=true"  width="70%" />
<br/>
  Figura 2.- Desarrollo multiplataforma actualmente en todos los dispositivos con la misma base de código
</p>

A continuación se deja un video resumiendo el contenido expuesto.

<p align="center">
 Dar clic para ver el video
 <br/>
<a target="_blank" href="https://youtu.be/uj_LsHgArEM">
    <img src="https://img.youtube.com/vi/uj_LsHgArEM/0.jpg" width="300px" />
</a>
</p>


# Herramientas LowCode/NoCode para Flutter

En la actualidad muchas personas quieren crear Apps con o sin conocimientos de programación, lo cual han surgido plataformas que apoyaran a crear Apps en algunos casos sin necesidad de escribir alguna línea de código y algunas otras se complementaran de las dos formas, es en esta parte que surgen los siguientes conceptos LowCode y NoCode que en un momento más se describirán cada una de estas.
 
Aunado a lo anterior, al desarrollar aplicaciones usando métodos y modelos visuales es más rápido que desarrollar usando código con el fin  de que sean desarrolladas con capacidades de modelado visual, las plataformas LowCode utilizan componentes integrados para representar cualquier información en una forma que sea legible para cualquier persona, desde usuarios comerciales habituales sin conocimientos técnicos hasta desarrolladores profesionales y algunas de estas herramientas pueden exportar el código para seguir trabajándolo, ahora las plataformas NoCode son las que directamente arrastras los elementos visuales y no tienes como resultado el código si no una App que tiene en medida de lo posible lo necesario para ser publicada.


<p align="center">
<img style="margin: 0px auto;" src="https://user-images.githubusercontent.com/92256063/173446169-591ca414-1b86-48e1-b11a-741eeda52359.png"  />
<br/>
</p>

En Flutter existen varias herramientas  tanto online como para instalar de manera local para poder crear aplicaciones en dicha tecnología, lo que si es cierto es que dependiendo lo que ofrezcan garantizara el éxito de la misma.

A continuación algunas de las herramientas LowCode y NoCode

1.- https://flutterstudio.app

![image](https://user-images.githubusercontent.com/92256063/173446659-a69fff07-3d71-417f-8811-24b6df936a2e.png)

2.- https://teta.so/

![image](https://user-images.githubusercontent.com/92256063/173446899-ea98c744-b6a3-49f4-8d58-c2b44d1e9707.png)

3.- https://www.waoo.co/

![image](https://user-images.githubusercontent.com/92256063/173446994-6f6fe7c1-fda1-4b9a-a50c-483d1383501a.png)

4.- https://flutterflow.io/

![image](https://user-images.githubusercontent.com/92256063/173447058-73c25d8f-7c17-4170-a17b-8fafd8e64389.png)


A continuación se deja un video sobre el tema de Flutter herramientas LowCode y NoCode

<p align="center">
 Dar clic para ver el video
 <br/>
<a target="_blank" href="https://www.youtube.com/watch?v=nB_-Dpr_8yc">
    <img src="https://img.youtube.com/vi/nB_-Dpr_8yc/0.jpg" width="300px" />
</a>
</p>


