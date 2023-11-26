# Proyecto : Modelos de aprendizaje automático que utilicen datos de emisiones de fuente abierta (de observaciones del satélite Sentinel-5P ) para predecir las emisiones de carbono.

## Miembros del grupo

Edwin David Duque Grajales cc. 1017255650 Ingenieria Ambiental

Peter Daniel Garrido Rodriguez cc. 1085952515 Ingenieria Industrial

Jheison Andres Benavides Rincon cc.1015466242 Ingenieria Civil

## Datos
Los datos del proyecto vienen de [Competición De Kaggle Predecir las emisiones de CO2 en Ruanda](https://www.kaggle.com/competitions/playground-series-s3e20/data) y se pueden hacer disponibles ejecutando desde cualquier notebook en Colab los siguientes comandos

En cada uno de los notebooks hay un titulo de 'cargar los archivos desde Kaggle', allí se importa la libreria opendatasets que permite abrir el dataset directamente sesde el kaggle, para ello se debe ingresar el usuario y clave del kaggle, el cual se obtiene creando un nuevo token en la parte de configuraciones del Kaggle, en donde se descargara un archivo JSON con el usuario y clave que se deben ingresar.

    ! !pip install opendatasets
    ! import opendatasets as od
    ! dataset_link="https://www.kaggle.com/competitions/playground-series-s3e20/data"od.download(dataset_link)
    ! import os
    ! os.chdir("playground-series-s3e20")
    ! os.listdir()
    ! d = pd.read_csv("train.csv")
    ! d.head()

## Videos

[Video segunda entrega](https://www.youtube.com/watch?v=YJWShZmztU4)

[Video entrega final](https://www.youtube.com/watch?v=YJWShZmztU4)
