1. Objetivo

Analizar el desempeño de campañas de marketing digital para identificar qué canales, audiencias, segmentos y tipos de campaña generan mejores resultados en términos de ROI, CTR, engagement y costo de adquisición.

2. Dataset

El dataset contiene información de campañas realizadas entre enero 2021, incluyendo:
Tipo de campaña
Segmento objetivo
Canal utilizado
Métricas de desempeño (impresiones, clics, conversiones, engagement)
ROI y costos

3. Proceso de análisis

3.1 Limpieza

Normalización de nombres de columnas
Conversión de fechas a formato YYYY-MM-DD
Conversión de valores numéricos (Conversion_Rate, ROI, Costos, Clicks, etc.)
Eliminación de filas con métricas faltantes críticas
Creación de nuevas métricas (CTR, CPC, CPM)

3.2 Cálculo de KPIs

CTR (%) = Clicks / Impressions × 100
CPC = Acquisition_Cost / Clicks
Conversion Rate (dataset) = Valor directo
ROI = Retorno / Inversión
Engagement Score = Métrica proporcionada

3.3 Modelado en SQL

Validación de nulos
Carga de datos
Pruebas de consistencia
Exploración inicial

3.4 Visualización (Power BI)

Se generaron páginas del dashboard enfocadas en:
Rendimiento por canal
Comparativa de ROI por campaña
Engagement por segmento
Distribución geográfica (Location)
Conversión por tipo de campaña

4. Insights

Las campañas en Google Ads con audiencias entre 18–24 años lograron CTR de >25%, significativamente superior al promedio.
Las campañas tipo Email tienen menor costo promedio por adquisición frente a Influencer o Display.
Los segmentos Tech Enthusiasts y Health & Wellness muestran los mejores niveles de engagement.
Las campañas con duración mayor a 30 días tienden a mejorar ROI observando estabilidad en clics y visibilidad.

5. Recomendaciones

Priorizar canales con ROI > 5.0 en campañas similares (Google Ads y YouTube).
Ajustar segmentación hacia audiencias con alto engagement (Tech Enthusiasts).
Analizar impacto de idiomas: Mandarin y German aparecen con conversiones relevantes.
Considerar reducir costos en campañas con baja relación clicks/impressions (<10%).

6. Próximos pasos

Crear modelo predictivo para ROI o CTR.
Implementar pruebas A/B sobre duración y canal.
Integrar análisis de gastos reales del cliente.

