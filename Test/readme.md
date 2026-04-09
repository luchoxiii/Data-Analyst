## Exámenes y Recursos

En esta sección del repositorio se encuentran disponibles distintos exámenes junto con sus respectivos enunciados y conjuntos de datos (*datasets*). En algunos casos, también se incluirán las resoluciones correspondientes, que serán subidas progresivamente.

---

### 📘 Examen 1

**Dataset:** `ubicaciones.csv`  
Este dataset contiene coordenadas de diferentes lugares de interés.

**Reglas:**
- Una zona se considera **comercial** si agrupa 8 o más lugares.
- Dos locales pertenecen a la misma zona si están a una distancia menor a **1.2 km**.

**Tareas:**
1. Crear **polígonos** que representen todas las zonas comerciales detectadas en el dataset.
2. Delimitar la **zona de influencia** de cada zona comercial. Esta comprende:
   - El interior del polígono.
   - Un radio adicional de **400 metros** desde los límites del polígono.
3. **Graficar en un mapa**:
   - Todos los comercios.
   - Las zonas de influencia comercial.

---

### 📘 Examen 2

![image](https://github.com/user-attachments/assets/e75fe838-12d9-4124-86fb-fce25af70ce7)


**Relaciones del modelo de datos:**
- Una **Persona** (`id`) puede tener muchas **Tarjetas** (relación por `id_titular`).
- Una **Compra** siempre se realiza con una única tarjeta.
- **(EXTRA)**: La tabla `Compra` contiene un histórico de más de 10 años y decenas de millones de registros, por lo que las consultas deben estar **optimizadas** para evitar largos tiempos de ejecución.

**Tarea:**
- Obtener los **números de tarjeta** que:
  - **No tengan consumos** en el último mes.
  - **Pertenecen a personas** que hayan realizado compras por un **mínimo total de $5000** en el último mes, en los rubros **FARMACIA** y **SUPERMERCADOS** en conjunto.

*(Si es posible, tener en cuenta el punto EXTRA mencionado previamente para mejorar la eficiencia de la consulta.)*


---

### 📘 Examen 3

Es un ejercicio teorico sobre analisis de datos & Powerbi, la notebook a hacer referencia es Ejercicio N2.

---

### 📘 Examen 4

Es un ejercicio practico, que el enunciado esta en Ejercicio N3, y el dataset son el csv: Productos.csv, Regiones.csv, Usuarios.csv y Ventas.csv.


---

### 📘 Examen 5

