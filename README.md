# Título Proyecto

## Miembros del grupo L4-FJO-6 (sustituir)

1. Gavira Baeza, Carmen
1. Pérez Soria, Carolina
1. Cook González, Elena Joanna
1. Toajas Samanego, Marco

## 1. Introducción al problema

<dd>&emsp;&emsp;El catering Eatsii desarrolla su actividad en la provincia de Sevilla y tiene su sede en la calle Carmona, 6. Se trata de una empresa de tamaño mediano que, además de ofrecer una amplia propuesta gastronómica especializadas en celebraciones privadas y eventos corporativos, dispone de diferentes espacios habilitados para la celebración de eventos. Asimismo, ofrece la posibilidad de desplazarse a otras localizaciones propuestas por los clientes, siempre que las condiciones del lugar y la organización del evento lo permitan.
  
<dd>&emsp;&emsp;Solicita el desarrollo de una aplicación cuya función principal sea conectar a los clientes con los servicios que puede proporcionar su empresa, se amoldarán a las necesidades de cada usuario. Dichos servicios se basarán en los tipos de eventos, presupuestos y alérgenos que cada consumidor precise.


<img width="1024" height="559" alt="d5435e34-a33c-4898-b274-daa7d004905c" src="https://github.com/user-attachments/assets/cb153172-313f-4cf0-83fa-75fb4ba987d4" />



## 2. Glosario de términos

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales
**Registro e inicio de sesión** de los usuarios.
**Consulta de los servicios disponibles**, incluyendo las diferentes opciones gastronómicas y espacios para la celebración de eventos.
**Selección del tipo de evento**, como bodas, cumpleaños, reuniones, celebraciones u otros eventos.
**Indicación del presupuesto disponible**, de manera que el sistema pueda mostrar opciones que se ajusten a las posibilidades económicas del usuario.
**Información sobre alergias e intolerancias alimentarias**, permitiendo al cliente indicar aquellos alimentos que debe evitar.
**Consulta de la disponibilidad** de los espacios y servicios para la fecha seleccionada.
**Información detallada de cada servicio**, incluyendo sus características, condiciones y precio orientativo.
**Adaptación a eventos** fuera de las instalaciones de Eatsii, siempre que la localización propuesta por el cliente sea viable para la empresa.


### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

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


