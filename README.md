# 🚴 Proyecto: Análisis de Usuarios Cyclistic — Conversión a Membresías Anuales
![Power BI](https://img.shields.io/badge/PowerBI-Data%20Visualization-yellow)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Data%20Cleaning-green)
![Analytics](https://img.shields.io/badge/Data-Analytics-blue)

## 📊 Descripción

Proyecto de análisis de datos enfocado en comprender las diferencias de uso entre ciclistas ocasionales y miembros anuales de Cyclistic, una empresa de bicicletas compartidas en Chicago.

Objetivo: identificar patrones de comportamiento para diseñar estrategias que aumenten las membresías anuales.

## 🎯 Contexto

Tipo: Proyecto de análisis de datos (caso de negocio)
Rol: Analista de datos junior – Marketing Analytics
Fecha: 2026
Entregables:

Dashboard en Power BI (.pbix)

Presentación ejecutiva (.pptx)

Documentación del análisis

Estado: ✅ Completado

## 🛠️ Tecnologías Utilizadas

Google Sheets (limpieza, transformación y cálculos)

Power BI Desktop (visualización y análisis)

Excel / CSV (fuentes de datos)

Google Slides / PowerPoint (presentación final)

## 📈 Características del Dashboard
📊 Página principal — Comportamiento de usuarios

Visualizaciones clave:

Duración promedio de viaje por tipo de usuario

Uso de bicicletas por día de la semana

Cantidad de viajes por tipo de usuario

Objetivo: comparar patrones entre casuales y miembros.

## 📁 Fuentes de Datos

Datos históricos de viajes de Cyclistic (3 meses de muestra).

Archivo	Filas aproximadas	Descripción
rides_jan.csv	~125,000	Viajes enero
rides_feb.csv	~120,000	Viajes febrero
rides_mar.csv	~129,000	Viajes marzo

Total: ~374,953 registros de viajes

Columnas principales:

ride_id

rideable_type

started_at

ended_at

start_lat / start_lng

end_lat / end_lng

member_casual

## 🧹 Limpieza y Transformación de Datos

Eliminación de registros con valores faltantes

Unificación de archivos mensuales en una sola hoja

Creación de variables calculadas:

ride_length (duración del viaje)

day_of_week (día de la semana)

Conversión de formatos de fecha y hora

Validación de valores inconsistentes

## 🔍 Insights Clave

✔ Los ciclistas ocasionales realizan viajes significativamente más largos
✔ Los miembros anuales viajan menos tiempo pero con mayor frecuencia
✔ El uso casual se concentra en fines de semana
✔ El uso de miembros es constante durante días laborales

## 🚀 Recomendaciones Estratégicas

Promociones de membresía durante fines de semana

Comunicación clara del ahorro frente al uso por viaje

Ofertas personalizadas luego de viajes largos de usuarios casuales

## 📚 Aprendizajes

Limpieza de grandes volúmenes de datos en Google Sheets

Análisis descriptivo orientado a negocio

Creación de dashboards claros en Power BI

Traducción de datos en decisiones de marketing
