# Dashboard-Accidentes-Viales
Pipeline de procesamiento analítico masivo de datos científicos mediante arquitecturas de lenguaje natural (NLP) y aprendizaje supervisado.
# Arquitectura de Business Intelligence y Analítica Predictiva: Control de Siniestralidad Vial en España (Fase 4)

## Propósito Estratégico del Proyecto
Este ecosistema analítico ha sido diseñado con el objetivo de transformar datos masivos en bruto correspondientes a la siniestralidad vial en España durante el periodo monitorizado, convirtiéndolos en conocimiento táctico accionable para la formulación de políticas públicas, auditorías viales y optimización de recursos de emergencia.

A través de un pipeline híbrido implementado en Python, la plataforma articula modelos de procesamiento de lenguaje natural (NLP) y clasificadores de Machine Learning (ML) para diagnosticar de forma cualitativa y cuantitativa los factores críticos que determinan la gravedad de los incidentes en la red vial nacional.

## Especificación de la Arquitectura del Pipeline Técnico
El flujo de trabajo analítico se encuentra estructurado de forma secuencial en las siguientes fases operativas:
1. **Ingesta y Normalización de Datos (df_accidentes):** Consolidación de registros históricos integrando variables de temporalidad, localización geográfica y tipología de la infraestructura vial.
2. **Módulo NLP (Natural Language Processing):** Implementación de una red neuronal optimizada enfocada en el análisis discursivo de las descripciones textuales de los partes policiales.
3. **Módulo de Machine Learning Predictivo:** Entrenamiento y validación de un algoritmo de clasificación supervisada RandomForestClassifier optimizado con 120 estimadores.

## Matriz de Interpretación Estratégica (Cognitive LLM Engine)
La consola del sistema genera de forma estructurada un cuadro analítico formal que replica el diseño metodológico de un entorno tabular de LaTeX:

```text
╔═════════════════════════════════════════╦══════════════════════════════════════════════════════════════════════════════╗
║ CUADRO DE INTERPRETACIÓN ESTRATÉGICA    │ INTEGRACIÓN COGNITIVA LLM - INFORME DE REPORTE CRÍTICO                       ║
╠═════════════════════════════════════════╬══════════════════════════════════════════════════════════════════════════════╣
║ SECCIÓN I: MARCO DIAGNÓSTICO            │ MÉTRICAS EXTRAÍDAS Y COMPORTAMIENTO DE VARIABLES                             ║
╠═════════════════════════════════════════╪══════════════════════════════════════════════════════════════════════════════╣
║ Volumen Histórico Procesado             │ Registros correspondientes a partes policiales y reportes oficiales          │
║                                         │ de siniestralidad vial analizados bajo un modelo secuencial homogéneo.       │
╟─────────────────────────────────────────┼──────────────────────────────────────────────────────────────────────────────╢
║ Dinámica Temporal del Fenómeno          │ Los datos consolidados muestran una concentración crítica de eventos severos │
║                                         │ durante el año 2024, estructurando un comportamiento macroestadístico de     │
║                                         │ meseta que exige una revisión de las políticas públicas de ese periodo.      │
╟─────────────────────────────────────────┼──────────────────────────────────────────────────────────────────────────────╢
║ Diagnóstico Discursivo (NLP)            │ El procesamiento de lenguaje natural (NLP) aplicado a los campos de texto    │
║                                         │ libre revela una alta densidad de términos vinculados a riesgos críticos,   │
║                                         │ demostrando que la gravedad real supera los indicadores numéricos base.      │
╟─────────────────────────────────────────┼──────────────────────────────────────────────────────────────────────────────╢
║ Vector de Riesgo Estructural            │ Las vías de alta velocidad (autovías y carreteras nacionales) concentran los  │
║                                         │ nodos de colisión con mayor energía cinética, vinculando la gravedad de los  │
║                                         │ eventos directamente con el diseño vial y los límites de velocidad locales.  │
╠═════════════════════════════════════════╪══════════════════════════════════════════════════════════════════════════════╣
║ SECCIÓN II: PROPUESTA ESTRATÉGICA       │ LINEAMIENTOS DE GESTIÓN Y POLÍTICAS PÚBLICAS RECOMENDADAS                    ║
╠═════════════════════════════════════════╪══════════════════════════════════════════════════════════════════════════════╣
║ 1. Optimización en Emergencias          │ Implementar el pipeline de minería de texto (NLP) dentro de las centrales de │
║                                         │ despacho 112 de forma nativa. Esto permitirá automatizar la clasificación de │
║                                         │ la gravedad del incidente, priorizando el envío de unidades de soporte vital │
║                                         │ avanzado a los tramos de riesgo analizados de forma inmediata.               │
╟─────────────────────────────────────────┼──────────────────────────────────────────────────────────────────────────────╢
║ 2. Intervención de Infraestructura      │ Diseñar planes de contingencia focalizados en las comunidades autónomas con  │
║                                         │ mayores picos de riesgo según el mapa analítico, promoviendo la instalación  │
║                                         │ de radares de tramo y la aplicación de pavimentos de alta fricción.          │
╟─────────────────────────────────────────┼──────────────────────────────────────────────────────────────────────────────╢
║ 3. Robustecimiento del Modelo ML        │ Garantizar la gobernanza de datos expandiendo el dataframe. Es mandatorio    │
║                                         │ indexar variables exógenas como la intensidad de precipitación pluvial e     │
║                                         │ índice de luminosidad para maximizar el ajuste del RandomForestClassifier.   │
╚═════════════════════════════════════════╩══════════════════════════════════════════════════════════════════════════════╝
