# Capítulo III: Requirements Specification.

## 3.1. To-Be Scenario Mapping.

**Geraldo Colchado Ruiz**
<table>
  <thead>
    <tr>
      <th>Phases</th>
      <th>Busqueda cliente</th>
      <th>Presentacion de la Propuesta</th>
      <th>Ejecucion del Proyecto</th>
      <th>Post venta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Acciones</td>
      <td>Geraldo se suscribe a la aplicación y crea un perfil para su negocio. Publica fotos de sus proyectos, recibe reseñas de clientes que lo ayudan a encontrar mas clientes</td>
      <td>Geraldo se comunica con los clientes potenciales a través de la aplicación, les envía mensajes y recibe solicitudes de cotización.</td>
      <td>Utiliza la aplicación para gestionar el proyecto y coordina con los proveedores y los clientes</td>
      <td>Utiliza la aplicación para enviar recordatorios de mantenimiento a los clientes y para obtener comentarios sobre su trabajo.</td>
    </tr>
    <tr>
      <td>Pensamientos</td>
      <td>Se siente confiado de que la aplicación le ayudará a llegar a un público más amplio y a encontrar más clientes.</td>
      <td>Se siente más organizado y eficiente gracias a la aplicación.</td>
      <td>Se siente más tranquilo al tener toda la información del proyecto en la aplicacion, la cual puede referenciar</td>
      <td>Se siente agradecido por la fidelidad de sus clientes y por la oportunidad de hacer crecer su negocio.</td>
    </tr>
    <tr>
      <td>Sentimiento</td>
      <td>Optimista, motivado</td>
      <td>Seguro, profesional</td>
      <td>En control, confiado</td>
      <td>Satisfecho, orgulloso</td>
    </tr>
  </tbody>
</table>

**Cesar Enrique Salas Arbaiza**
<table>
  <thead>
    <tr>
      <th>Phases</th>
      <th>Busqueda remodelador</th>
      <th>Seleccion de remodelador</th>
      <th>Ejecucion del Proyecto</th>
      <th>Post venta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Acciones</td>
      <td>Cesar busca un remodelador en la aplicación, utilizando filtros para especificar el tipo de proyecto y la ubicación</td>
      <td>Lee las reseñas de los clientes, compara precios y solicita presupuestos directamente a través de la aplicación</td>
      <td>Utiliza la aplicación para comunicarse con el remodelador, realizar pagos, seguir el progreso del proyecto y recibir notificaciones</td>
      <td>Califica al remodelador y deja una reseña en la aplicación.</td>
    </tr>
    <tr>
      <td>Pensamientos</td>
      <td>Se siente confiado de que la aplicación le ayudará a encontrar el remodelador adecuado de forma rápida y sencilla.</td>
      <td>Se siente más informado y seguro de su decisión gracias a la información disponible en la aplicación.</td>
      <td>Se siente más tranquilo al tener toda la información del proyecto en un solo lugar.</td>
      <td>Se siente satisfecho con la experiencia y con la ayuda que recibió de la aplicación.</td>
    </tr>
    <tr>
      <td>Sentimientos</td>
      <td>Optimista, motivado</td>
      <td>Seguro, confiado</td>
      <td>En control, satisfecho</td>
      <td>Agradecido, satisfecho</td>
    </tr>
  </tbody>
</table>

## 3.2. User Stories. 

<table>
    <thead>
        <tr>
            <th>Epic / Story ID</th>
            <th>Título </th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionado con (Epic ID)</th>
        </tr>
    </thead>
    <body  >
        <tr style="text-align:center">
            <td>UH01</td>
            <td>Hipervínculos en el encabezado</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> visitante de la landing page, 
            <strong>quiero</strong> que las opciones del encabezado me dirijan a las diferentes secciones de la Landing Page 
            <strong>para</strong>, poder navegar de forma rapida y fluida. 
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Navegación fluida.</h5>
            <strong>Dado</strong> Un usuario ha navegado a una sección de la Landing Page.
            <strong>cuando</strong> El usuario hace clic en otra opción del encabezado.
            <strong>Entonces</strong> La página se desplaza suavemente a la nueva sección seleccionada.
            <strong>Y</strong> La URL de la página cambia para reflejar la nueva sección.
            <!-- ---------- -->
            <h5>Escenario 02: Múltiples Dispositivos</h5>
            <strong>Dado</strong> Un usuario visita la landing page desde un dispositivo móvil.
            <strong>cuando</strong> El usuario hace clic en una opción del encabezado.
            <strong>Entonces</strong> La página se desplaza suavemente a la sección correspondiente, adaptándose al tamaño de la pantalla del dispositivo.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td>UH02 </td>
            <td>Información sobre beneficios de la aplicación</td>
            <!-- Descripción -->
            <td>
            <strong>Como</strong> usuario, 
            <strong>quiero</strong> saber más sobre los beneficios de la aplicación web 
            <strong>para</strong> considerar ser miembro de la aplicacion. 
            </td>
            <!-- Criterios de Aceptación -->
            <td>
            <h5>Escenario 01: Navegación a la sección de beneficios</h5>
            <strong>Dado</strong> Un usuario visita la página de inicio de la aplicación web.
            <strong>Cuando</strong> El usuario hace clic en la sección "Beneficios".
            <strong>Entonces</strong> Se muestra una página con información clara y concisa sobre los beneficios de la aplicación.
            <strong>Y</strong> La información incluye una lista de beneficios, imágenes ilustrativas y ejemplos concretos.
            <strong>Y</strong> La página ofrece la posibilidad de descargar la aplicación o registrarse para obtener una prueba gratuita. 
            Dado: Un usuario está leyendo la página de beneficios.
            <h5>Escenario 02: Información Clara y Concisa</h5>
            <strong>Dado</strong> Un usuario está leyendo la página de beneficios.
            <strong>Cuando</strong> El usuario lee la información sobre un beneficio específico.
            <strong>Entonces</strong> La información es fácil de entender y no contiene lenguaje técnico.
            <strong>Y</strong> La información se presenta de forma organizada y atractiva.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td>UH03</td>
             <td>Mostrar los planes disponibles</td>
            <!-- Descripción -->
            <td>
            <strong>Como</strong> visitante del landing page, 
            <strong>quiero</strong> saber sobre los planes que tiene, 
            <strong>para</strong> poder analizar si el plan que me ofrecen se adecua a las necesidades de mi negocio.
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 1: Información Clara y Concisa.</h5>
            <strong>Dado</strong> Un usuario está leyendo la página de un plan específico.
            <strong>Cuando</strong> El usuario lee la información sobre una función específica del plan.
            <strong>Entonces</strong> La información es fácil de entender y no contiene lenguaje técnico.
            <strong>Y</strong> La información se presenta de forma organizada y atractiva.
            <h5>Escenario 2: Comparación de Planes.</h5>
            <strong>Dado</strong> Un usuario está leyendo la página de un plan específico.
            <strong>Cuando</strong> El usuario quiere comparar el plan con otro plan.
            <strong>Entonces</strong> La página ofrece una herramienta para comparar los planes en paralelo, mostrando las diferencias en precio, funciones, beneficios y limitaciones.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td>UH04 </td>
            <td> Información útil en el footer </td>
            <!-- Descripción -->
            <td>
            <strong>Como</strong> usuario que visita la landing page, 
            <strong>quiero</strong> encontrar información útil en el footer 
            <strong>para</strong> poder contactarme con la empresa, conocer más sobre ella, leer sus políticas y seguirla en redes sociales.</td>
            <!-- Criterios de Aceptación -->
            <td>
            <h5>Escenario 01: Información de Contacto</h5>
            <strong>Dado </strong> Un usuario visita la landing page.
            <strong>Cuando</strong> El usuario busca información de contacto en el footer.
            <strong>Entonces</strong> El footer muestra la siguiente información de correo electrónico, teléfono y dirección
            <strong>Y</strong> La información de contacto está resaltada en un color diferente al resto del texto del footer.
            <h5>Escenario 02: Redes Sociales</h5>
            <strong>Dado</strong> Un usuario visita la landing page.
            <strong>Cuando</strong> El usuario busca los iconos de redes sociales en el footer.
            <strong>Entonces</strong> El footer muestra iconos de las redes sociales Facebook, Twitter e Instagram.
            <strong>Y</strong> Al hacer clic en un icono de red social, el usuario es dirigido a la página de la empresa en esa red social.
            <h5>Escenario 03: Navegación</h5>
            <strong>Dado</strong> Un usuario visita la landing page.
            <strong>Cuando</strong> El usuario decida visitar otras secciones desde el footer.
            <strong>Entonces</strong> El footer muestra las opciones de navegación de las secciones de la landing page
            <strong>Y</strong> Al hacer clic en alguna de las opciones, el usuario es dirigido a la sección correspondiente
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH05</td>
            <td> Información sobre el producto </td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario que visita la landing page, 
            quiero</strong> entender claramente qué ofrece el producto 
            <strong>para</strong> poder tomar una decisión informada sobre si adquirirlo o no.
            </td>
             <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 1: Descripción Clara y Concisa</h5>
            <strong>Dado</strong> Un usuario visita la landing page.
            <strong>Cuando</strong> El usuario lee y visualiza un video sobre la descripción del producto 
            <strong>Entonces</strong> La descripción del producto debe ser:
            clara y concisa, resaltar los beneficios clave del producto, enfatizar las ventajas que ofrece el producto al usuario 
            <strong>Y</strong> así Motivar al usuario a adquirir el producto.
            <h5>Escenario 02: Llamado a la Acción</h5>
            <strong>Dado</strong> un usuario ha leído la información del producto.
            <strong>Cuando</strong> el usuario decide que quiere adquirir el producto.
            <strong>Entonces</strong> la sección del producto debe ofrecer un botón claro y visible para descargar e iniciar a utilizar el producto.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH06 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH07 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH08 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH09 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH10 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH11 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH12 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH13 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH14 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH15 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH16 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH17 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH18 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH19 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center"> 
            <td> UH20 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH21 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH22 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH23 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH24 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> UH25 </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
    </body>
</table>











| **Epic / Story ID** | **Título**                                          | **Descripción**                                                                                                                                                                                                                                                                  | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | **Relacionado con (Epic ID)** |
|---------------------|-----------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| EPIC-001            | Conexion de empresas remodeladoras con contratistas | **Como** usuario remodelador, **quiero** poder promocionar mis servicios de remodelación **para** aumentar el alcance de mi empresa                                                                                                                                              | **Dado** que el remodelador se encuentra en la plataforma de ReStyle  **Cuando** se registre al sistema **Y** se suscriba a un plan premium  **Entonces** el usuario puede acceder a todas las opciones y publicar sus servicios dentro de aplicación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | N/A                           | 
| EPIC-002            | Contratar empresas remodeladoras                    | **Como** usuario contratista, **quiero** poder contratar remodeladoras **para** realizar mis proyectos de diseño                                                                                                                                                                 | **Dado** que el cliente se encuentra en la plataforma de ReStyle  **Cuando** encuentra una empresa remodeladora de su agrado **Y** se acuerda un contrato entre ambas partes  **Entonces** el proyecto de diseño se crea en el sistema                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | N/A                           |
| EPIC-003            | Implementar API RESTful                             | **Como** desarrollador, **quiero** poder integrar el sistema de creación de proyectos de diseño con la aplicación web **para** implementar la funcionalidad de la plataforma                                                                                                     | **Dado** que el desarrollador tiene una aplicación que necesita integrar con el sistema **Cuando** utiliza la API RESTful **Entonces** puede integrar el sistema con la aplicación web                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | N/A                           |
| US-001              | Subir contenido a un portafolio                     | **Como** usuario remodelador, **quiero** poder subir contenido multimedia a mi portafolio online **para** poder promocionar servicios y proyectos pasados a mis posibles clientes                                                                                                | Escenario 01: **Dado** que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle  **Cuando** sube contenido a la aplicación **Y** guarda los cambios  **Entonces** el sistema muestra los contenidos subidos en la plataforma y le notifica al remodelador sobre los cambios realizados. Escenario 02: **Dado** que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle  **Cuando** sube contenido a la aplicación **Y** no guarda los cambios  **Entonces** el sistema le notifica al usuario que necesita guardar los cambios para ver los contenidos en la plataforma. Escenario 03: **Dado** que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle  **Cuando** intenta subir contenido a la aplicación que supera los límites de carga **Entonces** el sistema le notifica al usuario que necesita respetar los límites de carga para poder subir los contenidos a la plataforma                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EPIC-001                      | 
| US-002              | Crear proyecto de diseño                            | **Como** usuario remodelador, **quiero** poder crear proyectos de diseño dentro de la plataforma **para** poder comenzar el proceso de remodelación                                                                                                                              | Escenario 01: **Dado** que el remodelador se encuentra en sus proyectos dentro de su perfil de ReStyle **Cuando** crea un proyecto de diseño **Y** rellena los campos requeridos  **Entonces** el sistema guarda los datos ingresados, genera un nuevo proyecto de diseño **Y** le notifica al remodelador sobre el mismo. Escenario 02: **Dado** que el remodelador se encuentra en sus proyectos dentro de su perfil de ReStyle **Cuando** crea un proyecto de diseño **Y** no rellena los campos requeridos  **Entonces** el sistema le notifica al remodelador que necesita completar los campos faltantes antes de crear un proyecto de diseño **Y** no realiza ningún cambio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | EPIC-001                      | 
| US-003              | Búsqueda de empresas remodeladoras                  | **Como** visitante del segmento contratista, **quiero** poder buscar remodeladoras por ubicación geográfica y estilos de diseño **para** obtener un resultado más personalizado                                                                                                  | Escenario 01: **Dado** que el visitante del segmento contratista se encuentra en la plataforma de ReStyle  **Cuando** realiza una búsqueda **Y** selecciona la ubicación mediante un filtro **Entonces** el sistema solo le muestra las remodeladoras que cumplen con los requisitos. Escenario 02: **Dado** que el visitante del segmento contratista se encuentra en la plataforma de ReStyle  **Cuando** realiza una búsqueda **Y** selecciona uno o varios estilos de diseño mediante filtros **Entonces** el sistema solo le muestra las remodeladoras que cumplen con los requisitos. Escenario 03: **Dado** que el visitante del segmento contratista se encuentra en la plataforma de ReStyle  **Cuando** realiza una búsqueda **Y** no selecciona ningún filtro **Entonces** el sistema le muestra todas las remodeladoras disponibles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | EPIC-002                      | 
| US-004              | Revisar críticas y opiniones                        | **Como** visitante del segmento contratista, **quiero** ver las opiniones de otros clientes **para** tener una idea de la calidad del trabajo del remodelador                                                                                                                    | Escenario 01: **Dado** que el visitante del segmento contratista se encuentra el perfil de un remodelador en la plataforma de ReStyle **Cuando** accede a la sección de reviews **Y** no selecciona ningún filtro **Entonces** el sistema le muestra en orden cronológico todas las reviews hechas al remodelador escogido. Escenario 02: **Dado** que el visitante del segmento contratista se encuentra el perfil de un remodelador en la plataforma de ReStyle **Cuando** accede a la sección de reviews **Y** selecciona un filtro por cantidad de estrellas **Entonces** el sistema solo le muestra las reviews que coinciden con los requisitos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EPIC-002                      | 
| US-005              | Gestión de solicitudes al servidor                  | **Como** desarrollador, **quiero** asegurarme de que el API pueda gestionar múltiples solicitudes de varios dispositivos **para** que el sistema funcione sin interrupciones durante temporadas de alta demanda                                                                  | Escenario 01: **Dado** que el desarrollador realiza las pruebas de carga en el API **Cuando** envía múltiples solicitudes simultáneas **Entonces** el tiempo de respuesta está dentro del rango promedio **Y** no existen errores o caídas del sistema. Escenario 02: **Dado** que el desarrollador realiza las pruebas de carga en el API **Cuando** envía múltiples solicitudes simultáneas de distintos dispositivos **Entonces** el tiempo de respuesta está dentro del rango promedio **Y** no existen errores o caídas del sistema                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EPIC-003                      | 
| US-006              | Autorización y seguridad de acceso al API           | **Como** desarrollador, **quiero** poder configurar una autenticación y autorización segura en el API **para** garantizar que solos los usuarios admin puedan acceder al sistema                                                                                                 | Escenario 01: **Dado** que un usuario con rol admin quiere ingresar al API **Cuando** proporciona sus credenciales **Y** estas son válidas **Entonces** el sistema le permite ingresar. Escenario 02: **Dado** que un usuario con rol admin quiere ingresar al API **Cuando** proporciona sus credenciales **Y** estas no son válidas **Entonces** el sistema no le permite ingresar **Y** le notifica que tiene 2 intentos restantes para ingresar al sistema. Escenario 03: **Dado** que un usuario con un rol distinto a admin quiere ingresar al API **Cuando** proporciona sus credenciales **Y** estas no son válidas **Y** superó los intentos restantes **Entonces** el sistema no le permite ingresar **Y** notifica a los administradores sobre el intento de acceso                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EPIC-003                      |
| US-007              | Promocionar contenido                               | **Como** usuario remodelador, **quiero** poder promocionar el contenido de mi portafolio  **para** aumentar mi cantidad de clientes                                                                                                                                              | Escenario 01: **Dado** que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle, **Cuando** seleccione el contenido que quiere promocionar **Y** haga Click en el boton  de Promocionar, **Entonces** le saldra una pantalla en donde podra seleccionar cuanto tiempo el contenido se mostrara, a cuantas personas y el costo y seleccionar la tarjeta con la que quiere pagar Escenario 02: **Dado** que el usuario remodelador ha usado su tarjeta de credito o debito en ReStyle antes, **Cuando** seleccione su tarjeta en la pantalla de pago  para promocioin de contenido y seleccione la promocion por la cual desea pagar y le de click en aceptar, **Entonces** salda un mensaje de pago exitoso Escenario 03: **Dado** a que el usuario remodelador  nunca antes ha usado su tarjeta de credito o debito en ReStyle, **Cuando** este en la pantalla de pago de promocion de contenido, **Entonces** le saldan los campos de su tarjeta que debe llenar para poder realizar el pago Escenario 04: **Dado** que el usuario remodelador no ha seleccionado el plan de promocion de contenido por el que quiere pagar, **Cuando** le de Click a Aceptar, **Entonces** saldra un mensaje de error. Escenario 05: **Dado** a que el usuario remodelador  nunca antes ha usado su tarjeta de credito o debito en ReStyle **y** no haya llenado los datos solicitados de tarjeta, **Cuando** le de click en aceptar, Entonces saldra un mensaje de error.                                                                                                                                                                                                   | EPIC-001                      |
| US-008              | Continuar promocion de contenido                    | **Como** usuario remodelador, **quiero** extender el plazo de tiempo de la promocion de mi contenido  **para** mantener el aumento de alcanze de mi negocio                                                                                                                      | Escenario 01: **Dado** que el usuario remodelador ha pagado por promocion de contenido,  **Cuando** falte 1 dia para terminar el plazo de promocion, **Entonces** le aparecera una pantalla para continuar la promocion y aprobar el pago. Escenario 02: **Dado** que el usuario remodelador ha pagado por promocion de contenido, **Cuando** le aparezca la pantalla de Continuar Promocion **y** le de Click al boton de Continuar **y** le de click a Aceptar Pago, **Entonces** el pago sera aprovado y se continuara la promocion de contenido. Escenario 03 **Dado** que el usuario remodelador ha pagado por promocion de contenido, **Cuando** le aparezca la pantalla de Continuar Promocion **y** le de Click al boton de No Continuar **Entonces** saldra una pantalla confirmando la negacion de promocion y la promocion concluira en un plazo menor a 24 horas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EPIC-001                      |
| US-009              | Suscripción remodelador                             | **Como** usuario remodelador, **quiero** poder suscribirme a ReStyle **para** poder acceder al mercado qué provee                                                                                                                                                                | Escenario 01: **Dado** que el usuario remodelador se encuentra la pantalla inicial de ReStyle , **Cuando** le de click al boton de Suscribirse (Para Negocios), **Entonces** le aparecera la pantalla de Creacion de Cuenta Nueva. Escenario 02: **Dado** que el usuario remodelador se encuentra en la pantalla de Creacion de Cuenta nueva, **Cuando** llene los datos solicitados **Y** le de Click al Boton Aceptar **Entonces** le aparecera la pantalla de Planes de Pago. Escenario 03: **Dado** que el usuario remodelador se encuentra en la pantalla de Creacion de Cuenta Nueva **Y** no haya llenado los datos solicitados, **Cuando** le de click al boton Aceptar, **Entonces** le aparecera un mensaje de error. Escenario 04: **Dado** que el usuario remodelador se encuentra en la pantalla de Planes de Pago **Cuando** seleccione el plan al que desea suscribirse **Y** le de click a aceptar, **Entonces** le aparecera la pantalla de Pagos. Escenario 05: **Dado** que el usuario remodelador se encuentra en la pantalla de Planes de Pago **y** no haya seleccionado un plan al que desea suscribirse **Cuando** le de click a aceptar, **Entonces** le aparecera un mensaje de error. Escenario 06: **Dado** que el usuario remodelador se encuentra en la pantalla de Pagos **Cuando** ingrese los datos de su tarjeta **Y** le de click a aceptar, **Entonces** el pago sera procesado le aparecera un mensaje suscripcion exitosa. Escenario 07: **Dado** que el usuario remodelador se encuentra en la pantalla de Pagos **Y** no haya ingresado los datos de su tarjeta **Cuando**  le de click a aceptar, **Entonces** aparecera un mensaje de error | EPIC-001                      |
| US-010              | Crear cuenta contratista                            | **Como** usuario contratista, **quiero** poder crear una cuenta en ReStyle **para** poder acceder al mercado qué provee                                                                                                                                                          | Escenario 01: **Dado** que el usuario contratista se encuentra la pantalla inicial de ReStyle , **Cuando** le de click al boton de Crear cuenta, **Entonces** le aparecera la pantalla de Creacion de Cuenta Nueva. Escenario 02: **Dado** que el usuario contratista se encuentra en la pantalla de Creacion de Cuenta nueva, **Cuando** llene los datos solicitados **Y** le de Click al Boton Aceptar **Entonces** le aparecera la pantalla de Iniciar Sesion. Escenario 03: **Dado** que el usuario contratista se encuentra en la pantalla de Creacion de Cuenta Nueva **Y** no haya llenado los datos solicitados, **Cuando** le de click al boton Aceptar, **Entonces** le aparecera un mensaje de error.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EPIC-002                      |
| US-011              | Busqueda remodeladores                              | **Como** usuario contratista, **quiero** poder buscar remodeladores **para** facilitar el proceso de contrato                                                                                                                                                                    | Escenario 01: **Dado** que el usuario contratista se encuentra en la pantalla de busqueda, **Cuando** ingrese el nombre de un remodelador en la barra de busqueda, **Entonces** se mostrara el perfil del remodelador cuyo nombre sea igual al ingresado en la busqueda. Escenario 02: **Dado** que el usuario contratista se encuentra en la pantalla de busqueda, **Cuando** ingrese el nombre de un remodelador en la barra de busqueda **Y** no exista un perfil con un nombre igual al ingresado en la busqueda, **Entonces** se mostraran perfiles con nombres similares a los ingresados en la busqueda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EPIC-002                      |
| US-012              | Busqueda proyectos                                  | **Como** usuario contratista, **quiero** poder buscar proyectos hechos por remodeladores **para** saber qué el remodelador con el qué trabajo puede hacer el proyecto qué me interesa                                                                                            | Escenario 01: **Dado** que el usuario contratista se encuentra en la pantalla de busqueda, **Cuando** ingrese el proyecto que le interesa en la barra de busqueda **Entonces** mostrara todos los proyectos con un nombre igual al ingresado. Escenario 02: **Dado** que el usuario contratista se encuentra en la pantalla de busqueda, **Cuando** ingrese el proyecto que le interesa en la barra de busqueda **Y** no exista un proyecto con un nombre igual **Entonces** se mostraran proyectos con nombres parecidos a los ingresados                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EPIC-002                      |
| TS-001              | Get Portfolio                                       | **Como** desarrollador backend en reStyle, **quiero** obtener la información del portafolio de los remodeladores a través de una API **para** permitir al equipo de frontend utilizar los datos del portafolio en la interfaz de usuario                                         | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de Portfolio, **Cuando** envío una solicitud para la obtención de datos del portafolio de los usuarios. **Entonces** recibo la información de los portafolios en un response de formato JSON. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de Portfolios, **Cuando** envío una solicitud para la obtención de datos del portafolio de los usuarios **Y** el parámetro no exista o es erróneo **Entonces** recibo una mensaje de error en la solicitud                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                               |
| TS-002              | Get Portfolio by User                               | **Como** desarrollador backend en reStyle, **quiero** obtener la información del portafolio por usuario remodelador a través de una API **para** permitir al equipo de frontend utilizar los datos del portafolio en la interfaz de usuario                                      | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de Portfolio by user, **Cuando** envío una solicitud para la obtención de datos del portafolio de un usuario por id. **Entonces** recibo la información del portafolio en un response de formato JSON. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de Portfolio by user, **Cuando** envío una solicitud para la obtención de datos del portafolio del usuarios **Y** el parámetro de ID no exista o es erróneo **Entonces** recibo una mensaje de error en la solicitud                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                               |
| TS-003              | Get Project by User                                 | **Como** desarrollador backend en reStyle, **quiero** obtener los datos del proyecto actual de un remodelador a través de una API **para** permitir al equipo de frontend utilizar los datos del proyecto y mostrarlo a los contratistas                                         | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de Project by user, **Cuando** envío una solicitud para la obtención de datos del proyecto de un usuario por id. **Entonces** recibo la información del proyecto en un response de formato JSON. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de Project by user, **Cuando** envío una solicitud para la obtención de datos del proyectos del usuario **Y** el parámetro no exista o sea erróneo **Entonces** recibo una mensaje de error en la solicitud                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                               |
| TS-004              | Post Job Offer                                      | **Como** desarrollador backend en reStyle, **quiero** agregar una funcionalidad para que los contratistas puedan crear anuncios de oportunidad laboral a través una API **para** permitir a los contratistas hacer el registro adecuado de una publicación                       | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de JobOffer, **Cuando** envío una solicitud con datos validados para el registro de una nueva publicación.  **Entonces** la información de la publicación se guardará con éxito en la base de datos de la aplicación. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de JobOffer, **Cuando** envío una solicitud para el registro de una nueva publicación sin datos validados. **Entonces** recibo una mensaje de error en la solicitud y se rechaza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                               |
| TS-005              | Post Recommedation                                  | **Como** desarrollador backend en reStyle, **quiero** agregar una funcionalidad para que los contratistas puedan crear reseñas de recomendación sobre los remodeladores a través de  una API **para** permitir a los contratistas compartir su opinión del trabajador contratado | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de Recommendations, **Cuando** envío una solicitud con datos validados para el registro de una nueva reseña. **Entonces** la información de la reseña se guardará con éxito en la base de datos. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de Recommendations, **Cuando** envío una solicitud para el registro de una nueva reseña sin datos validados. **Entonces** recibo una mensaje de error en la solicitud y se rechaza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                               |
| TS-006              | Get Recommendation                                  | **Como** desarrollador backend en reStyle, **quiero** obtener la información de las reseñas creadas por los contratistas a través de una API **para** permitir al equipo de frontend utilizar los datos de la reseña                                                             | Escenario 01: **Dado** que tengo autorización en el uso de la API y al endpoint de Recommendations, **Cuando** envío una solicitud para la obtención de datos de las reseñas de los usuarios. **Entonces** recibo la información de las reseñas en un response de formato JSON. Escenario 02: **Dado** que tengo autorización en el uso de la API y al endpoint de Recommendations, **Cuando** envío una solicitud para la obtención de datos de las reseñas  **Y** el parámetro no exista o es erróneo **Entonces** recibo una mensaje de error en la solicitud                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                               |

## 3.3. Impact Mapping.

Contenido

## 3.4. Product Backlog.

Contenido
