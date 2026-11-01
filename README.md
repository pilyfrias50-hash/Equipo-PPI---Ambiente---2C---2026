# Análisis de Incendios Forestales y su impacto en la Argentina

**Prácticas Profesionalizantes 1 · Proyecto de Ciencia de Datos · Equipo 2 – Ambiente · 2C 2026**

Proyecto de análisis de datos sobre incendios forestales en Argentina (distribución, evolución e impacto ambiental), con alcance nacional (provincias y regiones de todo el país) y período 2020–2025. En el Sprint 2 se descartaron los datasets de Tierra del Fuego para pasar de un foco regional a un análisis nacional.

## Equipo
Jonatan · Pilar Frias · Laura

## Preguntas de análisis (Sprint 2)
- **Principal:** ¿Qué relación existe entre la cantidad de incendios forestales y la superficie afectada en las provincias argentinas entre 2020 y 2025?
- **Secundaria 1:** ¿Cómo se comportan los focos de calor en las distintas provincias de Argentina entre 2020 y 2025?
- **Secundaria 2:** ¿Cómo se distribuyen los incendios forestales entre las distintas regiones de Argentina entre 2020 y 2025?

## Estructura del repositorio
Misma numeración que la carpeta del proyecto en Google Drive.

| Carpeta | Contenido |
|---|---|
| `01_Organizacion/` | Gantt, retrospectiva y ficha de seguimiento de cada Sprint |
| `02_Datos/` | Datasets y Diccionario de Datos |
| `03_Analisis/` | EDA y análisis |
| `04_Documentacion/` | Informes técnicos |
| `05_Entrega/` | Material final de entrega |

## Branches
| Branch | Uso |
|---|---|
| `main` | Rama estable: README y estructura base |
| `sprint-1` | Planificación y análisis inicial (29/09 – 05/10/2026) |
| `sprint-2` | Preparación de datos, análisis de resultados e insights (08/10 – 24/10/2026) |
| `sprint-3` | Visualización, data storytelling y presentación final |

Cada Sprint se trabaja en su branch y se integra a `main` al cerrarse.

## Fuentes de datos
datos.gob.ar (focos de calor, incendios y hectáreas por provincia/región) y reportes mensuales de alerta temprana del Servicio Nacional de Manejo del Fuego (SNMF), de donde se reconstruyeron los datos por jurisdicción y mes. Detalle de variables en el Diccionario de Datos.
