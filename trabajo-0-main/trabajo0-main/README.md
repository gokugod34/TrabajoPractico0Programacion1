# trabajo-programacion

# Informe 

## Encapsulamiento

Para aplicar el principio de encapsulamiento, declaré los atributos de las clases Estudiante, Carrera y Materia como privados. Luego, implementé métodos públicos get y set que permiten acceder y modificar esos valores de forma controlada, respetando buenas prácticas de diseño orientado a objetos.

## Relaciones entre clases

Establecí la relación entre Estudiante y Materia incorporando una lista de materias (List<Materia>) dentro de la clase Estudiante. Además, agregué métodos que permiten asignar materias al estudiante y calcular su promedio en base a las calificaciones.
Por otro lado, la clase Carrera contiene una lista de estudiantes (List<Estudiante>), junto con métodos para agregar nuevos estudiantes, listarlos y buscarlos por nombre y apellido. Esto permite gestionar fácilmente la información académica dentro de cada carrera.

## Validaciones en los setters

Incluí validaciones en los métodos setEdad y setPromedio de la clase Estudiante para asegurar que los datos ingresados sean coherentes:
En setEdad, se verifica que el valor ingresado sea mayor a 16 antes de asignarlo.
En setPromedio, se controla que el promedio esté dentro del rango permitido (0 a 10). Si el valor no cumple con esta condición, se muestra un mensaje indicando el error.