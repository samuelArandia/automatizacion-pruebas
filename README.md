# Curso de introducción a la Automatización de pruebas

La automatización de pruebas es la práctica de ejecutar pruebas de una manera repetible, que permita utilizar la información y los resultados obtenidos para:

 Mejorar la calidad del software.
 Maximizar el retorno de la inversión (ROI).

El valor de la automatización de pruebas ya está probado, por lo tanto las empresas ya las están implementando.

La automatización de pruebas llegó para quedarse.

## Ventajas y desventajas de la automatización 

### Ventajas de la automatización de pruebas

Las ventajas que nos ofrece la automatización de pruebas son las siguientes:

-Mejorar la eficiencia de las pruebas.

-Proporcionar una cobertura de pruebas más amplia con respecto a las pruebas manuales.

-Reducir el costo total de las pruebas, es decir, no implicar costos que generarían acciones innecesarias como las pruebas manuales.

-Acortar el periodo de ejecución de las pruebas.

-Aumentar la frecuencia de las pruebas reduciendo el tiempo requerido para los ciclos de prueba.

-Se pueden ejecutar más pruebas por compilación o por liberación.

-La posibilidad de crear pruebas que no se pueden realizar manualmente, como las pruebas en tiempo real o pruebas paralelas.

-Las pruebas están menos sujetas a errores del operador. Una vez que se haya programado, no van a fallar.

### Desventajas de la automatización de pruebas

Las desventajas que nos ofrece la automatización de pruebas son las siguientes:

- Costos adicionales en herramientas, soluciones o profesionales.

- Requiere de conocimientos de programación, lo que implica que sea más difícil de solucionar errores o debuggear.

- Requiere un mantenimiento continuo porque el software evoluciona rápidamente.

-Es necesario agregar tecnologías adicionales en el stack de tu empresa.

-Las pruebas pueden volverse complejas.

-Distracción de los objetivos de la prueba, a veces no se evalúa correctamente lo que se debe automatizar o lo que no.

- Tiempos innecesarios en automatizar pruebas que hubieran sido resueltas más rápido de forma manual.

## Las limitaciones de la automatización de pruebas 

Se refieren a aquellas cosas que serán difíciles de automatizar, es decir, debes tener claro que no todo se puede automatizar.

Funcionalidades difíciles de probar automatizadamente

A continuación se expondrán ciertas funcionalidades que son difíciles de probar de forma automática:

### Probar la verificación de dos pasos

La verificación de dos pasos (Two Factor Authentication) consiste en enviar un código de seguridad para identificar a un usuario, por lo tanto, por cuestiones de seguridad y de la complejidad que se requiere, no es posible automatizar este procedimiento. Probar los sistemas anti-spam

El sistema de reCAPTCHA consiste en verificar que el usuario es una persona y no un robot o un programa.

Usualmente, estas técnicas son usadas por empresas que desean generar spam.

La verificación consiste en seleccionar imágenes relacionadas entre sí o un código, por lo que por su complejidad, no es posible automatizarlo. 

### Probar los correos automatizados

La automatización de correos, ya sea para realizar una restauración de contraseña o probar que un correo haya sido enviado correctamente, no es posible en su totalidad.

Existen muchas limitaciones para probar el envío de correos, aunque no es imposible porque hay herramientas que te permiten conectarte a un servidor y observar algunos de los resultados que se desean probar.

Sin embargo, el costo de automatizar estas pruebas puede ser elevado porque es necesario adquirir el servicio de correos.

Por el motivo anterior y el tiempo que es necesario invertir para este tipo de automatizaciones, no es rentable hacerlo. 

### Probar los sensores de los dispositivos móviles

Los sensores de los dispositivos móviles son difíciles de probar de manera automatizada, porque su comportamiento es difícil de emular por código.

Por ejemplo, si se quiere imitar el comportamiento del giroscopio, es necesario mover el dispositivo, quizás haya formas de emularlo por código, pero al final no va a ser una prueba que se acerque al uso real de un humano.

Otro ejemplo es escanear un código QR, que para automatizarlo se necesita que el celular esté bien soportado y que la distancia de lectura esté dentro de un rango específico.

Por lo tanto, siempre es importante que puedas analizar los beneficios y riesgos en una prueba automatizada.

### Limitaciones comunes de las pruebas automatizadas

Al momento de pensar en la automatización de pruebas, ten presente las siguientes limitaciones antes de diseñar las pruebas:
Solo se puede probar funcionalidades cuyo resultado sea interpretable por la máquina

Que los resultados sean interpretables por la máquina quiere decir que el criterio de aceptación elegido debe ser medible automáticamente.

Por ejemplo, no se puede medir si el usuario está feliz al usar la aplicación. Lo que sí se puede cuantificar es el color, el número de clics, o si le salió una alerta, entre otros.

Las pruebas automatizadas no reemplazan las pruebas exploratorias

Las pruebas exploratorias son las acciones manuales que realiza una persona. La curiosidad, impredecibilidad e imaginación humana no se pueden automatizar.

La Experiencia de Usuario (UX) no es medible

No se puede medir ni automatizar la experiencia de usuario. Solo es posible recopilar datos para realizar análisis futuros 

## Automatización basada en tipos de purebas 

Las pruebas se pueden dividir en dos grandes grupos, las funcionales y no funcionales.

Las pruebas funcionales permiten analizar los requisitos comerciales, es decir, lo que el cliente observará en la aplicación.

Las pruebas no funcionales permiten probar las cosas que son necesarias para que el cliente tenga una experiencia agradable, por ejemplo: el rendimiento, la seguridad y el almacenamiento de datos, entre otros.

## Tipos de pruebas automatizadas

Dependiendo del alcance, las pruebas automatizadas se pueden clasificar en diferentes tipos:

### Pruebas unitarias

Las pruebas unitarias son las que se practican sobre bloques unitarios de software que pueden ser automatizados.

Este tipo de pruebas son las más fáciles de desarrollar y las más económicas.

Usualmente son realizadas por el equipo de desarrollo.

### Pruebas de integración

Las pruebas de integración son las que se hacen cubriendo multiples funcionalidades relacionadas, pudiendo automatizarlas en un grupo.

### Pruebas de humo

Las pruebas de humo (smoke tests) son pruebas que se ejecutan después de una fase de compilación para evitar los fallos o que se haya “incendiado” la aplicación (de ahí su nombre).

### Pruebas de regresión

Las pruebas de regresión consiste en asegurar que nuevos bloques de software no afecten a los antiguos, es decir, que no se añadan errores (bugs) en la aplicación o algo que estuviera funcionando deje de funcionar.

### Pruebas de APIs

Las pruebas de APIs consisten en asegurar de que los endpoints funcionen correctamente.

Las API’s o Application Programming Interfaces es la forma de conectar tu frontend o lo que el usuario observa con el backend (el servidor).

Podrás aprender más de este tema en Curso de Consumo de API REST con JavaScript

### Pruebas de seguridad

Las pruebas de seguridad o pentesting consiste en buscar las vulnerabilidades que puede tener un software o sistema.

Para conocer más información te invitamos a explorar los cursos:

    Curso de Fundamentos de Pentesting
    Curso de Pentesting a Redes

### Pruebas de rendimiento

Las pruebas de rendimiento son pruebas no funcionales que consisten en evaluar la estabilidad y la capacidad de respuesta del software.

También se clasifican como pruebas de rendimiento, las pruebas de estrés, las cuales fuerzan la aplicación con condiciones de alto consumo, para analizar como se comporta en situaciones extremas.

### Pruebas de aceptación

Las pruebas de aceptación intentan determinar un criterio evaluable del cliente sobre la aplicación, es decir, cómo responderán al producto final.

Estas pruebas deben superarse con éxito antes del despliegue.

### Pruebas de Interfaz Gráfica de Usuario (UI)

Las pruebas de interfaces de usuario (UI) consisten en evaluar que el producto actúe correctamente.

Aquí se desarrollan las pruebas end-to-end, que consisten en analizar un flujo de principio a fin.
