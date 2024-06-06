# Crud_Estudiante
## Gestión de Estudiantes, Materias y Notas

Este proyecto en Python implementa un sistema de gestión de estudiantes, materias y notas. A través de un menú interactivo, permite agregar estudiantes y materias, registrar notas, y consultar diversas estadísticas relacionadas con los estudiantes y sus calificaciones.

### Funcionalidades

1. **Agregar Estudiante**: Permite registrar un nuevo estudiante con un código único y nombre.
2. **Agregar Materia**: Permite registrar una nueva materia con un código único y nombre.
3. **Agregar Nota**: Permite registrar una nota para un estudiante en una materia específica.
4. **Ver Promedio de Materias por Estudiante**: Calcula y muestra el promedio de notas de un estudiante.
5. **Ver Nota Mayor por Estudiante**: Muestra la nota más alta obtenida por un estudiante en todas sus materias.
6. **Ver Nota Menor por Materia**: Muestra la nota más baja registrada en una materia específica.
7. **Listar Estudiantes**: Muestra una lista de todos los estudiantes registrados.

### Estructura del Código

- **Variables Globales**:
  - `estudiantes`: Lista que almacena los códigos y nombres de los estudiantes.
  - `materias`: Lista que almacena los códigos y nombres de las materias.
  - `notas`: Lista que almacena las notas, cada entrada contiene el código del estudiante, el código de la materia y la nota.

- **Funciones Principales**:
  - `menu_principal()`: Muestra el menú principal.
  - `menu_agregar_estudiante()`: Registra un nuevo estudiante.
  - `menu_agregar_materia()`: Registra una nueva materia.
  - `menu_agregar_nota()`: Registra una nota para un estudiante en una materia.
  - `menu_ver_promedio_materias()`: Calcula y muestra el promedio de notas de un estudiante.
  - `menu_ver_nota_mayor()`: Muestra la nota más alta de un estudiante.
  - `menu_ver_nota_menor()`: Muestra la nota más baja en una materia específica.
  - `menu_listar_estudiantes()`: Muestra una lista de todos los estudiantes registrados.

### Uso

1. Ejecutar el script en un entorno de Python.
2. El menú principal se mostrará con las opciones disponibles.
3. Seleccione la opción deseada ingresando el número correspondiente.
4. Siga las instrucciones que aparecen en pantalla para ingresar los datos necesarios.
5. El programa continuará mostrando el menú principal después de completar cada operación.
6. Para salir del programa, seleccione la opción `0`.

### Ejecución

Para ejecutar el programa, simplemente corra el script en un intérprete de Python. Se mostrará el menú principal y podrá interactuar con el sistema siguiendo las instrucciones en pantalla.

```bash
python gestion_estudiantes.py
```

### Requisitos

- Python 3.x

### Notas

- Asegúrese de ingresar códigos únicos para estudiantes y materias para evitar errores.
- Los datos ingresados no se almacenan de manera persistente; se perderán al finalizar la ejecución del programa.

Este proyecto es una implementación básica para demostrar la gestión de estudiantes, materias y notas, y puede ser ampliado con características adicionales como almacenamiento persistente, interfaz gráfica de usuario, entre otros.
