# RecSysData

Este repositorio contiene los archivos y datos utilizados en el proyecto de sistemas de recomendación (RecSys). El objetivo del proyecto es desarrollar un sistema de recomendación utilizando datos de Goodreads.

## Contenidos del repositorio

- `Archivos finales/`: Carpeta que contiene los archivos finales del proyecto.
  - `all_reviews_df.csv`: Archivo CSV con todas las reseñas.
  - `book_id_map_10k.json`: Mapa de IDs de libros.
  - `test_w_title.csv`: Archivo CSV de prueba con títulos.
  - `train_w_title.csv`: Archivo CSV de entrenamiento con títulos.
  - `user_id_map_10k.json`: Mapa de IDs de usuarios.
- `dataset_names.csv`: Archivo CSV con los nombres de los datasets utilizados.
- `Multimodal.ipynb`: Notebook de Jupyter que contiene el código y análisis del proyecto.
- `.gitattributes`: Archivo de configuración de Git para el manejo de archivos grandes.
- `.gitignore`: Archivo de configuración de Git para ignorar archivos innecesarios.
- `README.md`: Este archivo, que describe el proyecto y el contenido del repositorio.

## Instrucciones

1. Clona el repositorio:
   ```sh
   git clone https://github.com/ssilvapinochet/RecSysData.git
   ```
2. Navega a la carpeta:
    ```sh
    cd RecSysData
    ```

## Requisitos

- Python 3.10 o superior
- Jupyter Notebook
- Bibliotecas de Python:
  - tensorflow (>=2.18.0)
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - tqdm
  - requests
  - keras-hub (>=0.18.1)
  - gzip
  - json

## Descripción del proyecto

El proyecto utiliza datos de Goodreads para desarrollar un sistema de recomendación. Los datos incluyen reseñas de libros, información de usuarios y libros, y otros metadatos relevantes. El notebook `Multimodal.ipynb` contiene el código para cargar, procesar y analizar los datos, así como para entrenar y evaluar modelos de recomendación.
