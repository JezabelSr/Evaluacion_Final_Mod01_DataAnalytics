# Evaluacion_Final_Mod01_DataAnalytics

## 📋 Descripción

Este proyecto consiste en la crear de una clase `TiendaOnline` en Python que simula la gestión de un comercio online, incluyendo manejo de inventario, clientes, compras y pagos.

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Jupyter Notebook**

---


## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:

git clone https://github.com/tu_usuario/Evaluacion_Final_Mod01_DataAnalytics.git


2. Abre el notebook:

jupyter notebook Examen-Mod01_resuelto.ipynb


3. Ejecuta las celdas **en orden** de arriba a abajo.

---

## ⚙️ Funcionalidades

### Ejercicio 1 — Clase `TiendaOnline`

La clase `TiendaOnline` gestiona el inventario y las operaciones básicas de una tienda online.

**Atributos:**
- `inventario` — Lista de diccionarios con los productos disponibles
- `ventas_totales` — Registro acumulado de todas las ventas
- `clientes` — Diccionario con los clientes registrados

**Métodos:**


- `agregar_producto(nombre, precio, cantidad)` — Añade un producto o actualiza su cantidad si ya existe
- `ver_inventario()` — Muestra todos los productos con sus detalles
- `buscar_producto(nombre)` — Busca un producto por nombre y muestra sus detalles
- `actualizar_stock(nombre, cantidad)` — Actualiza el stock de un producto
- `eliminar_producto(nombre)` — Elimina un producto del inventario
- `calcular_valor_inventario()` — Calcula el valor total del inventario

---

### ⚡ BONUS — Gestión de clientes y compras

**Métodos**

- `agregar_cliente(nombre, email)` — Registra un nuevo cliente
- `ver_clientes()` — Muestra todos los clientes registrados
- `realizar_compra()` — Permite al cliente seleccionar productos y cantidades
- `registrar_compra(nombre_cliente, carrito)` — Registra la compra en el historial del cliente
- `ver_compras_cliente(nombre_cliente)` — Muestra el historial de compras de un cliente
- `calcular_ventas_totales()` — Muestra el total de ventas de la tienda
- `procesar_pago(total_compra)` — Procesa el pago y calcula el cambio

---

## 💡 Ejemplo de uso

```python
# Crear una instancia de la tienda
tienda = TiendaOnline()

# Añadir productos
tienda.agregar_producto("camisetas", 29.99, 100)
tienda.agregar_producto("funko", 18, 79)

# Ver inventario
tienda.ver_inventario()

# Registrar un cliente y realizar una compra
tienda.agregar_cliente("Pandora", "pandi@panditopia.com")
carrito = tienda.realizar_compra()
tienda.registrar_compra("Pandora", carrito)
```

---

## 👩‍💻 Autor

Desarrollado por **Jezabel Sanchez** como finalización del Modulo 1 de Data Analytics.

[🔗 Repositorio en GitHub](https://github.com/JezabelSr/Evaluacion_Final_Mod01_DataAnalytics)