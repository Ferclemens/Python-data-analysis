# Python-data-analysis
Análisis de datos de ventas utilizando pandas

Comenzamos por limpiar nuestros datos. Las tareas durante esta sección incluyen:
Eliminar valores NaN de DataFrame
Eliminar filas según una condición
Cambiar el tipo de columnas (to_numeric, to_datetime, astype)

Una vez que hayamos limpiado un poco nuestros datos, pasamos a la sección de exploración de datos. En esta sección, exploramos 5 preguntas comerciales de alto nivel relacionadas con nuestros datos:
¿Cuál fue el mejor mes en ventas? ¿Cuánto se ganó ese mes?

¿En qué ciudad se vendió más producto?

¿A qué hora deberíamos mostrar anuncios para maximizar la probabilidad de que el cliente compre el producto?

¿Qué productos se venden juntos con más frecuencia?

¿Qué producto se vendió más? ¿Por qué cree que se vendió más?

Para responder a estas preguntas, analizamos muchos métodos diferentes de pandas y matplotlib. Incluyen:
Concatenar varios archivos CSV para crear un nuevo DataFrame (pd.concat)
Agregar columnas
Analizar celdas como cadenas para crear nuevas columnas (.str)
Usar el método .apply()
Usar groupby para realizar análisis agregados
Trazar gráficos de barras y gráficos de líneas para visualizar nuestros resultados
Etiquetar nuestros gráficos
