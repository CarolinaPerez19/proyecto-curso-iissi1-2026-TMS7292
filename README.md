# CATERING EATSII

## Miembros del grupo L4-FJO-6

1. Gavira Baeza, Carmen
1. Pérez Soria, Carolina
1. Cook González, Elena Joanna
1. Toajas Samanego, Marco

## 1. Introducción al problema

<dd>&emsp;&emsp;El catering Eatsii desarrolla su actividad en la provincia de Sevilla y tiene su sede en la calle Carmona, 6. Se trata de una empresa de tamaño mediano que, además de ofrecer una amplia propuesta gastronómica especializadas en celebraciones privadas y eventos corporativos, dispone de diferentes espacios habilitados para la celebración de eventos. Asimismo, ofrece la posibilidad de desplazarse a otras localizaciones propuestas por los clientes, siempre que las condiciones del lugar y la organización del evento lo permitan.
  
<dd>&emsp;&emsp;Solicita el desarrollo de una aplicación cuya función principal sea conectar a los clientes con los servicios que puede proporcionar su empresa, se amoldarán a las necesidades de cada usuario. Dichos servicios se basarán en los tipos de eventos, presupuestos y alérgenos que cada consumidor precise.


<img width="1024" height="559" alt="d5435e34-a33c-4898-b274-daa7d004905c" src="https://github.com/user-attachments/assets/cb153172-313f-4cf0-83fa-75fb4ba987d4" />


## 2. Glosario de términos

- **Administrador:** Usuario miembro de la empresa que revisa y confirma las solicitudes hechas por los clientes.
- **Alérgenos:** Sustancias presentes en los alimentos que pueden provocar reacciones alérgicas.
- **Camareros:** Personal encargado de servir la comida y atender a los clientes durante el evento.
- **Capacidad / Aforo:** Número máximo de personas que pueden asistir a un evento.
- **Cliente:** Son los usuarios que solicitan los servicios de catering.
- **Cocineros:** Personal responsable de preparar y elaborar los platos del menú.
- **Contaminación cruzada:** Transferencia accidental de alérgenos o contaminantes entre alimentos, utensilios o superficies.
- **Duración:** Tiempo estimado de prestación del servicio de catering durante un evento.
- **Instalaciones:** Espacios y equipamientos disponibles para la preparación y prestación del servicio.
- **Menús:** Conjunto de platos y bebidas ofrecidos para un evento.
- **Platos:** Elaboraciones culinarias individuales que forman parte de un menú.
- **Postres:** Elaboraciones dulces que se ofrecen al finalizar una comida.
- **Presupuesto:** Estimación del coste total del servicio de catering solicitado.
- **Reservas:** Solicitudes confirmadas para contratar un servicio de catering en una fecha determinada.
- **Servicios:** Prestaciones de catering que la empresa ofrece a sus clientes.
- **Solicitud:** Petición realizada por un cliente para contratar un servicio de catering.
- **Usuarios:** Personas que acceden a la aplicación para consultar, solicitar o gestionar servicios de catering.

## 3. Visión general del sistema

### 3.1. Requisitos generales

- **R.G.01. Registro e inicio de sesión:** La aplicación permitirá a los usuarios registrarse e iniciar sesión, diferenciando entre usuarios y clientes.

- **R.G.02. Consulta de los servicios disponibles:** La aplicación permitirá consultar las diferentes opciones gastronómicas ofrecidas por la empresa, así como los espacios disponibles para la celebración de eventos.

- **R.G.03. Selección del tipo de evento:** La aplicación permitirá seleccionar el tipo de evento que se desea organizar.

- **R.G.04. Indicación del presupuesto disponible:** La aplicación permitirá indicar el presupuesto disponible para el evento, teniendo en cuenta las opciones elegidas por el usuario.

- **R.G.05. Información sobre alergias e intolerancias alimentarias:** La aplicación permitirá al cliente indicar las alergias e intolerancias alimentarias que deban tenerse en cuenta en la elaboración del menú.

- **R.G.06. Consulta de la disponibilidad:** La aplicación permitirá consultar la disponibilidad de los espacios y servicios para la fecha seleccionada.

- **R.G.07. Información detallada de cada servicio:** La aplicación proporcionará información sobre las características y condiciones de cada servicio ofrecido por la empresa.

- **R.G.08. Adaptación a eventos fuera de las instalaciones de Eatsii:** La aplicación permitirá solicitar servicios en otras localizaciones propuestas por el cliente, siempre que sean viables para la empresa.

- - **R.G.08. Gestion de solicitudes por parte del administrador:** La aplicación permitirá al administrador consultar, revisar y confirmar las solicitudes de reserva realizadas por los clientes.

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

- Verificar que el usuario pueda registrarse proporcionando datos válidos (nombre, email, contraseña, teléfono).

- Comprobar que el usuario no pueda iniciar sesión si las credenciales son erróneas.

- Comprobar que tras el inicio de sesión se redirija al panel correspondiente (Cliente o Administrador).


#### R.F.02. Filtrado y búsqueda de servicios tipo de evento

**Como** cliente

**quiero** filtrar los servicios por tipo de evento (boda, cumpleaños, corporativo)

**para** visualizar únicamente las propuestas gastronómicas y espacios disponibles.


**Prueba de aceptación**
- Verificar que al seleccionar un tipo de evento solo se muestran las especificaciones de este.


#### R.F.03.  Gestión e indicación de alérgeno

**Como** 

**quiero** 

**para** 


**Prueba de aceptación**


#### R.F.04. Solicitud de eventos en localizaciones de Eatsii

**Como** cliente

**quiero** seleccionar una localización de los ofrecidos por Eatsii

**para** solicitar el servicio de catering en el lugar de mi elección. 


**Prueba de aceptación**
- Verificar que el cliente pueda elegir una de las opciones disponibles.
- Comprobar que el lugar ha sido reservado para dicha cita en la fecha seleccionada.


#### R.F.05. Solicitud de eventos en localizaciones externas

**Como** cliente

**quiero** proponer una localización externa fuera de las instalaciones de Eatsii

**para** solicitar el servicio de catering en el lugar de mi elección.


**Prueba de aceptación**
- Verificar que el cliente pueda introducir la dirección y detalles técnicos del lugar propuesto.
- Comprobar que la solicitud quede en estado "Pendiente de evaluación de viabilidad".


#### R.F.06.  Evaluación de viabilidad de localizaciones externas

**Como** administrador de Eatsii

**quiero** revisar y evaluar las localizaciones externas propuestas por los clientes

**para** determinar si el evento es viable para la empresa.


**Prueba de aceptación**
- Verificar que el administrador pueda ver el listado de solicitudes externas pendientes.
- Comprobar que el administrador pueda cambiar el estado a "Aprobado" o "Rechazado", añadiendo comentarios explicativos para el cliente.



#### 4.1.1. Requisitos de información

##### R.I.01. Información de los usuarios

**Como** administrador

**quiero** disponer de la información identificativa de los usuarios

**para** gestionar sus cuentas y controlar el acceso a la aplicación.

**Prueba de aceptación**
- Cada usuario tendrá un identificador único.
- Se registrarán el nombre, los apellidos, el correo electrónico y la contraseña del usuario.
- Cada cuenta tendrá asignado un rol, que podrá ser cliente o administrador.
- Las contraseñas se almacenarán de forma segura y deberán cumplir unos criterios.


##### R.I.02. Información de los servicios

**Como** administrador

**quiero** almacenar la información de los servicios ofrecidos por Eatsii

**para** mantener actualizado el catálogo de la empresa.

**Prueba de aceptación**
- Cada servicio tendrá un identificador único, un nombre y una descripción.
- Se registrará el precio orientativo de cada servicio.
- Cada evento tendrá asociado un tipo de servicio.
- Se podrá indicar si un servicio está disponible o no.
- Se podrá consultar la información gastronómica y las características.


##### R.I.03. Información de los espacios 

**Como** administrador 

**quiero** almacenar los datos de los espacios de Eatsii 

**para** conocer sus características y gestionar su utilización.

**Prueba de aceptación**
- Cada espacio tendrá un identificador único, un nombre y una descripción.
- Se registrará la ubicación de cada espacio.
- Cada espacio tendrá una capacidad máxima mayor que cero.
- Se registrará el precio orientativo del espacio.
- Se podrá consultar si el espacio está fuera de servicio.


##### R.I.04. Información de los tipos de evento

**Como** administrador

**quiero** almacenar los tipos de evento admitidos por la empresa

**para** clasificar las solicitudes de los clientes.

**Prueba de aceptación**
- Cada tipo de evento tendrá un identificador único.
- Cada tipo de evento tendrá un nombre y una descripción.
- No se permitirá registrar dos tipos de evento con el mismo nombre.
- Los tipos de evento podrán consultarse al crear una solicitud.


##### R.I.05. Información de las solicitudes 

**Como** cliente 

**quiero** que se almacenen los datos de mi solicitud 

**para** poder consultar su estado y conocer las condiciones de mi evento.

**Prueba de aceptación**
- Cada solicitud tendrá un identificador único.
- Cada solicitud estará asociada al cliente que la haya realizado.
- Se registrarán el tipo de evento, la fecha y el número de asistentes.
- Se registrará la modalidad de celebración, indicando si se realizará en un espacio de Eatsii o en una ubicación externa.
- Cada solicitud tendrá una fecha de creación y un estado.
- No se permitirá registrar solicitudes sin los datos obligatorios.


##### R.I.06. Información de alergias e intolerancias 

**Como** cliente

**quiero** que se almacenen las alergias e intolerancias relevantes 

**para** mi evento para que Eatsii pueda tenerlas en cuenta.

**Prueba de aceptación**
- Cada alergia o intolerancia tendrá un identificador único.
- Se registrará el nombre y la descripción de cada alergia o intolerancia.
- Una solicitud podrá tener asociadas varias alergias o intolerancias.
- Una misma alergia o intolerancia podrá estar asociada a distintas solicitudes.
- Se podrá consultar qué alergias e intolerancias se han indicado para cada solicitud.


##### R.I.07. Información de presupuestos 

**Como** cliente

**quiero** consultar el presupuesto asociado a mi solicitud 

**para** conocer el coste del evento.

**Prueba de aceptación**
- Cada presupuesto estará asociado a una solicitud.
- Se registrarán el importe total, la fecha de elaboración y el estado de la propuesta.
- Se podrán consultar los servicios incluidos y sus importes correspondientes.
- El importe total coincidirá con la suma de los conceptos y ajustes aplicables.


##### R.I.08. Información de reservas y disponibilidad 

**Como** administrador

**quiero** almacenar las reservas confirmadas

**para** controlar la ocupación de los espacios y evitar incompatibilidades de fechas y horarios.

**Prueba de aceptación**
- Cada reserva tendrá un identificador único.
- Cada reserva estará vinculada a una solicitud válida.
- Se registrarán la fecha, el horario y el estado de la reserva.
- Si la reserva corresponde a un espacio de Eatsii, se identificará dicho espacio.
- No se permitirá confirmar dos reservas del mismo espacio cuyos horarios se solapen.
- Se podrá consultar la disponibilidad de los espacios para una fecha y un horario determinados


##### R.I.09. Información de los alérgenos presentes en los servicios 

**Como** administrador 

**quiero** registrar los alérgenos asociados a cada servicio gastronómico

**para** proporcionar información alimentaria a los clientes.

**Prueba de aceptación**
- Cada alérgeno tendrá un identificador único y un nombre.
- Se podrá registrar una descripción del alérgeno.
- Un servicio podrá tener asociados varios alérgenos.
- Un mismo alérgeno podrá estar presente en varios servicios.
- Se podrá consultar qué alérgenos están asociados a cada servicio.


##### R.I.10. Información de las notificaciones

**Como** usuario

**quiero** que se almacenen las notificaciones recibidas 

**para** consultar los cambios relevantes relacionados con mis solicitudes.

**Prueba de aceptación**
- Cada notificación tendrá un identificador único.
- Cada notificación estará asociada a un usuario destinatario.
- Se registrarán el mensaje y la fecha de creación.
- Las notificaciones relacionadas con solicitudes estarán vinculadas a la solicitud correspondiente.
- Cada usuario solo podrá consultar sus propias notificaciones.


##### R.I.11.  Información de las ubicaciones externas 

**Como** administrador 

**quiero** disponer de los datos de las ubicaciones externas propuestas por los clientes 

**para** evaluar si es viable prestar el servicio fuera de las instalaciones de Eatsii.

**Prueba de aceptación**
- Se registrará la dirección o localización propuesta por el cliente.
- La ubicación externa estará asociada a la solicitud correspondiente.
- Se podrán registrar observaciones sobre las condiciones del lugar.
- Se registrará el resultado de la evaluación de viabilidad.
- No se confirmará una solicitud en una ubicación externa sin una evaluación favorable de su viabilidad.



#### 4.1.2. Reglas de negocio

##### R.N.01. Capacidad de los espacios

El número de asistentes de un evento celebrado en un espacio de Eatsii no podrá superar la capacidad máxima establecida para dicho espacio.

##### R.N.02. Disponibilidad de los espacios

Un mismo espacio no podrá tener dos reservas confirmadas cuyos horarios se solapen.

##### R.N.03. Control de alergias e intolerancias

Las propuestas gastronómicas deberán tener en cuenta las alergias e intolerancias indicadas por el cliente. Los servicios identificados como incompatibles deberán excluirse de las propuestas automáticas. La falta de información sobre un alérgeno no podrá interpretarse como garantía de que el servicio sea seguro.

##### R.N.04. Viabilidad de las ubicaciones externas

Los servicios solicitados en ubicaciones externas solo podrán confirmarse cuando un administrador haya evaluado y aprobado la viabilidad del desplazamiento y de la prestación del servicio.

##### R.N.05. Coherencia de los presupuestos

El importe total de un presupuesto deberá coincidir con la suma de los importes de los servicios incluidos y los costes adicionales o ajustes que correspondan.

##### R.N.06. Correspondencia entre solicitudes y reservas

Toda reserva confirmada deberá estar vinculada a una solicitud válida y aceptada. Antes de confirmar una reserva, se deberá comprobar la disponibilidad de los espacios y recursos necesarios.

##### R.N.07. Estados de las solicitudes

Las solicitudes solo podrán encontrarse en uno de los siguientes estados: pendiente, en revisión, aceptada o  rechazada.

##### R.N.08. Control de permisos

Únicamente los usuarios con rol de administrador podrán crear, modificar o desactivar servicios y espacios, gestionar el catálogo y resolver las solicitudes de los clientes.

##### R.N.09. Número de asistentes

Toda solicitud deberá indicar un número de asistentes entero y mayor que cero.

##### R.N.10. Validez de las fechas y horarios

La fecha de un nuevo evento no podrá ser anterior a la fecha actual en el momento de registrar la solicitud. Cuando se indiquen las horas de inicio y finalización, la hora de finalización deberá ser posterior a la de inicio.

##### R.N.11. Integridad de los servicios solicitados

Los servicios incluidos en una solicitud deberán tener cantidades válidas y precios unitarios no negativos. 

##### R.N.12. Privacidad de las solicitudes

Cada cliente solo podrá consultar y gestionar las solicitudes de las que sea titular. Los administradores podrán acceder a la información necesaria para realizar sus funciones.

##### R.N.13. Validación y verificación de los datos del usuario

El sistema deberá comprobar que los datos introducidos por el usuario cumplen con el formato establecido y verificar el correo electrónico.



### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

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


