# reconocimiento-automático-de-placas-de-matrícula-python-yolov8

[Video utilizado para pruebas](https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/).

## modelos

Se utilizó un modelo preentrenado de Yolov8 para detectar vehículos.

Se empleó un detector de placas de matrícula para identificar las placas. El modelo fue entrenado con Yolov8 usando [este conjunto de datos](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/4) y siguiendo este [tutorial paso a paso sobre cómo entrenar un detector de objetos con Yolov8 en tus propios datos](https://github.com/computervisioneng/train-yolov8-custom-dataset-step-by-step-guide).

## dependencias

Es necesario descargar el módulo sort desde [este repositorio](https://github.com/abewley/sort) tal como se menciona en el [video](https://youtu.be/fyJB1t0o0ms?t=1120).
