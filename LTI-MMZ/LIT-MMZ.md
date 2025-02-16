# User Stories para el Servicio de Gestión de Ofertas de Empleo de LTI

Título de la Historia de Usuario: Crear una Oferta de Empleo Simple

Como reclutador,

quiero poder crear una nueva oferta de empleo con información básica (título, descripción, requisitos, departamento, ubicación),

para que pueda comenzar a atraer candidatos para la posición.

Criterios de Aceptación:

Puedo acceder a un formulario para crear una nueva oferta de empleo.
El formulario incluye campos para el título, descripción, requisitos, departamento y ubicación.
Puedo guardar la oferta de empleo como un borrador.
Puedo publicar la oferta de empleo en la plataforma LTI.
Notas Adicionales:

En esta primera iteración, la publicación solo será interna en la plataforma LTI.
Se puede considerar la validación básica de los campos del formulario.
Historias de Usuario Relacionadas:

Publicar Oferta de Empleo en Portales Externos
Añadir Campos Adicionales a la Oferta de Empleo
Título de la Historia de Usuario: Publicar Oferta de Empleo en Portales Externos

Como reclutador,

quiero poder publicar una oferta de empleo en portales de empleo externos (ej. Indeed, LinkedIn),

para que pueda llegar a un público más amplio de candidatos.

Criterios de Aceptación:

Puedo seleccionar los portales de empleo en los que quiero publicar la oferta.
LTI formatea la oferta de empleo para que sea compatible con los portales seleccionados.
Puedo hacer un seguimiento de las publicaciones en cada portal.
Notas Adicionales:

Se puede implementar la integración con APIs de portales de empleo populares.
Se puede considerar la posibilidad de programar la publicación en diferentes momentos.
Historias de Usuario Relacionadas:

Crear una Oferta de Empleo Simple
Gestionar las Publicaciones de la Oferta de Empleo
Título de la Historia de Usuario: Añadir Campos Adicionales a la Oferta de Empleo

Como reclutador,

quiero poder añadir campos adicionales a la oferta de empleo (ej. salario, tipo de contrato, beneficios),

para que pueda proporcionar información más completa a los candidatos.

Criterios de Aceptación:

Puedo añadir campos personalizados a la oferta de empleo.
Puedo definir el tipo de campo (ej. texto, número, selección múltiple).
Puedo marcar campos como obligatorios u opcionales.
Notas Adicionales:

Se puede considerar la posibilidad de crear plantillas de ofertas de empleo con campos predefinidos.
Historias de Usuario Relacionadas:

Crear una Oferta de Empleo Simple
Buscar Ofertas de Empleo por Campos Adicionales
Título de la Historia de Usuario: Buscar Ofertas de Empleo

Como reclutador,

quiero poder buscar ofertas de empleo por diferentes criterios (ej. título, departamento, ubicación, estado),

para que pueda encontrar rápidamente las ofertas que necesito.

Criterios de Aceptación:

Puedo buscar ofertas de empleo por título, departamento, ubicación y estado.
Puedo combinar diferentes criterios de búsqueda.
Los resultados de la búsqueda se muestran de forma clara y ordenada.
Notas Adicionales:

Se puede implementar la búsqueda por texto libre en la descripción y los requisitos.
Historias de Usuario Relacionadas:

Gestionar las Publicaciones de la Oferta de Empleo
Título de la Historia de Usuario: Gestionar las Publicaciones de la Oferta de Empleo

Como reclutador,

quiero poder gestionar las publicaciones de una oferta de empleo (ej. pausar, reanudar, finalizar),

para que pueda controlar la visibilidad de la oferta en los diferentes canales.

Criterios de Aceptación:

Puedo pausar una publicación en un portal específico.
Puedo reanudar una publicación pausada.
Puedo finalizar una publicación antes de su fecha de cierre.
Notas Adicionales:

Se puede considerar la posibilidad de programar la pausa y la reanudación de las publicaciones.
Historias de Usuario Relacionadas:

Publicar Oferta de Empleo en Portales Externos
Obtener Estadísticas de las Publicaciones de la Oferta de Empleo
Título de la Historia de Usuario: Obtener Estadísticas de las Publicaciones de la Oferta de Empleo

Como reclutador,

quiero poder obtener estadísticas sobre las publicaciones de una oferta de empleo (ej. número de visitas, número de solicitudes),

para que pueda evaluar el rendimiento de la oferta en los diferentes canales.

Criterios de Aceptación:

Puedo ver el número de visitas y solicitudes para cada publicación.
Puedo comparar las estadísticas de diferentes publicaciones.
Puedo exportar las estadísticas en un formato CSV o Excel.
Notas Adicionales:

Se puede considerar la posibilidad de visualizar las estadísticas en gráficos.
Historias de Usuario Relacionadas:

Gestionar las Publicaciones de la Oferta de Empleo
Título de la Historia de Usuario: Duplicar una Oferta de Empleo Existente

Como reclutador,

quiero poder duplicar una oferta de empleo existente,

para que pueda crear nuevas ofertas de forma rápida y sencilla.

Criterios de Aceptación:

Puedo seleccionar una oferta de empleo existente y crear una copia.
La copia incluye toda la información de la oferta original.
Puedo modificar la información de la copia antes de guardarla.
Notas Adicionales:

Se puede considerar la posibilidad de duplicar solo la información básica de la oferta.
Historias de Usuario Relacionadas:

Crear una Oferta de Empleo Simple
Título de la Historia de Usuario: Archivar una Oferta de Empleo

Como reclutador,

quiero poder archivar una oferta de empleo que ya no está activa,

para que pueda mantener el sistema organizado.

Criterios de Aceptación:

Puedo archivar una oferta de empleo desde la lista de ofertas.
Las ofertas archivadas no se muestran en la lista principal de ofertas.
Puedo acceder a las ofertas archivadas en una sección separada.
Notas Adicionales:

Se puede considerar la posibilidad de eliminar ofertas de empleo archivadas.
Historias de Usuario Relacionadas:

Buscar Ofertas de Empleo
Estas historias de usuario proporcionan una base sólida para el desarrollo del Servicio de Gestión de Ofertas de Empleo de LTI. Se pueden añadir o modificar historias de usuario a medida que se avanza en el proceso de desarrollo y se obtienen más requisitos.

# Backlog de Producto

## Backlog de Producto para LTI - Servicio de Gestión de Ofertas de Empleo

A continuación, se presenta el backlog de producto para el Servicio de Gestión de Ofertas de Empleo de LTI, basado en las historias de usuario previamente definidas. Se han considerado los siguientes criterios de priorización:

* **Valor para el usuario:** ¿Cuánto valor aporta esta funcionalidad al usuario final? (Alto, Medio, Bajo)
* **Esfuerzo de desarrollo:** ¿Cuánto esfuerzo se requiere para implementar esta funcionalidad? (Alto, Medio, Bajo)
* **Riesgo:** ¿Qué tan arriesgado es el desarrollo de esta funcionalidad? (Alto, Medio, Bajo)
* **Dependencias:** ¿Esta funcionalidad depende de otras funcionalidades? (Sí/No, y se listan las dependencias)

La prioridad agregada se calcula asignando valores numéricos a cada criterio (Alto=3, Medio=2, Bajo=1) y sumando los valores.

| Tarea | Valor para el usuario | Esfuerzo de desarrollo | Riesgo | Dependencias | Prioridad Agregada |
|---|---|---|---|---|---|
| Crear una Oferta de Empleo Simple | Alto | Medio | Bajo | No | 8 |
| Buscar Ofertas de Empleo | Alto | Medio | Bajo | No | 8 |
| Añadir Campos Adicionales a la Oferta de Empleo | Medio | Medio | Bajo | No | 7 |
| Publicar Oferta de Empleo en Portales Externos | Alto | Alto | Medio | Crear una Oferta de Empleo Simple | 10 |
| Gestionar las Publicaciones de la Oferta de Empleo | Medio | Medio | Bajo | Publicar Oferta de Empleo en Portales Externos | 8 |
| Obtener Estadísticas de las Publicaciones de la Oferta de Empleo | Medio | Medio | Medio | Publicar Oferta de Empleo en Portales Externos | 9 |
| Duplicar una Oferta de Empleo Existente | Medio | Bajo | Bajo | Crear una Oferta de Empleo Simple | 6 |
| Archivar una Oferta de Empleo | Bajo | Bajo | Bajo | No | 4 |

## Orden de Implementación

Teniendo en cuenta la prioridad agregada y las dependencias, el orden de implementación recomendado es el siguiente:

1. **Crear una Oferta de Empleo Simple:** Esta funcionalidad es fundamental y tiene un alto valor para el usuario. Sirve como base para otras funcionalidades.
2. **Buscar Ofertas de Empleo:** Permite a los reclutadores encontrar fácilmente las ofertas que necesitan, mejorando la usabilidad de la plataforma.
3. **Añadir Campos Adicionales a la Oferta de Empleo:**  Aumenta la flexibilidad y la capacidad de personalización de las ofertas de empleo.
4. **Duplicar una Oferta de Empleo Existente:**  Facilita la creación de nuevas ofertas a partir de plantillas, ahorrando tiempo a los reclutadores.
5. **Publicar Oferta de Empleo en Portales Externos:**  Amplía el alcance de las ofertas de empleo, llegando a un público más amplio de candidatos.
6. **Gestionar las Publicaciones de la Oferta de Empleo:**  Permite controlar la visibilidad de las ofertas en los diferentes canales.
7. **Obtener Estadísticas de las Publicaciones de la Oferta de Empleo:**  Proporciona información valiosa para evaluar el rendimiento de las publicaciones y optimizar las estrategias de reclutamiento.
8. **Archivar una Oferta de Empleo:**  Ayuda a mantener el sistema organizado, aunque tiene una prioridad menor en comparación con otras funcionalidades.

Este orden de implementación permite entregar valor al usuario desde las primeras etapas del desarrollo, al tiempo que se gestionan los riesgos y se minimiza el esfuerzo de desarrollo.

**Consideraciones adicionales:**

* Es importante mantener una comunicación fluida con los stakeholders para validar las prioridades y obtener feedback durante el proceso de desarrollo.
* Se puede utilizar un enfoque iterativo e incremental para el desarrollo, entregando funcionalidades en ciclos cortos y adaptando el backlog en función del feedback recibido.
* Se deben realizar pruebas exhaustivas en cada etapa del desarrollo para garantizar la calidad del producto final.


# Desglose de tareas para la publicación en portales externos

¡Perfecto! Aquí tienes el desglose en tareas técnicas de la user story "Publicar Oferta de Empleo en Portales Externos", siguiendo el formato de ejemplo que proporcionaste:

**Título:** Investigación y Selección de APIs de Portales de Empleo

**Descripción:** Investigar las APIs de los principales portales de empleo (Indeed, LinkedIn, Glassdoor, etc.) para identificar cuáles ofrecen la funcionalidad de publicación de ofertas de empleo a través de APIs y evaluar su documentación, requisitos técnicos y costos.

**Criterios de Aceptación:**

* Se ha elaborado un informe con las APIs de portales de empleo más relevantes.
* El informe incluye una tabla comparativa con las características de cada API (funcionalidades, documentación, costos).
* Se han seleccionado las APIs que mejor se adaptan a las necesidades de LTI.

**Prioridad:** Alta

**Estimación:** 5 puntos de historia

**Asignado a:** Equipo de Backend

**Etiquetas:** Backend, APIs, Integraciones, Investigación

**Comentarios:** Contactar con los portales de empleo para obtener acceso a las APIs y aclarar cualquier duda técnica.

---

**Título:** Diseño e Implementación de la Capa de Abstracción de APIs

**Descripción:** Diseñar e implementar una capa de abstracción que permita interactuar con las APIs de los diferentes portales de empleo de forma unificada, independientemente de sus particularidades técnicas.

**Criterios de Aceptación:**

* Se ha creado una capa de abstracción con interfaces claras y bien documentadas.
* La capa de abstracción permite realizar las operaciones básicas de publicación y gestión de ofertas de empleo.
* Se han implementado adaptadores para las APIs de los portales de empleo seleccionados.

**Prioridad:** Alta

**Estimación:** 8 puntos de historia

**Asignado a:** Equipo de Backend

**Etiquetas:** Backend, APIs, Integraciones, Arquitectura

**Comentarios:** Considerar el uso de patrones de diseño como el Factory Pattern o el Adapter Pattern para facilitar la adición de nuevos portales en el futuro.

---

**Título:** Desarrollo del Servicio de Publicación de Ofertas de Empleo

**Descripción:** Desarrollar el servicio que se encarga de publicar las ofertas de empleo en los portales externos a través de la capa de abstracción de APIs.

**Criterios de Aceptación:**

* El servicio recibe la información de la oferta de empleo y la publica en los portales seleccionados.
* El servicio maneja los errores y las excepciones de las APIs de forma robusta.
* El servicio registra las acciones realizadas y los resultados de las publicaciones.

**Prioridad:** Alta

**Estimación:** 13 puntos de historia

**Asignado a:** Equipo de Backend

**Etiquetas:** Backend, APIs, Integraciones, Desarrollo

**Comentarios:** Implementar mecanismos de reintento y notificaciones en caso de fallos en la publicación.

---

**Título:** Pruebas de Integración con Portales de Empleo

**Descripción:** Realizar pruebas de integración con las APIs de los portales de empleo para verificar el correcto funcionamiento del servicio de publicación.

**Criterios de Aceptación:**

* Se han realizado pruebas unitarias y de integración para el servicio de publicación.
* Se han probado las diferentes funcionalidades de publicación y gestión de ofertas.
* Se han verificado los mensajes de error y las notificaciones.

**Prioridad:** Alta

**Estimación:** 8 puntos de historia

**Asignado a:** Equipo de QA

**Etiquetas:** QA, Pruebas, Integraciones, APIs

**Comentarios:** Utilizar mocks y stubs para simular las respuestas de las APIs durante las pruebas.

---

**Título:** Implementación de la Interfaz de Usuario para la Publicación

**Descripción:** Desarrollar la interfaz de usuario que permite a los reclutadores seleccionar los portales de empleo y publicar las ofertas.

**Criterios de Aceptación:**

* La interfaz muestra una lista de los portales de empleo disponibles.
* Los reclutadores pueden seleccionar los portales en los que quieren publicar la oferta.
* La interfaz muestra el estado de la publicación (en curso, completada, fallida).

**Prioridad:** Alta

**Estimación:** 8 puntos de historia

**Asignado a:** Equipo de Frontend

**Etiquetas:** Frontend, UI, UX, Desarrollo

**Comentarios:** Diseñar una interfaz intuitiva y fácil de usar para la selección de portales y la gestión de publicaciones.

---

**Título:** Pruebas de la Interfaz de Usuario para la Publicación

**Descripción:** Realizar pruebas de la interfaz de usuario para verificar su correcto funcionamiento y usabilidad.

**Criterios de Aceptación:**

* Se han realizado pruebas funcionales y de usabilidad de la interfaz.
* Se han verificado los flujos de publicación y gestión de ofertas.
* Se han corregido los errores y las inconsistencias encontradas.

**Prioridad:** Alta

**Estimación:** 5 puntos de historia

**Asignado a:** Equipo de QA

**Etiquetas:** QA, Pruebas, UI, UX

**Comentarios:** Involucrar a usuarios reales en las pruebas de usabilidad para obtener feedback valioso.

Este desglose de tareas técnicas proporciona una visión detallada de las actividades necesarias para implementar la user story de "Publicar Oferta de Empleo en Portales Externos". Permite una mejor planificación, seguimiento y control del proyecto.

# Backlog actualizado con las estimaciones por tallas

¡Excelente! Aquí tienes la tabla del backlog de tareas con la columna "Talla" añadida, utilizando la secuencia de Fibonacci para la estimación del esfuerzo:

| Tarea | Valor para el usuario | Esfuerzo de desarrollo | Riesgo | Dependencias | Prioridad Agregada | Talla (Puntos de Historia) |
|---|---|---|---|---|---|---|
| Crear una Oferta de Empleo Simple | Alto | Medio | Bajo | No | 8 | 8 |
| Buscar Ofertas de Empleo | Alto | Medio | Bajo | No | 8 | 5 |
| Añadir Campos Adicionales a la Oferta de Empleo | Medio | Medio | Bajo | No | 7 | 5 |
| Publicar Oferta de Empleo en Portales Externos | Alto | Alto | Medio | Crear una Oferta de Empleo Simple | 10 | 13 |
| Gestionar las Publicaciones de la Oferta de Empleo | Medio | Medio | Bajo | Publicar Oferta de Empleo en Portales Externos | 8 | 5 |
| Obtener Estadísticas de las Publicaciones de la Oferta de Empleo | Medio | Medio | Medio | Publicar Oferta de Empleo en Portales Externos | 9 | 8 |
| Duplicar una Oferta de Empleo Existente | Medio | Bajo | Bajo | Crear una Oferta de Empleo Simple | 6 | 3 |
| Archivar una Oferta de Empleo | Bajo | Bajo | Bajo | No | 4 | 2 |
| Investigación y Selección de APIs de Portales de Empleo | Alto | Medio | Medio | No | 9 | 5 |
| Diseño e Implementación de la Capa de Abstracción de APIs | Alto | Alto | Alto | No | 11 | 13 |
| Desarrollo del Servicio de Publicación de Ofertas de Empleo | Alto | Alto | Alto | Diseño e Implementación de la Capa de Abstracción de APIs | 12 | 21 |
| Pruebas de Integración con Portales de Empleo | Alto | Medio | Medio | Desarrollo del Servicio de Publicación de Ofertas de Empleo | 11 | 8 |
| Implementación de la Interfaz de Usuario para la Publicación | Alto | Medio | Bajo | Diseño e Implementación de la Capa de Abstracción de APIs | 10 | 8 |
| Pruebas de la Interfaz de Usuario para la Publicación | Medio | Bajo | Bajo | Implementación de la Interfaz de Usuario para la Publicación | 7 | 3 |

**Consideraciones sobre la estimación de la talla:**

* La secuencia de Fibonacci se utiliza para reflejar la incertidumbre inherente a la estimación del esfuerzo. A medida que las tareas son más grandes, la incertidumbre aumenta, y la diferencia entre los valores de la secuencia también aumenta.
* La estimación de la talla es una actividad colaborativa que debe involucrar al equipo técnico.
* Es importante revisar y ajustar las estimaciones a medida que se avanza en el desarrollo y se obtiene más información.

Con esta información adicional, el equipo técnico puede planificar mejor los sprints y gestionar el desarrollo de forma más eficiente.

