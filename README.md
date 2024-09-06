# Shopping Prediction - K-Nearest Neighbors Model

Este proyecto utiliza un modelo de **k-Nearest Neighbors (k-NN)** para predecir si un usuario realizará una compra basándose en su actividad en un sitio web. Los datos provienen de un archivo CSV que contiene características como la duración de la visita, las páginas vistas, el tipo de visitante y otros factores que influyen en la probabilidad de compra.

## Características

- **Modelo K-Nearest Neighbors**: Utiliza el algoritmo k-NN con `k=1` para hacer predicciones.
- **Evaluación de sensibilidad y especificidad**: El rendimiento del modelo se evalúa mediante estas métricas, permitiendo conocer la eficacia del modelo en clasificar compradores y no compradores.
- **Datos de comportamiento de los usuarios**: Utiliza diversas características de navegación del usuario en el sitio web para predecir si completará una compra o no.
  
## Requisitos

Para ejecutar este proyecto, necesitarás:

- Python 3.x
- Paquetes de Python: `scikit-learn`

Puedes instalar las dependencias necesarias con el siguiente comando:

```bash
pip install -r requirements.txt
