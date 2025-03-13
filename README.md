# ML_Tickets_cinema

## Descripción del Problema
En los últimos años, los cines tradicionales han enfrentado desafíos significativos debido al auge de las plataformas de streaming como Netflix y HBO, que han afectado la asistencia a los cines. Este proyecto tiene como objetivo analizar los datos de ventas de entradas de cine para comprender las tendencias, predecir las ventas futuras y explorar soluciones para aumentar la rentabilidad y competir con estas nuevas plataformas.

## Dataset
El conjunto de datos utilizado en este proyecto es `cinema_hall_ticket_sales_ampliado.csv`. Este conjunto de datos contiene información sobre las ventas de entradas de cine, incluidos los ID de los tickets, las edades de los compradores, los precios de las entradas, los géneros de las películas, los tipos de asientos, el número de personas y si volverían a comprar. Los datos abarcan desde 2010 hasta 2025, incluyendo el impacto de la pandemia de COVID-19 y el auge de las plataformas de streaming. El conjunto de datos es público y se puede acceder a él desde el repositorio del proyecto en el directorio `/src/data_sample`.

## Enfoque de la Solución
1. **Limpieza y Preprocesamiento de Datos**: Manejar valores faltantes, corregir tipos de datos y realizar ingeniería de características.
2. **Análisis Exploratorio de Datos (EDA)**: Analizar tendencias en ventas de entradas, géneros de películas, tipos de asientos y el impacto de factores externos.
3. **Modelos de Machine Learning**: Construir modelos de machine learning supervisados y no supervisados para predecir ventas de entradas y segmentar clientes.
4. **Recomendaciones**: Proponer soluciones como precios dinámicos, marketing dirigido y experiencias mejoradas en el cine para aumentar la asistencia y la rentabilidad.

            -------------------------------------------------------------------


# ML_Tickets_cinema

## Problem Statement
In recent years, traditional cinemas have faced significant challenges due to the rise of streaming platforms like Netflix and HBO, which have affected cinema attendance. This project aims to analyze cinema ticket sales data to understand trends, predict future sales, and explore solutions to increase profitability and compete with these new platforms.

## Dataset
The dataset used in this project is `cinema_hall_ticket_sales_ampliado.csv`. This dataset contains information about cinema ticket sales, including ticket IDs, ages of buyers, ticket prices, movie genres, seat types, number of persons, and whether they would purchase again. The data spans from 2010 to 2025, including the impact of the COVID-19 pandemic and the rise of streaming platforms. The dataset is public and can be accessed from the project repository in the `/src/data_sample` directory.

## Solution Approach
1. **Data Cleaning and Preprocessing**: Handle missing values, correct data types, and perform feature engineering.
2. **Exploratory Data Analysis (EDA)**: Analyze trends in ticket sales, movie genres, seat types, and the impact of external factors.
3. **Machine Learning Models**: Build supervised and unsupervised machine learning models to predict ticket sales and segment customers.
4. **Recommendations**: Propose solutions such as dynamic pricing, targeted marketing, and enhanced in-cinema experiences to increase attendance and profitability.


## Estructura del Repositorio
```plaintext
ML_Tickets_cinema/
├── src/
│   ├── data_sample/
│   │   └── cinema_hall_ticket_sales_ampliado.csv
│   ├── img/
│   ├── notebooks/
│   ├── results_notebook/
│   │   └── final_model_notebook.ipynb
│   ├── models/
│   └── utils/
├── README.md

