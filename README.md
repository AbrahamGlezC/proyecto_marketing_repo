# proyecto_marketing_repo
# Proyecto: Marketing Campaign Analysis

**Autor:** Abraham Moisés González Contreras  
**Rol:** Analista de Datos (Junior)

## Descripción
Análisis del desempeño de campañas de marketing usando el dataset `marketing_campaign_dataset.csv`. Incluye limpieza de datos, cálculo de KPIs (CTR, CPC, ROI), vistas SQL y visualizaciones en Power BI.

## Estructura del repositorio
- `/data` - dataset original.
- `/dashboard` - archivo Power BI (`marketing.pbix`) y capturas.
- `/scripts` - scripts de limpieza y análisis (Python).
- `/sql` - scripts SQL para crear la base de datos y vistas.
- `data_dictionary.md` - diccionario de columnas.
- `report.md` - reporte del proyecto.

## Requisitos
- Power BI Desktop (para abrir `dashboard/marketing.pbix`)
- Python 3.8+ (recomiendo usar un virtualenv)
- Python packages: pandas, numpy
- MySQL o MariaDB (opcional) si quieres ejecutar `sql/MARKETING.sql`

## Reproducir localmente (pasos)
1. Clonar o descargar el repo.  
2. Colocar `marketing_campaign_dataset.csv` en `/data` y `marketing.pbix` en `/dashboard`.  
3. (Opcional) Crear un virtualenv e instalar dependencias:
```bash
python -m venv .venv
source .venv/bin/activate     # Linux/Mac
.venv\Scripts\activate        # Windows
pip install pandas numpy
