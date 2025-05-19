# Monografia_Proyeccion_Demanda-Precio
Repositorio para la monografía sobre la elasticidad precio de la demanda, incluyendo el análisis realizado con datos de papel higiénico utilizando el conjunto de datos Dominicks-Manual-and-Codebook_KiltsCenter y generación de datos sintéticos. El objetivo es comprender cómo los cambios en el precio afectan la demanda de ciertos productos.
Este repositorio contiene el código y los datos correspondientes a la monografía sobre la elasticidad precio de la demanda.

## Contenido

* `Monografia__Proyeccion_Demanda-Precio.ipynb`: El notebook de Jupyter con el análisis descriptivo y la preparación de los datos para un posterior modelado con ténicas de ML utilizando un conjunto de datos de una cadena de supermercados de Estados Unidos de America.
* `README.md`: Este archivo, que proporciona una descripción general del proyecto.
* `upctti.csv`: Este archivo contiene los datos maestros de las refernecias.
* `wtti.csv`: Este archivo contiene los datos de ventas, precios, promociones, tiendas y productos.
* `requirements.txt`: Archivo que lista las dependencias necesarias para ejecutar el notebook.

## Descripción del Proyecto

El presente trabajo de monografía tiene como objetivo analizar la elasticidad precio de la demanda de productos de papel higiénico (Bathroom Tissue) utilizando el conjunto de datos Dominicks-Manual-and-Codebook_KiltsCenter. Este dataset, proporcionado por el Kilts Center for Marketing de la Universidad de Chicago, contiene información real detallada sobre precios, volúmenes de venta y características de productos comercializados en la cadena de supermercados Dominick's.

Este notebook documenta el proceso completo del análisis, incluyendo la preparación y limpieza de los datos, la exploración inicial, 4 modelos de machine learning(Arboles de decisión, Random Forest, Moment T5,  feed-forward neural network) para predecir y analizar la elasticidad del precio basado en las promociones aplicadas, resultados y conclusiones. El objetivo es contribuir al entendimiento de las dinámicas de mercado de bienes de consumo masivo, para luego proponer su implementación en empresas del mercado Colombiano.

El dataset cuenta con 2 conjuntos de datos:
1. UPC (Universal product code) corresponde datos de información de los productos, códigos, descripción, tamaño.
2. Archivo de movimientos, contiene data de ventas semanales por UPC, semanas, precios, promociones, margen de ganancia, tienda, otros.
El análisis se realiza en un notebook de Jupyter  utilizando librerías de Python como pandas, numpy, matplotlib, seaborn y scikit-learn.

## Cómo utilizar

1.  **Clonar el repositorio:**
    ```bash
    git clone (https://github.com/LMelisaGaviria/Monografia_Proyeccion_Demanda-Precio.git)
    ```
2.  **Navegar al directorio del proyecto:**
    ```bash
    cd Monografia_Proyeccion_Demanda-Precio
    ```
3.  **Instalar las dependencias (opcional, si tienes `requirements.txt`):**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Abrir y ejecutar el notebook:**
    Puedes abrir `Monografia_Proyeccion_Demanda-Precio.ipynb` utilizando Jupyter Notebook o JupyterLab.

