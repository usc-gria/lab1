# LAB1: Creación de un Sistema Básico de Música en Streaming con Programación Funcional

## **Objetivos Generales**
1. Aplicar conceptos fundamentales de Python como listas, diccionarios, bucles y estructuras de control.
2. Introducir la programación funcional usando `filter`, `map` y `sorted` para realizar operaciones eficientes.
3. Diseñar un sistema modular y organizado para gestionar un sistema básico de música en streaming.

---

## **Actividades**

### **1. Creación del Catálogo de Canciones**
#### **Descripción:**
Se debe crear un catálogo de canciones usando una lista de diccionarios. Cada diccionario representa una canción con los siguientes atributos:

- `id`: Identificador único de la canción, auto-incrementado (primera canción id=1, segunda canción id=2...).
- `titulo`: Título de la canción.
- `artista`: Nombre del artista.
- `album`: Nombre del álbum.
- `duracion`: Duración de la canción en minutos (número flotante)
- `reproducciones`: Número total de reproducciones.


#### **Tareas:**
1. Crear una función `agregar_cancion (titulo, artista, album, duracion)` para añadir nuevas canciones al catálogo.
2. Crear una función `eliminar_cancion (id)` para eliminar canciones por su ID.
3. Crear una función `buscar_cancion (id)` para buscar canciones por ID.
4. Crear una función `buscar_cancion (titulo)` para buscar canción por título.
5. Crear una función `buscar_cancion (artista)` para buscar las canciones de un artísta.

---

### **2. Operaciones sobre el Catálogo de Canciones**
#### **Tareas:**
1. Crear una función `duracion_total_catalogo(catalogo)` que calcule la duración total de todas las canciones en el catálogo.
2. Crear una función `canciones_top_reproducciones(catalogo, n)` que devuelva las n canciones más reproducidas.
3. Crear una función `reproducir_cancion(catalogo, id_cancion)` que incremente en 1 el contador de reproducciones de una canción.

---

### **3. Programación Funcional**
Es obligatorio usar al menos una vez el operador `lambda`. Tienes ejemplos en el archivo `funcional_examples.md`

#### **Tareas:**
1. Crear una función `filtrar_canciones_por_duracion(catalogo, duracion_maxima)` que use `filter` para devolver las canciones con duración menor a `duracion_maxima`.
2. Crear una función `mapear_titulos_mayusculas(catalogo)` que use `map` para convertir los títulos de todas las canciones a mayúsculas.
3. Crear una función `ordenar_canciones_por_duracion(catalogo)` que use `sorted` para ordenar las canciones por duración.
4. Crear una función `filtros_compuestos(catalogo, duracion_maxima, artista)` que combine `filter` y `map` para devolver las canciones de un artista específico con duración menor a `duracion_maxima`.

---

### **4. Desafío Final**
#### **Descripción:**
Combinar todas las funcionalidades anteriores para crear un menú interactivo que permita al usuario:

1. Gestionar las canciones dentro del catálogo.
2. Consultar el catálogo.
3. Aplicar filtros funcionales al catálogo.

#### **Ejemplo de Menú:**
```python
while True:
    print("\nSistema de Música en Streaming")
    print("1. Gestionar Catálogo")
    print("2. Consultar Estadísticas")
    print("3. Aplicar Filtros")
    print("4. Salir")
    opcion = input("Seleccione una opción: ")

    if opcion == "1":
        # Llamar a funciones de gestión de catálogo
        pass
    elif opcion == "2":
        # Llamar a funciones de estadísticas
        pass
    elif opcion == "3":
        # Llamar a funciones de programación funcional
        pass
    elif opcion == "4":
        print("Saliendo del sistema.")
        break
    else:
        print("Opción inválida. Intente de nuevo.")
```

---

## **Entrega y Evaluación**

### **Criterios de Evaluación:**
1. **Estructura del Código:** Uso correcto de funciones, modularidad y claridad del código.
2. **Uso de Listas y Diccionarios:** Implementación correcta de las estructuras de datos.
3. **Programación Funcional:** Uso adecuado de `filter`, `map` y `sorted`.
4. **Interactividad:** Implementación de un menú funcional que integre todas las tareas.

### **Criterios específicos evaluables:**
- [ ] 

