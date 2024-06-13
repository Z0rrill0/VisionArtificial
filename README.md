# VisionArtificial

## Objetivo del Script

El objetivo de este script es realizar operaciones básicas de procesamiento de imágenes utilizando la biblioteca OpenCV. El script carga una imagen, la convierte a escala de grises, detecta los bordes utilizando el algoritmo de Canny, y guarda la imagen resultante con los bordes detectados en un nuevo archivo. Además, el script muestra la imagen original, la imagen en escala de grises y la imagen con los bordes detectados en ventanas emergentes.

## Requisitos

- Python 3.x
- OpenCV (cv2)

## Instalación de OpenCV

Para instalar OpenCV, sigue estos pasos:

1. **Abre PyCharm**:
   - Abre PyCharm desde tu entorno de desarrollo.

2. **Abre la terminal de PyCharm**:
   - Ve a `View` > `Tool Windows` > `Terminal`.

3. **Instala OpenCV**:
   - Ejecuta el siguiente comando en la terminal de PyCharm:

     ```bash
     pip install opencv-python
     ```

   Esto instalará la biblioteca OpenCV en tu entorno de Python.

## Ejecución del Script

Sigue estos pasos para ejecutar el script:

1. **Clona o descarga el repositorio**:
   - Si tienes `git` instalado, clona el repositorio usando el siguiente comando en la terminal de PyCharm:

     ```bash
     git clone <URL_del_repositorio>
     ```

   - Alternativamente, descarga el archivo ZIP del repositorio y extráelo en tu máquina local.

2. **Abre el proyecto en PyCharm**:
   - Abre PyCharm y selecciona `File` > `Open`.
   - Navega hasta el directorio del proyecto clonado o descargado y ábrelo.

3. **Asegúrate de que la ruta de la imagen sea correcta**:
   - Abre el archivo `detect_objects.py` en PyCharm.
   - Reemplaza `'path_to_your_image.jpg'` con la ruta a una imagen existente en tu sistema.

4. **Ejecuta el script**:
   - Haz clic derecho en `detect_objects.py` en PyCharm y selecciona `Run 'detect_objects'`.

   Esto ejecutará el script y mostrará las imágenes en ventanas emergentes.

## Estructura del Código

El script `detect_objects.py` realiza las siguientes operaciones:

1. **Carga de la imagen**:
   ```python
   image_path = 'path_to_your_image.jpg'
   image = cv2.imread(image_path)

# VisionArtificial

## Imagen de Ejemplo

Aquí tienes una imagen de ejemplo que muestra el resultado de nuestro proyecto:

![Resultado del proyecto](imagen1.png)
![Resultado del proyecto](imagen2.png)
![Resultado del proyecto](imagen3.png)
![Resultado del proyecto](imagen4.png)