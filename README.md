
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/530addf8-1830-4a8f-8266-3bb5a81f63fe" />

---
# Implementación de una Red Neuronal Convolucional
---

Kevin Alejandro Ramírez Luna | A01711063@tec.mx | 13/11/2025


Repositorio de la evidencia realizada en la unidad de formación TC3006C.

>Estructura del Repositorio
> # Evidencia 1. Implementación de una Red Neuronal Convolucional
>---
>Resumen:
>
>* El archivo `cnn_micros.ipynb` cuenta con la implementación de una Red Neuronal Convolucional para el clasiifcado de MicroControladores usando PyTorch
>    * El archivo `test_cnn.ipynb` pone a prueba el modelo desarrollado en `cnn_micros.ipynb` con imagenes de test y métricas
>* La documeción con todo el desarrollo, detalles del dataset y modelado se puede observar en el archivo `Implementación de una Red Neuronal Convolucional.pdf`
>* El directorio `Otros` contiene imagenes e ilustraciones hechas en todo el proyecto
>
>
> --- 
> Archivos a encontrar con más detalle
> ---
>
> <img width="445" height="624" alt="image" src="https://github.com/user-attachments/assets/557f3f0b-ab50-4deb-abf8-9f470281fdbd" />
>
>> NOTA: Para transformar las imagenes se tiene que descargar el directorio de imagenes de Kaggle y pasarlo por `cnn_micros.ipynb`
> * Archive - Directorio con las imágenes de Kaggle. Descargar de [Kaggle](https://www.kaggle.com/datasets/frettapper/micropcb-images).
> * Dentro del directorio se tiene lo siguiente. La documentación con más detalle se puede ver en el mismo enlace compartido. A continuación se lista lo que contiene:
>    * test_coded es un directorio con imágenes de prueba de 13 diferentes clases de Micro´s
>    * train_coded es un directorio con imágenes para el entrenamiento del modelo. Con 13 diferentes clases de Micro´s
>    * archivos.csv son un conjunto de archivos csv que nos proporciona el autor del dataset - No útiles para nuestro objetivo principal.
>    * imagenes_procesadas es un directorio en el que estaremos organizando las imágenes transformadas por clase
>
> * Proyecto CNN - Directorio principal
>     * cnn_micros es un archivo de Google Colab con el proceso de exploración e implementación de nuestro modelo de Deep Learning
>     * test_cnn es un archivo de Google Colab en el que se evalúa y prueba el desempeño del modelo 
>     * best_model es un archivo de pytorch que contiene los mejores valores de pesos para nuestro modelo 
>     * checkpoint_epoch_n es un archivo de pytorch que contiene los mejores valores de los pesos en una época del entrenamiento del modelo 
>     * Implementación de una Red Neuronal Convolucional.pdf es el reporte
>  
> Adicionado a las carpetas principales del proyecto se deja el directorio `Otros/` con las imagenes que se usaron para la parte de prueba del archivo `test_cnn.ipynb` e ilustraciones realizadas para `Implementación de una Red Neuronal Convolucional.pdf`

