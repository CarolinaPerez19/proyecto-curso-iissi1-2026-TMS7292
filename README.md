# CATERING EATSII

## Miembros del grupo L4-FJO-6

1. Gavira Baeza, Carmen
1. Pérez Soria, Carolina
1. Cook González, Elena Joanna
1. Toajas Samanego, Marco

## 1. Introducción al problema

<dd>&emsp;&emsp;El catering Eatsii desarrolla su actividad en la provincia de Sevilla y tiene su sede en la calle Carmona, 6. Se trata de una empresa de tamaño mediano que, además de ofrecer una amplia propuesta gastronómica especializada en celebraciones privadas y eventos corporativos, dispone de diferentes espacios habilitados para la celebración de eventos. Asimismo, ofrece la posibilidad de desplazarse a otras localizaciones propuestas por los clientes, siempre que las condiciones del lugar y la organización del evento lo permitan.
  
<dd>&emsp;&emsp;Solicita el desarrollo de una aplicación cuya función principal sea conectar a los clientes con los servicios que puede proporcionar su empresa, se amoldarán a las necesidades de cada usuario. Dichos servicios se basarán en los tipos de eventos, presupuestos y alérgenos que cada consumidor precise.


<img width="1024" height="559" alt="d5435e34-a33c-4898-b274-daa7d004905c" src="https://github.com/user-attachments/assets/cb153172-313f-4cf0-83fa-75fb4ba987d4" />


## 2. Glosario de términos

- **Administrador:** Usuario miembro de la empresa que revisa y confirma las solicitudes hechas por los clientes.
- **Alérgenos:** Sustancias presentes en los alimentos que pueden provocar reacciones alérgicas.
- **Capacidad / Aforo:** Número máximo de personas que pueden asistir a un evento.
- **Cliente:** Son los usuarios que solicitan los servicios de catering.
- **Contaminación cruzada:** Transferencia accidental de alérgenos o contaminantes entre alimentos, utensilios o superficies.
- **Duración:** Tiempo estimado de prestación del servicio de catering durante un evento.
- **Instalaciones:** Espacios y equipamientos disponibles para la preparación y prestación del servicio.
- **Menús:** Conjunto de platos y bebidas ofrecidos para un evento.
- **Platos:** Elaboraciones culinarias individuales que forman parte de un menú.
- **Presupuesto:** Estimación del coste total del servicio de catering solicitado.
- **Reservas:** Contratacion confirmada despues de aceptar la solicitud y comprobar la disponibilidad.
- **Servicios:** Prestaciones de catering que la empresa ofrece a sus clientes.
- **Solicitud:** Petición realizada por un cliente para contratar un servicio de catering.
- **Usuarios:** Personas que acceden a la aplicación para consultar, solicitar o gestionar servicios de catering.

## 3. Visión general del sistema

### 3.1. Requisitos generales

- **R.G.01. Gestión de usuarios y acceso al sistema:** La aplicación permitirá el acceso a los usuarios según su perfil, diferenciando entre clientes y administradores de la empresa.

- **R.G.02. Gestión de la oferta de servicios:** La aplicación permitirá gestionar y consultar la información relativa a los servicios de catering, las propuestas gastronómicas y los espacios ofrecidos por Eatsii.

- **R.G.03. Gestión de eventos y solicitudes:** La aplicación permitirá a los cliente elegir el tipo de evento acorde a  sus necesidades y gestionar las solicitudes de contratación de los servicios de la empresa.


### 3.2. Usuarios del sistema
En la aplicación se pueden identificar principalmente dos tipos de usuarios:

**1. Clientes**
Son las personas que utilizan la aplicación para consultar y solicitar los servicios ofrecidos por Eatsii. Podrán registrarse en la plataforma, consultar las opciones disponibles que mejor se adapten a sus necesidades y especificar posibles alergias o intolerancias

**2. Administradores de Eatsii**
Serán los responsables de gestionar la información de la empresa dentro de la aplicación. Podrán administrar los servicios y espacios disponibles, actualizar precios y características, consultar las solicitudes realizadas por los clientes y gestionar la información relacionada con los eventos. También podrán valorar la viabilidad de desplazarse a las localizaciones propuestas por los clientes.


## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Registro e inicio de sesión

**Como** cliente / administrador

**quiero** registrarme e iniciar sesión en la plataforma

**para** acceder de forma personalizada a las funcionalidades según mi rol.


**Prueba de aceptación**

- Verificar que el usuario pueda registrarse proporcionando datos válidos.

- Comprobar que el usuario no pueda iniciar sesión si las credenciales son erróneas.

- Comprobar que tras el inicio de sesión se redirija al panel correspondiente (Cliente o Administrador).


#### R.F.02. Filtrado y búsqueda de servicios tipo de evento

**Como** cliente

**quiero** filtrar los servicios por tipo de evento (particular, corporativo)

**para** visualizar únicamente las propuestas gastronómicas y espacios disponibles.


**Prueba de aceptación**
- Verificar que al seleccionar un tipo de evento solo se muestran las especificaciones de este.


#### R.F.03.  Gestión e indicación de alérgeno

**Como** cliente

**quiero** seleccionar alergias y/o intolerancias de los asistentes

**para** asegurar que los menús propuestos sean seguros y adaptados.


**Prueba de aceptación** 
- Verificar que el usuario pueda marcar uno o varios alérgenos del catálogo en su reserva.

- Comprobar que las propuestas gastronómicas muestren advertencias explícitas o alternativas para los alérgenos marcados.


#### R.F.04. Solicitud de eventos en localizaciones de Eatsii

**Como** cliente

**quiero** seleccionar una localización de los ofrecidos por Eatsii

**para** solicitar el servicio de catering en el lugar de mi elección. 


**Prueba de aceptación**
- Verificar que el cliente pueda elegir uno de los espacios ofrecidos por Eatsii.
- Comprobar que se consulte la disponibilidad del espacio para la fecha y el horario seleccionados.
- Comprobar que la reserva quede registrada y que el espacio solo se reserve cuando se cumplan las condiciones de confirmación.


#### R.F.05. Solicitud de eventos en localizaciones externas

**Como** cliente

**quiero** proponer una localización externa fuera de las instalaciones de Eatsii

**para** solicitar el servicio de catering en el lugar de mi elección.


**Prueba de aceptación**
- Verificar que el cliente pueda introducir la dirección y detalles técnicos del lugar propuesto.
- Comprobar que la reserva quede en estado "Pendiente".


#### R.F.06.  Evaluación de viabilidad de localizaciones externas

**Como** administrador de Eatsii

**quiero** revisar y evaluar las localizaciones externas propuestas por los clientes

**para** determinar si el evento es viable para la empresa.


**Prueba de aceptación**
- Verificar que el administrador pueda ver el listado de solicitudes externas pendientes.
- Comprobar que el administrador pueda cambiar el estado a "Pendiente", "En revision", "Aceptada" o "Rechazada", añadiendo comentarios explicativos para el cliente.

#### R.F.07.   Gestión del catálogo de servicios, espacios y alérgenos

**Como** administrador de Eatsii

**quiero** dar de alta, modificar y desactivar servicios, espacios, tipos de eventos y alérgenos

**para** mantener actualizada la oferta gastronómica y la disponibilidad de las instalaciones.


**Prueba de aceptación**
- Verificar que el administrador pueda crear, editar y modificar la disponibilidad de los servicios y espacios de Eatsii.
- Comprobar que se puedan asociar y actualizar los alérgenos presentes en cada servicio gastronómico.
- Comprobar que el sistema impida registrar dos tipos de eventos con el mismo nombre.
- Verificar que el número máximo de aforo indicado para un espacio sea un valor mayor que cero.

#### R.F.08.   Consulta del historial y estado de solicitudes

**Como** cliente

**quiero** acceder al listado de mis solicitudes enviadas

**para** conocer el estado actual de la tramitación de mi evento.


**Prueba de aceptación**
- Verificar que el cliente solo pueda acceder y consultar las solicitudes de las cuales sea titular.
- Comprobar que se muestre el estado de la solicitud (pendiente, en revisión, aceptada o rechazada).
- Verificar que el cliente pueda consultar los detalles completos de la solicitud (fecha, hora, número de asistentes, localización y alérgenos indicados).

#### R.F.09.   Generación y consulta de presupuestos

**Como** cliente/administrador

**quiero** visualizar el presupuesto desglosado asociado a una solicitud

**para** conocer el importe total.


**Prueba de aceptación**
- Comprobar que el sistema/administrador genere un presupuesto vinculado a una solicitud existente
- Comprobar que el cliente pueda consultar el presupuesto detallado correspondiente a su solicitud.


### 4.1.1. Requisitos de información

#### R.I.01. Información de los usuarios

**Como** administrador

**quiero** disponer de la información identificativa de los usuarios

**para** gestionar sus cuentas y controlar el acceso a la aplicación.

**Prueba de aceptación**
- Cada usuario tendrá un identificador único.
- Se registrarán el nombre, los apellidos, el correo electrónico y la contraseña del usuario.
- Cada cuenta tendrá asignado un rol, que podrá ser cliente o administrador.
- Las contraseñas se almacenarán de forma segura y deberán cumplir unos criterios.
- La contraseña debera tener más de ocho caracteres.


#### R.I.02. Información de los servicios

**Como** administrador

**quiero** almacenar la información de los servicios ofrecidos por Eatsii

**para** mantener actualizado el catálogo de la empresa.

**Prueba de aceptación**
- Cada servicio tendrá un identificador único, un nombre y una descripción.
- Se registrará el precio orientativo de cada servicio.
- Cada evento tendrá asociado un tipo de servicio.
- Se podrá indicar si un servicio está disponible o no.
- Se podrá consultar la información gastronómica y las características.


#### R.I.03. Información de los espacios 

**Como** administrador 

**quiero** almacenar los datos de los espacios de Eatsii 

**para** conocer sus características y gestionar su utilización.

**Prueba de aceptación**
- Cada espacio tendrá un identificador único, un nombre y una descripción.
- Se registrará la ubicación de cada espacio.
- Cada espacio tendrá una capacidad máxima mayor que cero.
- Se registrará el precio orientativo del espacio.
- Se podrá consultar si el espacio está fuera de servicio.


#### R.I.04. Información de los tipos de evento

**Como** administrador

**quiero** almacenar los tipos de evento admitidos por la empresa

**para** clasificar las solicitudes de los clientes.

**Prueba de aceptación**
- Cada tipo de evento tendrá un identificador único.
- Cada tipo de evento tendrá un nombre y una descripción.
- No se permitirá registrar dos tipos de evento con el mismo nombre.
- Los tipos de evento podrán consultarse al crear una solicitud.


#### R.I.05. Información de las reserva 

**Como** cliente 

**quiero** que se almacenen los datos de mi reserva 

**para** poder consultar su estado y conocer las condiciones de mi evento.

**Prueba de aceptación**
- Cada reserva tendrá un identificador único.
- Cada reserva estará asociada al cliente que la haya realizado.
- Se registrarán el tipo de evento, la fecha y el número de asistentes.
- Se registrará el tipo, indicando si se realizará en un espacio de Eatsii o en una ubicación externa.
- Cada reserva tendrá una fecha de creación y un estado.
- No se permitirá registrar reserva sin los datos obligatorios.


#### R.I.06. Información de alergias e intolerancias 

**Como** cliente

**quiero** que se almacenen las alergias e intolerancias relevantes 

**para** mi evento para que Eatsii pueda tenerlas en cuenta.

**Prueba de aceptación**
- Cada alergia o intolerancia tendrá un identificador único.
- Se registrará el nombre y la descripción de cada alergia o intolerancia.
- Una solicitud podrá tener asociadas varias alergias o intolerancias.
- Una misma alergia o intolerancia podrá estar asociada a distintas solicitudes.
- Se podrá consultar qué alergias e intolerancias se han indicado para cada solicitud.


#### R.I.07. Información de presupuestos 

**Como** cliente

**quiero** consultar el presupuesto asociado a mi solicitud 

**para** conocer el coste del evento.

**Prueba de aceptación**
- Cada presupuesto estará asociado a una solicitud.
- Se registrarán el importe total, la fecha de elaboración y el estado de la propuesta.
- Se podrán consultar los servicios incluidos y sus importes correspondientes.
- El importe total coincidirá con la suma de los conceptos y ajustes aplicables.


#### R.I.08. Información de reservas y disponibilidad 

**Como** administrador

**quiero** almacenar las reservas confirmadas

**para** controlar la ocupación de los espacios y evitar incompatibilidades de fechas y horarios (inicial y final). Las reservas solo podrán encontrarse en uno de los siguientes estados: pendiente, en revisión, aceptada o  rechazada.

**Prueba de aceptación**
- Cada reserva tendrá un identificador único.
- Cada reserva estará vinculada a una solicitud válida.
- Se registrarán la fecha, el horario y el estado de la reserva.
- Si la reserva corresponde a un espacio de Eatsii, se identificará dicho espacio.
- No se permitirá confirmar dos reservas del mismo espacio cuyos horarios se solapen.
- Se podrá consultar la disponibilidad de los espacios para una fecha y un horario determinados.


#### R.I.09. Información de los alérgenos presentes en los servicios 

**Como** administrador 

**quiero** registrar los alérgenos asociados a cada servicio gastronómico

**para** proporcionar información alimentaria a los clientes.

**Prueba de aceptación**
- Cada alérgeno tendrá un identificador único y un nombre.
- Se podrá registrar una descripción del alérgeno.
- Un servicio podrá tener asociados varios alérgenos.
- Un mismo alérgeno podrá estar presente en varios servicios.
- Se podrá consultar qué alérgenos están asociados a cada servicio.


#### R.I.10.  Información de las ubicaciones externas 

**Como** administrador 

**quiero** disponer de los datos de las ubicaciones externas propuestas por los clientes 

**para** evaluar si es viable prestar el servicio fuera de las instalaciones de Eatsii.

**Prueba de aceptación**
- Se registrará la dirección o localización propuesta por el cliente.
- La ubicación externa estará asociada a la solicitud correspondiente.
- Se podrán registrar observaciones sobre las condiciones del lugar.
- Se registrará el resultado de la evaluación de viabilidad.
- No se confirmará una solicitud en una ubicación externa sin una evaluación favorable de su viabilidad.



### 4.1.2. Reglas de negocio

#### R.N.01. Validación de capacidad de espacio al confirmar reserva 

Antes de confirmar una nueva reserva  vinculada a un espacio de Eatsii, el sistema deberá comprobar que el número de asistentes indicado en la solicitud asociada no supere el aforo registrado en dicho espacio. Si lo supera, se cancelará la operación. 

**Prueba de aceptación**
- Verificar que se confirma la reserva cuando el número de comensales es inferior o igual al aforo del espacio de Eatsii.

#### R.N.02. Control de alergias e intolerancias

Las propuestas gastronómicas deberán tener en cuenta las alergias e intolerancias indicadas por el cliente. Los servicios identificados como incompatibles deberán excluirse de las propuestas automáticas. La falta de información sobre un alérgeno no podrá interpretarse como garantía de que el servicio sea seguro.

**Prueba de aceptación**
- Verificar que, al marcar un alérgeno en la solicitud, los servicios que lo contienen no aparecen en las propuestas automáticas.
- Comprobar que, al marcar varios alérgenos, se excluyen los servicios que contengan cualquiera de ellos.

#### R.N.03. Viabilidad de las ubicaciones externas

Los servicios solicitados en ubicaciones externas solo podrán confirmarse cuando un administrador haya evaluado y aprobado la viabilidad del desplazamiento y de la prestación del servicio.

**Prueba de aceptación**
- Comprobar que una solicitud en ubicación externa con viabilidad “Rechazado” no puede confirmarse.
- Verificar que solo el usuario con rol administrador puede registrar la evaluación de viabilidad.
- Verificar que esta regla no se aplica a las solicitudes en espacios de Eatsii.

#### R.N.04. Coherencia de los presupuestos

El importe total de un presupuesto deberá coincidir con la suma del importe de la localidad y la cuantía resultante de la multiplicación del precio del menú por la cantidad de comensales.

**Prueba de aceptación**
- Verificar que, si cambia el número de comensales, el presupuesto se recalcula y sigue siendo coherente.
- Verificar que, si cambia el precio del espacio o del menú, el presupuesto se recalcula o se identifica como desactualizado.

#### R.N.05. Número de asistentes

Toda solicitud deberá indicar un número de asistentes entero y mayor que cero.

**Prueba de aceptación**
- Comprobar que se rechaza una solicitud con un número de asistentes negativo.
- Comprobar que se rechaza una solicitud con el campo vacío o con valores no numéricos.

#### R.N.06. Validez de las fechas y horarios

La fecha de un nuevo evento no podrá ser anterior a la fecha actual en el momento de registrar la solicitud. Cuando se indiquen las horas de inicio y finalización, la hora de finalización deberá ser posterior a la de inicio.

**Prueba de aceptación**
- Comprobar que se rechaza una solicitud con fecha anterior a la fecha actual
- Verificar que se acepta una solicitud cuya hora de finalización es posterior a la de inicio.

#### R.N.07. Privacidad de las reservas

Cada cliente solo podrá consultar y gestionar las solicitudes de las que sea titular. Los administradores podrán acceder a la información necesaria para realizar sus funciones.

**Prueba de aceptación**
- Verificar que un cliente solo tiene acceso a las reservas de las que es titular.
- Verificar que un administrador puede consultar las reservas de todos los clientes para realizar sus funciones.



### 4.2. Mapa de historias de usuario

#### RG.01. Gestión de usuarios y acceso al sistema

Registro e inicio de sesión
- Como usuario, quiero registrarme en la aplicación para acceder a sus funcionalidades.
-  Como usuario registrado, quiero iniciar sesión para acceder a las funcionalidades correspondientes a mi rol.
Acceso según el rol
- Como cliente, quiero acceder a las funcionalidades destinadas a los clientes.
- Como administrador, quiero acceder a las funcionalidades de administración de la empresa.

#### RG.02. Gestión de la oferta de servicios

Consulta de servicios
- Como cliente, quiero consultar los servicios de catering ofrecidos por Eatsii para conocer las opciones disponibles.
- Como cliente, quiero filtrar los servicios por tipo de evento para consultar las propuestas que se ajusten a mis necesidades.
- Como cliente, quiero consultar las características y condiciones de cada servicio para valorar las opciones disponibles.
Consulta de espacios
- Como cliente, quiero consultar los espacios ofrecidos por Eatsii para conocer sus características y condiciones.
Gestión del catálogo
- Como administrador, quiero gestionar los servicios y espacios para mantener actualizada la oferta de la empresa.
- Como administrador, quiero actualizar los precios y las características de los servicios y espacios para mantener su información al día.

#### RG.03. Gestión de eventos y solicitudes

Definición de las necesidades del evento
- Como cliente, quiero seleccionar el tipo de evento para solicitar una propuesta adecuada.
- Como cliente, quiero indicar el número de asistentes y la fecha del evento para definir las características de mi solicitud.
- Como cliente, quiero indicar las alergias e intolerancias alimentarias relevantes para que se tengan en cuenta al proponer los servicios gastronómicos.
Creación y seguimiento de solicitudes
- Como cliente, quiero enviar una solicitud de servicio para comunicar a Eatsii las características de mi evento.
- Como cliente, quiero consultar el estado de mis solicitudes para conocer su evolución.
Revisión de solicitudes
- Como administrador, quiero consultar y revisar las solicitudes recibidas para gestionar su aceptación o rechazo.
- Como administrador, quiero registrar la decisión sobre una solicitud para comunicar el resultado de su revisión.

#### RG.04. Gestión económica de los servicios

Consulta y elaboración de presupuestos
- Como cliente, quiero indicar el presupuesto disponible para que se tengan en cuenta mis posibilidades económicas.
- Como cliente, quiero consultar el presupuesto asociado a mi solicitud para conocer el coste del evento.
- Como administrador, quiero elaborar presupuestos asociados a las solicitudes para detallar el coste de los servicios incluidos.
- Como cliente, quiero consultar los servicios incluidos y sus importes para conocer el desglose del presupuesto.
  
#### RG.05. Gestión de la prestación de servicios

Disponibilidad y reservas
- Como cliente, quiero consultar la disponibilidad de los espacios para la fecha y el horario de mi evento.
- Como cliente, quiero solicitar la celebración de un evento en un espacio de Eatsii para elegir dónde realizarlo.
- Como administrador, quiero gestionar las reservas confirmadas para controlar la ocupación de los espacios.
Ubicaciones externas
- Como cliente, quiero proponer una ubicación externa para solicitar el servicio fuera de las instalaciones de Eatsii.
- Como administrador, quiero evaluar la viabilidad de las ubicaciones externas propuestas para determinar si se puede prestar el servicio.
- Como administrador, quiero registrar el resultado de la evaluación para aprobar o rechazar la ubicación propuesta.
- Como cliente, quiero conocer el resultado de la evaluación de la ubicación externa para saber si puede realizarse el evento.

#### RG.06. Gestión y control de la información

Gestión de la información de la empresa
- Como administrador, quiero mantener actualizados los datos de los servicios y espacios para gestionar la oferta de Eatsii.
- Como administrador, quiero consultar la información de las solicitudes para realizar su seguimiento.
Consulta y protección de la información
- Como cliente, quiero consultar las solicitudes asociadas a mi cuenta para realizar su seguimiento.
- Como usuario, quiero que el acceso a mis datos esté restringido según los permisos establecidos para proteger mi información.
- Como usuario, quiero recibir notificaciones relacionadas con mis solicitudes para conocer los cambios relevantes.



### 4.3. Requisitos no funcionales

#### R.N.F.01. Seguridad y control de acceso
**Como** usuario de la aplicación

**quiero** que mis datos y mi cuenta estén protegidos mediante mecanismos de seguridad y control de acceso

**para** garantizar la privacidad de mi información y evitar accesos no autorizados.

**Pruebas de aceptación**

- Verificar que las contraseñas se almacenen de forma segura.
- Comprobar que cada usuario solo pueda acceder a las funcionalidades correspondientes a su rol.
- Verificar que los clientes no puedan consultar ni modificar las solicitudes de otros clientes.

#### R.N.F.02. Usabilidad de la aplicación
**Como** cliente

**quiero** disponer de una interfaz sencilla e intuitiva

**para** consultar los servicios de catering y solicitar la organización de un evento fácilmente.

**Pruebas de aceptación**

- Comprobar que las opciones principales estén claramente identificadas.
- Verificar que los formularios indiquen los campos obligatorios y los posibles errores.
- Comprobar que el proceso de solicitud de un evento pueda realizarse sin instrucciones externas.


#### R.N.F.03. Rendimiento del sistema
**Como** usuario de la aplicación

**quiero** que las páginas y consultas respondan en un tiempo adecuado

**para** consultar los servicios, los espacios y la disponibilidad sin esperas excesivas.

**Pruebas de aceptación**

- Verificar que las operaciones habituales respondan rápidamente en condiciones normales de uso.
- Comprobar que las búsquedas y los filtros de servicios funcionen sin bloqueos.
- Verificar que el sistema mantenga un rendimiento adecuado cuando varios usuarios lo utilicen simultáneamente.

#### R.N.F.04. Disponibilidad del sistema

**Como** cliente

**quiero** poder acceder a la aplicación cuando necesite consultar los servicios de Eatsii

**para** planificar y solicitar eventos con antelación.

**Pruebas de aceptación**
- Comprobar que la aplicación esté disponible durante los periodos de funcionamiento establecidos.
- Verificar que los errores o interrupciones se comuniquen al usuario de forma comprensible.
- Comprobar que, tras una interrupción, el sistema pueda recuperar su funcionamiento sin perder los datos confirmados.


#### R.N.F.05. Compatibilidad y diseño adaptable

**Como** cliente

**quiero** utilizar la aplicación desde diferentes dispositivos y navegadores

**para** consultar los servicios y gestionar mis solicitudes desde el dispositivo que prefiera.

**Pruebas de aceptación**
- Verificar que la aplicación funcione correctamente en los principales navegadores actuales.
- Comprobar que la interfaz se adapte a ordenadores, tabletas y teléfonos móviles.
- Verificar que los formularios y las opciones principales puedan utilizarse en diferentes tamaños de pantalla.


#### R.N.F.06. Integridad y consistencia de los datos
**Como** administrador de Eatsii

**quiero** que la información almacenada se mantenga íntegra y coherente

**para** evitar errores en las solicitudes, los presupuestos, las reservas y la disponibilidad de los espacios.

**Pruebas de aceptación**

- Comprobar que los datos obligatorios se validen antes de almacenarse.
- Verificar que los importes de los presupuestos coincidan con la suma de sus conceptos y ajustes.
- Comprobar que no se confirmen reservas incompatibles para un mismo espacio y horario.


#### R.N.F.07. Mantenibilidad del sistema

**Como** administrador de Eatsii

**quiero** que la aplicación esté organizada y documentada de forma clara

**para** facilitar futuras modificaciones, correcciones y ampliaciones del sistema.

**Pruebas de aceptación**
- Comprobar que las funcionalidades principales dispongan de documentación suficiente.
- Verificar que se puedan realizar modificaciones sin afectar innecesariamente al resto de funcionalidades.



#### R.N.F.08. Protección de la información personal

**Como** cliente

**quiero** que mis datos personales y la información de mis solicitudes se traten de forma confidencial

**para** evitar que mi información sea utilizada o consultada por personas no autorizadas.

**Pruebas de aceptación**
- Verificar que solo se recopilen los datos necesarios para prestar el servicio.
- Comprobar que el acceso a la información personal esté restringido según los permisos establecidos.
- Verificar que los datos se transmitan mediante conexiones seguras.


#### R.N.F.09. Fiabilidad de la información sobre alérgenos

**Como** cliente

**quiero** que la información sobre los alérgenos presentes en los servicios gastronómicos sea clara y esté actualizada

**para** poder tener en cuenta mis alergias e intolerancias al seleccionar las opciones de catering.

**Pruebas de aceptación**
- Comprobar que los servicios dispongan de información sobre los alérgenos registrados.
- Verificar que los cambios realizados por los administradores se reflejen en la información consultada.
- Comprobar que a la aplicación no le falte la información sobre un alérgeno como garantía de que un servicio sea seguro.


-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

<img width="1189" height="1310" alt="Modelado_UML_Eatsii drawio (1)-1copia" src="https://github.com/user-attachments/assets/b65459e3-3583-45e2-8035-8f49ecd6d702" />


### 5.2. Escenarios de prueba

#### ESC-01. Reserva válida con aforo completo y presupuesto

**Reglas:** R.N.01, R.N.04, R.N.05, R.N.06

**Como cliente**

**quiero** solicitar una reserva para un evento en una localidad con el aforo completo permitido y consultar su presupuesto

**para** poder organizar un evento asegurándome de que se cumplen las condiciones de capacidad, fecha y presupuesto.

**Estado inicial.** La localidad terrazaTriana tiene un aforo de 80 personas y no tiene ninguna reserva el 12/12/2026. La cliente Carmen ha iniciado sesión.

**Acción.** Carmen solicita un evento corporativo en terrazaTriana para el 12/12/2026 a las 20:00, con el menú menuMed y 80 comensales. Después, la administradora Elena revisa la solicitud y la confirma.

**Resultado esperado.** La solicitud se registra en estado `pendiente`. Cuando Elena la confirma, pasa a `aceptada`, porque el número de comensales (80) es igual al aforo de la localidad y no lo supera. La fecha es futura y los comensales son un entero mayor que cero, así que se cumplen R.N.05 y R.N.06.

El presupuesto de la reserva es 500 + 40 × 80 = **3.700 €**. Si carmen reduce después los comensales a 60, el presupuesto se recalcula a 500 + 40 × 60 = **2.900 €**.

<img width="802" height="294" alt="Diagrama sin título-ESC-01 drawio (1)" src="https://github.com/user-attachments/assets/1eb1ea99-185d-4b8e-8675-aaac1d036ac3" />


#### ESC-02. Aforo superado

**Reglas:** R.N.01

**Como cliente**

**quiero** que el sistema compruebe que el número de comensales no supera el aforo de la localidad seleccionada

**para** evitar realizar reservas que no puedan llevarse a cabo por falta de capacidad.

**Estado inicial.** La localidad salonGiralda tiene un aforo de 50 personas y está libre el 15/01/2027. El cliente marco ha iniciado sesión.

**Acción.** Marco solicita una reserva en salonGiralda para el 15/01/2027 a las 21:00 con 51 comensales. A continuación, Elena intenta confirmarla.

**Resultado esperado.** El sistema no permite la confirmación y muestra un mensaje de error, porque los 51 comensales superan el aforo de 50. La reserva no pasa a `aceptada` y se rechaza, de modo que el salón sigue libre para otras solicitudes. Si marco corrigiera la solicitud a 50 comensales, sí podría confirmarse.

<img width="802" height="432" alt="Diagrama sin título-ESC-02 drawio" src="https://github.com/user-attachments/assets/e821cb86-3588-4ac7-89b6-3beb76ad1f32" />



#### ESC-03. Datos de la solicitud no válidos

**Reglas:** R.N.05, R.N.06

**Como cliente**

**quiero** que el sistema valide el número de comensales y la fecha de la solicitud

**para** evitar registrar reservas con datos incorrectos o que no cumplan las condiciones establecidas.

**Estado inicial.** La fecha actual es el 04/11/2026. marco ha iniciado sesión y dispone de la localidad terrazaTriana para solicitar.

**Acción.** Marco intenta registrar tres solicitudes incorrectas. La primera indica 0 comensales. La segunda indica 10,5 comensales. La tercera tiene como fecha el 01/11/2026, que ya ha pasado.

**Resultado esperado.** Las tres solicitudes se rechazan con un mensaje de error y no se guardan. Las dos primeras incumplen R.N.05, porque el número de comensales debe ser un entero mayor que cero. La tercera incumple R.N.06, porque la fecha es anterior a la actual. En cambio, una solicitud con 1 comensal y fecha del 04/11/2026 sí se registraría, ya que son los valores límite válidos.

<img width="802" height="358" alt="Diagrama sin título-ESC-03 drawio" src="https://github.com/user-attachments/assets/9a2c1cb6-c282-472d-a1a4-60bee47fce41" />



#### ESC-04. Ingredientes prohibidos en la propuesta de menús

**Reglas:** R.N.02

**Como cliente**

**quiero** que el sistema filtre los menús según los ingredientes que he marcado como prohibidos

**para** evitar seleccionar opciones gastronómicas que contengan ingredientes que puedan provocarme alergias o intolerancias.

**Estado inicial.** Existen tres menús: menuMed, cuyo plato ensaladaMixta incluye tomate; menuMarisco, cuyo plato gambasAjillo incluye crustáceos; y menuGourmet, cuyo plato tartaQueso incluye lácteos. carmen está creando una reserva.

**Acción.** Crmen marca *crustáceos* y *lácteos* como ingredientes prohibidos en su reserva y consulta los menús propuestos.

**Resultado esperado.** El sistema solo propone menuMed. Los menús menuMarisco y menuGourmet quedan excluidos de las propuestas automáticas, porque cada uno contiene un plato con alguno de los ingredientes prohibidos. Si carmen marcara solo *crustáceos*, se propondrían menuMed y menuGourmet. Los menús propuestos son únicamente los que tienen sus ingredientes registrados y ninguno de ellos prohibido, ya que la falta de información nunca se considera una garantía de seguridad.

<img width="1082" height="336" alt="Diagrama sin título-ESC-04 drawio" src="https://github.com/user-attachments/assets/7f23b85f-5e4c-40c9-9a20-c5aaf6c61f90" />



#### ESC-05. Ubicaciones externas: viabilidad aprobada y rechazada

**Reglas:** R.N.03

**Como administrador**

**quiero** evaluar la viabilidad de las ubicaciones externas propuestas por los clientes y registrar el resultado de dicha evaluación

**para** garantizar que solo se confirmen reservas en ubicaciones que cumplan las condiciones necesarias para realizar el evento.

**Estado inicial.** Carmen solicita un evento en fincaOlivar para el 20/03/2027 con 60 comensales. marco solicita otro en cortijoVega para el 10/04/2027 con 40 comensales. Ambas localidades son ubicaciones propuestas por los clientes fuera de las instalaciones de Eatsii, y las dos reservas quedan en estado `pendiente`.

**Acción.** Elena revisa las dos solicitudes y las pasa a `en revisión`. Tras evaluar los lugares, rechaza la de cortijoVega con la observación "Sin acceso para vehículos" y acepta la de fincaOlivar con la observación "Acceso y cocina viables". Después se intenta confirmar de nuevo la reserva rechazada. Además, marco intenta cambiar él mismo el estado de su reserva.

**Resultado esperado.** La reserva de fincaOlivar pasa a `aceptada` solo después de la evaluación favorable de elena, y carmen puede consultar la observación. La reserva de cortijoVega queda en `rechazada` y no puede confirmarse, igual que ninguna reserva que siga en `pendiente` o `en revisión`. El intento de marco de cambiar el estado se deniega, porque solo un administrador puede registrar la evaluación de viabilidad.

<img width="862" height="362" alt="Diagrama sin título-ESC-05 drawio" src="https://github.com/user-attachments/assets/c79322a7-3ce4-40b5-9272-ca9819f65c7e" />





## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

| Requisito | Usuario | Administrador | Cliente | Reserva | Localidad | Menú | Plato | Ingredientes | esSolicitadaPor | esRealizadaEn | elige | contiene | incluye | estánProhibidosEn | R1 (Aforo) | R2 (Disponibilidad) | R3 (Unicidad) | R4 (Datos/Precios) | R5 (Viabilidad) |
|-----------|---------|---------------|---------|---------|-----------|------|-------|--------------|-----------------|---------------|-------|----------|---------|-------------------|------------|---------------------|---------------|--------------------|-----------------|
| RI.01     | X       | X             | X       |         |           |      |       |              |                 |               |       |          |         |                   |            |                     |               | X                  |                 |
| RI.02     |         |               |         |         | X         | X    | X     | X            |                 |               | X     |          |         |                   |            |                     | X             |                    |                 |
| RI.03     |         |               |         |         |           | X    |       |              |                 |               |       |          |         | X                 |            |                     | X             |                    |                 |
| RI.04     |         |               |         | X       |           |      |       |              |                 |               |       |          |         |                   |            | X                   |               |                    |                 |
| RI.05     |         |               | X       | X       | X         |      |       |              | X               | X             |       |          |         |                   |            |                     |               | X                  |                 |
| RI.06     |         |               |         | X       |           |      |       | X            |                 |               |       |          |         | X                 |            |                     |               |                    |                 |
| RI.07     |         |               |         | X       |           | X    |       |              |                 |               | X     |          |         |                   |            |                     |               | X                  |                 |
| RI.08     |         |               |         | X       | X         |      |       |              |                 | X             |       |          |         |                   | X          | X                   |               |                    |                 |
| RI.09     |         |               |         | X       |           | X    | X     | X            |                 |               | X     | X        |         |                   |            |                     |               | X                  |                 |
| RI.10     |         | X             |         | X       | X         |      |       |              |                 | X             |       |          |         |                   |            |                     |               |                    | X               |
| RF.01     | X       | X             | X       |         |           |      |       |              |                 |               |       |          |         |                   |            |                     |               | X                  |                 |
| RF.02     |         |               |         | X       | X         | X    |       |              |                 |               |       |          |         |                   |            |                     | X             |                    |                 |
| RF.03     |         |               | X       | X       |           | X    | X     | X            |                 |               |       |          | X       | X                 |            |                     |               | X                  |                 |
| RF.04     |         |               | X       | X       | X         |      |       |              | X               | X             |       |          |         |                   | X          | X                   |               |                    |                 |
| RF.05     |         |               | X       | X       | X         |      |       |              | X               | X             |       |          |         |                   |            |                     |               |                    | X               |
| RF.06     |         | X             |         | X       | X         |      |       |              |                 | X             |       |          |         |                   |            |                     |               |                    | X               |
| RF.07     |         | X             |         |         | X         | X    | X     | X            |                 |               |       | X        | X       |                   | X          |                     | X             | X                  |                 |
| RF.08     |         |               | X       | X       |           |      |       |              | X               |               |       |          |         |                   |            |                     |               |                    |                 |
| RF.09     |         |               | X       | X       |           | X    | X     |              |                 |               | X     |          |         |                   |            |                     |               | X                  |                 |
| RN.01     |         |               |         | X       | X         |      |       |              |                 | X             |       |          |         |                   | X          | X                   |               |                    |                 |
| RN.02     |         |               |         | X       |           |      | X     | X            |                 |               |       |          | X       |                   |            |                     |               |                    |                 |
| RN.03     |         | X             |         | X       | X         |      |       |              |                 | X             |       |          |         |                   |            |                     |               |                    | X               |
| RN.04     |         |               |         | X       | X         | X    |       |              |                 |               | X     |          |         |                   |            |                     |               | X                  |                 |
| RN.05     |         |               |         | X       |           |      |       |              |                 |               |       |          |         |                   |            |                     |               | X                  |                 |
| RN.06     |         |               |         | X       |           |      |       |              |                 |               |       |          |         |                   |            |                     |               | X                  |                 |
| RN.07     |         |               | X       | X       |           |      |       |              | X               |               |       |          |         |                   |            |                     |               | X                  |                 |


## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


