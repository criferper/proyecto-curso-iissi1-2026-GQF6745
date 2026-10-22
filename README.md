# ALQUILERES VECA

## Miembros del grupo L7-Grupo 7-Grupo 4 

1. Cruz España, Victoria
2. Gómez Núñez, Elena
3. Fernández de Villavicencio Periáñez, Cristina
4. Pérez Calvo, Ángeles

## 1. Introducción al problema

En la actualidad, los dispositivos electrónicos se han vuelto un imprescindible en nuestra vida. Donde más repercute es en el ámbito académico y en los primeros años de vida laboral. Existe una gran variedad de dispositivos con características muy diversas entre ellos. Ordenadores portátiles, tablets, teléfonos móviles, etc, y cada uno tiene su función, estudiar, programar, asistir a clases online o desarrollar tareas laborales. Sin embargo, estas necesidades no siempre son permanentes. Muchas veces nuestros propios dispositivos no pueden realizar las tareas que necesitamos, ante la necesidad de proyectos temporales más complejos que no solemos realizar habitualmente.

Esta necesidad temporal de disponer de determinados dispositivos es habitualmente un problema. La única solución es adquirir un recurso tecnológico nuevo para cubrir una necesidad temporal. Aparte de este desembolso económico, damos lugar al abandono de dispositivos a los que podríamos prolongar su vida útil. Todo esto origina una gran cantidad de residuos tecnológicos. Por lo que debemos buscar formas de consumo más responsables, sostenibles y orientadas a extender su periodo de uso.

Como respuesta a esta situación, proponemos una plataforma de alquiler temporal de aparatos electrónicos reacondicionados, ofreciendo una alternativa más económica, flexible y sostenible a la compra tradicional. Cada usuario podrá acceder al hardware que necesite, durante el periodo de tiempo necesario. De este modo, un mismo dispositivo será reutilizado por diferentes personas reduciendo su sustitución innecesaria.

Los principales destinatarios de este servicio serán estudiantes de Formación Profesional, estudiantes universitarios y jóvenes que se encuentren en el principio de su etapa laboral y que tengan este problema. No obstante, la plataforma cubre otras muchas necesidades, como cuando falla tu ordenador y necesitas sustituirlo inmediatamente. El sistema también será utilizado por el personal de la empresa, los encargados del catálogo de equipos, su disponibilidad, tramitar los alquileres y devoluciones...

Con este proyecto ofrecemos una solución que proporcione accesibilidad, flexibilidad y sostenibilidad, dando la oportunidad a distintos usuarios de poder acceder a tecnologías sin tener que comprar nuevos equipos electrónicos. También buscamos aportar un modelo de consumo más responsable con la reutilización de estos dispositivos, dando lugar a una economía circular. De esta forma, la plataforma no solo quiere responder a la necesidad económica, sino también contribuir a disminuir el impacto ambiental asociado al mundo de la tecnología.

## 2. Glosario de términos

- Ciclo de reutilización: periodo en el cual un dispositivo vuelve a ser utilizado, alargando su vida útil.
- Consumo responsable: forma de consumir la cual busca reducir el impacto ambiental siempre satisfaciendo nuestras necesidades pero evitando acciones innecesarias.
- Economía circular: modelo económico el cual apuesta por la reutilización, reparación y reacondicionamiento de los dispositivos para poder alargar su vida útil.
- Vida útil: periodo en el cual un dispositivo puede seguir utilizándose.

## 3. Visión general del sistema

### 3.1. Requisitos generales

**R.G.01. Consultar el catálogo de dispositivos**

Como cliente,

quiero consultar los dispositivos electrónicos ofrecidos por la plataforma,

para conocer sus características y disponibilidad y encontrar el dispositivo que mejor se adapte a mis necesidades.

**R.G.02. Gestionar los dispositivos**

Como administrador de la plataforma,

quiero gestionar los dispositivos registrados en el sistema,

para mantener actualizado el catálogo de equipos ofrecidos por la plataforma.

**R.G.03. Gestionar los alquileres y devoluciones**

Como administrador de la plataforma,

quiero gestionar los alquileres y devoluciones de los dispositivos,

para controlar qué dispositivos se encuentran alquilados, sus periodos de alquiler y su posterior devolución.

**R.G.04. Gestionar el mantenimiento de los dispositivos**

Como técnico de reacondicionamiento,

quiero gestionar el mantenimiento y seguimiento de los dispositivos,

para controlar sus incidencias, reacondicionamientos y estados tras su utilización.

### 3.2. Usuarios del sistema

Podemos encontrar tres tipos de usuarios: cliente, técnico de reacondicionamiento y administrador de la plataforma.

CLIENTE: Persona que consulta el catálogo y utiliza los servicios.

TÉCNICO DE REACONDICIONAMIENTO: Empleado encargado de revisar, reacondicionar y reparar los dispositivos.

ADMINISTRADOR DE LA PLATAFORMA: Empleado encargado de gestionar la información y actualizarla

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

### R.F.01 Dispositivos disponibles

**Como** cliente

quiero consultar el listado de dispositivos disponibles aplicando filtros de categoría y marca

para encontrar un dispositivo que se adapte a mis necesidades.

**Prueba de aceptación**
- Se debe comprobar que el cliente pueda **consultar** los dispositivos disponibles para el alquiler.
- Se debe comprobar que el sistema muestre un **listado** con los dispositivos disponibles.
- Se debe comprobar que el cliente pueda **filtrar** los dispositivos por categoría y marca.
- Se debe comprobar que los dispositivos alquilados, el mantenimiento o dados de baja no aparaezcan en el **listado** de dispositivos disponibles.
- Se debe comprobar que al realizar el **limpiado** de los filtros aplicados, vuelvan a mostrarse todos los recursos tecnológicos disponibles.
- Se debe comprobar que, si ningún dispositivos cumple los filtros seleccionados el sistema muestre un **listado** vacío e informe de que no existen resultados.

### R.F.02 Historial de alquileres de un dispositivo

**Como** técnico de reacondicionamiento

quiero consultar el historial de alquileres de un dispositivo concreto

para conocer su trayectoria de uso previa y evaluar su estado de desgate antes de volver a estar disponible en la plataforma de alquiler.

**Prueba de aceptación**

-Se debe comprobar que el técnico pueda realizar la **consulta** del historial de alquileres de un dispositivo concreto.
-Se debe comprobar que el sistema muestre un **listado** de los alquileres realizados anteriormente con dichos dispositivos.
-Se debe comprobar que el **listado** de alquileres aparezca ordenado cronológicamente.
-Se debe comprobar que, mediante la **consulta** del historial pueda conocerse la condición en la que fue devuelto el recurso electrónico en cada alquiler finalizado.
-Se debe comprobar que si el dispositivo nunca ha sido alquilado, el sistema muestre un **listado** vacío e informe de que no existen alquileres anteriores.
-Si se utilizan criterios para localizar un dispositivo, se debe comprobar que su **limpiado** permite realizar una nueva búsqueda.

### R.F.03. Información de un dispositivo

**Como** cliente

quiero consultar los detalles de un dispositivo concreto, incluyendo sus características, precio y disponibilidad,

para ver si se ajusta a mis necesidades.

**Prueba de acepatción** PREGUNTAR AL PROFESOR
-Se debe comprobar que el cliente pueda realizar la **consulta** del dispositivo seleccionado, y que durante esta se muestren las características correspondientes al modelo del dispositivo.
-Se debe comprobar que durante la **consulta** se muestre el precio del alquiler correspondiente.
-Se debe comprobar que durante la **consulta** se indique si el dispositivo se encuentre disponible para alquiler.
-Se debe comprobar que, cuando una característica opcional no tenga información registrada, la **consulta** pueda realizarse correctamente mostrando dicha información como no especificada.
-Se debe comprobar que un dispositivo dado de **baja** no aparezca como disponible para el alquiler.

### R.F.04. Alquiler activo en un cliente

**Como** administrador de la plataforma

quiero saber el listado de alquileres de un cliente concreto,

para poder informarle lo antes posible sobre el estado de los equipos actuales o resolverle cualquier duda sobre sus alquileres en curso. 

**Prueba de aceptación**
- Se debe comprobar que el administrador pueda realzar la **consulta** de un alquiler activo de un cliente registrado.
- Se debe comprobar que en la **consulta** se muestre el dispositivo alquilado y la información necesaria para el realizar el seguimiento del alquiler.
- Se debe comprobar que el alquiler mostrado en la **consulta** corresponde al cliente seleccionado.
- Se debe comprobar que, si se intenta realizar la **consulta** de un cliente no registrado, el sistema informa de que el cliente no existe.
- Si existen criterios de búsqueda del cliente se debe comprobar que su **limpiado** permita realizar una nueva consulta.

### R.F.05. Incidencias abiertas

**Como** técnico de reacondicionamiento

quiero saber el listado de incidencias abiertas de los diferentes dispositivos

para solucionarlas lo antes posible y evitar que afecten a alquileres futuros.

**Prueba de aceptación**
- Se debe comprobar que el técnico pueda realizar la **consulta** de incidencias que se encuentran abiertas.
- Se debe comprobar que el sistema muestre un **listado** de las incidencias abiertas y el dispositivo al que corresponde cada uno.
- Se debe comprobar que el técnico pueda **filtrar** el listado para consultar las incidencias abiertas de un dispositivo concreto.
- Se debe comprobar que, si se intenta realizar la **consulta** de un dispositivo que no existe, el sistema informe de que no se encuentra registrado.
- Se debe comprobar que, si no existen incidencias abiertas, el sistema muestre un **listado** vacío en forme de dicha situación.
- Se debe comprobar que, al realizar el **limpiado** de los filtros utilizados, vuelvan a mostrarse todas las incidencias abiertas.

### R.F.06. Alquileres próximos a vencer

**Como** administrador de la plataforma
quiero saber el listado de alquileres que se encuentran próximos a vencer 
para ponerme en contacto con los clientes y gestionar la renovación o recogida de los dispositivos antes de que finalice el contrato

**Pruebas de acepatción**
- Se debe comprobar que el administrador pueda realizar la **consulta** de los alquileres cuya fecha prevista de finalización se encuentre próxima.
- Se debe comprobar que el sistema muestre un **listado** de los alquileres próximos a vencer junto con el cliente y dispositivos correspondientes.
- Se debe comprobar que el administrador pueda **filtrar** el listado mediante un intervalo de fechas.
- Se debe comprobar que el sistema impida realizar la **consulta** cuando el rango de fechas no sea válido.
- Se debe comprobar que, si ningún alquiler finaliza dentro del periodo seleccionado,el sistema muestra un **listado** vacío.
- Se debe comprobar que, al realizar el **limpiado** del intervalo o de los filtros utilizados, la consulta vuelva a su estado inicial.

### R.F.07. Dispositivos con mayor reutilización

**Como** técnico de reacondicionamiento

quiero consultar el listado de dispositivos con mayor ciclo de reutilización

para identificar el desgaste material y planificar su renovación o mantenimiento.

**Pruebas de aceptación**
- Se debe comprobar que el técnico pueda realizar la **consulta** del número de alquileres realizados por cada dispositivo.
- Se debe comprobar que el sistema muestre un **listado** de dispositivos ordenados de mayor a menor según su número de alquileres.
- Se debe comprobar que el técnico pueda **filtrar** el listado por categoría de dispositivo.
- Se debe comprobar que, si ningún dispositivo cumple los criterios seleccionados, el sistema muestre un **listado** vacío e informe de que no existen resultados.
- Se debe comprobar que, al realizar el **limpiado** de los filtros aplicados, vuelva a mostrar se el listado completo.

### R.F.08. Gestionar dispositivos

**Como** administrador de la plataforma,

quiero dar de alta, consultar, modificar y dar de baja dispositivos 

para mantener actualizado el catálogo de equipos disponibles en la plataforma.

**Pruebas de aceptación**
- Se debe comprobar que el administrador pueda realizar el **alta** de un nuevo dispositivo introduciendo sus datos obligatorios.
- Se debe comprobar que el administrador pueda realizar la **consulta** de un dispositivo registrado.
- Se debe comprobar que el sistema permita obtener un **listado** de los dispositivos registrados.
- Se debe comprobar que el administrador pueda realizar a **modificación** de los datos permitidos de un dispositivo.
- Se debe comprobar que el administrador pueda realizar la **baja** de un dispositivo cuando corresponda, y que una vez dado de baja deje de aparecer en el listado de dispositivos disponibles para alquiler.
- Si se utilizan criterios de búsqueda se debe comprobar que el **limpiado** de los filtros permita volver a visualizar todos los recursos tecnológicos.

### R.F.09. Gestionar alquileres

**Como** administrador de la plataforma,

quiero registrar, consultar y actualizar los alquileres de los dispositivos

para controlar que dispositivos se encuentran alquilados y durante que periodo.

**Pruebas de aceptación**
- Se debe comprobar que el administrador pueda realizar el **registro** de un nuevo alquiler indicando el cliente, el dispositivo y el periodo correspondiente.
- Se debe comprobar que el administrador pueda realizar la **consulta** de un alquiler registrado.
- Se debe comprobar que el sistema permita obtener un **listado** de los alquileres registrados.
- Se debe comprobar que el administrador pueda realizar la **modificación** de los datos permitidos de un alquiler.
- Se debe comprobar que no pueda realizarse el **registro** de un alquiler para un dispositivo que no se encuentra disponible.
- Se debe comprobar que no pueda realizarse el **registro** de un nuevo alquiler para un cliente que ya tenga un alquiler activo.
- Si existen filtros de búsqueda, se debe comprobar que su **limpiado** permita volver a visualizar todos los alquileres.

### R.F.10. Gestionar devoluciones

**Como** administrador de la plataforma,

quiero registrar, consultar y actualizar las devoluciones de los dispositivos alquilados,

para controlar la finalización de los alquileres y el estado en el que se devuelven los dispositivos.

**Pruebas de aceptación**
-Se debe comprobar que el administrador pueda realizar el **registro** de una devolución asociada a un alquiler existente.
-Se debe comprobar que pueda realizar la **consulta** de una devolución registrada.
-Se debe comprobar que el sistema permita obtener un **listado** de las devoluciones realizadas.
-Se debe comprobar que el administrador pueda realizar la **modificación** de los datos permitidos de una devolución.
-Se debe comprobar que no pueda realizarse el **registro** de una segunda devolución para un alquiler que ya tenga una devolución asociada.
-Se debe comprobar que, al realizar el **registro** de la devolución, el alquiler correspondiente quede identificado como finalizado.
-Si existen filtros de búsqueda, se debe comprobar que su **limpiado** permita volver a mostrar todas las devoluciones.

### R.F.11. Gestionar incidencias

**Como** técnico de reacondicionamiento,

quiero registrar, consultar, modificar y cerrar las incidencias de los dispositivos,

para controlar los problemas detectados y realizar su seguimiento hasta que sean solucionados.

**Pruebas de aceptación**
- Se debe comprobar que el técnico pueda realizar el **registro** de una nueva incidencia asociada a un dispositivo.
- Se debe comprobar que el sistema permita obtener un **listado** de las incidencias.
- Se debe comprobar que el técnico pueda realizar la **consulta** de una incidencia registrada.
- Se debe comprobar que el técnico pueda realizar la **modificación** de la información de una incidencia mientras permanezca abierta.
- Se debe comprobar que el técnico pueda realizar el **cierre** de una incidencia cuando el problema haya sido solucionado.
- Se debe comprobar que una incidencia tras su **cierre** deje de aparecer en el listado de incidencias abiertas.
- Si se utilizan criterios de búsqueda, se debe comprobar que el **limpiado** de los filtros permita volver a visualizar todas las incidencias correspondientes.

### R.F.12. Gestionar reacondicionamientos

Como técnico de reacondicionamiento,

quiero registrar, consultar y actualizar los reacondicionamientos realizados sobre los dispositivos,

para mantener un historial de las intervenciones realizadas y conocer el estado de cada equipo.

**Pruebas de aceptación**

- Se debe comprobar que el técnico pueda realizar el **registro** de un reacondicionamiento asociado a un dispositivo.
- Se debe comprobar que pueda realizar la **consulta** de un reacondicionamiento registrado.
- Se debe comprobar que el sistema permita obtener un **listado** de los reacondicionamientos realizados.
- Se debe comprobar que el técnico pueda realizar la **modificación** de los datos permitidos de un reacondicionamiento.
- Se debe comprobar que cada reacondicionamiento quede asociado al dispositivo sobre el que se ha realizado.
- Se debe comprobar que mediante la **consulta** pueda conocerse el estado resultante del dispositivo después del reacondicionamiento.
- Si existen criterios de búsqueda, se debe comprobar que su **limpiado** permita volver a mostrar todos los reacondicionamientos.

### 4.1.1. Requisitos de información

#### R.I.01. Información de usuarios

Como administrador de la plataforma,

quiero disponer de la información de los usuarios registrados. Esta información incluye su nombre, apellidos, correo electrónico, usuario, contraseña, teléfono,

para poder conocer cada caso dentro de la plataforma.

**Prueba de aceptación**
- Se debe comprobar que cada usuario tenga un identificador único.
- Se debe comprobar que se almacenen su nombre, apellidos, correo electrónico, teléfono y tipo de usuario.
- Se debe comprobar que un usuario pueda estar identificado como cliente, administrador o técnico de reacondicionamiento.
- Se debe comprobar que la información de un usuario registrado pueda consultarse posteriormente.

#### R.I.02. Información de modelos y características de dispositivos

Como cliente,

quiero tener al alcance la información de todos los tipos de recursos electrónicos disponibles en el catálogo, incluyendo su marca, modelo, categoría, descripción y características principales, 

para comparar estos dispositivos y ver cual se adapta mejor a lo que necesito.

**Prueba de aceptación**
- Se debe comprobar que cada modelo tenga un identificador único.
- Se debe comprobar que se almacenen la marca, nombre del modelo, categoría, descripción y características correspondientes.
- Se debe comprobar que la información del modelo pueda mostrarse cuando se consulta un dispositivo.

#### R.I.03. Información de dispositivos

Como técnico de reacondicionamiento,

quiero tener a mano la información sobre el estado, condición y disponibilidad de cada dispositivo, dependiendo de su modelo,

para saber cual está preparado para ser alquilado o si necesita ser revisado o reparado.

**Prueba de aceptación**
- Se debe comprobar que cada dispositivo tenga un identificador único.
- Se debe comprobar que cada dispositivo este asociado a un modelo existente.
- Se debe comprobar que se almacenen su condición y su estado.
- Se debe comprobar que el estado permita conocer si el dispositivo se encuentra disponible, alquilado, en mantenimiento o dado de baja.
- Se debe comprobar que la información almacenada permita determinar si el dispositivo puede aparecer entre los dispositivos disponibles.

#### R.I.04. Información de tarifas

Como cliente,

quiero tener la información de las tarifas de cada dispositivo electrónico, incluyendo el periodo de alquiler y su precio,

para poder saber el coste de alquiler y elegir la mejor opción para mí.

**Prueba de aceptación**
- Se debe comprobar que cada tarifa tenga un identificador único.
- Se debe comprobar que se almacene el periodo de alquiler correspondiente.
- Se debe comprobar que se almacena el precio de la tarifa.
- Se debe comprobar que pueda determinarse qué tarifa corresponde al dispositivo y periodo seleccionados.

#### R.I.05. Información de alquileres

Como administrador de la plataforma,

quiero conocer los alquileres realizados, junto al cliente que realiza el alquiler , el dispositivo alquilado, periodo y precio correspondiente,

para poder hacer un seguimiento de los alquileres gestionados por la plataforma.

**Prueba de aceptación**
- Se debe comprobar que cada alquiler tenga un identificador único.
- Se debe comprobar que cada alquiler este asociado a un cliente registrado.
- Se debe comprobar que cada alquiler este asociado a un dispositivo registrado.
- Se debe comprobar que se almacenen la fecha de inicio y la fecha prevista de finalización.
- Se debe comprobar que se almacenen la tarifa y el precio aplicados.
- Se debe comprobar que pueda conocerse si el alquiler se encuentra activo o finalizado.
- Se debe comprobar que la información almacenada permita consultar los alquileres próximos a vencer.

#### R.I.06. Información de devoluciones

Como administrador de la plataforma,

quiero conocer la información relacionada con la devolución de los dispositivos alquilados, incluyendo la fecha de devolución y la condición en la que se entrega,

para comprobar que el alquiler ha finalizado correctamente y mantener actualizada la información.

**Prueba de aceptación**
- Se debe comprobar que cada devolución tenga un identificador único.
- Se debe comprobar que cada devolución este asociada a un alquiler existente.
- Se debe comprobar que se almacene la fecha en la que se realizó la devolución.
- Se debe comprobar que se registre la condición del dispositivo al ser devuelto.
- Se debe comprobar que puedan almacenarse observaciones sobre la devolución.
- Se debe comprobar que la información de la devolución pueda consultarse posteriormente.

#### R.I.07. Información de reacondicionamientos

Como técnico de reacondicionamiento,

quiero disponer de la información sobre los reacondicionamientos realizados a los dispositivos, incluyendo el dispositivo afectado, las averías y los problemas detectados, y la condición resultante del aparato electrónico,

para comprobar si puede volver a ofrecerse en alquiler.

**Prueba de aceptación**
- se debe comprobar que cada incidencia tenga un identificador único.
- Se debe comprobar que cada incidencia este asociada a un dispositivo existente.
- Se debe comprobar que se almacenen la descripción y la fecha de apertura.
- Se debe comprobar que pueda conocerse si la incidencia permanece abierta o está cerrada.
- Se debe comprobar que la fecha de cierre pueda almacenarse cuando la incidencia sea solucionada.
- Se debe comprobar que, cuando la incidencia se produzca durante un alquiler, pueda quedar asociada al alquiler correspondiente.

#### R.I.08. Información de incidencias

Como técnico de reacondicionamiento,

quiero conocer la información sobre las incidencias detectadas en los aparatos tecnológicos, incluyendo el dispositivo afectado, la descripción del problema, el estado de la incidencia y el alquiler durante el cual se produjo,

para poder hacer un seguimiento y asegurar que el problema se ha resuelto.

**Prueba de aceptación**
- Se debe comprobar que cada reacondicionamiento tenga un identificador único.
- Se debe comprobar que este asociado a un dispositivo existente.
- Se debe comprobar que se almacene la fecha de realización.
- Se debe comprobar que puedan almacenarse los problemas detectados y las actualizaciones realizadas.
- Se debe comprobar que se registre el estado resultante del dispositivo.
- Se debe comprobar que puedan consultarse posteriormente los reacondicionamientos realizados sobre un dispositivo.

### 4.1.2. Reglas de negocio

#### R.N.01. Ausencia de solapamiento entre alquileres

Un mismo dispositivo no puede estar asociado a dos alquileres en periodos que coincidan. Para realizar un nuevo alquiler, el dispositivo debe encontrarse disponible durante todo el periodo.

#### R.N.02. Estado adecuado para el alquiler

Un dispositivo solo puede ser alquilado cuando se encuentre disponible y en las condiciones necesarias para su uso. Si necesita una revisión o reparación no podrán ofrecerse hasta que se compruebe nuevamente su correcto funcionamiento.

#### R.N.03. Límite de alquileres activos por cliente

Un cliente solo podrá realizar un alquiler activo al mismo tiempo. Para alquilar otro dispositivo deberá haber finalizado y devuelto el anterior.

#### R.N.04. Dispositivo con incidencia

Cuando se presente una incidencia que afecte al correcto funcionamiento de un dispositivo electrónico, este no volverá a estar disponible hasta que haya sido revisado y el técnico de reacondicionamiento determine que puede volver a su uso.

### R.N.03.


### 4.2. Mapa de historias de usuario
| **Consultar dispositivos** | **Gestionar alquileres** | **Gestionar mantenimiento y reacondicionamiento** |
| --- | --- | --- |
| RF01. Listado de dispositivos disponibles por filtros | RF04. Consulta del alquiler activo de un cliente | RF02. Consulta de alquileres de un dispositivos |
| RF03. Consulta detallada de un dispositivo | RF06. Listado de alquileres próximo a vencer | RF05. Listado de incidencias abiertas |
|   |   | RF07. Listado de dispositivos con mayor ciclo de reutilización |


### 4.3. Requisitos no funcionales 

**R.N.F.01. Usabilidad**

Como cliente 

quiero que la plataforma tenga una interfaz clara e intuitiva

para poder consultar los dispositivos, precios y disponibilidad de forma sencilla.

**R.N.F.02. Rendimiento**

Como cliente,

quiero que las consultas y listados habituales respondan en un tiempo máximo de 3 segundos en condiciones normales de funcionamiento,

para poder utilizar la plataforma de forma fluida.

**R.N.F.03. Seguridad** 

Como cliente,

quiero que el acceso a las funciones de la plataforma este protegido según el tipo de usuario,

para evitar operaciones no autorizadas.

**R.N.F.04. Fiabilidad**

Como cliente,

quiero que la información registrada sobre dispositivos, alquileres, devoluciones, incidencias y reacondicionamientos se mantenga íntegra y consistente, 

para poder confiar en los datos almacenados.

**R.F.N.05. Compatibilidad**

Como usuario

quiero poder utilizar la plataforma desde distintos dispositivos y navegadores web actuales

para poder acceder al servicio independientemente del equipo utilizado.

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


