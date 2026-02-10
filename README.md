# Image Contrast Enhancement using Histogram Equalization and CLAHE

Proyecto académico de **Procesamiento de Imágenes** enfocado en la mejora del contraste de imágenes digitales mediante técnicas de ecualización de histograma y CLAHE (Contrast Limited Adaptive Histogram Equalization).

El trabajo analiza imágenes con distintos niveles de contraste (bajo, normal y alto), evaluando visualmente y mediante histogramas los resultados obtenidos tras el procesamiento.

---

## Objetivo
Analizar y comparar el efecto de:
- **Ecualización de histograma tradicional**
- **CLAHE (Contrast Limited Adaptive Histogram Equalization)**

sobre imágenes en escala de grises, observando cómo se modifica la distribución de intensidades y el contraste general.

---

## Tecnologías utilizadas
- Python  
- OpenCV  
- NumPy  
- Matplotlib  

---

## Contenido del repositorio
- Notebook con el desarrollo completo del ejercicio
- Conversión de imágenes a escala de grises
- Aplicación de ecualización de histograma tradicional
- Aplicación de CLAHE
- Visualización de histogramas antes y después del procesamiento
- Comparación visual de resultados

---

## Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/image-contrast-histogram-clahe.git
2. Instalar las dependencias necesarias:
   pip install opencv-python numpy matplotlib
3. Abrir y ejecutar el notebook:
   jupyter notebook

 
 Descripción del análisis

Se trabajó con imágenes representativas de:

Bajo contraste

Contraste normal

Alto contraste

Para cada imagen se analizaron:

Imagen original

Imagen ecualizada

Histograma original

Histograma posterior al procesamiento

A partir de los resultados se observa que:

La ecualización de histograma tradicional mejora notablemente imágenes con bajo contraste, redistribuyendo las intensidades.

CLAHE permite un realce local del contraste, evitando en muchos casos la sobre-amplificación del ruido y preservando mejor los detalles.

 Aplicaciones

Procesamiento de imágenes médicas

Visión por computadora

Preprocesamiento de datos para modelos de Machine Learning

Mejora visual en fotografía digital

 Nota

Si GitHub no renderiza correctamente el notebook debido a su tamaño o a la cantidad de imágenes generadas, se recomienda descargar el archivo .ipynb y ejecutarlo localmente para una correcta visualización.


---

