# Capítulo III: Requirements Specification.

## 3.1. To-Be Scenario Mapping.

**Henry Silva**
![ToBeHenry](/docs/assets/img/ToBeHenry.jpg)

**Danilo Alvez**
![ToBeDanilo](/docs/assets/img/ToBeDanilo.jpg)

## 3.2. User Stories. 

Contenido

<table>
      <thead>
            <tr>
                <th>Epic / Story ID</th>
                <th>Título</th>
                <th>Descripción</th>
                <th>Criterios de Aceptación</th>
                <th>Relacionado con (Epic ID)</th>
            </tr>
      </thead>
      <tbody>
            <tr>
                <td>EPIC-001</td>
                <td>Establecer comunicación con los remodeladores</td>
                <td>
                    <strong>Como</strong> usuario contratista, <strong>quiero</strong> establecer comunicación
                    efectiva con los remodeladores <strong>para</strong> poder expresar mis necesidades, expectativas
                    y recibir información actualizada sobre el proyecto de remodelación.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-002</td>
                <td>Contratación de servicios de remodelación</td>
                <td>
                    <strong>Como</strong> usuario contratista, <strong>quiero</strong> contratar los servicios
                    de remodelación de manera eficiente y llevar un control <strong>para</strong> asegurar que el 
                    proyecto se realice acorde a mi presupuesto y necesidades.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-003</td>
                <td>Implementar API RESTful</td>
                <td>
                <strong>Como</strong> desarrollador, <strong>quiero</strong> implementar una API RESTful
                <strong>para</strong> poder acceder a los datos del sistema de forma segura.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-004</td>
                <td>Implementar Landing Page</td>
                <td>
                    <strong>Como</strong> vistante de la landing page, <strong>quiero</strong> acceder a una
                    Landing Page con distintas secciones informativas e interactivas que mencionen las características
                    y beneficios que obtendré <strong>para</strong> tener un conocimiento claro de la aplicación.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-005</td>
                <td>Gestión de portafolio</td>
                <td>
                    <strong>Como</strong> usuario remodelador, <strong>quiero</strong> tener una herramienta
                    que me ayude a gestionar mi portafolio de proyectos de manera eficiente <strong>para</strong> poder 
                    compartir mi trabajo a los contratistas interesados en mi perfil.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-006</td>
                <td>Gestión de proyecto</td>
                <td>
                    <strong>Como</strong> usuario remodelador, <strong>quiero</strong> tener una herramienta
                    que me ayude a gestionar el proyecto encargado por un contratista <strong>para</strong>
                    permitir el monitoreo de los avances y cumplimiento de los objetivos, presupuesto y cronograma.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>EPIC-007</td>
                <td>Gestión de suscripción</td>
                <td>
                    <strong>Como</strong> usuario remodelador, <strong>quiero</strong> contar con la posibilidad de 
                    suscribirme a un plan de pago <strong>para</strong> acceder a beneficios exclusivos y mejorar mi
                    experiencia en la aplicación.
                </td>
                <td>N/A</td>
                <td>N/A</td>
            </tr>
      </tbody>
</table>

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
            <td>US-001</td>
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
            <td>EPIC-004</td>
        </tr>
        <tr style="text-align:center">
            <td>US-002 </td>
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
            <td>EPIC-004 </td>
        </tr>
        <tr style="text-align:center">
            <td>US-003</td>
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
            <td> EPIC-004</td>
        </tr>
        <tr style="text-align:center">
            <td>US-004 </td>
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
            <td>EPIC-004 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-005</td>
            <td> Información sobre el producto </td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario que visita la landing page, 
            quiero entender claramente qué ofrece el producto 
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
            <td>EPIC-004 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-006 </td>
            <td> Subir contenido a un portafolio </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario remodelador,
            <strong> quiero </strong> poder subir contenido multimedia a mi portafolio online
            <strong>para</strong> poder promocionar servicios y proyectos pasados a mis posibles clientes.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle
            <strong>Cuando</strong> sube contenido a la aplicación
            <strong>Y</strong> guarda los cambios
            <strong>Entonces</strong> el sistema muestra los contenidos subidos en la plataforma y le notifica al remodelador sobre los cambios realizados.
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle
            <strong>Cuando</strong> sube contenido a la aplicación
            <strong>Y</strong> no guarda los cambios
            <strong>Entonces</strong> el sistema le notifica al usuario que necesita guardar los cambios para ver los contenidos en la plataforma. 
            <h5>Escenario 03: </h5>
            <strong>Dado</strong> que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle
            <strong>Cuando</strong> intenta subir contenido a la aplicación que supera los límites de carga
            <strong>Entonces</strong> el sistema le notifica al usuario que necesita respetar los límites de carga para poder subir los contenidos a la plataforma. 
            </td>
            <td>EPIC-005 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-007 </td>
            <td> Crear proyecto de diseño </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario remodelador,
            <strong> quiero</strong> poder crear proyectos de diseño dentro de la plataforma
            <strong>para</strong> poder comenzar el proceso de remodelación.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que el remodelador se encuentra en sus proyectos dentro de su perfil de ReStyle
            <strong>Cuando</strong> crea un proyecto de diseño
            <strong>Y</strong> rellena los campos requeridos
            <strong>Entonces</strong> el sistema guarda los datos ingresados, genera un nuevo proyecto de diseño
            <strong>Y</strong> le notifica al remodelador sobre el mismo.
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que el remodelador se encuentra en sus proyectos dentro de su perfil de ReStyle
            <strong>Cuando</strong> crea un proyecto de diseño
            <strong>Y</strong> no rellena los campos requeridos
            <strong>Entonces</strong> el sistema le notifica al remodelador que necesita completar los campos faltantes antes de crear un proyecto de diseño
            <strong>Y</strong> no realiza ningún cambio.
            </td>
            <td>EPIC-006 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-008 </td>
            <td> Búsqueda de empresas remodeladoras </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> visitante del segmento contratista,
            <strong>quiero</strong> poder buscar remodeladoras por ubicación geográfica y estilos de diseño
            <strong>para</strong> obtener un resultado más personalizado.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que el visitante del segmento contratista se encuentra en la plataforma de ReStyle
            <strong>Cuando</strong> realiza una búsqueda
            <strong>Y</strong> selecciona la ubicación mediante un filtro
            <strong>Entonces</strong> el sistema solo le muestra las remodeladoras que cumplen con los requisitos.
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que el visitante del segmento contratista se encuentra en la plataforma de ReStyle
            <strong>Cuando</strong> realiza una búsqueda
            <strong>Y</strong> selecciona uno o varios estilos de diseño mediante filtros
            <strong>Entonces</strong> el sistema solo le muestra las remodeladoras que cumplen con los requisitos.
            <h5>Escenario 03: </h5>
            <strong>Dado</strong> que el visitante del segmento contratista se encuentra en la plataforma de ReStyle
            <strong>Cuando</strong> realiza una búsqueda
            <strong>Y</strong> no selecciona ningún filtro
            <strong>Entonces</strong> el sistema le muestra todas las remodeladoras disponibles.
            </td>
            <td>EPIC-001 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-009 </td>
            <td> Revisar críticas y opiniones </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> visitante del segmento contratista,
            <strong>quiero</strong> ver las opiniones de otros clientes
            <strong>para</strong> tener una idea de la calidad del trabajo del remodelador.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que el visitante del segmento contratista se encuentra el perfil de un remodelador en la plataforma de ReStyle
            <strong>Cuando</strong> accede a la sección de reviews
            <strong>Y</strong> no selecciona ningún filtro
            <strong>Entonces</strong> el sistema le muestra en orden cronológico todas las reviews hechas al remodelador escogido.
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que el visitante del segmento contratista se encuentra el perfil de un remodelador en la plataforma de ReStyle
            <strong>Cuando</strong> accede a la sección de reviews
            <strong>Y</strong> selecciona un filtro por cantidad de estrellas
            <strong>Entonces</strong> el sistema solo le muestra las reviews que coinciden con los requisitos.
            </td>
            <td>EPIC-001 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-010 </td>
            <td> Gestión de solicitudes al servidor </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> desarrollador,
            <strong>quiero</strong> asegurarme de que el API pueda gestionar múltiples solicitudes de varios dispositivos
            <strong>para</strong> que el sistema funcione sin interrupciones durante temporadas de alta demanda.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que el desarrollador realiza las pruebas de carga en el API
            <strong>Cuando</strong> envía múltiples solicitudes simultáneas
            <strong>Entonces</strong> el tiempo de respuesta está dentro del rango promedio
            <strong>Y</strong> no existen errores o caídas del sistema. 
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que el desarrollador realiza las pruebas de carga en el API
            <strong>Cuando</strong> envía múltiples solicitudes simultáneas de distintos dispositivos
            <strong>Entonces</strong> el tiempo de respuesta está dentro del rango promedio
            <strong>Y</strong> no existen errores o caídas del sistema. 
            </td>
            <td>EPIC-003 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-011 </td>
            <td> Autorización y seguridad de acceso al API </td>
           <!-- Descripción -->
            <td> 
            <strong>Como</strong> desarrollador,
            <strong>quiero</strong> poder configurar una autenticación y autorización segura en el API
            <strong>para</strong> garantizar que solos los usuarios admin puedan acceder al sistema.  
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: </h5>
            <strong>Dado</strong> que un usuario con rol admin quiere ingresar al API
            <strong>Cuando</strong> proporciona sus credenciales
            <strong>Y</strong> estas son válidas 
            <strong>Entonces</strong> el sistema le permite ingresar. 
            <h5>Escenario 02: </h5>
            <strong>Dado</strong> que un usuario con rol admin quiere ingresar al API
            <strong>Cuando</strong> proporciona sus credenciales
            <strong>Y</strong> estas no son válidas
            <strong>Entonces</strong> el sistema no le permite ingresar 
            <strong>Y</strong> le notifica que tiene 2 intentos restantes para ingresar al sistema.
            <h5>Escenario 03: </h5>
            <strong>Dado</strong> que un usuario con un rol distinto a admin quiere ingresar al API
            <strong>Cuando</strong> proporciona sus credenciales
            <strong>Y</strong> estas no son válidas
            <strong>Y</strong> superó los intentos restantes
            <strong>Entonces</strong> el sistema no le permite ingresar
            <strong>Y</strong> notifica a los administradores sobre el intento de acceso.  
            </td>
            <td>EPIC-003 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-012 </td>
            <td>Promocionar contenido </td>
            <td> <strong>Como</strong> usuario remodelador, 
              <strong>quiero</strong> poder promocionar el contenido de mi portafolio 
              <strong>para</strong> aumentar mi cantidad de clientes</td>
            <td>
              <h5>Escenario 01: </h5>
              <strong>Dado</strong> que el remodelador se encuentra en su portafolio dentro de su perfil de ReStyle, 
              <strong>Cuando</strong> seleccione el contenido que quiere promocionar 
              <strong>Y</strong> haga Click en el boton de Promocionar, 
              <strong>Entonces</strong> le saldra una pantalla en donde podra seleccionar cuanto tiempo el contenido se mostrara, a cuantas personas y el costo y seleccionar la tarjeta con la que quiere pagar 
              <h5>Escenario 02:</h5>
              <strong>Dado</strong> que el usuario remodelador ha usado su tarjeta de credito o debito en ReStyle antes,
              <strong>Cuando</strong> seleccione su tarjeta en la pantalla de pago para promocioin de contenido 
              <strong>Y</strong> seleccione la promocion por la cual desea pagar 
              <strong>Y</strong> le de click en aceptar, 
              <strong>Entonces</strong> salda un mensaje de pago exitoso 
              <h5>Escenario 03:</h5>
              <strong>Dado</strong> a que el usuario remodelador nunca antes ha usado su tarjeta de credito o debito en ReStyle, 
              <strong>Cuando</strong> este en la pantalla de pago de promocion de contenido, 
              <strong>Entonces</strong> le saldan los campos de su tarjeta que debe llenar para poder realizar el pago 
              <h5>Escenario 04:</h5>
              <strong>Dado</strong> que el usuario remodelador no ha seleccionado el plan de promocion de contenido por el que quiere pagar, 
              <strong>Cuando</strong> le de Click a Aceptar, 
              <strong>Entonces</strong> saldra un mensaje de error. 
              <h5>Escenario 05:</h5>
              <strong>Dado</strong> a que el usuario remodelador nunca antes ha usado su tarjeta de credito o debito en ReStyle 
              <strong>Y</strong> no haya llenado los datos solicitados de tarjeta, 
              <strong>Cuando</strong> le de click en aceptar, 
              <strong>Entonces</strong> saldra un mensaje de error. </td>
            <td> EPIC-007</td>
        </tr>
        <tr style="text-align:center">
            <td> US-013 </td>
            <td>Continuar promocion de contenido </td>
            <td>
              <strong>Como</strong> usuario remodelador, 
              <strong>quiero</strong> extender el plazo de tiempo de la promocion de mi contenido 
              <strong>para</strong> mantener el aumento de alcanze de mi negocio </td>
            <td>
              <h5>Escenario 01: </h5>
              <strong>Dado</strong> que el usuario remodelador ha pagado por promocion de contenido, 
              <strong>Cuando</strong> falte 1 dia para terminar el plazo de promocion, 
              <strong>Entonces</strong> le aparecera una pantalla para continuar la promocion y aprobar el pago. 
              <h5>Escenario 02:</h5>
              <strong>Dado</strong> que el usuario remodelador ha pagado por promocion de contenido, 
              <strong>Cuando</strong> le aparezca la pantalla de Continuar Promocion 
              <strong>Y</strong> le de Click al boton de Continuar 
              <strong>Y</strong> le de click a Aceptar Pago, 
              <strong>Entonces</strong> el pago sera aprovado y se continuara la promocion de contenido. 
              <h5>Escenario 03:</h5>
              <strong>Dado</strong> que el usuario remodelador ha pagado por promocion de contenido, 
              <strong>Cuando</strong> le aparezca la pantalla de Continuar Promocion 
              <strong>Y</strong> le de Click al boton de No Continuar,
              <strong>Entonces</strong> saldra una pantalla confirmando la negacion de promocion y la promocion concluira en un plazo menor a 24 horas. </td>
            <td>EPIC-007</td>
        </tr>
        <tr style="text-align:center">
            <td> US-014 </td>
            <td> Suscripción remodelador</td>
            <td> 
              <strong>Como</strong> usuario remodelador,
              <strong>quiero</strong> poder suscribirme a ReStyle 
              <strong>para</strong> poder acceder al mercado qué provee</td>
            <td>
              <h5>Escenario 01: </h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra la pantalla inicial de ReStyle ,
              <strong>Cuando</strong> le de click al boton de Suscribirse (Para Negocios), 
              <strong>Entonces</strong> le aparecera la pantalla de Creacion de Cuenta Nueva. 
              <h5>Escenario 02:</h5> 
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Creacion de Cuenta nueva, 
              <strong>Cuando</strong> llene los datos solicitados 
              <strong>Y</strong> le de Click al Boton Aceptar 
              <strong>Entonces</strong> le aparecera la pantalla de Planes de Pago. 
              <h5>Escenario 03:</h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Creacion de Cuenta Nueva 
              <strong>Y</strong> no haya llenado los datos solicitados,
              <strong>Cuando</strong> le de click al boton Aceptar, 
              <strong>Entonces</strong> le aparecera un mensaje de error. 
              <h5>Escenario 04:</h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Planes de Pago 
              <strong>Cuando</strong> seleccione el plan al que desea suscribirse 
              <strong>Y</strong> le de click a aceptar, 
              <strong>Entonces</strong> le aparecera la pantalla de Pagos. 
              <h5>Escenario 05: </h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Planes de Pago 
              <strong>Y</strong> no haya seleccionado un plan al que desea suscribirse 
              <strong>Cuando</strong> le de click a aceptar, 
              <strong>Entonces</strong> le aparecera un mensaje de error.
              <h5>Escenario 06: </h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Pagos 
              <strong>Cuando</strong> ingrese los datos de su tarjeta 
              <strong>Y</strong> le de click a aceptar, 
              <strong>Entonces</strong> el pago sera procesado le aparecera un mensaje suscripcion exitosa. 
              <h5>Escenario 07: </h5>
              <strong>Dado</strong> que el usuario remodelador se encuentra en la pantalla de Pagos 
              <strong>Y</strong> no haya ingresado los datos de su tarjeta 
              <strong>Cuando</strong> le de click a aceptar, 
              <strong>Entonces</strong> aparecera un mensaje de error </td>
            <td>EPIC-007 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-015 </td>
            <td> Crear cuenta contratista</td>
            <td> 
              <strong>Como</strong> usuario contratista, 
              <strong>quiero</strong> poder crear una cuenta en ReStyle 
              <strong>para</strong> poder acceder al mercado qué provee</td>
            <td>
              <h5>Escenario 01: </h5> 
              <strong>Dado</strong> que el usuario contratista se encuentra la pantalla inicial de ReStyle , 
              <strong>Cuando</strong> le de click al boton de Crear cuenta, 
              <strong>Entonces</strong> le aparecera la pantalla de Creacion de Cuenta Nueva. 
              <h5>Escenario 02:</h5>
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de Creacion de Cuenta nueva, 
              <strong>Cuando</strong> llene los datos solicitados 
              <strong>Y</strong> le de Click al Boton Aceptar 
              <strong>Entonces</strong> le aparecera la pantalla de Iniciar Sesion. 
              <h5>Escenario 03:</h5> 
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de Creacion de Cuenta Nueva 
              <strong>Y</strong> no haya llenado los datos solicitados, 
              <strong>Cuando</strong> le de click al boton Aceptar, 
              <strong>Entonces</strong> le aparecera un mensaje de error. </td>
            <td> EPIC-002</td>
        </tr>
        <tr style="text-align:center">
            <td> US-016 </td>
            <td> Busqueda remodeladores</td>
            <td> 
              <strong>Como</strong> usuario contratista, 
              <strong>quiero</strong> poder buscar remodeladores 
              <strong>para</strong> facilitar el proceso de contrato</td>
            <td> 
              <h5>Escenario 01: </h5>
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de busqueda, 
              <strong>Cuando</strong> ingrese el nombre de un remodelador en la barra de busqueda, 
              <strong>Entonces</strong> se mostrara el perfil del remodelador cuyo nombre sea igual al ingresado en la busqueda. 
              <h5>Escenario 02:</h5>
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de busqueda, 
              <strong>Cuando</strong> ingrese el nombre de un remodelador en la barra de busqueda 
              <strong>Y</strong> no exista un perfil con un nombre igual al ingresado en la busqueda, 
              <strong>Entonces</strong> se mostraran perfiles con nombres similares a los ingresados en la busqueda</td>
            <td> EPIC-001</td>
        </tr>
        <tr style="text-align:center">
            <td> US-017 </td>
            <td>Busqueda proyectos</td>
            <td> 
              <strong>Como</strong> usuario contratista, 
              <strong>quiero</strong> poder buscar proyectos hechos por remodeladores 
              <strong>para</strong> saber qué el remodelador con el qué trabajo puede hacer el proyecto qué me interesa</td>
            <td> 
              <h5>Escenario 01: </h5>
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de busqueda,
              <strong>Cuando</strong> ingrese el proyecto que le interesa en la barra de busqueda 
              <strong>Entonces</strong> mostrara todos los proyectos con un nombre igual al ingresado. 
              <h5>Escenario 02:</h5>
              <strong>Dado</strong> que el usuario contratista se encuentra en la pantalla de busqueda, 
              <strong>Cuando</strong> ingrese el proyecto que le interesa en la barra de busqueda 
              <strong>Y</strong> no exista un proyecto con un nombre igual 
              <strong>Entonces</strong> se mostraran proyectos con nombres parecidos a los ingresados</td>
            <td>EPIC-001</td>
        </tr>
        <tr style="text-align:center">
            <td>US-018</td>
            <td>Cambiar idioma</td>
            <!-- Descripción -->
            <td>
            <strong>Como</strong> visitante del landing page, 
            <strong>quiero</strong> acceder a una versión en otro idioma, 
            <strong>para</strong> poder entender mejor la información y navegar con mayor facilidad.
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 1: Información desplegada en español</h5>
            <strong>Dado</strong> que el usuario quiere acceder al contenido de la landing page en español
            <strong>Cuando</strong> el usuario presione el botón switch para cambiar idioma.
            <strong>Entonces</strong> La información será traducida 
            <strong>Y</strong> el contenido se presentará en el idioma elegido por el usuario.
            <h5>Escenario 2: Información desplegada en inglés </h5>
            <strong>Dado</strong> que el usuario quiere acceder al contenido de la landing page en inglés
            <strong>Cuando</strong> el usuario presione el botón switch para cambiar idioma.
            <strong>Entonces</strong> La información será traducida 
            <strong>Y</strong> el contenido se presentará en el idioma elegido por el usuario.
            </td>
            <td> EPIC-004</td>
        </tr>
        <tr style="text-align:center">
            <td> US-019 </td>
            <td>Programar Consulta con un Remodelador</td>
            <td>
            <strong>Como</strong> propietario de vivienda interesado en remodelar, quiero poder programar uan consulta con un remodelador a través de la plataforma <strong>para</strong> discutir mis necesidades y obtener recomendaciones.
            </td>
            <td>
            <h5>Esceneario 1:</h5>
            <strong>Dado</strong> que soy un propietario de vivienda registrado en la plataforma, <strong>Cuando</strong> accedo al perfil de un remodelador. <strong>Entonces</strong> tengo la opción de programar una consulta con ese remodelador, seleccionando una fecha y hora conveniente.
            <h5>Escenario 2:</h5>
            <strong>Dado</strong> que he programado una consulta con un remodelador, <strong>Cuando</strong> se confirma la cita. <strong>Entonces</strong> recibo una notificación por correo electrónico y/o mensaje en la plataforma confirmando la fecha, hora y detalles adicionales sobre la consulta.
            <h5>Escenario 3:</h5>
            <strong>Dado</strong> que he programado una consulta con un remodelador, <strong>Cuando</strong> se acerca la fecha y hora de la cita. <strong>Entonces</strong> recibo un recordatorio automático por correo electrónico y/o mensaje en la plataforma para asegurarme de no perder la cita.
            </td>
            <td>EPIC-002 </td>
        </tr>
        <tr style="text-align:center"> 
            <td> US-020 </td>
            <td>Solicitar Presupuesto de Remodelación</td>
            <td>
            <strong>Como</strong> propietario de vivienda interesado en remodelar, quiero poder solicitar presupuestos a múltiples remodeladores a través de la plataforma <strong>para</strong> comparar opciones y tomar decisiones informadas.
            </td>
            <td>              
            <h5>Escenario 1: </h5>
            <strong>Dado</strong> que soy un propietario de vivienda registrado en la plataforma, <strong>Cuando</strong> accedo a la sección de solicitudes de presupuesto. <strong>Entonces</strong> puedo completar un formulario con detalles sobre mi proyecto de remodelación y enviar la solicitud a los remodeladores disponibles.
            <h5>Escenario 2:</h5>
            <strong>Dado</strong> que he enviado una solicitud de presupuesto, <strong>Cuando</strong> los remodeladores interesados reciben mi solicitud. <strong>Entonces</strong> comienzan a enviar sus ofertas y propuestas a través de la plataforma para que yo las revise.
            <h5>Escenario 3:</h5>
            <strong>Dado</strong> que he recibido múltiples ofertas de remodeladores, <strong>Cuando</strong> reviso las propuestas y comparo los presupuestos. <strong>Entonces</strong> puedo evaluar factores como el costo, el tiempo de ejecución y la calidad del trabajo para tomar una decisión informada.
            </td>
            <td>EPIC-002 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-021 </td>
            <td>Responder Solicitudes de Presupuesto </td>
            <td>
            <strong>Como</strong> profesional de remodelación, quiero poder responder rápidamente a las solicitudes de presupuesto de los propietarios de viviendas <strong>para</strong> demostrar profesionalismo y captar nuevos clientes. </td>
            <td>
            <h5>Escenario 1: </h5>
            <strong>Dado</strong> que soy un remodelador registrado en la plataforma, <strong>Cuando</strong> recibo una nueva solicitud de presupuesto. <strong>Entonces</strong> recibo una notificación por correo electrónico y/o mensaje en la plataforma para informarme sobre la solicitud entrante.
            <h5>Escenario 2: </h5>
            <strong>Dado</strong> que he recibido una solicitud de presupuesto, <strong>Cuando</strong> reviso los detalles del proyecto proporcionados por el propietario de la vivienda. <strong>Entonces</strong> puedo evaluar la viabilidad del proyecto y preparar una oferta personalizada.
            <h5>Escenario 3: </h5>
            <strong>Dado</strong> que he preparado una oferta para un proyecto de remodelación, <strong>Cuando</strong> la envío al propietario de la vivienda a través de la plataforma. <strong>Entonces</strong> proporciono detalles claros sobre el alcance del trabajo, el costo estimado y cualquier término adicional para la consideración del cliente.
            </td>
            <td>EPIC-001 </td>
        </tr>
        <tr style="text-align:center">
            <td> US-022 </td>
            <td> Acceso a Herramientas de Gestión </td>
            <td>
            <strong>Como</strong> profesional de remodelación, quiero poder acceder a herramientas de gestión de proyectos y clientes dentro de la plataforma <strong>para</strong> optimizar la organización y la comunicación en mi negocio.</td>
            <td>
            <h5>Escenario 1:</h5>
            <strong>Dado</strong> que soy un remodelador registrado en la plataforma, <strong>Cuando</strong> accedo a mi panel de control personalizado. <strong>Entonces</strong> puedo ver un resumen de proyectos activos, solicitudes de presupuesto, citas programadas y otras métricas importantes para mi negocio.
            <h5>Escenario 2:</h5>
            <strong>Dado</strong> que necesito comunicarme con un cliente sobre un proyecto en curso, <strong>Cuando</strong> utilizo las funciones de mensajería interna o correo electrónico dentro de la plataforma para enviar actualizaciones, responder preguntas y mantener una comunicación clara y transparente. <strong>Entonces</strong> el cliente recibe mis mensajes y puede responder a ellos directamente desde la plataforma, lo que facilita una comunicación fluida y eficiente entre ambas partes.
            </td>
            <td> EPIC-005</td>
        </tr>
        <tr style="text-align:center">
            <td> US-023 </td>
            <td>Galería de Testimonios </td>
            <td>
            <strong>Como</strong> propietario de vivienda en busca de un remodelador confiable, quiero poder acceder a una galería de testimonios y reseñas de clientes anteriores <strong>para</strong> validar la reputación y la calidad del trabajo de los profesionales en la plataforma. </td>
            <td>
            <h5>Escenario 1:</h5>
            <strong>Dado</strong> que soy un propietario de vivienda registrado en la plataforma, <strong>Cuando</strong> accedo a la sección de testimonios desde el menú principal. <strong>Entonces</strong> puedo explorar una variedad de testimonios y reseñas dejados por clientes anteriores, filtrando por ubicación, tipo de proyecto o calificación.
            <h5>Escenario 2:</h5>
            <strong>Dado</strong> que estoy revisando testimonios de clientes anteriores, <strong>Cuando</strong> leo las experiencias y comentarios compartidos por propietarios de viviendas que han trabajado con un remodelador específico. <strong>Entonces</strong> puedo obtener una idea de la calidad del servicio, la comunicación y la satisfacción general del cliente.
            </td>
            <td> EPIC-001</td>
        </tr>
        <tr style="text-align:center">
            <td> US-024 </td>
            <td> Programación de Citas</td>
            <td>
            <strong>Como</strong> profesional de remodelación, quiero poder programar citas con clientes potenciales a través de la plataforma <strong>para</strong> discutir sus proyectos y evaluar sus necesidades antes de comenzar cualquier trabajo.
            </td>
            <td>
            <h5>Escenario 1:</h5>
            <strong>Dado</strong> que soy un remodelador registrado en la plataforma, <strong>Cuando</strong> accedo a mi calendario de citas desde mi panel de control. <strong>Entonces</strong> puedo ver mi disponibilidad actual y reservar horarios para reuniones con clientes potenciales.
            <h5>Esceneario 2:</h5>
            <strong>Dado</strong> que he programado una cita con un cliente potencial, <strong>Cuando</strong> el cliente recibe una notificación sobre la cita programada y confirma su asistencia. <strong>Entonces</strong> recibo confirmación de la cita y preparo la reunión según lo acordado.
            </td>
            <td>EPIC-002 </td>
        </tr>
         <tr style="text-align:center">
            <td>US-025</td>
            <td>Visualizar testimonios de los usuarios que han utilizado la aplicación </td>
            <!-- Descripción -->
            <td>
            <strong>Como</strong> usuario visitante de la landing page, 
            <strong>quiero</strong> saber la opinión de los usuarios que han utilizado la aplicación
            <strong>para</strong> tener una referencia de la experiencia de estos usuarios con el producto.
            </td>
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 1: Testimonios sobre los contratistas</h5>
            <strong>Dado</strong> que el usuario quiere conocer la opinión de los contratistas sobre la plataforma
            <strong>Cuando</strong> el usuario lea las reseñas de valoración
            <strong>Entonces</strong> podrá evaluar según los comentarios
            <strong>Y</strong> decidirá la posibilidad de uso de la aplicación.
            <h5>Escenario 2: Testimonio sobre los remodeladores </h5>
            <strong>Dado</strong> que el usuario quiere conocer la opinión de los remodeladores sobre la plataforma
            <strong>Cuando</strong> el usuario lea las reseñas de valoración
            <strong>Entonces</strong> podrá evaluar según los comentarios
            <strong>Y</strong> decidirá la posibilidad de uso de la aplicación.
            </td>
            <td> EPIC-004</td>
        </tr>   
        <tr style="text-align:center">
            <td> TS001 </td>
            <td> Get Portfolios </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> obtener la información del portafolio de los remodeladores
            a través de una API <strong> para </strong> permitir al equipo de frontend utilizar
            los datos del portafolio en la interfaz de usuario </td>
            <td> 
            <h5>Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Portfolio,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del portafolio 
            de los usuarios. <strong> Entonces </strong>  recibo la información de los portafolios en un response 
            de formato JSON. 
            <h5>Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Portfolios,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del portafolio de los usuarios
            <strong> Y </strong> el parámetro es erróneo o no exista <strong> Entonces </strong> 
            recibo una mensaje de error en la solicitud </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS002 </td>
            <td> Get Portfolio by User </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> obtener la información del portafolio  por usuario remodelador a través de una API 
            <strong> para </strong> permitir al equipo de frontend utilizar
            los datos del portafolio en la interfaz de usuario </td>
            <td> 
            <h5> Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Portfolio by user,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del portafolio de un usuario por id
            <strong> Entonces </strong>  recibo la información del portafolio en un response de formato JSON. 
            <h5> Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Portfolio by user,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del portafolio del usuario
            <strong> Y </strong> el parámetro de ID es erróneo o no exista <strong> Entonces </strong> 
            recibo una mensaje de error en la solicitud </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS003 </td>
            <td> Get Project by User </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> obtener los datos del proyecto actual de un remodelador a través de una API 
            <strong> para </strong> permitir al equipo de frontend utilizar
            los datos del proyecto y mostrarlo a los contratistas  </td>
            <td> 
            <h5> Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Project by user,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del proyecto de un usuario por id
            <strong> Entonces </strong>  recibo la información del portafolio en un response de formato JSON. 
            <h5> Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Project by user,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos del proyecto del usuario
            <strong> Y </strong> el parámetro de ID es erróneo o no exista <strong> Entonces </strong> 
            recibo una mensaje de error en la solicitud </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS004 </td>
            <td> Post Publications </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> permitir a los contratistas puedan crear publicaciones de oportunidad laboral 
            <strong> para </strong>  registrarlas en la base de datos 
            </td>
            <td> 
            <h5>Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Publications,
            <strong> Cuando </strong> envío una solicitud envío una solicitud con datos validados para el
            registro de una nueva publicación. <strong> Entonces </strong> la información de la publicación se
            almacenará con éxito en la base de datos de la aplicación.
            <h5>Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Publications,
            <strong> Cuando </strong> envío una solicitud envío una solicitud sin datos validados 
            <strong> Entonces </strong> recibo una mensaje de error en la solicitud y esta es rechazada.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS005 </td>
            <td> Post Reviews </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> permitir a los contratistas crear reseñas sobre los remodeladores a través de una API 
            <strong> para </strong> permitir a los contratistas compartir su opinión del trabajador contratado 
            </td>
            <td> 
            <h5>Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Post Reviews,
            <strong> Cuando </strong> envío una solicitud envío una solicitud con datos validados para el
            registro de una nueva reseña. <strong> Entonces </strong> la información de la reseña se
            almacenará con éxito en la base de datos de la aplicación.
            <h5>Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Post Reviews,
            <strong> Cuando </strong> envío una solicitud envío una solicitud sin datos validados 
            <strong> Entonces </strong> recibo una mensaje de error en la solicitud y esta es rechazada.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS006 </td>
            <td> Get Reviews </td>
            <td> 
            <strong> Como </strong> desarrollador backend en reStyle,
            <strong> quiero </strong> obtener la información del portafolio de las reseñas creadas por los contratistas
            a través de una API <strong> para </strong> permitir al equipo de frontend utilizar
            los datos de la reseña. </td>
            <td> 
            <h5>Escenario 01: </h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Reviews,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos de las reseñas  
            de los usuarios. <strong> Entonces </strong>  recibo la información de las reseñas en un response 
            de formato JSON. 
            <h5>Escenario 02: </h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Reviews,
            <strong> Cuando </strong> envío una solicitud para la obtención de datos de las reseñas de los usuarios
            <strong> Y </strong> el parámetro es erróneo o no exista <strong> Entonces </strong> 
            recibo una mensaje de error en la solicitud </td>
            <td> </td>
        </tr>
    </body>
</table>

## 3.3. Impact Mapping.

Contenido

## 3.4. Product Backlog.

Utilizamos la escala de Fibonacci para la estimación de los Story Points.

<table>
        <thead>
            <tr>
                <th>Orden</th>
                <th>User Story Id</th>
                <th>Título</th>
                <th>Descripción</th>
                <th>Story Points (1/2/3/5/8)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>US-001</td>
                <td>Hipervínculos en el encabezado</td>
                <td>Como visitante de la landing page, quiero que las opciones del encabezado me dirijan a las 
                diferentes secciones de la Landing Page para, poder navegar de forma rapida y fluida.</td>
                <td>1</td>
            </tr>
            <tr>
                <td>2</td>
                <td>US-005</td>
                <td>Información sobre el producto</td>
                <td> Como usuario que visita la landing page, quiero entender claramente qué ofrece el producto
                para poder tomar una decisión informada sobre si adquirirlo o no.</td>
                <td>2</td>
            </tr>
            <tr>
                <td>3</td>
                <td>US-002</td>
                <td>Información sobre beneficios de la aplicación</td>
                <td>Como usuario, quiero saber más sobre los beneficios de la aplicación web para considerar 
                ser miembro de la aplicacion.</td>
                <td>1</td>
            </tr>
            <tr>
                <td>4</td>
                <td>US-003</td>
                <td>Mostrar los planes disponibles</td>
                <td>Como visitante del landing page, quiero saber sobre los planes que tiene, para poder analizar 
                si el plan que me ofrecen se adecua a las necesidades de mi negocio.</td>
                <td>1</td>
            </tr>
            <tr>
                <td>5</td>
                <td>US-004</td>
                <td>Información útil en el footer</td>
                <td>Como usuario que visita la landing page, quiero encontrar información útil en el footer para
                poder contactarme con la empresa, conocer más sobre ella, leer sus políticas y seguirla en redes sociales.</td>
                <td>1</td>
            </tr>
        </tbody>
</table>