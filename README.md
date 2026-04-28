# CarbonTrace v16.0 — Logistics Audit & Sustainability Engine 🚛🌱

**CarbonTrace** es un motor de auditoría dinámica desarrollado para la optimización de procesos logísticos. El sistema permite visualizar, medir y auditar el impacto ambiental y financiero del transporte de carga pesada, integrando la normativa argentina y estándares internacionales de descarbonización.

## 🎯 Objetivo del Proyecto
Cerrar la brecha entre la **gestión operativa** y los **objetivos de sustentabilidad**, demostrando que la reducción de la intensidad de carbono (GCI) es un indicador directo de la rentabilidad financiera (ROI).

## 📚 Fundamentos Técnicos y Legales

El simulador se basa en tres pilares de ingeniería:

1.  **Marco Normativo (Argentina):** Implementación de los parámetros de carga y dimensiones del **Decreto 32/2018**, permitiendo la simulación de unidades **Escaladas (52.5t/55t)** y **Bitrenes (60t/75t)**.
2.  **Contabilidad de Carbono:** Cálculos basados en el **GHG Protocol** e **ISO 14064**. Utiliza factores de emisión estequiométricos del **IPCC** ($2.68$ kg $CO_2$e/L para Diesel Grado 3).
3.  **Física Aplicada:** Modelado de consumo dinámico considerando:
    * **Resistencia al rodamiento ($C_{rr}$):** Impacto de la presión de neumáticos en el consumo.
    * **Arrastre Aerodinámico ($C_x$):** Eficiencia por deflectores y kits de carrocería.
    * **Factor de Ocupación:** Penalización por subutilización del activo (mover aire).

## 🚀 Características Principales

- **Geocodificación Global:** Cálculo de rutas reales mediante la integración de **OpenStreetMap API**.
- **Auditoría Proactiva:** Sistema de alertas que identifica viajes ineficientes (GCI > 155 g/tn-km) y sugiere consolidación de carga o cambio de activo.
- **ROI Sustentable:** Cálculo en tiempo real del ahorro operativo en **USD/viaje**, integrando el valor de mercado de los créditos de carbono.
- **Visualización Estocástica:** Trazado de una "Pluma de Carbono" que codifica el color de la ruta según el desempeño ambiental detectado.

## 🛠️ Stack Tecnológico

- **Core:** JavaScript (ES6+), HTML5, CSS3.
- **Geolocalización:** Leaflet.js & CartoDB.
- **UI/UX:** Dashboard industrial optimizado para análisis de datos con tipografía JetBrains Mono para entornos técnicos.

## 👨‍💻 Autor
**Ing. Giulio Stocco** *Analista de Procesos | Especialización en Energía Nuclear (UTN) | Toyota Tsusho.*

---
> *Este software es una herramienta de ingeniería de libre acceso para la promoción de una logística más eficiente y sustentable.*
