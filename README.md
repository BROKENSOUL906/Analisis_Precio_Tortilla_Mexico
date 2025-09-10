# **Análisis del Precio de la Tortilla en México**

### 

##  **Por: Víctor Humarán Breceda**

## **1\. Resumen Ejecutivo**

Este documento presenta un análisis exploratorio del dataset de precios de la tortilla en México. Se identificó una tendencia de crecimiento constante en el precio promedio nacional a lo largo de los años. Además, se observaron diferencias significativas entre regiones, con precios más altos en los estados del norte (como Sonora) y más bajos en los del centro (como Tlaxcala). El análisis también mostró que los precios varían según el canal de venta, siendo generalmente más altos en las tiendas pequeñas que en los supermercados.

## **2\. Motivación y Objetivos del Proyecto**

El precio de la tortilla es un tema de interés nacional, ya que este alimento básico es un indicador crucial de la salud económica y el poder adquisitivo de los hogares mexicanos. Un aumento en su precio puede tener un impacto significativo en la economía familiar.

El objetivo principal de este proyecto es utilizar un enfoque de análisis exploratorio de datos (EDA) para entender el comportamiento de los precios de la tortilla en México. A través de este proceso, busco:

* **Aplicar mis conocimientos de Python** en un proyecto real.  
* **Aprender a limpiar y preparar datos** para su análisis.  
* **Desarrollar habilidades de visualización de datos** con librerías como Matplotlib y Seaborn.  
* **Documentar mi proceso** de manera profesional para un portafolio de proyectos.

## 

## **3\. Metodología**

El proyecto se dividió en varias fases, desde la limpieza y preparación de los datos hasta el análisis y la visualización.

### **3.1. Tecnologías y Librerías Utilizadas** 

Para el desarrollo de este proyecto se empleó **Python**, un lenguaje de programación ampliamente utilizado en el análisis de datos. Las siguientes librerías fueron fundamentales en cada etapa del proceso:

* **Pandas:** Se utilizó para la manipulación y limpieza de los datos. Nos permitió cargar el archivo CSV en un DataFrame, manejar valores faltantes y reestructurar los datos para el análisis temporal.  
* **Matplotlib:** Esta librería fue la base para la creación de los gráficos. Es una herramienta poderosa para generar visualizaciones estáticas.

Seaborn: Construida sobre Matplotlib, Seaborn nos permitió crear gráficos más estéticos y complejos de forma más sencilla, mejorando la calidad visual del análisis.

###  **3.2: Carga y Limpieza de Datos**

Para empezar, se cargó el archivo tortilla\_prices.csv en un DataFrame de Pandas. La inspección inicial reveló valores faltantes en la columna Price per kilogram. Se decidió eliminar estas filas, ya que representaban solo el 2.1% del total de los datos, evitando así cualquier sesgo en el análisis.


### **3.3: Preparación para el Análisis Temporal**

Para facilitar el análisis de tendencias a lo largo del tiempo, se combinaron las columnas Year, Month y Day en una sola columna de tipo datetime.

### 

### **3.4: Análisis y Visualización de Datos**

Utilizando las librerías Matplotlib y Seaborn, se crearon visualizaciones para responder a preguntas clave sobre los datos.

## 

## **4\. Análisis de Datos y Hallazgos Clave**

### **4.1. Tendencia General de Precios**

El análisis muestra una clara **tendencia al alza** en el precio promedio nacional de la tortilla desde 2007\. Este incremento constante puede estar relacionado con factores macroeconómicos, como la inflación y el aumento en el costo de la gasolina y el transporte.

### **4.2. Variaciones Regionales**

El precio de la tortilla no es uniforme en todo el país. Los datos revelan diferencias significativas entre estados. Los precios más altos se encontraron en los estados del norte, como Sonora y Baja California, mientras que los precios más bajos se registraron en los estados del centro, como Tlaxcala y Puebla.

### **4.3. Comparación de Canales de Venta** {#4.3.-comparación-de-canales-de-venta}

El análisis mostró una clara diferencia en el precio de la tortilla entre **tortillerías** y **tiendas de autoservicio (supermercados)**. Generalmente, el precio es más bajo en los supermercados, lo cual puede atribuirse a su capacidad de compra a gran escala y estrategias de precios para atraer clientes.

### 

## **6\. Conclusión**

El análisis del dataset de precios de la tortilla confirma que su precio ha aumentado constantemente en los últimos años, con una notable variación entre regiones y canales de venta. Este estudio sienta las bases para futuras investigaciones, como la correlación entre el precio de la tortilla y el costo del maíz, o el impacto de la sequía y las políticas de importación en su costo final. El precio de este alimento no es solo un número, es un reflejo de la compleja economía mexicana.

## **7\. Referencias**

* **Fuente del dataset: [Tortilla prices in Mexico](https://www.kaggle.com/datasets/richave/tortilla-prices-in-mexico)** disponible en Kaggle.  
