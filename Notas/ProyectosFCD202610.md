# **Proyectos Feria de Ciencias (Machine Learning 2026-10)**

## I. Presentación general de los proyectos

Los proyectos de la Feria de Ciencias de Datos del curso de Machine Learning están diseñados como experiencias integrales de aprendizaje en las que los estudiantes desarrollan, de principio a fin, un sistema de aprendizaje automático aplicado a un problema del mundo real. Más allá del uso de modelos, el énfasis está en comprender y construir todo el proceso que transforma un fenómeno observable en una predicción cuantificable.

## II. Idea central de los proyectos

La idea fundamental de estos proyectos es que los estudiantes no trabajen con datasets preexistentes, sino que diseñen y construyan sus propios conjuntos de datos. Esto implica decidir qué medir, cómo medirlo, bajo qué condiciones y con qué nivel de precisión. En este proceso, los estudiantes enfrentan directamente los desafíos reales de la recolección de datos: ruido, sesgos, variabilidad, limitaciones instrumentales y decisiones de diseño experimental.
Cada proyecto parte de una pregunta concreta —por ejemplo, reconocer un objeto, clasificar un sonido o predecir una condición— y la convierte en un problema de aprendizaje automático mediante la construcción deliberada de representaciones (features) a partir de datos recolectados por los propios estudiantes.

## III. Objetivo general

El objetivo general es que los estudiantes desarrollen una comprensión profunda y práctica del pipeline completo de Machine Learning: (i) Formulación del problema, (ii) Diseño del experimento y recolección de datos, (iii) Construcción y curaduría del dataset, (iv) Ingeniería de características, (v) Entrenamiento y evaluación de modelos, (vi) Interpretación de resultados
Implementación de una aplicación demostrativa.

Se busca que los estudiantes no solo logren modelos con buen desempeño, sino que comprendan críticamente las decisiones tomadas en cada etapa y sus implicaciones.

## IV. Construcción de datos propios

Un componente central del curso es la creación de datos desde cero. Esto implica que cada grupo debe diseñar su propio proceso de medición, definir sus variables y recolectar observaciones de manera sistemática. El objetivo no es únicamente obtener datos, sino reflexionar sobre:
- Qué se está midiendo realmente
- Qué información se pierde al representar un fenómeno
- Qué sesgos o limitaciones introduce el proceso de recolección
Este enfoque permite entender el aprendizaje automático no solo como modelado, sino como una forma de construir conocimiento a partir de observaciones imperfectas.

## V. Desarrollo de aplicaciones y demostración en vivo

Cada proyecto debe culminar en el desarrollo de una aplicación funcional que permita demostrar el modelo en tiempo real durante la feria. Esta aplicación puede ser una interfaz sencilla (en computador o dispositivo móvil) que reciba nuevas entradas —imagen, sonido, datos manuales— y produzca una predicción en vivo. La demostración es un componente esencial: el modelo debe enfrentarse a datos no vistos en condiciones reales, evidenciando tanto sus capacidades como sus limitaciones. Se busca que el proyecto sea interactivo, comprensible y atractivo para el público.

## VI. Trabajo “con las manos”: el pipeline completo

Los proyectos están concebidos bajo la filosofía de “hacer desde cero”. Esto implica que los estudiantes participan activamente en todas las etapas del proceso, evitando depender exclusivamente de soluciones preempaquetadas o datasets estándar.
El énfasis está en:
- experimentar, medir y construir,
- tomar decisiones informadas,
- equivocarse y refinar el proceso,
- entender el vínculo entre fenómeno físico, datos y modelo.
Este enfoque busca desarrollar una comprensión más profunda, crítica y aplicada del Machine Learning.

## VII. Póster científico y presentación en la feria

Cada grupo deberá presentar su proyecto mediante un póster científico en formato estándar, con diseño libre pero visualmente claro, atractivo y bien estructurado. El póster debe comunicar de manera efectiva la historia del proyecto: el problema, la forma en que se construyeron los datos, el modelo utilizado, los resultados obtenidos y las principales conclusiones.
Se espera especial cuidado en el storytelling: el póster debe guiar al espectador de forma natural, resaltando la motivación, las decisiones clave y los aprendizajes del proceso. Durante la feria, el póster se complementará con una demostración en vivo, permitiendo una experiencia completa que combine explicación, evidencia visual e interacción directa con el modelo desarrollado.

# **PROYECTOS Propuestos (pueden haber más o pueden sugerir otros)**

| N | Nombre | Observaciones |
|---|---:|---|
| 1. | **Clasificación de billetes colombianos por denominación** | **Descripción**: Este proyecto busca construir un sistema de clasificación automática de billetes colombianos a partir de imágenes capturadas en condiciones reales, incluyendo variaciones de iluminación, desgaste y arrugas. **Objetivo**: Desarrollar un modelo que identifique correctamente la denominación del billete y analizar el impacto del deterioro físico en el desempeño del modelo. **Features**: Textura (GLCM), entropía, histogramas de color, transformadas de Fourier (FFT). **Modelo**: Clasificación multiclase (por ejemplo: k-NN, SVM, Random Forest). **Aplicación relevante**: Reconocimiento automático en contextos financieros y análisis del efecto del ruido físico en sistemas de visión. |
| 2. | **Clasificación de monedas colombianas por denominación** | **Descripción**:: Sistema de clasificación de monedas basado en imágenes, considerando variaciones de brillo, desgaste y condiciones de captura. **Objetivo**:: Clasificar monedas según su denominación utilizando imágenes recolectadas por los estudiantes. **Features**:: Histogramas de intensidad, textura, detección de bordes, características de forma y FFT. **Modelo**:: Clasificación multiclase. **Aplicación relevante**:: Automatización de conteo de monedas y sistemas de reconocimiento en dispositivos embebidos. |
| 3. | **Identificación de superficies por sonido** | **Descripción**:: Clasificación de materiales a partir del sonido producido al golpearlos. **Objetivo**:: Determinar el tipo de superficie (madera, metal, vidrio, concreto, etc.) usando características acústicas. **Features**:: MFCC, energía de la señal, espectro de frecuencia. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Reconocimiento de materiales en robótica e inspección no invasiva.|
| 4. | **Clasificación de frutas por madurez** | **Descripción**:: Análisis visual de frutas a lo largo del tiempo para determinar su estado de maduración. **Objetivo**: Clasificar el nivel de madurez (verde, intermedio, maduro). **Features**:: Color en espacio HSV, textura, brillo. **Modelo**:: Clasificación ordinal o multiclase. **Aplicación relevante**:: Control de calidad en alimentos y optimización de cadenas de suministro. |
| 5. | **Identificación de género musical** | **Descripción**:: Clasificación automática de géneros musicales a partir de señales de audio. **Objetivo**:: Determinar el género de una pista utilizando características espectrales. **Features**:: MFCC, energía, espectro de frecuencia. **Modelo**:: Clasificación multiclase. **Aplicación relevante**:: Sistemas de recomendación musical y organización automática de bibliotecas de audio. |
| 6. | **Clasificación de tipos de rocas por imagen** | **Descripción**:: Clasificación de rocas utilizando propiedades visuales observables en imágenes. **Objetivo**:: Identificar el tipo de roca a partir de imágenes recolectadas por los estudiantes. **Features**:: Textura, granulometría (FFT), color. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Geología aplicada y clasificación automática de materiales naturales. |
| 7. | **Clasificación de estados de ánimo por voz (controlado)** | **Descripción**:: Análisis de señales de voz bajo condiciones controladas para identificar variaciones en el tono. **Objetivo**:: Clasificar estados de voz (neutral, feliz, serio, eufórico, etc.) desde una perspectiva acústica. **Features**:: Pitch, energía, MFCC. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Interfaces de interacción humano-computador y análisis de señales de voz. |
| 8. | **Clasificación de objetos por sonido al caer** | **Descripción**:: Clasificación de objetos a partir del sonido que producen al impactar una superficie. **Objetivo**:: Identificar el tipo de objeto (llaves, monedas, libros, etc.) usando señales acústicas. **Features**:: Espectro de frecuencia, duración del sonido, energía. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Reconocimiento acústico de objetos en entornos inteligentes. |
| 9. | **Clasificación de tipos de nubes** | **Descripción**:: Clasificación de nubes utilizando imágenes capturadas localmente o recolectadas por los estudiantes. **Objetivo**:: Identificar diferentes tipos de nubes a partir de sus patrones visuales. **Features**:: Textura, color, patrones espaciales. **Modelo**:: Clasificación multiclase. **Aplicación relevante**:: Apoyo a observación meteorológica y análisis climático básico. |
| 10. | **Clasificación de calidad de conexión WiFi en la UTB** | **Descripción**:: Evaluación y modelado de la calidad de conexión WiFi en distintos puntos del campus. **Objetivo**:: Predecir la calidad de conexión (buena, media, baja) a partir de variables contextuales. **Features**:: Ubicación, hora del día, día de la semana, obstáculos, mediciones de velocidad y latencia. **Modelo**:: Clasificación o regresión. **Aplicación relevante**:: Optimización de infraestructura de red y análisis de cobertura. |
| 11. | **Clasificación de tipos de empaques** | **Descripción**:: Clasificación de materiales de empaques a partir de imágenes tomadas en el entorno cotidiano. **Objetivo**:: Identificar si un empaque es plástico, papel o metal. **Features**:: Color, textura, características superficiales. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Sistemas de reciclaje automatizado y separación de residuos. |
| 12. | **Clasificación de tipos de aplauso** | **Descripción**:: Análisis de señales acústicas para identificar distintos patrones de aplauso. **Objetivo**:: Clasificar tipos de aplauso (lento, rápido, intenso). **Features**:: Ritmo, energía, patrones temporales. **Modelo**:: Clasificación supervisada. **Aplicación relevante**:: Análisis de comportamiento colectivo y procesamiento de señales de audio. |




