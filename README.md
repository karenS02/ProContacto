# ProContacto
# ProContacto Prácticas

## Ejercicio 1: Instalación del ambiente

**Instalación de Visual Studio Code**
(https://github.com/karenS02/ProContacto/tree/main/img/visuals.jpg?raw=true)
(https://github.com/karenS02/ProContacto/tree/main/img/vscode.jpg?raw=true)

**Instalación de Git y GitBash**
(https://github.com/karenS02/ProContacto/tree/main/img/gitbash.jpg?raw=true)
(https://github.com/karenS02/ProContacto/tree/main/img/git.jpg?raw=true)


## Ejercicio 2: Protocolo HTTP

**¿Qué es un servidor HTTP?**

Un servidor HTTP es una parte de software que comprende URLs para visualizar páginas web en un navegador.

**¿Qué son los verbos HTTP? Mencionar los más conocidos**

Los verbos *HTTP* son un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado. *GET*, se utiliza para recuperar información de un recurso, no se produce ningún efecto secundario cuando un cliente realiza esta llamada. *POST*, se utiliza para crear recursos nuevos, cuando se utiliza en una operación de creación devolverá la *URL* para el recurso creado recientemente. *PUT y PATCH* son muy similares, ambos verbos se utilizan para modificar un recurso existente, la diferencia es que *PUT* indica que se va a sustituir por completo el recurso, mientras que *PATCH* actualiza algunos elementos del recurso sin sustituirlo por completo. Por último, *DELETE*, se utiliza para eliminar registros tanto de un recurso individual como eliminar una colección completa.

**¿Qué es un request y un response en una comunicación HTTP?**

Un request es una petición enviada por un cliente para iniciar una acción en el servidor y una vez que el servidor ha procesado la solicitud del cliente, devuelve un mensaje de respuesta, es decir, un response.

**¿Qué son los headers?**

Las cabeceras o headers HTTP permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta.

**¿Qué es un queryString? (En el contexto de una url).**

Es la parte de la URL que contiene los datos que deben pasar a aplicaciones web.

**¿Qué es el responseCode?**

Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica.

**¿Qué significado tiene los posibles valores devueltos?**

Las respuestas se agrupan en cinco clases:

 - Respuestas informativas (100–199)
 - Respuestas satisfactorias (200–299)
 - Redirecciones (300–399)
 - Errores de los clientes (400–499)
 - Errores de los servidores (500–599).

**¿Cómo se envía la data en un Get y cómo en un POST?**

El método GET envía los datos usando la URL mientras que el método POST los envía de forma que no se pueden ver (en un segundo plano u ocultos al usuario).

**¿Qué verbo http utiliza el navegador cuando accedemos a una página?**

Se utiliza el método GET.

**Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**

JSON es un formato de texto pensado para el intercambio de datos. Su sintaxis está basada originalmente en la sintaxis de JavaScript.

En JSON existen dos tipos de elementos:

 - Las matrices son listas de valores separados por comas. Las matrices se escriben entre corchetes [ ].
     Por ejemplo: [1, "pepe", 3.14, "Pepito Conejo"]
     
 - Objetos (objects). Los objetos son listas de parejas nombre / valor. El nombre y el valor están separados por dos puntos : y las parejas están separadas por comas. Los objetos se escriben entre llaves { } y los nombres de las parejas se escriben siempre entre comillas dobles.

    Por ejemplo: {"nombre": "Pepito Conejo", "edad": 25, "carnet de conducir": true}
    
  XML,  representa información estructurada en la web (todos documentos), de modo que esta información pueda ser almacenada, transmitida, procesada, visualizada e impresa, por muy diversos tipos de aplicaciones y dispositivos.
 Un documento XML está formado por  **datos de caracteres**  y  **marcado**, el marcado lo forman las etiquetas:
 (https://github.com/karenS02/ProContacto/tree/main/img/xml.jpg?raw=true)

**Explicar brevemente el estándar SOAP.**

SOAP es un protocolo estándar que define cómo dos objetos en diferentes procesos pueden comunicarse por medio de intercambio de datos XML. Los mensajes SOAP son las transmisiones de información de remitentes a destinatarios y se pueden combinar para crear patrones de petición/respuesta.

**Explicar brevemente el estándar REST Full**

Es considerado una técnica de arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear una forma de pensar y construir las APIs. Este tipo de arquitectura se define por un conjunto de restricciones entre los elementos, componentes, conectores y datos usados.

**¿Qué son los headers en un request?**

Lo que permite al cliente enviar información adicional junto a una petición.

**¿Para qué se utiliza el key Content-type en un header?**

Para definir el tipo de contenido de un request o response, ya sea json, xml, html, etc.

## Ejercicio 3: Peticiones en Postman

Request GET a la URL: [https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json](https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json)
(https://github.com/karenS02/ProContacto/tree/main/img/RequestGET.jpg?raw=true)

Request POST a la URL anterior, y con body:
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
(https://github.com/karenS02/ProContacto/tree/main/img/RequestPOST.jpg?raw=true)


Request GET a la URL: [https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json](https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json)
(https://github.com/karenS02/ProContacto/blob/main/img/Request%20GET%202.jpg)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
En la primera petición GET aún no eran visibles los datos enviados en la petición POST, si no hasta hacer un GET nuevamente.
## Ejercicio 4: Módulos de Trailhead

Liga de perfil público 
https://trailblazer.me/id/karensoto02

## Ejercicio 5: Objetos de salesforce

 1. **Lead:** es un prospecto o cliente potencial que demuestra interes en un producto o servicio, el cual debe ser evaluado y cualificado para saber si esta listo para entrar a un proceso comercial. El modelo de Salesforce pasa por convertir el lead en cuenta, cliente y oportunidad.
 2. **Account:** en Salesforce, se almacena la informacion de los clientes mediente cuentas y contactos. Las cuentas son organizaciones, empresas o consumidores a los que se les desea realizar un seguimiento (cliente, socio, competidor).
 3. **Contact:** un contacto es una persona asociada a una cuenta.
 4. **Opportunity:** una oportunidad permite gestionar y realizar un seguimiento de las ventas potenciales. Las oportunidades son ventas en proceso que contienen variedad de informacion para ayudar a realizar un seguimiento de las posibles ventas y ventas pendientes.
 5. **Product:** los productos son un catalogo de base de todos los elementos y servicios que se venden y sus precios estandar.
 6. **Pricebook:** las listas de precios permiten crear un conjunto personalizado de productos con precios de lista asociados para usos especificos.
 7. **Quote:** un presupuesto representa una cotizacion, que es un registro que muestra los precios propuestos para productos y servicios.
 8. **Asset:** los activos representan los productos especificos que han comprado los clientes.
 9. **Case:** Un caso es una descripción detallada de los problemas de un cliente.
 10. **Article:**  Los articulos  capturan información sobre los productos y servicios de tu empresa que deseas que estén disponibles en tu base de conocimientos.

(https://github.com/karenS02/ProContacto/blob/main/img/Diagrama%20objetos%20salesforce.drawio.png)


## Ejercicio 6: Trigger



## Ejercicio 7: Salesforce

### Soluciones de Salesforce

**¿Qué es Salesforce?**
Salesforce es una empresa estadounidense de software bajo demanda, más conocida por producir un CRM llamado Sales Cloud.

**¿Qué es Sales Cloud?**
Sales Cloud_ es un software de ventas y CRM que reúne la mayor parte de las funcionalidades encontradas en las demás plataformas.

**¿Qué es Service Cloud?** 
Service Cloud es una solución completa de atención al cliente creado especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

**¿Qué es Health Cloud?**
Health Cloud es una plataforma que permite una conversación personalizada entre el paciente y las entidades sanitarias asociadas. No solo es beneficioso para los equipos de atención médica, sino que también beneficia a los pacientes al establecer comunicaciones digitales con su equipo de atención.

**¿Qué es Marketing Cloud?** 
Marketing Cloud es una plataforma de Salesforce que las pymes y grandes empresas pueden utilizar para invertir en estrategias de email marketing de nivel profesional.

## Funcionalidades de Salesforce

**¿Qué es un RecordType?** 
Un recordType o tipo de registro, determinan los procesos de negocio, los formatos de página y los valores de lista de selección a los que los usuarios tienen acceso.

**¿Qué es un ReportType?** 
Un reportType o tipo de informe actua como una plantilla que define que objetos puede ver el informe, las relaciones de los objetos, los campos incluidos en los resultados, los campos marcados de forma predeterminada y los nombres de campo para mostrar.

**¿Qué es un Page Layout?** 
Un Page Layout controla el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos. También ayuda a determinar qué campos son visibles, de solo lectura y obligatorios. Utilice diseños de página para personalizar el contenido de las páginas de registro para sus usuarios.

**¿Qué es un Compact Layout?** 
Un compact Layout muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

**¿Qué es un Perfil?** 
Los perfiles definen cómo los usuarios acceden a objetos y datos, y los perfiles determinan qué pueden hacer los usuarios dentro de la aplicación. Puede crear o clonar un perfil estándar para trabajar con la aplicación de fidelización.

**¿Qué es un Rol?** 
Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

**¿Qué es un Validation Rule?** 
Las reglas de validación verifican que los datos que un usuario ingresa en un registro cumplen con los estándares que usted especifica antes de que el usuario pueda guardar el registro. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y devuelve un valor de "Verdadero" o "Falso". Las reglas de validación también incluyen un mensaje de error para mostrar al usuario cuando la regla devuelve un valor de "Verdadero" debido a un valor no válido.

**¿Qué diferencia hay entre una relación *Master Detail* y *Lookup*?** 
En la búsqueda, ambos objetos no comparten propiedades entre ellos, lo que significa que están débilmente acoplados. En Master-detail, ambos objetos comparten propiedades entre sí, lo que significa que están estrechamente acoplados.

**¿Qué es un Sandbox?** 
Un Sandbox es una copia de una organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de la organización de producción de Salesforce. Un Sandbox es una copia de la organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación.

**¿Qué es un ChangeSet?** 
Un conjunto de cambios es una manera de enviar información sobre personalizaciones desde una organización a otra.

**¿Para qué sirve el import Wizard de Salesforce?** 
Se utiliza para mapear los campos de datos y ejecutar la importación.

**¿Para qué sirve la funcionalidad Web to Lead?** 
Es el proceso de usar un formulario de sitio web para capturar información del visitante y almacenar esa información como un nuevo cliente potencial en Salesforce.

**¿Para qué sirve la funcionalidad Web to Case? **
Web-to-Case ofrece a los usuarios una forma de recopilar información en un formato más específico. Puede recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa con Salesforce Web-to-Case. Esto puede ayudar a su organización a responder a los clientes más rápido mientras mejora la productividad de su equipo de soporte.

Ofrece la posibilidad de crear una página de envío de casos públicos simple en su propio sitio web con su propia marca y estilo. Funciona generando un fragmento de HTML.

**¿Para qué sirve la funcionalidad Omnichannel?** 
OmniCanal enruta las solicitudes de trabajo a los agentes de soporte más disponibles y calificados en la consola. También puede proporcionar inteligencia operativa en tiempo real para ayudar a los supervisores con Omni Supervisor.

**¿Para qué sirve la funcionalidad Chatter?** 
Chatter es la red social de Salesforce que ayuda a conectarse, colaborar y actuar de manera eficiente en el dia a dia de los clientes de una organizacion.

### Conceptos generales

**¿Qué significa SaaS?**
El software como servicio (SaaS) es un modelo de entrega de software basado en la nube en el que el proveedor de la nube desarrolla y mantiene el software de las aplicaciones en la nube, proporciona actualizaciones automáticas del mismo y lo pone a disposición de sus clientes a través de Internet con un sistema de pago por uso. El proveedor de la nube pública administra todo el hardware y el software tradicional, incluidos middleware, software de aplicaciones y seguridad.

**¿Salesforce es Saas?**
Salesforce es una compañía de PaaS (Plataforma como Servicio), un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio).

**¿Qué significa que una solución sea Cloud?**
Una solución Cloud se refiere a que en lugar de almacenar los datos y software en un ordenador personal o servidor, se almacena en «la nube».

**¿Qué significa que una solución sea On-Premise?**
El término  _on-premise_  o en local se refiere al  **tipo de instalación**  de una solución de  software. Esta instalación se lleva a cabo dentro del  servidor y la infraestructura (TIC) de la empresa. Es el modelo tradicional de aplicaciones empresariales. Con el modelo on-premise, la  empresa es la responsable  de la  seguridad disponibilidad y gestión del software.

**¿Qué es un pipeline de ventas?**
Pipeline de ventas es el mapa de las actividades diarias que componen el proceso de ventas en el trabajo de un representante comercial, mostrando cada una de las etapas de una negociación. 

**¿Qué es un funnel de ventas?**
El embudo de ventas o conversión es una metáfora usada en mercadotecnia o administración de empresas para referirse a las fases de la venta. Es el proceso por el que las oportunidades potenciales de ventas son cualificadas y seleccionadas para convertirlas en oportunidades reales que terminan en transacciones reales.​

**¿Qué significa Customer Experience?**
Customer Experience es un concepto utilizado en los procesos de las organizaciones para representar la experiencia que una empresa le entrega a sus clientes, desde el momento en que conocen a la marca hasta que se conviertan en clientes y comiencen a utilizar efectivamente su producto o servicio.

**¿Qué significa omnicanalidad?**
Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado.

**¿Qué significa que un negocio sea B2B?** 
Significa que entrega servicios a otro negocio o compañía con el objetivo de mejorar las ventas de los productos y bienes que ofrece. Es decir, una transacción comercial entre empresas.

**¿Qué significa que un negocio sea B2C?** 
Significa que el negocio o empresa le vende de forma directa al consumidor final. Este modelo es el de las empresas que ofrecen bienes y servicios de consumo masivo.

**¿Qué es un KPI?** 
Un KPI o indicador clave de gestión es un valor medible de rendimiento. Este demuestra la eficacia con la que una empresa está logrando los objetivos estratégicos clave, una vez puesto el plan de acción en marcha.

**¿Qué es una API y en qué se diferencia de una Rest API?** 
Una API es un conjunto de subrutinas, funciones y procedimientos que ofrece cierta biblioteca para ser utilizada por otro software como una capa de abstracción.​

**¿Qué es un Proceso Batch?** 
Se conoce como sistema por, o modo batch, a la ejecución de un programa sin el control o supervisión directa del usuario que se denomina . Este tipo de programas se caracterizan porque su ejecución no precisa ningún tipo de interacción con el usuario. Generalmente, este tipo de ejecución se utiliza en tareas repetitivas sobre grandes conjuntos de información, ya que sería tedioso y propenso a errores realizarlo manualmente.

**¿Qué es Kanban?** 
Es un sistema de información que controla de modo armónico la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica, como entre distintas empresas.

**¿Qué es un ERP?** 
El término ERP se refiere a Enterprise Resource Planning, que significa “sistema de planificación de recursos empresariales”. Estos programas se hacen cargo de distintas operaciones internas de una empresa, desde producción a distribución o incluso recursos humanos.

**¿Salesforce es un ERP?**
Si bien Salesforce es la plataforma de gestión de relaciones con los clientes (CRM) n.º 1 del mundo, no es un sistema de gestión de recursos empresariales (ERP). Salesforce CRM proporciona muchas funciones críticas para las ventas y el servicio, pero no proporciona la funcionalidad ERP como el inventario, la producción, la cadena de suministro y la gestión financiera.
