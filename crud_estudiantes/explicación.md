# CRUD de Estudiantes - POO + MVC

Proyecto de consola en Python para administrar estudiantes utilizando Programación Orientada a Objetos y el patrón MVC.

## Archivos

- `model.py`: clase `Estudiante`, validaciones y almacenamiento de datos.
- `view.py`: menú y entradas/salidas por consola.
- `controller.py`: conecta la vista con el modelo.
- `main.py`: inicia el programa.

## Datos del estudiante

- ID automático
- Cédula
- Nombres
- Apellidos
- Carrera
- Semestre
- Promedio
- Estado (Aprobado/Reprobado)

## Funciones

1. Registrar estudiante.
2. Listar estudiantes.
3. Buscar por ID.
4. Buscar por cédula.
5. Buscar por nombre o apellido.
6. Actualizar estudiante.
7. Eliminar estudiante.
8. Listar por carrera.
9. Mostrar aprobados.
10. Mostrar reprobados.

## Colecciones usadas

- `list`: almacenamiento principal.
- `dict`: índice por ID.
- `set`: control de cédulas únicas.
- `tuple`: resultados de consultas.

## Validaciones sencillas

- La cédula debe tener 10 números y no puede repetirse.
- Nombres, apellidos y carrera no pueden estar vacíos.
- El semestre debe estar entre 1 y 10.
- El promedio debe estar entre 0 y 10.
- Promedio mayor o igual a 7: APROBADO.

## Ejecutar

```bash
python main.py
```
