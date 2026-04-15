# EVALUACION MODULO 1, DATA NALYTICS, INGRID ESPINEL

# Tienda Online en Python

Proyecto de evaluación desarrollado en Python con programación orientada a objetos.

---

## Descripción

Este proyecto simula la gestión básica de una tienda online mediante una clase principal llamada `TiendaOnline`.

La aplicación permite trabajar con:

- Inventario de productos  
- Control de stock  
- Búsqueda y eliminación de productos  
- Cálculo del valor total del inventario  
- Registro de clientes  
- Inicio de la lógica de compra como parte del bonus  

---

## Funcionalidades implementadas

- Agregar productos al inventario  
- Visualizar inventario  
- Buscar productos por nombre  
- Actualizar stock  
- Eliminar productos  
- Calcular el valor total del inventario  
- Registrar clientes  
- Mostrar clientes registrados  

---

## Bonus en desarrollo

Actualmente se ha comenzado la funcionalidad de `realizar_compra()`, incluyendo:

- Visualización de productos  
- Salida del proceso de compra  
- Primera lógica de selección de producto  

---

## Estructura del proyecto

El proyecto está construido a partir de una clase:

- `TiendaOnline`

Se utilizan las siguientes estructuras de datos:

- Listas para almacenar el inventario  
- Diccionarios para guardar la información de productos y clientes  

---

## Retos principales

Uno de los mayores retos fue diseñar correctamente la lógica para evitar duplicados en el inventario y actualizar cantidades cuando un producto ya existía.

Otro reto importante fue trabajar la lógica del flujo de compra, especialmente al mostrar productos al usuario sin que la experiencia resultara confusa dentro del `while`.

También fue clave controlar casos límite, como evitar que el stock quedara en negativo al actualizar cantidades.

---

## Aprendizajes

Con este proyecto he practicado:

- Clases y métodos  
- Uso de `for`, `if`, `else` y `break`  
- Listas y diccionarios  
- Validación de datos  
- Organización de la lógica paso a paso  

---

## Estado del proyecto

El proyecto se encuentra funcional en su parte principal y con la parte del bonus parcialmente avanzado.

---

## Próximos pasos

- Completar la lógica de compra  
- Registrar compras realizadas por cliente  
- Actualizar ventas totales automáticamente  

---

## Autoría

Proyecto de evaluación realizado por **Ingrid Espinel** como parte de su práctica y aprendizaje en Python.