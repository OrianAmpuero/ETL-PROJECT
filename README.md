![Ironhack logo](https://i.imgur.com/1QgrNNw.png) 
# PROYECTO ETL:pushpin:
Tercer proyecto como Data Analyst en [Ironhack](https://www.ironhack.com/):snake:. 
    Aplicar ETL sobre un tema de elección personal y según ciertos requisitos:
    1.Extraer datos
    2.Limpieza y análisis de los datos.
    3.Crear base de datos SQL relacional.
    4.Presentar resultados.

---
# Vinos de España:wine_glass:
![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/wines.jpg)
La calidad del vino en España según usuarios, mediante un ranking que valora su experiencia por olor, cuerpo y acidez mientras degustaban de diversos tipos en las diferentes regiones y bodegas del pais; además de un top 25 en las mejores selecciones de vino por James Suckling.
![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/mapa%20de%20vino.jpg)

<b> Herramientas para este proyecto🛠: Workbench, Jupyter Notebook, Python, Pandas, Selenium.</b>

---

## Extracción:heavy_check_mark:
Se extrajó información sobre el vino de España desde tres fuentes diferentes y usando dos métodos (Web Scraping con Selenium y CSV)

## Transformación:heavy_check_mark:
Se eliminaron las columnas innecesarias como por ejemplo la de pais en la tabla principal ya que solo estamos analizando los vinos de España, se cambió el tipo de datos de alguna de ellas para que estuviera correctamente.....

## Carga de Datos:heavy_check_mark:
Se creó una base de datos desde Jupyter Notebook para Workbech, luego la relación de entidades de cada tabla en un esquema...


---


## VISUALIZACIÓN:dart:

![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/top%2020%20bodegas%20por%20numero%20total%20de%20vinos.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/top%2020%20bodegas%20por%20precio%20medio.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/top%2020%20regiones%20por%20precio%20promedio.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/tipo%20de%20vino%20-%20precio%20medio.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/tipo%20de%20vino%20-%20opini%C3%B3n%20usuario.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/precio%20de%20vino%20-%20a%C3%B1o%20que%20se%20recolect%C3%B3%20uva.jpg)


![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/tipo%20de%20vino%20-%20precio.jpg)



![Image](https://github.com/OrianAmpuero/PROJECT-3/blob/main/IMAGES/precio%20-%20puntaje%20del%20usuario.jpg)



### Fuente de los Datos:computer:

[Dataset Kaggle](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)

[Top100 Vinos](https://www.bdelvino.com/2019/12/10/top-100-espana-james-suckling/)