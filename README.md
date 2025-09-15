# 💊 Dataset Farmacéutico Colombia

Dataset de ejemplo relacionado con el sector farmacéutico, diseñado para ser utilizado en proyectos de **análisis de datos, visualización, inteligencia de negocios, estadística y aprendizaje automático**.

El objetivo de este repositorio es proporcionar un conjunto de datos que pueda ser utilizado libremente por estudiantes, desarrolladores, analistas y cualquier persona que quiera practicar con datos del sector farmacéutico.

## 📊 Descripción del dataset

El dataset contiene **5.075 registros y 33 variables** relacionadas con operaciones comerciales y de abastecimiento de productos farmacéuticos.

La información incluye aspectos como:

* Productos farmacéuticos
* Fabricantes
* Ventas
* Costos y utilidades
* Descuentos
* Inventario
* Tiempo de entrega
* Devoluciones
* Pacientes impactados
* Riesgo de desabastecimiento
* Regiones y ciudades
* Tipo de institución
* Canal de distribución
* Línea terapéutica
* Necesidad de receta médica

## 🗂️ Variables principales

| Variable                | Descripción                               |
| ----------------------- | ----------------------------------------- |
| `ID_Registro`           | Identificador único del registro          |
| `Fecha`                 | Fecha de la operación                     |
| `Año`                   | Año de la operación                       |
| `Mes`                   | Mes de la operación                       |
| `Trimestre`             | Trimestre correspondiente                 |
| `Región`                | Región de Colombia                        |
| `Ciudad`                | Ciudad asociada al registro               |
| `Tipo_Institución`      | Tipo de institución                       |
| `Institución`           | Institución o establecimiento             |
| `Canal`                 | Canal de distribución                     |
| `Línea_Terapéutica`     | Categoría terapéutica                     |
| `Producto`              | Producto farmacéutico                     |
| `Fabricante`            | Fabricante del producto                   |
| `Requiere_Receta`       | Indica si requiere receta                 |
| `Unidades`              | Cantidad de unidades                      |
| `Precio_Unitario_USD`   | Precio unitario                           |
| `Costo_Unitario_USD`    | Costo unitario                            |
| `Descuento_Pct`         | Porcentaje de descuento                   |
| `Lead_Time_Días`        | Tiempo de entrega                         |
| `Inventario_Días`       | Días de inventario disponibles            |
| `Devolución_Pct`        | Porcentaje de devoluciones                |
| `Pacientes_Impactados`  | Cantidad estimada de pacientes impactados |
| `Urgencia_Abasto`       | Nivel de urgencia de abastecimiento       |
| `Ventas_Brutas_USD`     | Ventas antes de descuentos                |
| `Monto_Descuento_USD`   | Valor del descuento                       |
| `Ventas_Netas_USD`      | Ventas después de descuentos              |
| `Costo_Total_USD`       | Costo total                               |
| `Utilidad_Bruta_USD`    | Utilidad bruta                            |
| `Margen_Bruto_Pct`      | Margen bruto                              |
| `Devoluciones_Unidades` | Número de unidades devueltas              |
| `Riesgo_Stockout`       | Indicador de riesgo de desabastecimiento  |

## 🚀 ¿Para qué puedes utilizar este dataset?

Este dataset puede utilizarse como material de práctica para diferentes proyectos, por ejemplo:

### 📈 Análisis de datos

* Analizar las ventas por región.
* Identificar los productos más vendidos.
* Comparar fabricantes.
* Analizar la rentabilidad de los productos.
* Estudiar los niveles de inventario.

### 📊 Visualización de datos

Puede utilizarse para crear dashboards y visualizaciones utilizando herramientas como:

* Power BI
* Tableau
* Excel
* Python
* R

### 🐍 Python

También puede utilizarse para practicar librerías como:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### 🤖 Machine Learning

El dataset también puede servir como punto de partida para proyectos académicos de aprendizaje automático, por ejemplo:

* Predicción del riesgo de desabastecimiento.
* Análisis de patrones de ventas.
* Clasificación de niveles de urgencia.
* Análisis de rentabilidad.
* Exploración de variables relacionadas con el inventario.

## 📥 Uso

Puedes descargar el archivo `dataset_farmaceutico.csv` y utilizarlo en tus propios proyectos.

Ejemplo utilizando Python:

```python
import pandas as pd

df = pd.read_csv("dataset_farmaceutico.csv", sep=";", decimal=",")

print(df.head())
print(df.info())
```

## ⚠️ Importante

Este dataset tiene fines **educativos y de práctica**. Los datos no deben interpretarse como información oficial, clínica, financiera o comercial de una institución farmacéutica real.

No debe utilizarse para tomar decisiones médicas, clínicas o de abastecimiento reales.

## 🤝 Contribuciones

Si quieres mejorar este proyecto, puedes contribuir mediante:

1. Fork del repositorio.
2. Creación de una nueva rama.
3. Realización de los cambios.
4. Creación de un Pull Request.

Las contribuciones relacionadas con análisis, visualizaciones, documentación y ejemplos de uso son bienvenidas.

## 📄 Licencia

Este proyecto puede distribuirse bajo una licencia abierta que permita su uso, modificación y redistribución.

Consulta el archivo `LICENSE` para conocer las condiciones de uso.

---

**Si este dataset te resulta útil para aprender o desarrollar un proyecto, puedes darle ⭐ al repositorio.**
