#  Challenge de Data Science con Python - Alura Store

Este repositorio contiene la resolución del challenge de Alura para el curso **Data Science: Python**, disponible en [este enlace](https://app.aluracursos.com/course/python-data-science-challenge-alura-store/task/90519).

---

##  Descripción

El desafío consiste en analizar los datos de ventas de cuatro tiendas distintas y determinar cuál de ellas representa la mejor opción para ser vendida, basándose en indicadores clave como:

- Ingresos totales por tienda  
- Productos y categorías más/menos vendidos  
- Calificación promedio de los clientes  
- Costos de envío (promedio y total)

---

##  Instrucciones de uso

Para ejecutar correctamente el análisis y generar los gráficos:

1. **Ejecuta primero las celdas de importación** para cargar las librerías necesarias (`pandas`, `matplotlib`, etc.).
2. Asegúrate de que los archivos de datos estén correctamente ubicados o cargados en el entorno.
3. Corre las celdas en orden lógico para evitar errores de contexto entre variables.

---

## Observaciones importantes

- **Posible defecto identificado**: al ejecutar todas las celdas de una vez (por ejemplo, con "Run All"), en ocasiones los gráficos de productos correspondientes a **Tienda1** y **Tienda4** muestran datos repetidos o incorrectos.

  - Si se ejecuta primero el gráfico de **Tienda4** y luego el de **Tienda1**, la información se presenta correctamente.
  - Aún no se ha identificado con certeza la causa del error. Se sospecha que puede estar relacionado con variables que no se actualizan correctamente entre celdas o un uso compartido del mismo `DataFrame` o figura de `matplotlib`.

- **Pendiente**: depurar y aislar el error que genera esta superposición de datos.
