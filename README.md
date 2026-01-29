## 📘 ConnectaTel — Análisis de Clientes y Uso (2024)

🎯 Objetivo del Proyecto
Analizar el comportamiento de los clientes de ConnectaTel utilizando datos de usuarios, planes y uso del servicio.
El proyecto busca limpiar y validar los datos, construir métricas de uso, segmentar clientes por edad y nivel de uso, identificar patrones extremos y generar insights accionables para mejorar la oferta comercial.

📂 Datasets Utilizados
plans.csv → Información de los planes (precio, minutos, GB, costos extra).

users_latam.csv → Datos de clientes (edad, ciudad, fecha de registro, plan, churn).

usage.csv → Registros de uso real (llamadas, mensajes, duración).

🔍 Etapas del Análisis Realizadas
Carga y exploración inicial de los tres datasets.

Detección de problemas de calidad: nulos, sentinels, fechas fuera de rango.

Limpieza de datos: corrección de edades, ciudades, fechas y nulos estructurales.

Construcción de métricas de uso por usuario (mensajes, llamadas, minutos).

Análisis estadístico y visualización de distribuciones y outliers.

Segmentación de clientes por edad y nivel de uso.

Generación de insights ejecutivos y recomendaciones de negocio.

▶️ Cómo ejecutar el notebook
Puedes ejecutarlo de dos formas:

Opción A — Google Colab
Abre el notebook desde GitHub.

Haz clic en “Open in Colab” (si está habilitado) o súbelo manualmente a Colab.

Ejecuta las celdas en orden.

Opción B — GitHub
Abre el archivo .ipynb directamente en GitHub para visualizarlo.

Si deseas ejecutarlo, descárgalo y ábrelo en Jupyter Notebook o VS Code.
