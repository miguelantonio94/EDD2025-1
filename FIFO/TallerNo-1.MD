# Taller Retador: Manejo de Memoria Dinámica y Listas Enlazadas en C

## Objetivo del taller:
Aplicar estructuras dinámicas y manejo de memoria con `malloc` y `free`, a través del desarrollo de un sistema de gestión de elementos usando listas enlazadas simples.

---

## Contexto del reto:
Estás diseñando una aplicación para gestionar una lista de productos en una bodega. Cada producto se representa como un nodo en una lista enlazada. El sistema debe permitir al usuario **registrar, buscar, eliminar, mostrar y contar los productos registrados**.

---

## Requisitos del sistema:
1. **Agregar Producto**
   - Cada producto tiene: 
     - `ID` (int)
     - `Nombre` (string[30])

2. **Mostrar todos los productos**
   - Muestra `ID` y `Nombre` de cada producto.

3. **Buscar producto por ID**

4. **Eliminar producto por ID**
   - Liberar correctamente la memoria al eliminar.

5. **Contar productos registrados**

6. **Liberar memoria al salir del sistema**

---

## Extras (Retadores – Puntos extra si los implementan):
7. **Insertar producto en posición específica** (inicio, medio o final)
8. **Ordenar productos por ID** (usando intercambio de datos, no punteros)
9. **Modificar nombre del producto dado un ID**

---

## Restricciones:
- No usar `new`, `delete`, `std::vector` ni `std::string`.
- Solo trabajar con arreglos de caracteres (`char nombre[30]`).
- La memoria debe manejarse con `malloc` y `free`.

---

## Sugerencia de menú:
1. Agregar producto  
2. Mostrar productos  
3. Buscar producto  
4. Eliminar producto  
5. Contar productos  
6. Salir  

---

## Evaluación sugerida del taller (si lo usas en clase):
| **Criterio**                        | **Puntaje** |
|-------------------------------------|-------------|
| Implementación básica (1-5)         | 30 pts      |
| Uso correcto de `malloc` y `free`   | 20 pts      |
| Eliminación de nodo                 | 15 pts      |
| Extras (modificación, ordenamiento, etc) | 20 pts      |
| Buen manejo del código y comentarios| 15 pts      |
| **Total**                           | **100 pts** |



