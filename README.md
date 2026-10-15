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

La finalidad de la plataforma es dar un servicio de alquiler de dispositivos electrónicos reacondicionados. El sistema recogerá la información de los dispositivos y facilitará su consulta.

Conforma a esto, establecemos los siguientes requisitos generales.

RG-1: Acceso asequible a la tecnología: el sistema facilitará un acceso temporal a dispositivos reacondicionados como alternativa de la compra de unos nuevos.

RG-2: Consulta del catálogo de dispositivos: los usuarios podrán ver los dispositivos del catálogo y sus características principales.

RG-3: Información sobre disponibilidad y precios: el sistema ofrece información clara y actualizada sobre el precio y disponibilidad de los dispositivos. 

RG-4: Flexibilidad de uso: el sistema facilitará información para que los usuarios puedan encontrar dispositivos adaptados a sus necesidades y el tiempo que lo necesitan.

RG-5: Fomento de la sostenibilidad: el sistema incitará a la reutilización de dispositivos reacondicionados para reducir la necesidad de comprar dispositivos nuevos.

RG-6: Gestión centralizada de la información: el sistema organzará la información importante sobre los dispositivos, clientes y alquileres para poder facilitar su consulta y mantenimiento.

### 3.2. Usuarios del sistema

Podemos encontrar tres tipos de usuarios: cliente, técnico de reacondicionamiento y administrador de la plataforma.

CLIENTE: Persona que consulta el catálogo y utiliza los servicios.

TÉCNICO DE REACONDICIONAMIENTO: Empleado encargado de revisar, reacondicionar y reparar los dispositivos.

ADMINISTRADOR DE LA PLATAFORMA: Empleado encargado de gestionar la información y actualizarla

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

### R.F.01 Listado de dispositivos disponibles por filtros

**Como** cliente

quiero consultar el listado de dispositivos disponibles aplicando filtros de categoría y marca
para encontrar un dispositivo que se adapte a misnnecesidades.

**Prueba de aceptación**
- Con tres portátiles de la marca Lenovo y uno HP disponibles en el sistema, al aplicar el filtro de categoría 'portátil' y de la marca 'HP', la plataforma muestra únicamente el dispositivo HP disponible.
- Al realizar el mismo filtro de categoría 'portátil' y marca 'HP', comprobar que los dispositivos con esos filtros que se encuentran en estado 'alquilado' o 'en mantenimiento' no aparecen en el listado.
- Al filtrar por una combinación de categoría y marca que no tiene dispositivo disponible en ese momento el sistema devuelve una lista vacía y un mensaje indicando que no hay dispositivos disponibles en ese momento, el sistema devuelve una lista vacía y un mensaje indicando que no hay dispositivos disponibles para esos filtros.

### R.F.02 Consulta de alquileres de un dispositivo

**Como** técnico de reaccondicionamiento
quiero consultar el historial de alquileres de un dispositivo concreto
para conocer su trayectoria de uso previa y evaluar su estado de desgate antes de volver a estar disponible en la plataforma de alquiler.

**Prueba de aceptación**
- Con un dispositivo seleccionado que tiene alquileres previos registrados, al consultar su historial, el sistema muestra el listado cronológico de sus usos anteriores, junto con las condiciones en las que fue devuelto.
- Al consultar el historial de un dispositivo concreto, la plataforma muestra únicamente la información correspondiente a ese equipo, sin mezclar datos de otros dispositivos.
- Al consultar el historial de un dispositivo que nunca ha sido alquilado, la plataforma muestra un mensaje indicando que el dispositivo no cuenta con alquileres previos.

### R.F.03. Consulta detallada de un dispositivo

**Como** cliente
quiero consultar los detalles de un dispositivo concreto, incluyendo sus características, precio y disponibilidad,
para ver si se ajusta a mis necesidades.

**Prueba de acepatción**
- En la plataforma hay registrado un portátil HP con 8GB de RAM, estado 'disponible', y un precio de 15€/día, cuando es seleccionado por el cliente, la plataforma muestra en pantalla sus características técnicas, su disponibilidad y precio.
- Si un cliente trata de acceder a los detalles de un dispositivo que ha sido dado de baja, el sistema no muestra los datos y avisa con un mensaje de que ya no se encuentra disponible.
- Si un dispositivo activo tiene alguna característica opcional o algún dato sin rellenar, el sistema muestra la ficha correctamente indicando correctamente el valor como 'No especificado' en en dicho campo, sin interrumpir la visualización del resto de la información.

### R.F.04. Listado de alquileres activos de un cliente

**Como** administrador de la plataforma
quiero saber el listado de alquileres de un cliente concreto,
para poder informarle lo antes posible sobre el estado de los equipos actuales o resolverle cualquier duda sobre sus alquileres en curso. 

**Prueba de aceptación**
- Dado un cliente registrado posee alquileres activos, al consultar su expediente, la plataforma muestra el listado detallado de todos sus dispositivos alquilados actualmente junto con los plazos de devolución y su estado.
- Al consultar la ficha de un cliente registrado que no tiene alquileres activos, la plataforma devuelve la lista vacía y muestra un mensaje indicando que el cliente no cuenta con ningún alquiler en curso.
- Al ingresar los datos de un cliente que no existe en la plataforma o buscar un dispositivo que no se encuentra registrado en la plataforma, esta genera un mensaje especificando que el usuario o dispositivo no está registrado.

### R.F.05. Listado de incidencias abiertas

**Como** técnico de reacondicionamiento
quiero saber el listado de incidencias abiertas de los diferentes dispositivos
para solucionarlas lo antes posible y evitar que afecten a alquileres futuros

**Prueba de aceptación**
- Al acceder al apartado de incidencias de la plataforma, el sistema muestra el listado de incidencias reportadas actualmente, permitiéndole identificar qué dispositivos requieren intervención.
- Al intentar filtrar el registro de incidencias de un dispositivo que no se encuentra en la base de datos de la plataforma y este muestra un mensaje de error que indica que no existe el dispositivo.
- Al acceder al listado de incidencias abiertas cuando no hay reportes de incidencias, la plataforma muestra una lista vacía y genera un mensaje indicando que no hay ninguna incidencia abierta.

### R.F.06. Listado de alquileres próximos a vencer

**Como** administrador de la plataforma
quiero saber el listado de alquileres que se encuentran próximos a vencer 
para ponerme en contacto con los clientes y gestionar la renovación o recogida de los dispositivos antes de que finalice el contrato

**Pruebas de acepatción**
- Al acceder a los listados de alquileres próximos a vencer para llevar un control diario, la plataforma muestra correctamente los contratos más próximos a vencer, permitiendo identificar a los clientes correspondientes para gestionar la renovación o recogida de los dispositivos.
- Al introducir un rango de fechas no válido, el sistema muestra un mensaje de error indicando que el filtro es erróneo y no permite realizar la búsqueda.
- Al acceder a los listados de alquileres próximos a vencer cuando no hay contratos que expiren en el periodo indicado, el sistema muestra una lista vacía, indicando que no hay ningún alquiler próximo a vencer.

### R.F.07. Listado de dispositivos con mayor ciclo de reutilización

**Como** técnico de reacondicionamiento
quiero consultar el listado de dispositivos con mayor ciclo de reutilización
para identificar el desgaste material y planificar su renovación o mantenimiento.

**Pruebas de aceptación**
- Al acceder al listado de dispositivos con mayor ciclo de reutilización para revisar el estado de los dispositivos, la plataforma de alquiler los muestra correctamente ordenados por su nivel de uso, indicando claramente cuáles requieren mantenimiento y cuáles sustitución.
- Al acceder al listado de dispositivos con mayor ciclo de reutilización consultando un dispositivo que no se encuentra en la plataforma de alquiler, esta muestra un mensaje indicando que no se encontraron resultados para la búsqueda.
- Al acceder al listado de dispositivos con mayor ciclo de reutilización aplicando un filtro por categoría de dispositivos sin resultados disponibles, la plataforma de alquiler muestra un mensaje indicando que no se encontraron coincidencias.


### 4.1.1. Requisitos de información

#### R.I.01. Información de usuarios

Como administrador de la plataforma, quiero disponer de la información de los usuarios registrados. Esta información incluye su nombre, apellidos, correo electrónico, contraseña, teléfono, para poder conocer cada caso dentro de la plataforma.

**Prueba de aceptación**
- Registrar un cliente indicando nombre, apellidos, correo electrónico y contraseña, para que toda la información se almacene correctamente.
- Registrar un usuario sin número de teléfono y comprobar que se guarden bien los datos.
- Registrar un técnico de reacondicionamiento y comprobar que quede identificado como corresponde.
- Registrar un administrador de la plataforma y comprobar que esté diferenciado del resto de usuarios.

#### R.I.02. Información de modelos y características de dispositivos

Como cliente, quiero tener al alcance la información de todos los tipos de recursos electrónicos disponibles en el catálogo, incluyendo su marca, modelo, categoría, descripción y características principales, para comparar estos dispositivos y ver cual se adapta mejor a lo que necesito.

**Prueba de aceptación**
- Registrar cada modelo de recurso tecnológico indicando su marca, modelo y categoría, y verificar que la información se almacena correctamente.
- Comprobar que las características descritas y los modelos correspondientes son verídicos.
- Registrar modelos de distintas categorías, como portátil, móvil y tablet, y comprobar que quedan clasificados correctamente.

#### R.I.03. Información de dispositivos

Como técnico de reacondicionamiento, quiero tener a mano la información sobre el estado, condición y disponibilidad de cada dispositivo, dependiendo de su modelo, para saber cual está preparado para ser alquilado o si necesita ser revisado o reparado.

**Prueba de aceptación**
- Registrar cada aparato electrónico asocicado a un modelo y comprobar que quede almacenado correctamente.
- Registrar la condición o estado de un dispositivo y asegurarse que todos los usuarios puedan acceder a verlo.
- Modificar el estado del equipo cuando necesite una reparación y actualizar la información en la página.
- Consultar si los dispositivos aparecen como disponibles o no disponibles para su alquiler.

#### R.I.04. Información de tarifas

Como cliente, quiero tener la información de las tarifas de cada dispositivo electrónico, incluyendo el periodo de alquiler y su precio, para poder saber el coste de alquiler y elegir la mejor opción para mí.

**Prueba de aceptación**
- Registrar cada tarifa indicando su periodo de alquiler y precio, y comprobar que la información corresponde a su modelo.
- Asociar cada tarifa a un modelo y comprobar que quede relacionada con el dispositivo al que corresponde.
- Registrar distintas tarifas para diferentes periodos de alquiler.

#### R.I.05. Información de alquileres

Como administrador de la plataforma, quiero conocer los alquileres realizados, junto al cliente que realiza el alquiler , el dispositivo alquilado, periodo y precio correspondiente, para poder hacer un seguimiento de los alquileres gestionados por la plataforma.

**Prueba de aceptación**
- Asociar un alquiler a un cliente y dispositivo, y almacenar la información.
- Registrar el periodo de alquiler.
- Registrar el precio de cada alquiler para poder consultarlo posteriormente.
- Consultar el historial de alquileres.

#### R.I.06. Información de devoluciones

Como administrador de la plataforma, quiero conocer la información relacionada con la devolución de los dispositivos alquilados, incluyendo la fecha de devolución y la condición en la que se entrega, para comprobar que el alquiler ha finalizado correctamente y mantener actualizada la información.

**Prueba de aceptación**
- Registrar una devolución asociada a un alquiler y vincularla correctamente.
- Registrar la fecha de devolución y comprobar su correcta almacenación.
- Registrar el estado en el que se devuelve el dispositivo y actualizarlo para consultarlo posteriormente.
- Registrar el alquiler finalizado asociado a su devolución correspondiente.

#### R.I.07. Información de reacondicionamientos

Como técnico de reacondicionamiento, quiero disponer de la información sobre los reacondicionamientos realizados a los dispositivos, incluyendo el dispositivo afectado, las averías y los problemas detectados, y la condición resultante del aparato electrónico, para comprobar si puede volver a ofrecerse en alquiler.

**Prueba de aceptación**
- Registrar un reacondicionamiento asociado a un recurso electrónico y vincularlo.
- Registrar los problemas o averías detectados durante la revisión.
- Registrar las actuaciones realizadas sobre el dispositivo y comprobar que se pueden consultar.
- Consultar el reacondicionamiento y comprobar que se muestra su condición tras la reparación o revisión.

#### R.I.08. Información de incidencias

Como técnico de reacondicionamiento, quiero conocer la información sobre las incidencias detectadas en los aparatos tecnológicos, incluyendo el dispositivo afectado, la descripción del problema, el estado de la incidencia y el alquiler durante el cual se produjo, para poder hacer un seguimiento y asegurar que el problema se ha resuelto.

**Prueba de aceptación**
- Registrar cada incidencia y vincularla al dispositivo.
- Registrar una descripción del problema detectado.
- Actualizar el estado de una incidencia y almacenar la modificación.
- Asociar la incidencia ocurrida a un alquiler cuando el problema se haya producido durante dicho alquiler.

### 4.1.2. Reglas de negocio

#### R.N.01. No solapamiento de alquileres

Un mismo dispositivo no puede estar asociado a dos alquileres en periodos que coincidan. Para realizar un nuevo alquiler, el dispositivo debe encontrarse disponible durante todo el periodo.

#### R.N.02. Estado adecuado para el alquiler

Un dispositivo solo puede ser alquilado cuando se encuentre en las condiciones necesarias para su uso. Si necesita una revisión o reparación no podrán ofrecerse hasta que se compruebe nuevamente su correcto funcionamiento.

#### R.N.03. Un único alquiler activo por cliente

Un cliente solo podrá realizar un alquiler a la vez. Para alquilar otro dispositivo deberá haber finalizado y devuelto el anterior.

#### R.N.04. Validez del periodo de alquiler 

La fecha de finalización prevista debe ser posterior a su fecha de inicio. El periodo de alquiler debe corresponder con una de las modalidades ofrecidas por la plataforma.

#### R.N.05. Devolución asociada a un alquiler

Toda devolución debe estar asociada a un alquiler previamente registrado. Un alquiler solo debe tener una devolución asociada.

#### R.N.06. Revisión antes de volver a ofrecer un dispositivo

Cuando se presente una incidencia que afecte al correcto funcionamiento, no volverá a estar disponible hasta que haya sido revisado y el técnico de reacondicionamiento determine que puede volver a su uso.

#### R.N.07. Aplicación de tarifas

El precio de un alquiler debe corresponder con una tarifa definida según el modelo y el alquiler seleccionado.

#### R.N.08. Asociación de incidencias

Toda incidencia debe estar asociada al dispositivo en el que se haya detectado. Si se produce durante el alquiler hay que asociar el usuario con la incidencia para realizar su seguimiento.


### 4.2. Mapa de historias de usuario
| **Consultar dispositivos** | **Gestionar alquileres** | **Gestionar mantenimiento y reacondicionamiento** |
| --- | --- | --- |
| RF01. Listado de dispositivos disponibles por filtros | RF04. Consulta del alquiler activo de un cliente | RF02. Consulta de alquileres de un dispositivos |
| RF03. Consulta detallada de un dispositivo | RF06. Listado de alquileres próximo a vencer | RF05. Listado de incidencias abiertas |
|   |   | RF07. Listado de dispositivos con mayor ciclo de reutilización |


### 4.3. Requisitos no funcionales 

**R.N.F.01. Facilidad de uso**

Como cliente quiero que la plataforma tenga una interfaz clara e intuitiva para poder consultar los dispositivos, precios y disponibilidad de forma sencilla.

**R.N.F.02. Seguridad de acceso** 

Como administrador de la plataforma quiero que cada tipo de usuario pueda acceder únicamente a la información y funciones que le correspondan para evitar accesos no autorizados dentro de la plataforma.

**R.N.F.03. Tiempo de respuesta**

Como cliente quiero que las consultas habituales del catálogo, precios y disponibilidad se muestren en un tiempo máximo de tres segundos para poder utilizar la plataforma de forma fluida.

**R.F.N.04. Compatibilidad**

Como usuario quiero poder utilizar la plataforma desde distintos tamaños de pantalla y navegadores web actuales para poder acceder al servicio tanto desde un ordenador como desde un dispositivo móvil.

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


