# 🛍️ Saint Lux Store - Sistema de Ventas / Mini Tienda

**Proyecto:** Lenguaje Visual II (Python + Tkinter + SQLite)  
**Autor:** Santiago González  
**Institución:** Universidad del Norte – Sede Caacupé  
**Año:** 2025  

---

## 📖 Descripción del proyecto

Saint Lux Store es un sistema de ventas de escritorio desarrollado en Python utilizando la librería Tkinter para la interfaz gráfica y SQLite3 como base de datos local. El sistema permite gestionar productos, realizar ventas, llevar un historial detallado de transacciones y exportar la información a archivos CSV para análisis o respaldo.  

El objetivo de este proyecto es demostrar la aplicación práctica de los conocimientos adquiridos en Lenguaje Visual II, integrando conceptos de programación visual, diseño de interfaces, manejo de base de datos y buenas prácticas de software. Además, el proyecto busca ofrecer una experiencia de usuario intuitiva y moderna, acorde con la identidad de la marca Saint Lux.

Este proyecto representa la versión final, con mejoras y optimizaciones respecto a la demo inicial presentada durante el curso.

---

## ⚙️ Tecnologías utilizadas

- **Python 3.x**: lenguaje principal del proyecto.  
- **Tkinter**: para la creación de la interfaz gráfica.  
- **SQLite3**: base de datos local para persistencia de información.  
- **CSV**: exportación de datos de productos y ventas.  
- **ttk.Style / Themes**: personalización visual de la interfaz.  

---

## 🧩 Mejoras realizadas respecto a la demo

A diferencia de la demo inicial, en la versión final se implementaron las siguientes mejoras:

- **Login seguro**: ahora se requiere usuario y contraseña para acceder al sistema, mejorando la seguridad básica.  
- **Gestión de productos optimizada**:  
  - Corrección de errores al editar o agregar productos.  
  - Validaciones más robustas (nombre obligatorio, código único, precio y stock enteros).  
- **Formato de precios en Gs**: todas las cantidades ahora se muestran correctamente en Guaraníes (ej.: Gs 130.000).  
- **Punto de venta (carrito)**:  
  - Alertas de stock insuficiente.  
  - Confirmación de venta funciona correctamente, actualizando el stock y registrando la transacción.  
  - Total de la venta calculado correctamente y mostrado en la interfaz.  
- **Historial de ventas completo**:  
  - Registro detallado de todas las ventas con fecha, total y detalle de productos vendidos.  
  - Visualización de cada venta, incluyendo cantidad y precio unitario.  
- **Exportación a CSV mejorada**:  
  - Ahora el historial de ventas puede exportarse a CSV, mostrando todos los productos de cada venta correctamente.  
- **Interfaz visual mejorada**:  
  - Colores negro y dorado (#000000 y #D4AF37) para mantener identidad de marca.  
  - Diseño limpio, intuitivo y adaptado para pantallas grandes.  
  - Inclusión opcional de logo `saint_lux_logo.png`.  

---

## 💾 Base de datos

La base de datos `saintlux_store.db` se genera automáticamente al iniciar el sistema. Contiene las siguientes tablas:

- `users` → información de usuarios (para login).  
- `products` → detalles de productos disponibles (código, nombre, categoría, talla, precio, stock, fecha de creación).  
- `sales` → registro de ventas realizadas (total y fecha).  
- `sale_items` → productos incluidos en cada venta (cantidad y precio unitario).  

---

## 🧑‍💻 Autor

**Santiago González**  
Estudiante de Ingeniería en Informática  
📘 Universidad del Norte – Sede Caacupé  
🧩 Asignatura: Lenguaje Visual II  

---

## ⚠️ Requisitos

- Python 3.x  
- Librerías estándar: `tkinter`, `sqlite3`, `csv`, `datetime` 

## 🔖 Notas finales

Esta versión final integra todas las correcciones y mejoras detectadas durante la fase de demo, asegurando la correcta funcionalidad del sistema de ventas y la fidelidad de los datos registrados. Representa un proyecto completo de escritorio con base de datos, interfaz visual y gestión integral de ventas.
