
## Introducción

En la era de la economía digital, los datos se han convertido en el activo más valioso de una organización, pero el verdadero poder no está en tener datos, sino en saber extraerles valor. Este módulo no es un curso teórico de algoritmos; es una hoja de ruta práctica para entender cómo la ciencia de datos transforma las decisiones operativas y estratégicas en cualquier industria.

A lo largo de este primer bloque, dejaremos atrás el mito de que Data Science es solo cosa de matemáticos excéntricos. Vamos a construir los cimientos que todo profesional necesita para hablar el mismo idioma que los equipos de negocio, traducir problemas del mundo real a soluciones analíticas y manejar las herramientas que dan vida a los datos.

---

## Roles

- **Ingeniero de datos:** Construye y mantiene las tuberías (pipelines) que llevan datos crudos desde las fuentes (BBDD, APIs, logs) hasta un repositorio central (Data Lake o Data Warehouse). Su enfoque es la **escalabilidad y la fiabilidad**.
- **Científico de datos:** Es el explorador. Se encarga del análisis exploratorio, la experimentación y la construcción de modelos predictivos (Machine Learning). Su enfoque es la **estadística, el álgebra y la experimentación** para encontrar patrones ocultos.
- **Analista de datos:** Es el traductor. Su misión es limpiar datos y crear dashboards (Power BI/Tableau) para responder preguntas del día a día (*¿Por qué bajaron las ventas en marzo?*). Su enfoque es la **visualización y la narrativa**.
- **MLOps (Ingeniero de Machine Learning):** Es el puente entre Data Science e IT. Su trabajo comienza donde termina el modelo del científico. Su misión es **poner ese modelo en producción**, monitorizarlo y reentrenarlo automáticamente (es el que evita que el modelo "muera" en un Jupyter Notebook).

---

## KPIs

Es inútil medir un modelo si no mejora su rendimiento financiero en la empresa.
Por eso los KPIs se dividen en 3:

### Técnicos (Interno del equipo)

- **Latencia:** ¿Cuánto tarda el modelo en dar una predicción?
- **Recall / Precisión:** Dependiendo del negocio (ej: en fraudes, importa más el Recall; en spam, la Precisión).
- **Drift:** ¿Cómo de estable es la distribución de los datos de entrada vs. los que usamos para entrenar?

### Procesos (Agilidad)

- **_Time-to-Insight:_** Tiempo que pasa desde que se pide un análisis hasta que se entrega el primer resultado.
- **_Time-to-Market:_** Tiempo desde que se valida un modelo en laboratorio hasta que se despliega en producción.

### Negocio (Primordiales)

- **ROI (Retorno de Inversión):** ¿El modelo generó más ingresos o ahorró costes?
- **Incremento de conversión:** Si el modelo recomienda productos, ¿aumentó el ticket medio un 5%?
- **Reducción de Churn:** ¿Hemos logrado retener un X% más de clientes gracias a los alerts predictivos?

---

## Ciclo de vida de un proyecto de datos (CRISP-DM)

<img width="837" height="770" alt="Pasted image 20260622154100" src="https://github.com/user-attachments/assets/c1fcc3b6-3e1f-421a-8528-0cff08fdf198" />

Esta metodología se compone de 6 fases, las cuales son:

### Primera Fase: Comprensión de negocio (Business Understanding)

- entender objetivos del proyecto de las perspectivas del negocio
- definir qué problemas se requieren resolver y traducirlos en un problema de minería de datos

### Segunda Fase: Comprensión de los datos (Data Understanding)

- recolectar datos iniciales
- explorar los datos
- identificar problemas de calidad
- descubrir patrones o intuiciones

### Tercera Fase: Preparación de los datos (Data Preparation)

- limpiar
- transformar
- seleccionar variables
- construir el dataset final que se usará para el modelado

### Cuarta Fase: Modelado (Modeling)

- aplicar técnicas de machine learning, estadística
- seleccionar algoritmos y ajustar parámetros

### Quinta Fase: Evaluación (Evaluation)

- verificar que el modelo cumple con los objetivos del negocio planteados al inicio, no solo que tenga buenas métricas técnicas.

### Sexta Fase: Despliegue (Deployment)

- poner modelo en producción
  - Puede ir desde generar reportes hasta integrar un modelo en un sistema operativo en tiempo real.

---

> **Nota:** El éxito de Data Science en una empresa no depende del algoritmo, sino de **la gestión del cambio**. Un modelo increíble será un fracaso si el equipo comercial no confía en él o no entiende cómo interpretarlo. Por eso, los mejores científicos de datos dedican el 50% de su tiempo a **comunicar** (storytelling con datos) y solo el 20% a programar modelos.
