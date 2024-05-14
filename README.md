# 3D-scanner
## Introducción

Este proyecto consiste en la generación de modelos 3D a partir del procesamiento de las imágenes tomadas de una figura desde distintas posiciones. El procesamiento está construido a partir de la colocación de las siluetas generadas en planos de proyección para que esas proyecciones se intercepten entre sí, obteniendo así una aproximación del mallado 3D de la figura.

## Manual de Usuario
### Estructura de Carpetas
**Carpeta principal:**
- **MISC**: Carpeta en la que se ha experimentado y desarrollado el código, dividido en los distintos pasos del algoritmo:
  - **1-camera-calibration**: Aquí se encuentra todo lo usado para la construcción de la calibración de la cámara. Contiene:
    - **img**: Carpeta con las imágenes utilizadas
    - **demo.ipynb**: Código de la calibración de la cámara.
  - **2-camera-position**:
    - **functions.ipynb:** Código con el que se ha estado trabajando y experimentando durante la obtención de la rotación y posición de la cámara.
    - **Posición.ipynb:** Código con el que se realizaron experimentaciones más detalladas de este paso.
  - **3-silhouettes**: Todo lo usado para la construcción de la generación de las siluetas. Contiene:
    - **Photos**: Imágenes genéricas para las experimentaciones.
    - **vistas**: Contiene 3 imágenes de una figura real para la experimentación.
    - **Tazas**: Imágenes de tazas para las experimentaciones de figuras con agujeros.
    - **GetSilhouettes.ipynb**: Código con el que se ha estado experimentando y desarrollando la generación de siluetas.
  - **4-visual-hull:**
- **MVP**: Carpeta en la que se encuentra todo el código asociado al Mínimo Producto Viable del proyecto, en el que se proporciona el código final del proyecto. Dentro de esto contiene:
  - **img**: Imágenes reales tomadas sobre un cubo de Rubik
  - **3d-scanner.ipynb**: Código del MVP.
