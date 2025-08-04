# Análisis del mercado automotriz

## Ventas en India

### Para el siguiente análisis se descargó un csv de Kaggle el cual contiene 8 filas y 248 columnas. Entre ellas 370 filas vacías y nuestro objetivo es obtener los datos mediante KNN.

#### Iniciando nuestra carga de datos podemos ver que los datos se expresan en Lakh y Crore. 
Para su convergencia averiguamos qué: 
1 Lakh = 100.000 rupias
1 Crore = 10.000.000 de rupias
Considerando que el valor de 1 rupia equivale a 0.012 dólar, ya sabemos por cuanto multiplicar el valor de cada vehículo. --> valor del auto 869000 rupias * 0.012 = 10428 USD

#### Para manipular los datos utilizamos la librería Pandas y para manipular los números utilizamos Numpy.

#### Mediante la creación de funciones procedí a cambiar los nombres de las columnas, y a eliminar carácteres en formato texto para poder realizar promedios en mi análisis y así dejar el ETL completo cada columna con su formato.

## KNN

#### El uso de la librería s-klearn hizo que fuera mas fácil el procesamiento y escalamiento de los datos, que luego de escalarlos procedí a realizar la imputación.
#### Realizando estas técnicas mis datos quedaron como Array de Numpy con valores de entre 0 y 1, por lo cual tuve que desescalarlos para verlos en el formato requerido.
#### Por último asigné las columnas numéricas como decimales y creé un nuevo archivo .csv para poder utilizar algún editor de BI.

## Power BI

![Image](https://github.com/user-attachments/assets/1d1cb6d1-9c5f-4a6a-99c4-51dcc0866785)
