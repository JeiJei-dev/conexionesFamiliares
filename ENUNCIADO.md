# conexionesFamiliares BASES DE DATOS BASADAS EN GRAFOS
## Enunciado

**Para ello se trabajará con Neo4j y Python para elaboración de la aplicación (Frontend-Backend):**

Los grupos deberán elaborar un Proyecto sobre una aplicación que soporte la base de datos Neo4j, que permita crear un árbol genealógico de al menos 3 niveles.

Cada integrante de equipo deberá aportar su árbol genealógico y unirlos con la relación ”amigo_de” los nodos de los alumnos, formando así una red o malla de nodos.

A continuación, se detallan las características que deben cumplir tanto los nodos como las relaciones:

### Requerimientos mínimos de desarrollo del Proyecto:
- Cada árbol debe tener al menos 25 nodos.
- Las relaciones y atributos mínimos de las mismas, utilizadas para unir los nodos deberán incluir al menos las siguientes:
  - Amigo_de | Atributos fecha_ini
  - Padre_de | Atributos fecha_ini
  - Casado_con/conviviente | Atributos: fecha_ini, fecha_fin(si corresponde)

- Los tipos de nodos y atributos mínimos de los mismos deben ser al menos:
  - Hombre | Atributo: nombre, edad, actividad, gusto1, gusto2, disgusto, defunción (Si corresponde)
  -Mujer | Atributo: nombre, edad, actividad, gusto1, gusto2, disgusto, defunción (Si corresponde)

- La lista de gusto/disgusto a utilizar es la siguiente:
  - Música 
  - Futbol
  - Béisbol
  - Volibol
  - Películas
  - Tecnologías
  - Viajar
  - Leer
  - Autos
  - Motos
  - Gatos
  - Perros
  - Naturaleza
  - Moda

- La lista de actividad es la siguiente:
  - Profesor
  - Ingeniero
  - Militar
  - Psicólogo
  - Estudiante
  - Abogado
  - Médico
  - Veterinario
  - Otros (No especificar)

Los alumnos deben experimentar con la red o malla de nodos, realizando consultas en base a las relaciones que existen entre los nodos y sus atributos. Algunas consultas que pueden poner en prácticas:

- Todas las personas que sean estudiantes.
- Primos que poseen – los amigos de alumnoA
- Persona a menos saltos que comparta algún gusto con el padre de alumnoA
- Persona a mayor distancia de alumnoA que comparta algún gusto, pero no le disguste algo de AlumnoA.
- Parientes que alumnoA podría presentarle a alumnoB según gustos y rango etario.
- Tíos masculinos de un amigo que le disgusten los gatos y sean veterinarios.
- Pariente vivo de mayor edad de cada alumno.

Además, permitirá agregar, eliminar y actualizar nodos de la base de datos.

El Proyecto incluye la elaboración de Informe en el que el equipo demuestre el aprendizajede los criterios anteriormente señalados.

Este Informe corresponderá al README de Github.
