# Modelos de Machine Learning aplicados a la clasificación de imágenes de vehículos

En este repositorio se encuentran los notebooks del trabajo realizado en la materia Modelos y Simulación de sistemas II, realizado por:
- Juan Esteban Salas Flórez
- Maria Camila Ramírez López
- Sebastián Suaréz Ramírez

Para ejecutar los notebooks primero:

Debes ejecutar balanceo_imagenes, se recomienda en local, para esto debes ingresar a Kaggle, obtener una KEY que permita utilizar su información, luego puedes ejecutar el notebook desde Visual Studio Code en local, primero te pedirá subir la Key, luego empieza a descargar el dataset para hacer los cambios, al correr todo en orden debe funcionar

Luego, debes ingresar a Kaggle y cargar el notebook clasificador_de_vehiculos, antes de ejecutar debes subir el dataset resultante del notebook anterior para su correcto funcionamiento, cuando esté cargado completamente puedes ejecutar todo en orden y debe funcionar

# balanceo_imagenes

En este notebook vas a encontrar la información del balanceo de las imagenes, para estofue descargado en local el dataset para poder modificarlo y subirlo a Kaggle Notebooks. 

Primero, se descarga el dataset y descomprime para poder trabajar sobre este, luego se muestra la distribucion de los datos y se toman decisiones sobre este
Segundo, se trabaja con sobremuestreo para crear nuevas imagenes a partir de las imagenes actuales del dataset
Tercer, se trabaja con submuestreo para borrar aleatoriamente la cantidad de imagenes que hay en el dataset, esto para las clases con muchos datos
Por ultimo, se imprimen las fotos de las imagenes que creamos, en algunas se pueden ver las imagenes que fueron creadas en este proceso, junto con las imagenes del dataset, con esto se nota la aleatoriedad.

Para saber mas, leer el documento del proyecto

# clasificador_de_vehiculos

En este notebook vas a encontrar la información de procesado de imagenes, creacion del modelo, entrenamientoy validación

Primero, se debe cargar el dataset creado por el notebook anterior, leer los pasos
Segundo, se define un datagen que permite reescalar las imagenes a conveniencia y asignar 80% para entrenamiento y 20% para validaciones
Tercero, se definen las metricas de validacion y se crea el modelo
Cuarto, se entrena el modelo, (se sugiere subir el notebook en kaggle para trabajar mas rapido)
Ultimo, se imprime la información de validaciones de desempeño, con unos test, la matriz de confusión, curva ROC, entre otros

Para saber mas, leer el documento del proyecto
