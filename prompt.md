# Prompt 0
Basado en los dos casos de usos principales: Crear puesto de trabajo (MVP) y Agendar entrevistas (MVP), genera dos historias de usuario para cada uno, considerando diferentes tipos de usuarios y sus necesidades.


# Prompt 1
Convierte la siguiente estructura de una user story en una plantilla en .md 

Título de la Historia de Usuario: 
1. Como [rol del usuario],
2. quiero [acción que desea realizar el usuario],
3. para que [beneficio que espera obtener el usuario].
Criterios de Aceptación:
1. [Detalle específico de funcionalidad]
2. [Detalle específico de funcionalidad]
3. [Detalle específico de funcionalidad]
Notas Adicionales:
* [Cualquier consideración adicional]
Historias de Usuario Relacionadas:
	•	[Relaciones con otras historias de usuario]

# Prompt 2

res un product owner experimentado en sistemas ATS, estructura cada historia de usuario que definiste en esta plantilla :
[RESULTADO ANTERIOR]
dame cada historia resultante en formato markdown también.

# Prompt 3
Estos 4 historias de usuario constituyen nuestro producto backlog, estima por cada item en el backlog (genera una tabla markdown):
* Impacto en el usuario y valor del negocio. ponderación 4
* Urgencia basada en tendencias del mercado y feedback de usuarios. ponderación 3
* Complejidad y esfuerzo estimado de implementación. ponderación 2
* Riesgos y dependencias entre tareas. ponderación 1,  

cada columna tiene una  ponderación, califica cada aspecto como alto (3), medio (2) o bajo (1), dependiendo de la ponderación dela columna y la calificación prioriza cada historia de usuario en una columna final.

# Prompt 5
Vamos a trabajar en la historia de usuario "Crear puesto de trabajo (Reclutador)", eres el producto owner y debes pensar en el ticket o los tickets de trabajo que se necesitan para implementar la historia de usuario, dame por ahora en formato md titulo de el o los tickets de trabajo y su descripción, necesito decidir si es realmente lo que necesito implementar antes de refinarlos, cada ticket debe contar con Pruebas e implementación de controles de calidad


# Prompt 5
Estoy de acuerdo con los tickets de trabajo que propones, ahora a las descripciones establecidas para cada ticket de trabajo, aplácales el template para dar mayor detalle a los desarrolladores para que implementen las funcionalidades.
[ESTRUCTURA DE TICKET DE TRABAJO]

**Aclaración** Tuve que refinar la estructura del [ESTRUCTURA DE TICKET DE TRABAJO] con la siguiente información  en la descrición

* si requiere crear campos de base de datos defínelos con su nombre y tipo de dato
* si requiere crear endpoints define el nombre el method, url, parametros, y todo lo que el desarrollador necesite para crearlo.
* Si requiere hacer frontend, Define la ruta dentro de la navegación del frontend en la que va ubicar la funcionalidad.

Ya que sin esto la información  que arrojaba en los tickets era muy vacía y ambigua para el desarrollador. 
