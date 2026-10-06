# Título Proyecto

## Miembros del grupo LX-XXX-X (sustituir)

1. Cruz España, Victoria
1. Gómez Núñez, Elena
1. Pérez Calvo, Ángeles
1. Fernández de Villavicencio, Cristina

## 1. Introducción al problema

En la actualidad, los dispositivos electrónicos se han vuelto un imprescindible en nuestra vida. Donde más repercute es en el ámbito académico y en los primeros años de vida laboral. Existe una gran variedad de dispositivos con características muy diversas entre ellos. Ordenadores portátiles, tablets, teléfonos móviles, etc, y cada uno tiene su función, estudiar, programar, asistir a clases online o desarrollar tareas laborales. Sin embargo, estas necesidades no siempre son permanentes. Muchas veces nuestros propios dispositivos no pueden realizar las tareas que necesitamos, ante la necesidad de proyectos temporales más complejos que no solemos realizar habitualmente.

Esta necesidad temporal de disponer de determinados dispositivos es habitualmente un problema. La única solución es adquirir un recurso tecnológico nuevo para cubrir una necesidad temporal. Aparte de este desembolso económico, damos lugar al abandono de dispositivos a los que podríamos prolongar su vida útil. Todo esto origina una gran cantidad de residuos tecnológicos. Por lo que debemos buscar formas de consumo más responsables, sostenibles y orientadas a extender su periodo de uso.

Como respuesta a esta situación, proponemos una plataforma de alquiler temporal de aparatos electrónicos reacondicionados, ofreciendo una alternativa más económica, flexible y sostenible a la compra tradicional. Cada usuario podrá acceder al hardware que necesite, durante el periodo de tiempo necesario. De este modo, un mismo dispositivo será reutilizado por diferentes personas reduciendo su sustitución innecesaria.

Los principales destinatarios de este servicio serán estudiantes de Formación Profesional, estudiantes universitarios y jóvenes que se encuentren en el principio de su etapa laboral y que tengan este problema. No obstante, la plataforma cubre otras muchas necesidades, como cuando falla tu ordenador y necesitas sustituirlo inmediatamente. El sistema también será utilizado por el personal de la empresa, los encargados del catálogo de equipos, su disponibilidad, tramitar los alquileres y devoluciones...

Con este proyecto ofrecemos una solución que proporcione accesibilidad, flexibilidad y sostenibilidad

## 2. Glosario de términos

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

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


