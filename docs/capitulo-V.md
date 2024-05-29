# Capítulo V: Product Implementation, Validation & Deployment.

## 5.1. Software Configuration Management. 

En este punto del informe se describe las decisiones y los principios que ayudarán al equipo a garantizar la coherencia durante el desarrollo de la solución.

### 5.1.1. Software Development Environment Configuration.

En este apartado se proporcionan los enlaces a las aplicaciones y productos de software creados durante el ciclo del proyecto utilizando los programas correspondientes.

Con ese fin, se organizará en las siguientes secciones:

* Project Management
* Requirements Management
* Product UX/UI Design
* Software Development
* Software Testing
* Software Documentation

Asimismo, se clasificarán los elementos de estas secciones como rutas de referencia (para software basado en modelos Saas) o rutas de descarga (para productos que se ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos de software.

**Project Management**

Esta disciplina se fundamenta en la administración de proyectos y busca principalmente la mejora de procesos y su entorno con el propósito de lograr los resultados esperados.

* Durante el ciclo digital del proyecto, se llevará a cabo la implementación de un producto de software basado en el modelo SaaS, el cual funcionará a través de un navegador web; no obstante, no se desarrollará una versión de la aplicación móvil correspondiente.

**Requirements Management:**

Este proceso se enfoca en asegurar que una organización documente, verifique y satisfaga las necesidades y expectativas de sus clientes, así como las de las partes interesadas internas o externas.

* **Pivotal Tracker:** Esta herramienta se describe como una plataforma que facilita la gestión de las historias de usuario, organizándolas en epopeyas y evaluando su importancia en el programa según su puntuación. Se utilizó debido a su capacidad para permitir que cada miembro del equipo comparta una vista en tiempo real de los avances en cada proyecto, contribuyendo con diferentes secciones o ajustando el flujo del proyecto.

**Product UX/UI Design**

Esta herramienta facilita la creación digital de modelos que se integran en la vida del consumidor. En este caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como con dispositivos móviles.

Para lograrlo, utilizamos varias herramientas de diseño y colaboración, que incluyen:

**1\. Uxpressia:** Uxpressia es una plataforma en línea especializada en el mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps. Puedes encontrar más información sobre Uxpressia en [este enlace](https://uxpressia.com/).

**2\. MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en [su sitio web](https://miro.com/app/dashboard/).

**3\. Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar Figma en [este enlace](https://www.figma.com/design/).

**4\. Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart en [este enlace](https://www.lucidchart.com/pages/es).

**5\. Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más información sobre Overflow, visita [su sitio web](https://userflow.com/app/).

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a garantizar que nuestros productos sean accesibles y atractivos en diferentes plataformas.

**Software Development:**

El desarrollo de software es una metodología aplicada en la creación de productos de software. Esta metodología se utiliza para establecer un proceso que guía el desarrollo del software, y cada uno de sus pasos describe un enfoque específico para las distintas actividades que ocurren durante el proceso.

Aquí te presentamos algunas herramientas y tecnologías clave que utilizaremos en el proyecto:

**1\. GitHub:** GitHub es una plataforma de repositorio comunitario que se utiliza para almacenar y gestionar los avances de proyectos realizados por grupos de personas. Puedes acceder al repositorio del proyecto en [este enlace](https://github.com/sw53-metasoft).

**2\. Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una empresa especializada en software, orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).

**3\. HTML:** HTML es un lenguaje de marcado que se utiliza en el desarrollo de sitios web para crear hipertextos y enlazar a otros documentos. Este lenguaje proporciona herramientas para diseñar sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos HTML para implementar la documentación de la página web. Obtén más información sobre la edición de archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).

**4\. CSS:** CSS es un lenguaje de diseño destinado al entorno web, que posibilita la mejora de la interfaz de usuario previamente diseñada al añadir elementos como colores y tamaños, entre otros. Además, es posible crear un estilo en CSS y compartirlo en el sitio web creado en HTML. Este lenguaje será empleado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información sobre CSS en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

**5\. JavaScript:** Es un lenguaje de programación que es interpretado por otros programas. Funciona bajo el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases para la implementación. Este lenguaje permite crear dinámicas para los usuarios a través de la lógica de programación y será utilizado en la creación de las interacciones dinámicas en la plataforma web. Puedes encontrar más detalles sobre JavaScript en [enlace](https://www.jetbrains.com/help/idea/javascript-specific-guidelines.html).

Estas herramientas y tecnologías desempeñarán un papel fundamental en la creación exitosa de nuestro producto de software.

**Software Testing:**

Se trata de la acción de evaluar los elementos y el funcionamiento del software sometido a prueba mediante procesos de validación y verificación.

**Lenguaje Gherkin:** Este lenguaje, conocido como DSL (Lenguaje Específico de Dominio), está diseñado específicamente para abordar problemas particulares. Además de poder ser interpretado en código, permite agregar historias de usuario del programa junto con sus componentes correspondientes, como Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.

**Software Documentation**

Se refiere a textos escritos o ilustraciones que acompañan al software de computadora o están integrados en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el software o cómo utilizarlo.

### 5.1.2. Source Code Management.

A continuación se describe la gestión del código fuente, también conocida por las siglas SCM (Source Code Management). Su función principal es rastrear los cambios que realizará el equipo durante el desarrollo de su proyecto en el repositorio de código fuente. Se utilizará como un sistema de control de versiones que le permitirá realizar un seguimiento de los cambios realizados por miembros o desarrolladores individuales del proyecto. Además, es importante tener en cuenta que usaremos GitHub como nuestro sistema de control de versiones.

* **URL de la organización:** sw53-metasoft - https://github.com/sw53-metasoft

* **URL del repositorio de la Landing Page:** ReStyle-Landing-Page - https://github.com/sw53-metasoft/ReStyle-Landing-Page

* **URL del repositorio del Front-End:** ReStyle-frontend - https://github.com/sw53-metasoft/ReStyle-frontend

* **URL del repositorio del Back-End:** ReStyle-backend - https://github.com/sw53-metasoft/ReStyle-backend 

**GitFlow**

GitFlow es un modelo alternativo para la creación de ramas en Git que se ha convertido en una herramienta esencial para muchos desarrolladores en los últimos años. Este flujo de trabajo de control de versiones, desarrollado y popularizado por Vicent Driessen, desempeña un papel crucial en la gestión de las versiones de un código, facilitando la creación ordenada de nuevas características (Features) y correcciones de problemas urgentes (Hotfixes).

![ GitFlow.png](/assets/img/chapter-V/sprint-1/Gitflow.png)

Como se mencionó previamente, GitFlow opera con ramas o "branches". A continuación, se detallan las ramas que se utilizarán en el flujo de trabajo de nuestro proyecto.

* **Main Branches:**
    * **Main:** Esta es la rama principal desde la cual se ramifican todas las demás. Contendrá la versión más reciente junto con las versiones anteriores creadas por los desarrolladores. Aquí se mantendrá el historial oficial de las versiones publicadas.
    * **Develop:** Esta rama puede ser creada a partir de la rama principal (Main) y contendrá todas las características (Features) estables. A través de esta rama, el equipo podrá integrar las funcionalidades de manera efectiva.

* **Support Branches**
A diferencia de las ramas principales, estas ramas secundarias tienen una vida útil limitada, ya que se eliminan al fusionarse con sus ramas primarias.
    * **Feature:**
        * Se ramifica de: develop
        * Debe fusionarse de nuevo en: develop
        * Se utilizan para desarrollar las nuevas funciones que se integrarán en la próxima versión. Es importante destacar que esta rama existe únicamente mientras está en proceso de desarrollo. Sin embargo, una vez que el desarrollador haya completado esa función, se fusionará nuevamente con la rama "develop".

* **Convenciones para nombrar los Features:**
    * **Feture Branch:** feature/name
    **Example:**
        1. feature/welcome
        2. feature/about
        3. feture/myfeture
    * **Conventional Commits**
    El commit debe seguir la siguiente estructura:
    **\<type> [optional scope]: \<description>**
    **[optional body]**
    **[optional footer(s)]**
        * **Type:**
        **1\. feat:** Cuando se agrega un nuevo feature.
        **2\. fix:** cuando corriges un error.
        **3\. build:** cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.
        **4\. chore:** modificaciones privadas del código.
        **5\. docs:** commits que afectan solo a la documentación.
        **6\. refractor:** commits que reescriben o reestructura el código, pero no cambia el comportamiento.
        **7\. perf:** commits especiales que mejoran el rendimiento.
        **8\. style:** commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).
        **9\. test:** commits que agregan pruebas.
        * **Scope**
        Ofrece información contextual adicional. Aunque es opcional, es beneficioso incluirlo para proporcionar a los desarrolladores una descripción más detallada del commit.
        **\<description>**
        Es una parte obligatoria del formato de los commits. Siempre debemos usar lenguaje en modo imperativo y evitar escribir en mayúsculas
        **[optional body]**
        El cuerpo es opcional y, cuando se utiliza, debe explicar la motivación detrás del cambio y contrastarlo con el comportamiento anterior. Es ideal para mencionar identificadores de problemas y sus relaciones.
        **[optional footer(s)]**
        Esta sección es opcional y puede incluir información sobre cambios significativos. Puede hacer referencia al problema por su identificación y, en esta sección, se incluyen los cambios importantes precedidos por "BREAKING CHANGES:" seguido de uno o dos saltos de línea.
        **Ejemplos:**
            1. feat(welcome): add welcome section
            2. build(release): bump version to 1.0.0
            3. style: remove empty line
            4. feat(sign up): add the button to sign up
            5. feat!: email the costumer when product is shipped
            6. feat: remove ticket list endpoint
            refers to JIRA-1337
            BREAKING CHANGES: ticket enpoints no longer supports list all entites.

Como se mencionó previamente, la gestión de nuestro código fuente se llevará a cabo mediante GitHub. El IDE utilizado en este caso, WebStorm, debe estar vinculado directamente al repositorio creado por nuestra empresa MIRAI. De esta manera, cada commit realizado por un miembro del equipo se subirá automáticamente y se cargará en el GitHub de la organización. Las instrucciones para completar con éxito este proceso de emparejamiento se detallan a continuación:

* **Activar el controlador de versiones del IDE**
Dado que utilizaremos GitHub para gestionar nuestro código, la opción que debe estar habilitada o seleccionada es aquella que indique que el sistema de control se realizará mediante Git. Para hacer esto, siga los siguientes pasos:
  1. Diríjase a la pestaña "VCS" en WebStorm.
  2. Luego, seleccione la opción "Enable Version Control Integration".

![activar-el-controlador-de-versiones-1.png](/assets/img/chapter-V/sprint-1/activar-el-controlador-de-versiones-1.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![activar-el-controlador-de-versiones-2.png](/assets/img/chapter-V/sprint-1/activar-el-controlador-de-versiones-2.png)

* **Aregar una cuenta de GitHub, siga estos pasos:**
  1. Diríjase a la sección de configuración en su aplicación.
  2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
  3. En la configuración, busque la sección de version control.
  4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.

![aregar-una-cuenta-de-GitHub-1.png](/assets/img/chapter-V/sprint-1/aregar-una-cuenta-de-GitHub-1.png)

![aregar-una-cuenta-de-GitHub-2.png](/assets/img/chapter-V/sprint-1/aregar-una-cuenta-de-GitHub-2.png)

* **Configurar el nombre de usuario de Git:** Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
  1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
  2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
  3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.

![configurar-el-nombre-de-usuario-de-Git-1.png](/assets/img/chapter-V/sprint-1/configurar-el-nombre-de-usuario-de-Git-1.png)


* **Guardar el progreso en GitHub:** Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.

![guardar-el-progreso-en-GitHub-1.png](/assets/img/chapter-V/sprint-1/guardar-el-progreso-en-GitHub-1.png)

![guardar-el-progreso-en-GitHub-2.png](/assets/img/chapter-V/sprint-1/guardar-el-progreso-en-GitHub-2.png)

* **Configurar la propiedad del repositorio en GitHub:** Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
  1. Ingresa al repositorio creado en GitHub.
  2. Selecciona la pestaña 'settings'
  3. Dirigite al apartado de 'DangerZone'
  4. Luego da click en 'transfer'
  5. Finalmente elegimos el nuevo lugar para guardar el repositorio.

![configurar-la-propiedad-del-repositorio-en-GitHub-1.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-1.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-2.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-2.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-3.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-3.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-4.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-4.png)


* **Configurar control remoto en Git:** Por último, dado que el repositorio ahora está bajo la propiedad de la empresa y depende de ella, es necesario acceder al control remoto del código. Para hacerlo, simplemente ingresa al repositorio creado y copia la URL del repositorio.

![configurar-control-remoto-en-Git-1.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-1.png)

Ahora, en el IDE, dirígete a la pestaña 'Git' y elige la opción 'Manage Remotes'.

![configurar-control-remoto-en-Git-2.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-2.png)

Finalmente, como último paso, debes pegar el enlace copiado en el campo de dirección que solicita el IDE para el control remoto en Git.

![configurar-control-remoto-en-Git-3.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-3.png)

Si has seguido correctamente todos los pasos y directrices mencionados, entonces has completado la configuración con éxito. Ahora, solo necesitas realizar un commit y los cambios que hayas efectuado se guardarán en el repositorio de GitHub, ya sea que hayas realizado modificaciones en el código, creado nuevas ramas u otras acciones.


### 5.1.3. Source Code Style Guide & Conventions.

En esta sección, se presentarán las pautas, convenciones, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en la creación de nuestra aplicación. La observancia de este conjunto de directrices reviste una importancia fundamental, ya que tiene el propósito de mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el mantenimiento del mismo.

Dado que en este proyecto se emplearán varios lenguajes, como HTML, CSS, JavaScript, Java y TypeScript para el desarrollo de la plataforma web, así como Gherkin para el proceso de pruebas del programa, a continuación, se detallarán y describirán las reglas y recomendaciones generales que se tendrán en cuenta al utilizarlos.

**Nomenclatura General**

Para los nombres de variables, objetos, elementos y funciones que se utilicen en el proyecto, se emplearán términos en inglés que estén relacionados con lo que representan. No se utilizarán mayúsculas en estos nombres, ya que, de acuerdo con W3Schools (sin fecha), la combinación de mayúsculas y minúsculas puede dificultar la legibilidad del código. En su lugar, se optará por utilizar exclusivamente letras minúsculas, lo que contribuirá a una mayor claridad en el código.

Ejemplos de nomenclatura estándar, siguiendo las recomendaciones de Google (s.f.):

```
.gallery {}
.video {}
.login {}
```

Estas pautas de nomenclatura ayudarán a mantener una coherencia en el código y facilitarán su comprensión.

**Sangría**

Cuando se trabaje con HTML, CSS y/o JavaScript, se aplicará un espaciado de dos espacios antes de cada línea que se encuentre dentro de un bloque. Según W3Schools (sin fecha), no se recomienda el uso de la tecla "Tabulación". A continuación, se muestra un ejemplo de la sangría estándar en HTML siguiendo las directrices de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Título del Documento</title>
  </head>
  <body>
    <h1>Encabezado Principal</h1>
    <p>Este es un párrafo dentro del cuerpo del documento.</p>
  </body>
</html>
```

Este estilo de sangría proporciona una estructura clara y organizada al código, lo que facilita su lectura y mantenimiento.

Ejemplo de formato estándar de sangría en CSS, conforme a las recomendaciones de W3Schools (s.f):

``` CSS
html {
  background: #fff; /* Fondo blanco */
  color: #404;     /* Color de texto gris */
}
```

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3School (s.f.):

``` JavaScript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

**Especificaciones generales**

A continuación, detallaremos las reglas específicas necesarias para comprender el código de nuestra aplicación en cada lenguaje.

**HTML:**

HTML, acrónimo de HyperText Markup Language en inglés, es un lenguaje de marcado que se utiliza para definir la estructura de una página web. También incluye funcionalidades que permiten controlar el comportamiento de diferentes elementos del contenido de la página, como cambiar el tamaño del texto o aplicar formato cursiva, entre otros. En nuestro proyecto, emplearemos HTML5, y a continuación, se presentan las características y directrices que debemos seguir para utilizar este lenguaje de la siguiente manera:

* **Declare Document Type**
La declaración del tipo de documento debe realizarse en la primera línea del código. Según las recomendaciones de Google (s.f.), se prefiere la sintaxis de HTML5 para todos los documentos HTML. Para declararla, simplemente copia lo siguiente:

``` html
<!DOCTYPE html>
```

* **Blank Lines**
Cada vez que comiences un nuevo bloque, lista o tabla de gran longitud, es recomendable dejar una línea en blanco después del elemento anterior para mejorar la legibilidad y la presentación del código, de acuerdo con las pautas de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
<head>
<title>Animales Exóticos</title>
</head>
<body>
<h1>Lemur de Madagascar</h1>
<p>El lémur de Madagascar es un primate endémico de la isla de Madagascar en el Océano Índico.</p>

<h1>Pangolín</h1>
<p>El pangolín es un mamífero cubierto de escamas que se encuentra en regiones de África y Asia.</p>

<h1>Ocelote</h1>
<p>El ocelote es un felino salvaje que habita en América del Sur y Central, conocido por su pelaje moteado.</p>
</body>
</html>
```

Esta práctica de dejar una línea en blanco mejora la estructura y legibilidad del código HTML.

* **Quote attribute Values**
Para los valores de los atributos, es común utilizar comillas dobles alrededor de ellos, aunque esta característica no sea obligatoria. Según W3Schools (sin fecha), esto mejora la legibilidad del código y es una práctica común entre los desarrolladores. Aquí tienes un ejemplo:

``` html
<table class="striped">
```

Este enfoque de usar comillas dobles alrededor de los valores de los atributos es ampliamente aceptado y recomendado en la comunidad de desarrollo web.

* **Never Skip the \<title> Element**
El elemento `<title>` permite que las páginas aparezcan en la lista de resultados al realizar búsquedas en un navegador web. Además, este elemento es responsable de proporcionar el nombre de la página cuando se agrega a marcadores o favoritos. A continuación, se muestra un ejemplo de su uso:

``` html
<title>Guía de Estilo HTML y Convenciones de Codificación</title>
```

Este elemento es esencial para mejorar la identificación y accesibilidad de una página web.

* **HTML Line-Wrapping**
A pesar de que en un documento HTML no exista un límite estricto en la cantidad de palabras por línea, no se recomienda generar líneas de código excesivamente largas. De hecho, hacerlo dificulta la legibilidad del código. Para continuar en la siguiente línea, se deben utilizar al menos cuatro espacios para distinguir elementos secundarios. Aquí tienes un ejemplo basado en las recomendaciones de Google (sin fecha):

``` html
<button mat-icon-button color='primary' class="menu-button"
(click)="openMenu()">
<mat-icon>menu</mat-icon>
</button>
```

Este estilo de formateo ayuda a mantener un código más legible y facilita la identificación de los elementos y su jerarquía en la estructura del documento HTML.

**CSS:**

CSS, conocido por sus siglas en inglés, Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje que se enfoca en definir y mejorar la presentación de un documento basado en HTML. A continuación, se presentan las directrices que debemos seguir al utilizar CSS:

* **Shorthand Properties**
Se recomienda utilizar abreviaturas de propiedades y declarar los campos de los elementos en la menor cantidad de líneas posible, según las pautas de Google (sin fecha). Esto aumenta la eficiencia del código y lo hace más legible. Además, se debe evitar agregar unidades después del valor cero. Aquí tienes un ejemplo:

``` css
border-top: 0;
font: 100%/1.6 palatino, georgia, serif;
padding: 0 1em 0;
```

Siguiendo estas recomendaciones, se puede lograr un código CSS más conciso y fácil de entender.

* **Declaration Stops**
Es importante incluir un punto y coma al final de cada declaración en CSS, al igual que en la mayoría de los lenguajes de programación. Siguiendo las pautas de Google (sin fecha), esta práctica contribuye a mantener la coherencia en el código. A continuación, se muestra un ejemplo:

``` css
html {
  background: #fff;
  color: #404;
}
```

El uso consistente de puntos y comas al final de las declaraciones CSS ayuda a prevenir errores y mejora la claridad del código.

* **Property Name Stops**
Es necesario incluir un espacio entre los dos puntos que siguen al nombre de una propiedad y el valor correspondiente. Siempre se debe colocar un solo espacio después de los dos puntos, pero no antes. A continuación, se muestra un ejemplo siguiendo esta convención estándar de Google (s.f):

``` css
html {
  background: #fff;
  color: #404;
}
```

Mantener esta consistencia en la colocación de espacios ayuda a que el código CSS sea más legible y fácil de entender.

* **Declaration Block Separation**
Es esencial utilizar un espacio separador después del nombre de un selector de elemento y antes de la llave que inicia un bloque de declaración CSS. Además, la llave de apertura del bloque debe estar en la misma línea que el selector. Aquí tienes un ejemplo siguiendo esta convención estándar de Google (sin fecha):

``` css
html {
  background: #fff;
  color: #404;
}
```

El cumplimiento de estas directrices ayuda a mantener la consistencia y la legibilidad en el código CSS.

* **CSS quotation Marks**
No se deben utilizar comillas dobles (`"`) en el código CSS; en su lugar, se permiten y deben emplearse comillas simples (`'`) únicamente para selectores de atributos y valores de propiedades.
Ejemplo conforme a las pautas estándar de Google (sin fecha):

``` css
html {
  font-family: 'open sans', arial, sans-serif;
}
```

Este ejemplo demuestra el uso de comillas simples para encerrar el valor del atributo `font-family` en CSS, lo cual es una práctica común y aceptada.

**JavaScript**

JavaScript es un lenguaje de programación que permite especificar de manera precisa las acciones que debe realizar el navegador web, incluyendo el orden de ejecución de tareas y la frecuencia con la que se deben llevar a cabo. A continuación, se presentan las pautas para el uso de JavaScript en nuestro proyecto:

* **Spaces around operators**
Es importante añadir espacios alrededor de cada operador matemático y comas que se utilicen en el código JavaScript. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso consistente de espacios alrededor de operadores y comas mejora la legibilidad del código JavaScript.

* **Simple Statement's End**
Es fundamental que una instrucción simple finalice con un punto y coma, tal como es el caso en muchos otros lenguajes de programación. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
let x = v + 7;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso de punto y coma al final de cada instrucción ayuda a garantizar la estructura correcta del código JavaScript y a evitar posibles errores.

* **Beginning and End of Function**
Un bloque de función debe incluir una llave al final de la primera línea, de modo que el cierre de la función esté en la última línea, sin necesidad de un punto y coma. Este mismo principio se aplica a las estructuras condicionales y los bucles. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

En este ejemplo, la función `toCelsius` está formateada de acuerdo con estas pautas, con la llave de apertura en la misma línea que la declaración de la función y la llave de cierre en la última línea. Esto ayuda a mantener la estructura y la legibilidad del código JavaScript.

* **Object Rules**
Para la creación de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea. Sin embargo, en este caso, la llave de cierre debe ir seguida de un punto y coma. Para definir las propiedades del objeto, se utilizan dos puntos y un espacio para separar el nombre de la propiedad de su valor. Si el valor es un string, se debe encerrar entre comillas dobles. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

En este ejemplo, el objeto `person` está formateado de acuerdo con estas pautas, lo que mejora la legibilidad y la estructura del código JavaScript.

**Gherking:**

Gherkin es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que se utiliza para resolver problemas específicos mediante la generación de casos de prueba que validan una característica en diversos escenarios. Gherkin incluye varios elementos, entre los cuales los más conocidos y utilizados son Feature, Scenario, Example, Given, When y Then. A continuación, se presentan las pautas que debemos seguir al utilizar Gherkin en nuestro código:

* **Discernible Given-When-Then Blocks**
Es importante aplicar sangría a los elementos que representan los pasos a seguir en un escenario. En el caso de "And", se debe aplicar una sangría adicional. Siguiendo la recomendación de Keiblinger (2021), este enfoque ayuda a identificar rápidamente las partes que componen un escenario. A continuación, se muestra un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
  Given que en el formulario de ingreso de oferta laboral
  When escribo claramente los requisitos
  Then se mostrará el mensaje
  And mi oferta solo aparecerá a quienes cumplan con estos
  And se habilita la opción
```

En este ejemplo, se ha aplicado la sangría de manera adecuada para resaltar los pasos del escenario, y se ha utilizado una sangría adicional para los pasos que comienzan con "And". Esto mejora la legibilidad y la comprensión de los escenarios escritos en Gherkin.

* **Step with Tables**
Conforme a la recomendación de Keiblinger (2021), cuando sea necesario introducir valores en partes del escenario, se debe emplear una tabla o crear un formulario que refleje esa parte del escenario. Antes de esta representación, se deben colocar dos puntos. Aquí tienes un ejemplo:

``` gherkin
Then se mostrará el mensaje:
  | Mensaje |
  | Se completaron los requisitos adecuadamente |
```

Este enfoque permite una representación clara y estructurada de los valores relacionados con una parte específica del escenario.

* **Reducing Noise**
Para evitar la acumulación de demasiadas líneas de código en un escenario, es recomendable incluir valores por defecto dentro de los pasos para campos que no sean muy relevantes para ese escenario en particular. Los valores "estándar" que se coloquen deben estar entre comillas simples. Siguiendo el consejo de Keiblinger (2021), esta práctica contribuye significativamente a la reducción del tamaño del código. A continuación, se muestra un ejemplo:

``` gherkin
When escribo claramente los requisitos 'dominio en C'
```

En este ejemplo, se ha incluido un valor por defecto ('dominio en C') entre comillas simples dentro del paso para representar un campo que no es esencial en ese escenario. Esto ayuda a mantener el escenario más conciso y legible.

* **Scenarios Separator**
Para separar dos escenarios, se debe insertar un salto de línea y, según la sugerencia de Keiblinger (2021), si es posible, agregar una línea de comentario para facilitar la visualización de estos. De esta manera, se identifica rápidamente el inicio y el fin de un escenario. A continuación, se presenta un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
Given que en el formulario de ingreso de oferta laboral
When escribo claramente los requisitos
Then se mostrará el mensaje
And mi oferta solo aparecerá a quienes cumplan con estos
And se habilita la opción

# --------------------------

Scenario: Otro escenario
Given que en otro contexto
When ocurre algo diferente
Then se muestra otro resultado
```

En este ejemplo, se ha agregado un salto de línea entre los dos escenarios y se ha incluido una línea de comentario como separador para mejorar la visualización y la identificación de cada escenario.

**Java:**

Java es una plataforma informática de lenguaje de programación que fue desarrollada por Sun Microsystems en 1995. A lo largo de los años, ha experimentado una evolución significativa y ha desempeñado un papel fundamental en la creación de numerosos servicios y aplicaciones que conforman gran parte del mundo digital actual. A continuación, se presentan las pautas para utilizar Java en nuestro proyecto:

* **Clases e interfaces en Java**
Los nombres de las clases deben ser sustantivos y seguir una convención de mayúsculas y minúsculas, con la primera letra de cada palabra interna en mayúscula. Del mismo modo, los nombres de las interfaces deben comenzar con una letra mayúscula, al igual que los nombres de las clases. Se debe utilizar palabras completas y evitar el uso de acrónimos y abreviaturas. Aquí tienes un ejemplo:

``` java
interface Bicycle
class MountainBike implements Bicycle
interface Sport
class Football implements Sport
```

En este ejemplo, se han seguido las pautas para nombrar clases e interfaces de manera clara y legible.

* **Métodos en Java**
Los métodos deben seguir una convención de nombres que utilice verbos y mantenga la combinación de mayúsculas y minúsculas, con la primera letra de cada palabra interna (a partir de la segunda) en mayúscula. A continuación, se presenta un ejemplo:

``` java
void changeGear(int newValue);
void speedUp(int increment);
void applyBrakes(int decrement);
```

En este ejemplo, los nombres de los métodos siguen la convención recomendada, lo que los hace descriptivos y legibles.

* **Variables en Java**
Los nombres de las variables deben ser concisos pero significativos, evitando comenzar con un guión bajo (\_) o caracteres especiales como el signo de dólar ($). Deben ser mnemotécnicos, es decir, diseñados de manera que indiquen claramente su propósito a un observador casual. Generalmente, se deben evitar los nombres de una sola letra para las variables, a menos que se utilicen como variables temporales. Los nombres comunes para variables temporales son: i, j, k, m y n para enteros, y c, d y e para caracteres. A continuación, se muestra un ejemplo:

``` java
// Variables para la clase MountainBike
int speed = 0;
int gear = 1;
```

En este ejemplo, se han utilizado nombres de variables significativos y legibles, lo que facilita la comprensión de su propósito en el contexto de la clase MountainBike.

* **Excepciones**
A menos que se justifique en un comentario, es extremadamente raro que sea apropiado no realizar ninguna acción en respuesta a una excepción detectada. En el caso en que no sea necesario realizar ninguna acción en un bloque catch, la razón debe explicarse de manera clara en un comentario. A continuación, se presenta un ejemplo:

``` java
try {
    int i = Integer.parseInt(response);
    return handleNumericResponse(i);
} catch (NumberFormatException ok) {
    // No es un valor numérico; eso está bien, simplemente continúa
    return handleTextResponse(response);
}
```

En este ejemplo, se ha incluido un comentario para explicar por qué no se realiza ninguna acción en el bloque catch cuando se detecta una excepción de formato numérico. Esto ayuda a comprender el motivo detrás de esta decisión en el código.
En el contexto de las pruebas, es aceptable ignorar una excepción detectada sin comentarios si su nombre es o comienza con "expected". Esto es un patrón común para verificar que el código bajo prueba arroje una excepción del tipo esperado, por lo que no se requiere un comentario adicional en este caso. A continuación, se muestra un ejemplo:

``` java
try {
    emptyStack.pop();
    fail();
} catch (NoSuchElementException expected) {
    // No es necesario comentar aquí, ya que esperábamos esta excepción
}
```

En este ejemplo, la excepción "expected" no requiere un comentario adicional, ya que el nombre mismo indica que es esperada como parte de la prueba.
La anotación `@Override` se utiliza para marcar un método cuando es legal hacerlo. Esto incluye un método de clase que anula un método de una superclase, un método de clase que implementa un método de una interfaz y un método de interfaz que vuelve a especificar un método de una superinterfaz.
Excepción: Se puede omitir la anotación `@Override` cuando el método principal está marcado como `@Deprecated`.

**Typescript**

JavaScript es uno de los lenguajes más populares y ha experimentado un rápido avance y mejora en los últimos años. A continuación, se presentan las pautas para utilizar JavaScript en nuestro proyecto:

En TypeScript, se recomienda que las variables se declaren en minúsculas y se especifique el tipo de dato utilizando dos puntos después del nombre de la variable. Aquí tienes ejemplos de cómo declarar y asignar valores a variables en TypeScript:

``` typescript
// Definición e inicialización separadas
let edad: number;
edad = 20;

// Definición e inicialización en la misma línea.
let edadAitor: number = 18;
```

Además, en TypeScript, se siguen las mismas convenciones que se utilizan en JavaScript.

### 5.1.4. Software Deployment Configuration.

Para desplegar la Landing Page desde GitHubPages hay que seguir los siguientes pasos: 

**1. Ubicar el repositorio que tiene guardado el codigo fuente y dirigirse al apartado de configuración (settings):**

![repo-landing-page.png](/assets/img/chapter-V/sprint-1/repo-landing-page.png)


**1. Seleccionar la sección pages:**

![pages-landing-page.png](/assets/img/chapter-V/sprint-1/pages-landing-page.png)


**1. Configurar la rama que será usada para hacer deploy:**

![rama-landing-page.png](/assets/img/chapter-V/sprint-1/rama-landing-page.png)


## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo gestionamos las tareas en Pivotal Tracker.

Repositorio: [ReStyle-Landing-Page -https://github.com/sw53-metasoft/ReStyle-Landing-Page ](https://github.com/sw53-metasoft/ReStyle-Landing-Page)
Landing Page Deployed: [ReStyle - https://sw53-metasoft.github.io/ReStyle-Landing-Page/](https://sw53-metasoft.github.io/ReStyle-Landing-Page/)


#### 5.2.1.1. Sprint Planning 1.

En el Sprint Planning 1, se llevó a cabo una sesión de planificación para la elaboración de
la landing page del proyecto. Durante esta reunión, se dividieron las secciones a programar entre los integrantes, 
además se determinó el plazo de entrega de estas tareas.


<!--suppress ALL -->
<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2"  ><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center">06-04-2024</td>
    </tr>
    <tr>
      <td style="text-align:center">Time</td>
      <td style="text-align:center">8:00 PM</td>
    </tr>
    <tr>
      <td style="text-align:center">Location</td>
      <td style="text-align:center">Discord</td>
    </tr>
    <tr>
      <td style="text-align:center">Prepared By</td>
      <td style="text-align:center">Janover Saldaña</td>
    </tr>
    <tr>
      <td style="text-align:center">Attendees</td>
      <td style="text-align:center">
      Alejandra Villacrez, Janover Saldaña, Josten Huaman, Daniel Valverde, Ariana Vargas
      </td>
    </tr>
    <tr>
      <td colspan="2"  ><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Goal</td>
      <td style="text-align:center"> Implementar la landing page incluyendo las distintas secciones 
      acordadas y el requisito de cambio de idioma para la aplicación de ReStyle </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Velocity</td>
      <td style="text-align:center">15</td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center">15</td>
    </tr>
  </tbody>
</table>


#### 5.2.1.2. Sprint Backlog 1.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>

   <tr>
    <td   colspan="2"> <strong>User Story</strong></td>
    <td   colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>Description</strong></td>
    <td  > <strong>Estimation (Hours)</strong></td>
    <td  > <strong>Assigned To</strong></td>
    <td  > <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3"> US-001</td>
    <td rowspan="3"> Hipervínculos en el encabezado</td>
    <td  > UT-01</td>
    <td  > Agregar navbar</td>
    <td  >Permitir a los usuarios interactuar con las opciones de la barra de navegación </td>
    <td  >2 </td>
    <td  > Josten Huaman </td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-02</td>
    <td  > Agregar botón de idioma</td>
    <td  > Permitir a los usuarios cambiar el idioma (inglés o español) clickeando el botón</td>
    <td  > 1</td>
    <td  > Josten Huaman</td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-03</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td > 1</td>
    <td  > Josten Huaman</td>
    <td  > Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="4"> US-002</td>
    <td rowspan="4"> Información sobre beneficios de la aplicación</td>
    <td  > UT-04</td>
    <td  > Mostrar Hero image</td>
    <td  >Permitir a los usuarios visualizar la imagen de presentación de la landing page</td>
    <td  >1 </td>
    <td  > Alejandra Diaz </td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-05</td>
    <td  > Mostrar beneficios</td>
    <td  > Permitir a los usuarios visualizar una sección con los beneficios de la aplicación</td>
    <td  > 2</td>
    <td  > Alejandra Diaz</td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-06</td>
    <td  > Agregar botón "Empezar Ahora"</td>
    <td  > Permitir a los usuarios dirigirse directamente a la aplicación clickeando el botón</td>
    <td  > 1</td>
    <td  > Alejandra Diaz</td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-07</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td  > 1</td>
    <td  > Alejandra Diaz </td>
    <td  > Done </td>
  </tr>
   <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2"> US-005</td>
    <td rowspan="2"> Información sobre la aplicación</td>
    <td  > UT-08</td>
    <td  > Mostrar información</td>
    <td  > Permitir a los usuarios visualizar una sección con la información de la aplicación </td>
    <td  > 1 </td>
    <td  > Daniel Valverde </td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-09</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td  > 1</td>
    <td  > Daniel Valverde </td>
    <td  > Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2"> US-003</td>
    <td rowspan="2"> Mostrar los planes disponibles</td>
    <td  > UT-10</td>
    <td  > Agregar sección de planes</td>
    <td  > Permitir a los usuarios visualizar una sección con los planes a los que pueden acceder en la aplicación </td>
    <td  > 1 </td>
    <td  > Ariana Vargas </td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-11</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td  > 1</td>
    <td  > Ariana Vargas </td>
    <td  > Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2"> US-025</td>
    <td rowspan="2"> Visualizar testimonios de los usuarios que han utilizado la aplicación</td>
    <td  > UT-12</td>
    <td  > Mostrar Testimonios</td>
    <td  > Permitir a los usuarios visualizar las valoraciones realizadas sobre la experiencia de uso de la aplicación </td>
    <td  > 1 </td>
    <td  > Daniel Valverde </td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-13</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td  > 1</td>
    <td  > Daniel Valverde </td>
    <td  > Done </td>
  </tr>
  <td rowspan="3"> US-004</td>
    <td rowspan="3"> Información útil en el footer</td>
    <td  > UT-14</td>
    <td  > Datos de contacto</td>
    <td  >Permitir a los usuarios visualizar datos para comunicarse como: Teléfono y correo. </td>
    <td  >1 </td>
    <td  > Josten Huaman </td>
    <td  > Done </td>
  <tr>
    <td  > UT-15</td>
    <td  > Redes Sociales</td>
    <td  > Permitir a los usuarios visualizar las redes sociales del producto (Instagram, Facebook y Twitter) </td>
    <td  > 1</td>
    <td  > Josten Huaman</td>
    <td  > Done </td>
  </tr>
  <tr>
    <td  > UT-16</td>
    <td  > Agregar html en inglés</td>
    <td  > Traducir el contenido asignado del html al idioma inglés </td>
    <td  > 1</td>
    <td  > Josten Huaman</td>
    <td  > Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="1"> US-018</td>
    <td rowspan="1"> Cambiar idioma	</td>
    <td  > UT-17</td>
    <td  > Agregar funcionalidad del botón de idioma</td>
    <td  > Agregar el script que permita el cambio de idioma al momento de clickear el botón </td>
    <td  > 2 </td>
    <td  > Janover Saldaña </td>
    <td  > Done </td>
  </tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.

<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
  <!-- rowspan="number of rows" -->
    <td rowspan="50">https://github.com/sw53-metasoft/ReStyle-Langin-Page</td>
    <td>main</td>
    <td>486a09cc609d0d8be0a1b4b76f7155162993ceb2</td>
    <td>Initial commit</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/hero</td>
    <td>ebe934a9e050088de3bd926d992c339850d0e450</td>
    <td>feat(develop): innital commit</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/hero</td>
    <td>5405d08d3596a1d652ef6011f57e14e2e864efc3</td>
    <td>feat(hero): added index section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/hero</td>
    <td>5405d08d3596a1d652ef6011f57e14e2e864efc3</td>
    <td>feat(hero): added index section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/hero</td>
    <td>d78327181c1fcfcf3bf90f8bd3e3747f89ece4fb</td>
    <td>feat(hero): added index-en section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/hero</td>
    <td>0a3a0e68e9f7546d296ccc6691562cd1710d8bac</td>
    <td>feat(hero): added css section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/benefits</td>
    <td>57e2026b09bd54a9863d7c02785b50d13a06940c</td>
    <td>feat(benefits): added index section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/benefits</td>
    <td>2dacbec45e9b61149428aa1105debb7b57efb579</td>
    <td>feat(benefits): added index-en section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/benefits</td>
    <td>f2bec277716e0969551289b580141bd1188ccd11</td>
    <td>feat(benefits): added styles section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/membership</td>
    <td>60369c4bc18d7d17cd74e6a508c45fa7098cc576</td>
    <td>feat(membership): added membership section structure</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/membership</td>
    <td>0b4c62b0052bfe7f785526323a1328a66a7ed0fd</td>
    <td>feat(membership):updated structure section membership</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/membership</td>
    <td>2da7b56add0939034298ae01d033047d4236aa1e</td>
    <td>feat(membership): added mebership-en section structure</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/membership</td>
    <td>48677bfd4155e8df0ada5b448643e6ab32eeafeb</td>
    <td>feat(membership): added css membership</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/header</td>
    <td>d553db3dbf49080c5aa07e78323a11c1f8459d81</td>
    <td>feat(header): added struct nav bar</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/header</td>
    <td>268061b240ad633f163e80e995e2c55d9c308ea6</td>
    <td>feat(header): added styles</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/footer</td>
    <td>5b4649797d9343557bd6bdb821e013e79997c0c0</td>
    <td>feat(footer): Added section footer</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/footer</td>
    <td>e130b1e21ea99e42640154d644216da817c74218</td>
    <td>feat(footer): added styles</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/footer</td>
    <td>d4a0e98a72581b125cd8a844428b8091f430ecc5</td>
    <td>fix(footer): deleted the content of the files</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/footer</td>
    <td>3c93484881568f7d02440c64e59e6801c92ec70b</td>
    <td>feat(footer): merge branch deevelop with branch feature/footer</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/footer</td>
    <td>d0b350f2c52453a0fa66be9dc3f66d233c911960</td>
    <td>feat(footer): added struct footer and styles</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/footer</td>
    <td>12bcb994dfaaaab1589552a8bace4586dd8a76df</td>
    <td>fix(footer): changed footer position</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
  <tr>
    <td>feature/about-the-app</td>
    <td>d176e3440ccfebe3bcb9e1c482e209ae90a19091</td>
    <td>feat(about-the-app): Added about the app section</td>
    <td></td>
    <td>11/04/2024</td>
  </tr>
   <tr>
    <td>feature/testimonials</td>
    <td>bc02ecbb36dae35e90510c9a34b1af506c326e11</td>
    <td>feat(testimonials): Added testimonials section</td>
    <td></td>
    <td>12/04/2024</td>
  </tr>
<tr>
    <td>feature/testimonials</td>
    <td>91ebd2ad022fcb3301f64846d796250417c438dd</td>
    <td>feat(testimonials): Fixed tag errors</td>
    <td></td>
    <td>12/04/2024</td>
  </tr>
  <tr>
    <td>feature/header</td>
    <td>3d34fc10a7a462d0596d36a92e67125be1f1ae91</td>
    <td>Fix(header): corrected media query navbar and footer</td>
    <td></td>
    <td>12/04/2024</td>
  </tr>
  <tr>
    <td>feature/contact-us</td>
    <td>2fa09143b82765a4cc2193d58ee37e6b5b1d0305</td>
    <td>feat(contact-us): Added structure and styles the section contact-us.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
   <tr>
    <td>feature/contact-us</td>
    <td>b583fe1c17b884f1cd7e4b494ffdbc967c7620a6</td>
    <td>feat(contact-us): Added content in English to the contact us section.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
   <tr>
    <td>feature/about-the-team</td>
    <td>16ae25c51bb604cf6dab26f3bf94633db0ed06f3</td>
    <td>feat(about-the-team): Added structure and styles section about the team.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
   <tr>
    <td>feature/about-the-team</td>
    <td>46c82bcbe76083d2a897daed385c683db2b34d25</td>
    <td>feat(about-the-team): Added informotion index-en.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
   <tr>
    <td>feature/about-the-team</td>
    <td>7e9f4936b15415764793a48f5cc388279079e052</td>
    <td>fix(): corrected media query tittle and buttons.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
   <tr>
    <td>develop</td>
    <td>14451d0842475efc8a9448fa951ade1c1559f2c1</td>
    <td>feat(develop): updated route bottom language.</td>
    <td></td>
    <td>13/04/2024</td>
  </tr>
</table>


#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Para el Sprint 1 no se han implementado tests. 

#### 5.2.1.5. Execution Evidence for Sprint Review.

Después de completar el Sprint 1, logramos implementar todas las secciones de nuestro Landing Page para garantizar una visualización perfecta. Además, le dimos un formato atractivo que captura la atención del usuario hacia sus diferentes componentes. También agregamos métodos de navegación en la página, como botones ubicados al principio, que te permiten moverte fácilmente de una sección a otra. A continuación, te mostraremos los avances a través de imágenes del resultado obtenido.

Es importante destacar que el objetivo principal del Landing Page es convertir a los visitantes en futuros clientes o usuarios habituales de nuestro servicio. Para lograrlo, utilizamos llamados a la acción (Call To Action) que los guían hacia la aplicación web.

A continuación, te presentamos capturas de pantalla del desarrollo del Landing Page:

**Encabezado y botones de desplazamiento:**

En la parte superior, se encuentra el encabezado (Header) que incluye botones de inicio (Home), beneficios (benefits), Pricing (Pricing), sobre la aplicación (about), testimonios de usuarios (testimonials), un formulario para que nos contacten (Contact), un apartado para saber sobre el equipo (About us) y un botón para cambiar el idioma entre inglés y español. Estos elementos permiten a los visitantes desplazarse fácilmente a la sección que deseen visualizar.

![navbar-landing-page.png](/assets/img/chapter-V/sprint-1/navbar-landing-page.png)
<p style="text-align:center"><strong>Imagen 01:</strong> Encabezado y botones de desplazamiento</p>


**Sección Hero:**
Se presenta la sección "Hero", que incluye una breve descripción y una frase representativa de TecHelp. Además, permite iniciar el uso del servicio web y proporciona una imagen relacionada con el mismo.

![hero-landing-page.png](/assets/img/chapter-V/sprint-1/hero-landing-page.png)

<p style="text-align:center"><strong>Imagen 02:</strong> Sección Hero</p>

**Sección Benefits:**

Se presenta la sección de beneficios del servicio para cada segmento objetivo identificado por el equipo.

![benefits-landing-page.png](/assets/img/chapter-V/sprint-1/benefits-landing-page.png)

<p style="text-align:center"><strong>Imagen 03:</strong> Sección de beneficios</p>


**Sección Membresip:**

Se presenta la sección membership de la landing page, en esta sección nuestros posibles usuarios podrán ver los tipos de membresias y sus costos.

![membreship-landing-page.png](/assets/img/chapter-V/sprint-1/membreship-landing-page.png)

<p style="text-align:center"><strong>Imagen 04:</strong> Sección de membresias de la web aplication</p>

**Sección About the App:**

Se presenta información y un video sobre como funciona la aplicación .

![about-the-app-landing-page.png](/assets/img/chapter-V/sprint-1/about-the-app-landing-page.png)

<p style="text-align:center"><strong>Imagen 05:</strong> Sección de membresias de la web aplication</p>

**Sección testimonials:**

Se presenta testimonios de nuestros usuarios fieles, para generar confianza. 


![testimonials-landing-page.png](/assets/img/chapter-V/sprint-1/testimonials-landing-page.png)

<p style="text-align:center"><strong>Imagen 06:</strong> Sección de membresias de la web aplication</p>



**Sección contact-us:**

A continuación se presenta la sección de contacto, aquí nuestros posibles usuarios pueden realizarnos preguntas personalizadas acerca de la aplicación que se está presentando.

![contact-us-landing-page.png](/assets/img/chapter-V/sprint-1/contact-us-landing-page.png)

<p style="text-align:center"><strong>Imagen 07:</strong> Sección de contatános</p>


**Sección AboutThe Team:**

Seguidamente, se presenta la sección sobre nuestro equipo (about-us). En este apartado se muestra información a manera de resumen sobre las personas que están desarrollando la salución de software.

![about-the-team-landing-page.png](/assets/img/chapter-V/sprint-1/about-the-team-landing-page.png)
<p style="text-align:center"><strong>Imagen 08:</strong> Sección de acerca del equipo</p>

**Sección footer:**

Por último, se exhibe la sección del pie de página, donde encontrará nuestros enlaces a redes sociales, correo y teléfono para que se comuniquen con nosotros.

![footer-landing-page.png](/assets/img/chapter-V/sprint-1/footer-landing-page.png)
<p style="text-align:center"><strong>Imagen 09:</strong> Sección de acerca del equipo</p>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer Sprint el equipo de desarrollo de MetaSoft ah diseñado, programado y puesto en funcionamiento el sitio web (Landing Page) Para presentar la aplicación Web propuesta denominada "ReStyle". En este sitio web (Landing Page), se lográ visualizar varias secciones que ilustran en que consiste "ReStyle", cada integrante del equipo de desarrollo de Metasoft estuvo a cargo de una sección en especifico. 

<table>

  <thead>
    <th> End Point</th>
    <th>Funciones</th>
  </thead>

  <tbody>
      <tr>
        <td><a href="https://sw53-metasoft.github.io/ReStyle-Landing-Page/">[http](https://sw53-metasoft.github.io/ReStyle-Landing-Page/)</a></td>
        <td>Mostrar la Landing Page Desplegada</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr>
  </tbody>

</table>


#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestra página, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "realease-V1.0" que previamente se encontrba en la rama release-1.0.

Langing Page -> 

#### 5.2.1.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de commits realizadas por cada integrante del equipo durante el desarrollo de la landing page.

![pulse.png](/assets/img/chapter-V/sprint-1/pulse.png)


Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![clone.png](/assets/img/chapter-V/sprint-1/clone.png)


### 5.2.2. Sprint 2
Durante el Sprint #2, el equipo se enfocará en diseñar y
desarrollar la fase inicial del front-end y una API ficticia para la aplicación web, con el propósito de garantizar una experiencia que cumpla con los requisitos de los usuarios.

#### 5.2.2.1. Sprint Planning 2

En el Sprint Planning 2, se llevó a cabo una sesión de planificación para la elaboración de
la aplicación en primera versión del proyecto. Durante esta reunión, se dividieron las secciones a programar entre los integrantes,
además se determinó el plazo de entrega de estas tareas.

<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2"  ><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center">28-04-2024</td>
    </tr>
    <tr>
      <td style="text-align:center">Time</td>
      <td style="text-align:center">8:00 PM</td>
    </tr>
    <tr>
      <td style="text-align:center">Location</td>
      <td style="text-align:center">Discord</td>
    </tr>
    <tr>
      <td style="text-align:center">Prepared By</td>
      <td style="text-align:center">Janover Saldaña</td>
    </tr>
    <tr>
      <td style="text-align:center">Attendees</td>
      <td style="text-align:center">
      Alejandra Villacrez, Janover Saldaña, Daniel Valverde, Ariana Vargas
      </td>
    </tr>
    <tr>
      <td>Sprint 2 Review Summary</td>
      <td>
        En el anterior Sprint fue dedicado al desarrollo y despliegue de la Landing Page.
        El equipo cumplió con las tareas asignada por ende se logró el objetivo del Sprint 1.
      </td>
    </tr>
    <tr>
      <td>Sprint 2 Retrospective Summary</td>
      <td>
        Se debe applicar la mejora continua con respecto a la documentación del proyecto
        Revisar las historias de usuario y reorganizarlas de manera que todos los desarrolladores entiendan fácilmente su propósito.
      </td>
    </tr>
    <tr>
      <td colspan="2"  ><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 2 Goal</td>
      <td style="text-align:center"> Implementar y desplegar la aplicación de ReStyle en fase inicial </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Velocity</td>
      <td style="text-align:center">34</td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center">34</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.2. Sprint Backlog 2
el segundo sprint se centró en el desarrollo del MVP del front-end de la aplicación web. Utilizamos Trello como 
herramienta para organizar y gestionar a los miembros del equipo. Esta plataforma nos permitió dividir todas las
historias de usuario en tareas manejables y asignarlas a los distintos integrantes del equipo.

![Trello Evidence](/assets/img/chapter-V/sprint-2/sprint-backlog2-trello.png)

Link del Tablero de Trello: https://trello.com/b/p6JtnTBC 

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 2</strong> </td>
  </tr>

   <tr>
    <td   colspan="2"> <strong>User Story</strong></td>
    <td   colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>Description</strong></td>
    <td  > <strong>Estimation (Hours)</strong></td>
    <td  > <strong>Assigned To</strong></td>
    <td  > <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">US007</td>
    <td rowspan="3">Búsqueda de empresas remodeladoras</td>
    <td>TA18</td>
    <td>Creación de componente de búsqueda</td>
    <td>Permite a los usuarios visualizar a las empresass remodeladoras según una búsqueda personalizada</td>
    <td>2</td>
    <td>Alejandra Diaz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA19</td>
    <td>Modificación de estilos</td>
    <td> Personaliza los estilos de acuerdo al prototipo propuesto</td>
    <td> 2</td>
    <td>Alejandra Diaz</td>
    <td> Done </td>
  </tr>
  <tr>
    <td>TA20</td>
    <td>Implementación de servicio de remodeladores</td>
    <td>Desarrolla los servicioes para el consumo de datos de los remodeladores de la fake API</td>
    <td>2</td>
    <td>Alejandra Diaz</td>
    <td> Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">US008</td>
    <td rowspan="3">Revisar críticas y opiniones</td>
    <td>TA21</td>
    <td>Creación de componente de reseñas</td>
    <td>Permite a los usuarios revisar las reseñas de un remodelador el cual seleccionaron en la búsqueda</td>
    <td>1</td>
    <td>Alejandra Diaz</td>
    <td>Done</td>
  </tr>
  <tr>
     <td>TA22</td>
    <td>Modificación de estilos</td>
    <td> Personaliza los estilos de acuerdo al prototipo propuesto</td>
    <td> 1</td>
    <td>Alejandra Diaz</td>
    <td> Done </td>
  </tr>
  <tr>
    <td>TA23</td>
    <td>Implementación de servicio de reseñas</td>
    <td>Desarrolla el servicio para el consumo de datos de las reseñas de la fake API</td>
    <td>1</td>
    <td>Alejandra Diaz</td>
    <td> Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">US009</td>
    <td rowspan="3">Agregar críticas y opiniones</td>
    <td>TA24</td>
     <td>Creación de componente de agregar reseñas</td>
    <td>Permite a los usuarios contratistas agregar las reseñas de un remodelador</td>
    <td>2</td>
    <td>Daniel Valverde</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA25</td>
    <td>Modificación de estilos</td>
    <td>Personaliza los estilos de acuerdo al prototipo propuesto</td>
    <td> 1</td>
    <td>Daniel Valverde</td>
    <td> Done </td>
  </tr>
  <tr>
    <td>TA26</td>
    <td>Implementación de servicio de creación de reseñas</td>
    <td>Desarrolla el servicio para la creación de datos de las reseñas</td>
    <td>2</td>
    <td>Daniel Valverde</td>
    <td> In process </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2">US012</td>
    <td rowspan="2">Crear cuenta contratista</td>
    <td>TA27</td>
    <td> SignUp contratista</td>
    <td> Permite a los usuarios contratistas registrarse en la aplicación como contratistas </td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA28</td>
    <td> Login contratista</td>
    <td> Permite a los usuarios contratistas iniciar sesión con su cuenta creada</td>
    <td> 3</td>
    <td>Janover Saldaña </td>
    <td> Done </td>
  </tr>
   <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2">US013</td>
    <td rowspan="2">Crear cuenta remodelador</td>
    <td>TA29</td>
    <td>SignUp remodelador </td>
    <td>Permite a los usuarios remodeladores registrarse en la aplicación como remodeladores </td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA30</td>
    <td> Login remodelador</td>
    <td> Permite a los usuarios remodeladores iniciar sesión con su cuenta creada </td>
    <td> 3</td>
    <td>Janover Saldaña</td>
    <td> Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">US014</td>
    <td rowspan="3">Busqueda de portafolios</td>
    <td>TA31</td>
    <td> Creación del componente de búsqueda de portafolios</td>
    <td>Permite a los contratistaas visualizar los proyectos de los remodeladores en su portafolio</td>
    <td>3</td>
    <td>Daniel Valverde</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA32</td>
    <td> Modificación de estilos</td>
    <td> Personaliza los estilos de acuerdo al prototipo propuesto</td>
    <td> 1</td>
    <td> Daniel Valverde</td>
    <td> Done </td>
  </tr>
  <tr>
    <td>TA33</td>
   <td>Implementación de servicio de búsqueda de portafolio</td>
    <td>Desarrolla el servicio para el consumo de datos de los portafolios de la fake API</td>
    <td>2</td>
    <td>Daniel Valverde </td>
    <td> Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">US015</td>
    <td rowspan="3">Seguimiento de proyecto</td>
    <td>TA34</td>
    <td>Creación del componente para el seguimiento</td>
    <td>Permite a los usuarios visualizar el seguimiento del proyecto por fases </td>
    <td>5</td>
    <td>Ariana Vargas</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA35</td>
    <td>Modificación de estilos </td>
    <td> Personaliza los estilos de acuerdo al prototipo propuesto</td>
    <td> 2</td>
    <td> Ariana Vargas</td>
    <td> Done </td>
  </tr>
  <tr>
    <td>TA36</td>
    <td>Implementación de servicio para el seguimiento del proyecto </td>
    <td>Desarrolla el servicio para el consumo de la fake API de proyectos </td>
    <td> 3</td>
    <td> Ariana Vargas </td>
    <td> In process </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2">US017</td>
    <td rowspan="2">Visualizar home de la plataforma</td>
    <td>TA37</td>
    <td> Creación del componente Home</td>
    <td>Permite a los usuarios tener una vista por defecto de la aplicación </td>
    <td>1</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA38</td>
    <td> Modificación de estilos del componente</td>
    <td> Agrega opciones necesarias par la navegación a las secciones de la aplicación</td>
    <td> 1</td>
    <td> Janover Saldaña</td>
    <td> Done </td>
  </tr>
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="2">US018</td>
    <td rowspan="2">Visualizar una página no encontrada</td>
    <td>TA39</td>
    <td> Creación del componente PageNotFound</td>
    <td>Permite a los usuarios volver a la vista principal </td>
    <td>1</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA40</td>
    <td> Creación de botón de retorno</td>
    <td> Implementa un botón que redirecciona a la vista Home</td>
    <td> 1</td>
    <td> Janover Saldaña</td>
    <td> Done </td>
  </tr>
</table>

#### 5.2.2.3. Development Evidence for Sprint Review.

<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
  <!-- rowspan="number of rows" -->
    <td rowspan="50">https://github.com/sw53-metasoft/ReStyle-Frontend</td>
    <td>main</td>
    <td>4276568e2e22118c837de6e6a287fdddf894949f</td>
    <td>feat: initial commit</td>
    <td></td>
    <td>23/04/2024</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>6358a15307a44ae909f3c5b980088d11130e297b</td>
    <td>feat(develop): Added intial structure for the project</td>
    <td></td>
    <td>24/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-search</td>
    <td>0e7e50810bd5b590d3972ab6d212849c49e51f53</td>
    <td>feat(remodeler-search): added remodeler-search feature</td>
    <td></td>
    <td>29/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-detail</td>
    <td>7947ac96af230bf5a72c23b522b8e8817ed0712e</td>
    <td>feat(remodeler-detail): added remodeler-detail feature</td>
    <td></td>
    <td>29/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-detail</td>
    <td>b01b942f4b9e4f4a231161a8d69aba629cc8f052</td>
    <td>fix: components path</td>
    <td></td>
    <td>30/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-detail</td>
    <td>a297e20bfe8088f9c9d5258d0167f4ef797032be</td>
    <td>feat(remodeler-detail): Add remodeler portfolio profile</td>
    <td></td>
    <td>30/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-detail</td>
    <td>fb67d68ca0b2c63888733b484c6824c01d84b431</td>
    <td>feat(remodeler-detail): Add remodeler portfolio projects</td>
    <td></td>
    <td>30/04/2024</td>
  </tr>
  <tr>
    <td>remodeler-detail</td>
    <td>0e792eaeb61cc67fa580129d9e534f92d4e1ace3</td>
    <td>fix: remove unavailable path</td>
    <td></td>
    <td>30/04/2024</td>
  </tr>
  <tr>
    <td>public</td>
    <td>f9d2a97401332a7fd1b765187c2dcca69fce898b</td>
    <td>feat(public): added home page.</td>
    <td></td>
    <td>30/04/2024</td>
  </tr>
  <tr>
    <td>feature/security</td>
    <td>0cf7035c24439df7a3bc71df44e0fe6b4a688e91</td>
    <td>feat(security): added security architecture.</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/profiles</td>
    <td>2652963ecdb0b04f8b609e841dfc09c651676591</td>
    <td>feat(login): added login.</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/profiles</td>
    <td>0b8cc4d2823cd77712d259922e6ce2aea2f33f11</td>
    <td>feat(sign-up): added sign up and updated page not found.</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/tracking</td>
    <td>4c0de68cc05a0cda6ef82ea01fb25b97fa96c712</td>
    <td>feat(feature/tracking): added tracking feature</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/profiles</td>
    <td>7b3ddadb6d81f863164c677c16b09d3e83fae70d</td>
    <td>7b3ddadb6d81f863164c677c16b09d3e83fae70d</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/profile</td>
    <td>feeb2e4a2ee4a54df9025126ba1daa21f7cb389b</td>
    <td>feat(profiles): Added profile contracter and remodeler</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
  <tr>
    <td>feature/profiles</td>
    <td>8f9969fde011ccce3526430aafc3eb7337ce4690</td>
    <td>feat(profiles): Add public components in coming-soon component</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
   <tr>
    <td>feature/reviews</td>
    <td>887e1b90ad702bd69bf96f78308e35a6dd12ca25</td>
    <td>feat(reviews): Add create review component</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
   <tr>
    <td>feature/reviews</td>
    <td>b79ffd69a9cb88356f5991aafddaea9cfff1f0d3</td>
    <td>feat(reviews): Add review snackbar</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
   <tr>
    <td>feature/reviews</td>
    <td>ef1dbe987eb1a0f0afa3b262a7fbbb4509744651</td>
    <td>feat(reviews): Add review component to routes</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
   <tr>
    <td>feature/reviews</td>
    <td>ef78e013ba78a52c912824326a7dab0c0150eb44</td>
    <td>feat(reviews): Add review component to sidebar component menu</td>
    <td></td>
    <td>01/05/2024</td>
  </tr>
   <tr>
    <td>feature/profiles</td>
    <td>0e051232919bae7d4757d222a7c7764b4aa5da6a</td>
    <td>feat(profiles): updated components paths</td>
    <td></td>
    <td>02/05/2024</td>
  </tr>
  <tr>
    <td>release-v1.0</td>
    <td>25a07199153297f1f45888adcc3118367117c4b7</td>
    <td>feat(release-v1.0): Deploy with firebase</td>
    <td></td>
    <td>02/05/2024</td>
  </tr>
</table>

#### 5.2.2.4. Testing Suite Evidence for Sprint Review.

Para esta entrega el equipo aún no han realizado pruebas de testing.

<table>
  <thead>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Commited on (Date)</th>
  </thead>
  <tbody>
    <tr>
      <td rowspan="9">https://github.com/sw53-metasoft/Acceptance-Tests-Sprint-2</td>
      <td>main</td>
      <td>d91a483a982592789f3e307d198c79d32a30486a</td>
      <td>feat(testing)</td>
      <td>Added Acceptance Criteria US007</td>
      <td>01/05/2024</td>
    </tr>
     <tr>
      <td>main</td>
      <td>0ad7d3fb2e258c9edb194e84cf10605015b074b9</td>
      <td>feat(testing)</td>
      <td>Added Acceptance Criteria US008</td>
      <td>01/05/2024</td>
    </tr>
    <tr>
      <td>main</td>
      <td>80c0d0f6c3d3bce63616fe2798ade53d46eba6a5</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS009</td>
      <td>01/05/2024</td>
    </tr>
    <tr>
      <td>main</td>
      <td>27a47fa27107ec5b197856462606ee39471673fe</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS012</td>
      <td>01/05/2024</td>
    </tr>
    <tr>
      <td>main</td>
      <td>337025ba8b8559cc5d29b4fce2e379ccdec9ab47</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS013</td>
      <td>01/05/2024</td>
    </tr>
      <tr>
      <td>main</td>
      <td>8d0703b4162e02c186a804aa2d9144d046ad322f</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS014</td>
      <td>01/05/2024</td>
    </tr>
      <tr>
      <td>main</td>
      <td>caadf0c6b8e90e00f6503ee83636c14afe5e9fe4</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS015</td>
      <td>01/05/2024</td>
    </tr>
      <tr>
      <td>main</td>
      <td>50a3654d2011d17072c81be681227b32374e7df2</td>
      <td>feat(testing)</td>
      <td>feat: Added Acceptance CriteriaUS017</td>
      <td>01/05/2024</td>
    </tr>
      <tr>
      <td>main</td>
      <td>996f036e6d483ddc085189374d34f3f583d381aa</td>
      <td>feat(testing)</td>
      <td>Added Acceptance CriteriaUS018</td>
      <td>01/05/2024</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.5. Execution Evidence for Sprint Review.

Despues de culminar satisfactoriamente el sprint 2, logramos implementar la pantalla de home, login, registro de usuario, vista de criticas y opiniones, búsqueda de empresas remodeldoras, busqueda de portafolios, seguimiento de proyecto, contacto con la empresa.
Link de la aplicación: https://restyle-app-ca200.web.app

* **Vista de Home de la aplicación:**

![home-vista.png](/assets/img/chapter-V/sprint-2/home-vista.png)

* **Vista de inicio de sesión (login):**

![login-vista.png](/assets/img/chapter-V/sprint-2/login-vista.png)

* **Vista de registro de usuario:**

![registro-usuario-vista.png](/assets/img/chapter-V/sprint-2/registro-usuario-vista.png)

* **Vista de perfil de Usuario:**

![perfil-usuario-vista.png](/assets/img/chapter-V/sprint-2/perfil-usuario-vista.png)

* **Vista de empresas remodeladoras:**

![empresa-remodeladora-vista.png](/assets/img/chapter-V/sprint-2/empresa-remodeladora-vista.png)

* **Busqueda y filtros de empresas remodeladoras:**

![busqueda-filtros-vista.png](/assets/img/chapter-V/sprint-2/busqueda-filtros-vista.png)

* **Vista de portafoliio y reseñas de empresas remodeladoras:**


![portafolio-vista.png](/assets/img/chapter-V/sprint-2/portafolio-vista.png)


![reseñas-vista.png](/assets/img/chapter-V/sprint-2/reseñas-vista.png)


* **Vista de contacto con la empresa:**

![contacto-vista.png](/assets/img/chapter-V/sprint-2/contacto-vista.png)


* **Sección de agregar reseña:**

![agregar-reseña-vista.png](/assets/img/chapter-V/sprint-2/agregar-reseña-vista.png)


* **Sección de seguimiento de proyecto:**

![tracking-view.png](/assets/img/chapter-V/sprint-2/tracking-view.png)


* **Vista de error al no encontrar la ruta ingresada:**

![PageNotFound-vista.png](/assets/img/chapter-V/sprint-2/PageNotFound-vista.png)

* **Vista de coming soon:**

![coming-soon.png](/assets/img/chapter-V/sprint-2/coming-soon-view.png)

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

Para el sprint 2 se ha desarrollado **únicamente** el Front-End de la aplicación. Por lo tanto, no se han realizado operaciones con la API. Sin embargo, se ha utilizado una fake-api, con la que hemos implementado la aplicación web. Además, utilizamos la plataforma My Json Server para publicar nuestras Fake-api. A continuación, se mostrarán los Endpoints desarrollados en este sprint.  

<table>
  <thead>
    <th>  Endpoint</th>
    <th> HTTP verb</th>
    <th> Action</th>
  </thead>
  <tbody>
    <tr>
      <td>https://my-json-server.typicode.com/JanoverSaldana/users/users</td>
      <td>GET</td>
      <td>Obtener todos los datos de los usuarios registrados en la aplicación web</td>
    </tr>
     <tr>
      <td>https://my-json-server.typicode.com/JanoverSaldana/remodeler/remodelers</td>
      <td>GET</td>
      <td>obtener la información de los remodeladores ya sea general o por ID para ser mostrado en las vistas que lo requieran</td>
    </tr>
     <tr>
      <td>https://my-json-server.typicode.com/JanoverSaldana/contracter/contracters</td>
      <td>GET</td>
      <td>obtener la información de los contratistas ya sea general o por ID para ser mostrado en las vistas que lo requieran</td>
    </tr>
     <tr>
      <td>https://my-json-server.typicode.com/alehandraxx/myrepo/remodelers</td>
      <td>GET</td>
      <td>Obtener la información de los remodeladores, ya sea todos o por ID.</td>
    </tr>
     <tr>
      <td>https://my-json-server.typicode.com/vargas3470/tracking/procesosRemodelacion</td>
      <td>GET</td>
      <td>Obtener la información de las etapas del proyecto.</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.7. Software Deployment Evidence for Sprint Review.
Utilizamos Firebase Hosting para el despliegue de la aplicación web. A continuación se mostrarán los pasos para lograr el despliegue

##### Creación de un nuevo proyecto en Firebase y elegimos el nombre del producto o alguno que este disponible

<img src="/assets/img/chapter-V/sprint-2/crear-proyecto-firebase.png" alt="Firebase new project"/>

##### Seleccionamos el tipo de sericio que vamos a utilizar, en este caso Hosting

<img src="/assets/img/chapter-V/sprint-2/seleccion-hosting.png" alt="Firebase new project"/>

##### Ejecutamos los comandos de configuración de Firebase en la terminal

<img src="/assets/img/chapter-V/sprint-2/comandos-firebase-1.png" alt="Firebase commands"/>

<img src="/assets/img/chapter-V/sprint-2/comandos-firebase-2.png" alt="Firebase commands"/>

##### Ejecutamos en la terminal el comando "firebase deploy", el cual nos generará una URL para acceder a la aplicación web

<img src="/assets/img/chapter-V/sprint-2/comandos-firebase-3.png" alt="Firebase commands"/>

Finalmente obtenemos el link de nustra aplicación web desplegada en Firebase Hosting: https://restyle-app-ca200.web.app

#### 5.2.2.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de nuestra aplicación web. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y Typescript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de commits realizadas por cada integrante del equipo durante el desarrollo de la aplicación web.

![PulseSprint2](/assets/img/chapter-V/sprint-2/pulse-sprint2.png)

Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![CloneSprint2](/assets/img/chapter-V/sprint-2/clone-sprint2.png)

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3

En el Sprint Planning 3, se llevó a cabo una sesión de planificación para la elaboración de

<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center"></td>
    </tr>
    <tr>
      <td style="text-align:center">Time</td>
      <td style="text-align:center"></td>
    </tr>
    <tr>
      <td style="text-align:center">Location</td>
      <td style="text-align:center">Discord</td>
    </tr>
    <tr>
      <td style="text-align:center">Prepared By</td>
      <td style="text-align:center">Daniel Valverde</td>
    </tr>
    <tr>
      <td style="text-align:center">Attendees</td>
      <td style="text-align:center">
      Alejandra Villacrez, Janover Saldaña, Daniel Valverde, Ariana Vargas
      </td>
    </tr>
    <tr>
      <td>Sprint 3 Review Summary</td>
      <td>
        review
      </td>
    </tr>
    <tr>
      <td>Sprint 2 Retrospective Summary</td>
      <td>
        summary
      </td>
    </tr>
    <tr>
      <td colspan="2"  ><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 3 Goal</td>
      <td style="text-align:center"> </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 3 Velocity</td>
      <td style="text-align:center"></td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center"></td>
    </tr>
  </tbody>
</table>

#### 5.2.3.2. Sprint Backlog 3

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 3</strong> </td>
  </tr>

   <tr>
    <td   colspan="2"> <strong>User Story</strong></td>
    <td   colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>Description</strong></td>
    <td  > <strong>Estimation (Hours)</strong></td>
    <td  > <strong>Assigned To</strong></td>
    <td  > <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks" -->
    <td rowspan="3">us-number</td>
    <td rowspan="3">us-title</td>
    <td>ta1</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td>ta2</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td>ta3</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Done</td>
  </tr>
  
</table>

#### 5.2.3.3. Development Evidence for Sprint Review 

<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
  <!-- rowspan="number of rows" -->
    <td rowspan="50"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

#### 5.2.3.4. Testing Suite Evidence for Sprint Review 

<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
  <!-- rowspan="number of rows" -->
    <td rowspan="50"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

#### 5.2.3.5. Execution Evidence for Sprint Review 

#### 5.2.3.6. Services Documentation Evidence for Sprint Review  

#### 5.2.3.7. Software Deployment Evidence for Sprint Review

#### 5.2.3.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
En esta sección se realizarán entrevistas mediante las cuales buscamos recoger opiniones y recomendaciones. Esto asegura
que la aplicación web no solo cumpla con los requisitos técnicos, sino también con las expectativas de nuestros segmentos
objetivo. A continuación, se detallan los user goals necesarios para llevar a cabo las entrevistas.

### 5.3.1. Diseño de Entrevistas

**User Goal: Navegar por la landing page** <br>
User persona → Remodeladores y contratistas <br>
Explicación del flujo → El usuario deberá ingresar a la landing page de la aplicación web. En esta, podrá desplazarse y
visualizar información general sobre los servicios ofrecidos, así como los beneficios de utilizar la aplicación. 
Además, podrá cambiar el idioma a inglés o español a través de un botón. También, tendrá acceso directo a la aplicación
web a través de un Call To Action situado en la vista principal de la landing page. 

**User Goal: Iniciar sesión** <br>
User persona → Remodeladores y contratistas <br>
Explicación del flujo → Primero, el usuario deberá ingresar a la aplicación desplegada. A continuación, verá en la 
pantalla un formulario que le pedirá sus datos de inicio de sesión, específicamente su correo electrónico y contraseña.
Una vez validadas las credenciales, el sistema le permitirá ingresar a la aplicación. En caso el usuario no tenga una
cuenta, puede registrarse completando otro formulario con sus datos personales.

**User Goal: Ver perfil** <br>
User persona → Remodeladores y contratistas <br>
Explicación del flujo → El usuario tiene dos formas de acceder a su perfil. La primera opción es a través de un panel 
lateral ubicado a la izquierda de la aplicación; al hacer clic en el ícono de la persona, podrá acceder a su perfil, 
donde verá sus datos personales y detalles de la cuenta. La segunda opción es desde la barra de navegación en la parte 
superior de la aplicación; al hacer clic en "Mi perfil", accederá a la misma vista mencionada.

**User Goal: Buscar remodeladores** <br>
User persona → Contratistas <br>
Explicación del flujo → Primero el usuario puede acceder a la vista de busqueda de remodeladores desde el sidebar lateral,
donde podrá buscar remodeladores por nombre, distrito, especialidad. Además, podrá filtrar los resultados de la búsqueda.
Una vez seleccionado un remodelador, podrá ver su portafolio, reseñas y una vista para contactar con el remodelador 
seleccionado.

**User Goal: Administrar proyecto** <br>
User persona → Remodeladores y contratistas <br>
Explicación del flujo → En primer lugar, el usuario deberá acceder a la vista de seguimiento de proyecto. En esta, podrá
ver el estado de los proyectos en los que está involucrado, así como los detalles de cada uno a través de las distintas 
etapas que se muestran. En caso se trate del remodelador, este podrá actualizar el estado de los proyectos y agregar comentarios. 


### 5.3.2. Registro de Entrevistas

Entrevista a Contratistas

<table>
        <thead>
            <tr>
                <th>Entrevistado 1</th>
                <th>Jose Gutierrez</th>
            </tr>
            <tr>
                <th>Entrevistador </th>
                <th>Alejandra Diaz</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Edad</td>
                <td>26</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>Lima</td>
            </tr>
            <tr>
                <td><img src="/assets/img/chapter-V/sprint-3/interview-contractor1.png" alt="agregar foto"></td>
                <td><strong>Resumen:</strong><br>
                  Resumen
                </td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>---</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>---</td>
            </tr>
            <tr>
                <th>Entrevistado 2</th>
                <th>Diego Cantoral</th>
            <tr>
                <th>Entrevistador </th>
                <th>Daniel Valverde </th>
            </tr>
            <tr>
                <td>Edad</td>
                <td>21</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>Pueblo Libre</td>
            </tr>
            <tr>
            <td><img src="/assets/img/chapter-V/sprint-3/fotoEntrvistaValidacionDiego.png" alt="Foto de entrevista"></td>
                <td><strong>Resumen:</strong><br>En esta oportunidad el entrevistado pudo completar los user goals diseñados
                para su segmento. En primer lugar navegó por la landing page para luego acceder a la aplicación de ReStyle
                desde esta misma. El entrevistado nos compartió su opinión sobre los productos mostrados, estuvo conforme con
                la mayoría de estilos presentados como la paleta de colores y la tipografía. Por otro lado, también realizó 
                un par de observaciones en cuestiones de accesibilidad de funciones en los productos mostrados.</td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>!</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>!</td>
            </tr>
            <tr>
                <th>Entrevistado 3</th>
                <th>Nombre</th>
            <tr>
                <th>Entrevistador </th>
                <th>Nombre </th>
            </tr>
            <tr>
                <td>Edad</td>
                <td>---</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>--</td>
            </tr>
            <tr>
            <td><img src="" alt="Foto de entrevista"></td>
                <td><strong>Resumen:</strong><br>--</td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>--</td>
            </tr>
        </tbody>
</table>

Entrevista a Remodeladores

<table>
        <thead>
            <tr>
                <th>Entrevistado 1</th>
                <th>Olga Samanez</th>
            <tr>
                <th>Entrevistador </th>
                <th>Alejandra Diaz</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Edad</td>
                <td>52</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>Pueblo Libre</td>
            </tr>
            <tr>
                <td><img src="/assets/img/chapter-V/sprint-3/interview-remodeler1.png" alt="Foto de entrevista"></td>
                <td><strong>Resumen:</strong><br>La entrevistada logra completar todos los user goals, desde visualizar el landing page, encontrar el boton call to action, iniciar sesion en la aplicacion web, realizar busqueda de remodeladores y utilizar el project management. Finaliza solicitando un tutorial pequeño o flechas que indiquen como utilizar la aplicacion para los visitantes nuevos, tambien solicita colores más llamativos en el sidebar.</td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <th>Entrevistado 2</th>
                <th>Nombre</th>
            <tr>
                <th>Entrevistador </th>
                <th>Nombre </th>
            </tr>
            <tr>
                <td>Edad</td>
                <td>---</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>--</td>
            </tr>
            <tr>
            <td><img src="" alt="Foto de entrevista"></td>
                <td><strong>Resumen:</strong><br>resumen aqui</td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <th>Entrevistado 3</th>
                <th>Nombre</th>
            <tr>
                <th>Entrevistador </th>
                <th>Nombre </th>
            </tr>
            <tr>
                <td>Edad</td>
                <td>---</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>--</td>
            </tr>
            <tr>
            <td><img src="" alt="Foto de entrevista"></td>
                <td><strong>Resumen:</strong><br>resumen aqui</td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>--</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>--</td>
            </tr>
</table>

### 5.3.3. Evaluaciones según heurísticas

**UX Heuristics & Principles Evaluation**

**Usability – Inclusive Design – Information Architecture**

CARRERA : Ingeniería de Software

CURSO : Desarrollo de Aplicaciones Open Source

SECCIÓN : SW53

PROFESOR : Elio Jefferrson Navarrete Vilca

AUDITOR : MetaSoft

CLIENTE(S) : Nombre de las personas que participan en la sesión

SITE o APP A EVALUAR: ReStyle

TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
* Landing Page
  * i. tarea 1
  * ii. tarea 2
  * iii. tarea 3
* Web Application
  * i. tarea 1
  * ii. tarea 2
  * iii. tarea 3

### ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel | Descripción                                                                                                                                                                                     |
|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                   |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.                                 |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                               |

#### TABLA DE RESUMEN - Landing Page

| # | Problema                                                                        | Escala de severidad | Heurística/Principio violada(o)                       |
|---|---------------------------------------------------------------------------------|---------------------|-------------------------------------------------------|
| 1 | No hay un control que permita regresar a la tienda durante el trámite de compra | 3                   | Usability: Libertad y control del usuario             |
| 2 | Se repiten constantemente algunas opciones                                      | 1                   | Usability: Consistencia y estándares                  |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** No hay un control que permita regresar a la tienda durante el trámite de compra

**Severidad:** 3

**Heurística violada:** Usabilidad - Libertad y control del usuario

**Problema:**

Al momento de ingresar nuestros datos, no podemos regresar a la tienda en caso así lo Una vez el cliente pase al trámite de
compra, en caso de que este quiera regresar a la tienda, no hay un botón que lo envié al inicio de la web, lo cual nos obliga a
efectuar el trámite y al momento de elegir más productos, realizar otro, incrementándose así la cantidad de esfuerzo del usuario.
(Incluir además una captura de pantalla ilustrando el problema).

**Recomendación:**

La más práctica es que al momento en que queramos realizar dicho trámite, el navegador lo abra en una ventana aparte para
no perder los cambios realizados en nuestro carrito de compras.

#### TABLA DE RESUMEN - Web Application

| # | Problema                                                                        | Escala de severidad | Heurística/Principio violada(o)                       |
|---|---------------------------------------------------------------------------------|---------------------|-------------------------------------------------------|
| 1 | No hay un control que permita regresar a la tienda durante el trámite de compra | 3                   | Usability: Libertad y control del usuario             |
| 2 | Se repiten constantemente algunas opciones                                      | 1                   | Usability: Consistencia y estándares                  |
| 3 | Imágenes sin atributo “alt”                                                     | 3                   | Inclusive Design: Proporcionaexperiencias comparables |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** No hay un control que permita regresar a la tienda durante el trámite de compra

**Severidad:** 3

**Heurística violada:** Usabilidad - Libertad y control del usuario

**Problema:**

Al momento de ingresar nuestros datos, no podemos regresar a la tienda en caso así lo Una vez el cliente pase al trámite de
compra, en caso de que este quiera regresar a la tienda, no hay un botón que lo envié al inicio de la web, lo cual nos obliga a
efectuar el trámite y al momento de elegir más productos, realizar otro, incrementándose así la cantidad de esfuerzo del usuario.
(Incluir además una captura de pantalla ilustrando el problema).

**Recomendación:**

La más práctica es que al momento en que queramos realizar dicho trámite, el navegador lo abra en una ventana aparte para
no perder los cambios realizados en nuestro carrito de compras.

## 5.4. Video About-the-Product

En esta sección presentamos el video about the product. Este consolida una orientación promocional, resumiendo el modelo de nuestro negocio de ReStyle, las características y beneficios del producto, incluyendo algunas escenas deinteracción con el producto y una opinión por cada segmento objetivo, en nuestro caso segmento ojetivo de contratistas y remodeladores.

¿Eres una empresa remodeladora que desea acceder a una amplia gama de clientes o eres un cliente que desea remodelar su propiedad? Te presentamos a ReStyle. ReStyle es nuestra plataforma que te ayuda a encontrar profesionales en la remodelación y reparación de cuestiones del hogar.

<img src="/assets/img/chapter-V/sprint-3/about-the-product.png" alt="Foto de video about-the-product">

Link de Microsoft Stream: https://shorturl.at/df2vW

Link de Youtube: https://youtu.be/H3xHZWDBIy0

## Avance de Conclusiones, Bibliografía y Anexos.

### **Conclusiones**

En conclusión, el propósito de este informe consiste en elaborar un documento que incluya especificaciones que permitan documentar una solución de software. Para lograrlo, es necesario incluir información detallada sobre el proyecto a desarrollar, lo cual implica describir la idea de manera clara y concisa. Este análisis debe ser completo y exhaustivo, y debe proporcionar información detallada sobre los requisitos, las funcionalidades y los objetivos del software.

Las user stories son una herramienta útil para describir requisitos de software de manera simple y centrada en el usuario. En conclusión, las user stories son una herramienta importante en el desarrollo de software ágil para garantizar que el equipo esté creando un producto centrado en el usuario y que se estén satisfaciendo las necesidades del cliente de manera efectiva.


  
### **Bibliografía**
Instituto Nacional de Estadística e Informática. (2018). En el país existen más de diez millones de viviendas particulares censadas. Recuperado de: https://m.inei.gob.pe/prensa/noticias/en-el-pais-existen-mas-de-diez-millones-de-viviendas-particulares-censadas-10893/

Instituto Nacional de Estadística e Informática. (2018). Informe Técnico N° 02: Demografía empresarial - I Trimestre 2018. Recuperado de: https://www.inei.gob.pe/media/MenuRecursivo/boletines/02-informe-tecnico-n-02-demografia-empresarial-i-trim2018_may2018.pdf 

Interaction Design Foundation. (s.f.). A simple introduction to Lean UX. Recuperado de: https://www.interaction-design.org/literature/article/a-simple-introduction-to-lean-ux#:~:text=Creating%20a%20Hypothesis%20in%20Lean%20UX,-The%20hypotheses%20created&text=There's%20a%20simple%20format%20that,level%20of%20sign%20up%20completions.

Ipsos. (2019). Planes para la vivienda y el mejoramiento del hogar 2019. Recuperado de: https://www.ipsos.com/es-pe/planes-para-la-vivienda-y-el-mejoramiento-del-hogar-2019

Microsoft. (2022). Aceleración digital: Más del 94% de las pymes peruanas invirtió en tecnología en el último año [Comunicado de prensa]. Recuperado de https://news.microsoft.com/es-xl/aceleracion-digital-mas-del-94-de-las-pymes-peruanas-invirtio-en-tecnologia-en-el-ultimo-ano/

Terrel E. (2023). Cinco razones por las que los peruanos eligen remodelar su vivienda. Recuperado de: https://peruconstruye.net/2023/08/03/cinco-razones-eligen-remodelar-vivienda/


### **Anexos**

<table>
        <thead>
            <tr>
                <th>Sección</th>
                <th>Características del video</th>
                <th>Sobre el contenido</th>
                <th>Integración y entrega</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Needfinding Interviews</td>
                <td>Cantidad de videos: 1 <br> 
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-needfinding-sprint-1 <br>
                  Formato: .mp4 <br>
                  Duración: 30:56 min </td>
                <td>Consolida todas las entrevistas realizadas</td>
                <td>Link: https://shorturl.at/acGL6
                  Captura: <br>
                  <img src="/assets/img/chapter-V/sprint-2/interview-video.png" alt="" width="350"/> </td>
            </tr>
            <tr>
                <td>Exposicion</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-expo-tb1 <br>
                  Formato: .mp4 <br>
                  Duración: 27:19 min</td>
                <td>Consolida las exposiciones de la TB1</td>
                <td>Link: https://shorturl.at/kxyF2 Captura: <br>
                  <img src="/assets/img/chapter-V/sprint-1/expo-video.png" alt="" width="350"/> </td>
            </tr>
            <tr>
                <td>Prototypes Navigation / Product Navigation</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-prototype-navigation-sprint-1 <br>
                  Formato: .mp4 <br>
                  Duración: 4:21 min</td>
                <td>Consolida demostración del flujo de navegación de las aplicaciones, priorizando los user flows relacionados con el core business.</td>
                <td>Link: https://shorturl.at/goCR6 Captura: <br>
                  <img src="/assets/img/chapter-V/sprint-1/prototype-video.png" alt="" width="350"/> </td>
            </tr> 
            <tr>
                <td>Exposicion</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-expo-tp <br>
                  Formato: .mp4 <br>
                  Duración: 22:34 min</td>
                <td>Consolida las exposiciones del TP</td>
                <td>Link: https://shorturl.at/ltEW4 Captura:<br>
                  <img src="/assets/img/chapter-V/sprint-2/exposixión-tp.png" alt="" width="350"/> </td>
            </tr>      
            <tr>
                <td>Validation Interviews</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-validation-sprint-3 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida sesiones y
                entrevistas de validación en
                las que usuarios de los
                segmentos objetivo
                interactúen con el landing
                page y con los prototipos de
                experiencias web,
                manifestando sus
                observaciones.
                </td>
                <td>Link:  Captura: <br>
                <img src="" width="350" alt=""/> </td>
            </tr>     
            <tr>
                <td>About the Product</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-about-the-product-sprint-3<br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida el video promocional, resumiendo el modelo de negocio, las características y beneficios del producto.
                </td>
                <td>Link: Stream: https://shorturl.at/O4FJW Youtube: https://youtu.be/H3xHZWDBIy0 Captura: <br>
                <img src="/assets/img/chapter-V/sprint-3/about-the-product.png" width="350" alt=""/> </td>
            </tr>   
            <tr>
                <td>About the Team</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-about-the-team-sprint-3<br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Video que resume el proceso
                  de trabajo realizado,
                  incluyendo escenas de
                  sesiones de trabajo real del
                  equipo, complementando con
                  narración (voz en off) del
                  proceso. Incluye además el
                  testimonio ante cámara de
                  cada participante
                  describiendo actividades
                  realizadas, logro de outcomes
                  y desarrollo de competencias
                  alcanzados.
                </td>
                <td>Link:  Captura: <br>
                <img src="" width="350" alt=""/> </td>
            </tr>   
            <tr>
                <td>Exposicion</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si729-sw53-metasoft-expo-tb2 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida las exposiciones del TB2</td>
                <td>Link:  Captura: <br>
                  <img src="" width="350" alt=""/> </td>
            </tr>   
        </tbody>
</table>

