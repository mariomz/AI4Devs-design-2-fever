Gemini Advanced
Cojo prestada la parte 1 de Skye para hacer esta parte 2. 

--- Prompt 1 ----

Guarda esta documentación en contexto: (le he pasado el contenido de [LIT-SGB-prestado-para-la-parte-2.md](LIT-SGB-prestado-para-la-parte-2.md))

--- Prompt 2 ----

# Objetivo principal

Teniendo en cuenta la información anterior, como un product manager senior, quiero que me generes todas las User Stories necesarias para llevar a cabo el módulo del Servicio de Gestión de Ofertas de Empleo.


# Información extra

Genera estas user stories utilizando todo el conocimiento que tengas de buenas prácticas, como las descritas cuando te preguntan qué es una user story en el contexto del desarrollo de software. No hace falta que cada user story saque en su primera iteración la versión óptima de la parte que estemos desarrollando. Podemos generar varias user stories sobre la misma funcionalidad siempre y cuando entreguemos valor al usuario final desde la primera.


# Plantilla de apoyo

Las user stories deberán seguir la siguiente plantilla:


Título de la Historia de Usuario:

Como [rol del usuario],

quiero [acción que desea realizar el usuario],

para que [beneficio que espera obtener el usuario].

Criterios de Aceptación:


[Detalle específico de funcionalidad]

[Detalle específico de funcionalidad]

[Detalle específico de funcionalidad]

Notas Adicionales:

[Cualquier consideración adicional]

Historias de Usuario Relacionadas:


[Relaciones con otras historias de usuario]

--- Prompt 3 ----

Ahora como Product Manager y Business Analyst experto en el mercado de plataformas de gestión de recursos humanos, quiero que me generes el backlog de producto de la compañía a partir de las user stories anteriores.

Las tareas del backlog deberán ser clasificadas de acuerdo a los diferentes criterios que consideres oportunos. Además, si hay dependencias entre ellas esto debería ser tenido en cuenta.

En la tabla debería haber al menos las siguientes columnas
* El título de la tarea
* Una columna por cada criterio de priorización
* Una columna final de tipo entero con la prioridad agregada

Finalmente ordena los resultados por el orden en que deberían llevarse a cabo estas user stories, teniendo en cuenta tanto la prioridad como las dependencias.


---- Prompt 4 ----

# Objetivo principal
Como arquitecto de software y con la ayuda de la información provista en las user stories generadas con anterioridad.

Queremos realizar el desglose en tareas técnicas a bajo nivel de la user story de "Publicar Oferta de Empleo en Portales Externos".

Estas deberían seguir el "Ejemplo de tarea" del siguiente bloque.

# Ejemplo de tarea

Título: Implementación de Autenticación de Dos Factores (2FA)

Descripción: Añadir autenticación de dos factores para mejorar la seguridad del login de usuarios. Debe soportar aplicaciones de autenticación como Authenticator y mensajes SMS.

Criterios de Aceptación:

Los usuarios pueden seleccionar 2FA desde su perfil.
Soporte para Google Authenticator y SMS.
Los usuarios deben confirmar el dispositivo 2FA durante la configuración.
Prioridad: Alta

Estimación: 8 puntos de historia

Asignado a: Equipo de Backend

Etiquetas: Seguridad, Backend, Sprint 10

Comentarios: Verificar la compatibilidad con la base de usuarios internacionales para el envío de SMS.


---- Prompt 5 ----

Ahora, en la tabla del backlog de tareas, añade una columna adicional llamada talla, y puntúa con la sucesión de fibonacci (hasta 21) las tareas como lo haría el equipo técnico de cara a un desarrollo agile por sprints.


