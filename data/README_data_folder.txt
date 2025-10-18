🔹 raw/
Datos en bruto.

Contiene los datos tal como fueron obtenidos desde su fuente original (en este caso se incluyen enlances a las fuentes para descarga).
Sin procesamiento, validación ni transformación.

🔹 stage/
Datos en etapa intermedia (staging).

Datos que ya han pasado por una limpieza inicial o transformación básica.
Se usa para preparar los datos antes de cargarlos al modelo analítico.
Es un área de trabajo temporal donde se realizan uniones, filtrados, renombramientos, etc.
Ejemplo: CSVs donde ya se han corregido nombres de columnas, eliminado duplicados o convertido tipos de datos.

🔹 analytics/
Datos listos para análisis o consumo.

Datos ya transformados y estructurados para responder preguntas de negocio o alimentar modelos de machine learning.
Suele estar muy limpio y organizado, muchas veces en forma de tablas o features listos para ser utilizados.
Ejemplo: Tablas resumen, datasets de entrenamiento, indicadores clave (KPIs).
