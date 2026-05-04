# 📊 Análisis RFM de Fidelidad de Clientes — thelook_ecommerce

## 📌 Descripción

Proyecto final del certificado de Google Data Analytics. Análisis de fidelidad de clientes aplicando el modelo RFM (Recencia, Frecuencia, Monetario) sobre el dataset público thelook_ecommerce en BigQuery.

**Pregunta de negocio:** ¿Qué factores determinan la fidelidad de un cliente?

---

## 🛠️ Tecnologías utilizadas

- **BigQuery** — consultas SQL y análisis de datos
- **Looker Studio** — dashboard interactivo conectado a BigQuery
- **Tableau** — visualización estática para portfolio
- **Power BI** — dashboard alternativo en ecosistema Microsoft
- **Obsidian** — documentación del proceso analítico
- **GitHub** — control de versiones y portfolio

---

## 📁 Estructura del repositorio
rfm-ecommerce-case-study/
│
├── README.md
├── queries/
│   ├── 01_kpis_generales.sql
│   ├── 02_frecuencia_clientes.sql
│   ├── 03_query_rfm.sql
│   ├── 04_segmentacion_rfm.sql
│   ├── 05_productos_mas_vendidos.sql
│   ├── 06_productos_clientes_fieles.sql
│   ├── 07_analisis_genero.sql
│   ├── 08_analisis_paises.sql
│   ├── 09_analisis_marcas.sql
│   └── 10_marcas_clientes_fieles.sql
├── documentacion/
│   └── caso_de_estudio_completo.md
└── assets/
└── dashboard_preview.png

---

## 🔍 Metodología — Google Data Analytics Framework

| Fase | Estado | Descripción |
|---|---|---|
| ASK | ✅ | Definición de pregunta de negocio y modelo RFM |
| PREPARE | ✅ | Identificación de tablas y fuentes de datos |
| PROCESS | ✅ | Verificación de calidad y limpieza in-query |
| ANALYZE | ✅ | 10 queries con hallazgos documentados |
| SHARE | ✅ | Dashboard en Looker Studio, Tableau y Power BI |
| ACT | ✅ | Recomendaciones accionables con hipótesis testeables |

---

## 💡 Hallazgos principales

### 🔴 Hallazgo crítico — Problema de retención
> Solo el **0.03% de los clientes** (5 de 19.297) son verdaderamente fieles aplicando los tres criterios RFM simultáneamente. El **90% de los clientes compró una sola vez**. El negocio tiene un problema crítico de retención, no de adquisición.

### 📊 Hallazgos por dimensión

**Género:**
- Volumen de compras prácticamente igual entre géneros (M: 10.671 / F: 10.633)
- Género masculino con ticket promedio **11% mayor** en el análisis general
- Entre clientes verdaderamente fieles, el **género femenino domina** (3 de 5) con $1.291 vs $758 en monetario total

**Mercados:**
- China lidera en revenue total ($625.305)
- Australia (65.26) y Reino Unido (64.67) lideran en **ticket promedio**
- Conclusión: volumen alto ≠ mayor rentabilidad por cliente

**Marcas:**
- Marcas masculinas dominan en volumen general
- Allegra K es la única marca presente en múltiples clientes fieles
- Los clientes fieles compran marcas variadas → **lealtad a la plataforma, no a una marca**

---

## 📋 Recomendaciones

1. **Monitoreo RFM continuo** — identificar clientes fieles y en riesgo en tiempo real
2. **Programa de fidelización a nivel de plataforma** — descuento en segunda compra para reducir el 90% de clientes con frecuencia 1
3. **Estrategia diferenciada por género** — priorizar fidelización del segmento femenino
4. **Foco en mercados de alto valor** — Australia y Reino Unido como mercados prioritarios por ticket promedio

---

## 📊 Dashboard

🔗 [Ver dashboard en Looker Studio](https://datastudio.google.com/reporting/4e6cf671-9d4f-4e38-9233-8dec9c09cdac)

---

## 🤖 Uso de Inteligencia Artificial

Este proyecto utilizó **Claude (Anthropic)** como guía metodológica mediante diálogo socrático, aplicando conocimientos del curso **Google Aspectos Básicos de Prompting** (Fundación Compromiso).

**Principios aplicados:**
- La IA no generó queries ni conclusiones directamente
- Todas las decisiones técnicas y de negocio fueron tomadas por el analista
- Validación cruzada entre modelos de IA como práctica de control de calidad
- Criterio propio para evaluar y filtrar el feedback de la IA

> El uso ético y transparente de herramientas de IA es una competencia central documentada en este proyecto.

---

## 📚 Documentación completa

La documentación detallada del proceso analítico, incluyendo errores identificados, decisiones metodológicas y aprendizajes, está disponible en:

📄 [Ver documentación completa](https://github.com/mariod37/rfm-ecommerce-case-study/commit/13b0f1f574c09853212b14ef5e6c5aff9ad3b81f)

---

## 🎓 Certificación

- Google Data Analytics Professional Certificate
- Google Aspectos Básicos de Prompting — Fundación Compromiso

---



Autor: Fernando Da silva
LinkedIn: linkedin.com/in/fernando-da-silva-342475254
Fecha: Mayo 2026
