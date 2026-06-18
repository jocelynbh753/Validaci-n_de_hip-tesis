📊 Análisis del Experimento A/B en Landing Page

📌 Descripción del proyecto
Este proyecto analiza un experimento A/B realizado en la página de inicio de un ecommerce, comparando dos versiones (A y B) para determinar cuál genera mejor desempeño en conversión y valor económico. El análisis incluye validación de datos, pruebas estadísticas y conclusiones orientadas al negocio.

🎯 Objetivo
Evaluar estadísticamente las diferencias entre las versiones A y B en términos de:

Tasa de conversión

Gasto promedio por usuario convertido

Comportamiento por canal de tráfico

Comportamiento por tipo de usuario

Con el fin de recomendar la versión de landing page que maximiza el impacto en el negocio.

🧩 Metodología
El análisis sigue una secuencia lógica:

1. Exploración y validación de datos
   
Revisión de estructura, tipos de datos y valores faltantes

Análisis de variables categóricas y numéricas

Validación de consistencia del experimento

2. Comparación del gasto promedio (A vs B)
   
Filtrado de usuarios convertidos

Prueba de Levene para evaluar homogeneidad de varianzas

t-test (o Welch) para comparar medias

Interpretación estadística y de negocio

3. Comparación de la tasa de conversión (A vs B)
   
Cálculo de conversiones por grupo

z-test de proporciones

Evaluación de significancia y conclusiones

4. Relación entre fuente de tráfico y conversión
   
Tabla de contingencia

Prueba Chi-cuadrado

Identificación de canales con mayor impacto

5. Relación entre tipo de usuario y conversión
   
Análisis de comportamiento entre usuarios nuevos y recurrentes

Evaluación de diferencias significativas

📈 Resultados principales

✔️ Gasto promedio

-Existe una diferencia estadísticamente significativa entre el gasto promedio de las versiones A y B.

-El valor p < 0.05 indica que la diferencia no es producto del azar.

✔️ Tasa de conversión

-La tasa de conversión entre A y B también muestra diferencias significativas.

-La versión de landing influye directamente en cuántos usuarios se convierten.

✔️ Fuente de tráfico

-La fuente de tráfico está asociada a la conversión (p < 0.05).

-Algunos canales convierten mejor que otros.

✔️ Tipo de usuario

-Los usuarios recurrentes y nuevos presentan comportamientos distintos en conversión y gasto.

🧠 Conclusiones y recomendación

-El experimento demuestra que las versiones A y B no son equivalentes:

-Cambian tanto la tasa de conversión como el gasto promedio.

-La elección de landing page impacta directamente en el valor generado por usuario.

-La recomendación final debe considerar qué métrica es prioritaria para el negocio:

-Maximizar conversiones

-Maximizar ingreso por usuario

-Optimizar por canal o tipo de usuario

🛠️ Tecnologías utilizadas

-Python

-Pandas

-NumPy

Matplotlib / Seaborn

SciPy

Statsmodels
