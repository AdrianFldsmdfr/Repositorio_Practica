# INTACTUS - Sistema de Monitoreo Continuo y No Invasivo de Glucosa

> **INTACTUS** *(del latín "intacto / no tocado")* es una solución tecnológica biomédica integral diseñada para monitorear los niveles de glucosa en sangre en tiempo real de forma **100% no invasiva**, eliminando la necesidad de punciones capilares y parches subcutáneos desechables.

---

## Tabla de Contenidos
- [Acerca del Proyecto](#-acerca-del-proyecto)
- [Propuesta de Valor](#-propuesta-de-valor)
- [Arquitectura del Sistema](#-arquitectura-del-sistema)
- [Características Principales](#-características-principales)
- [Stack Tecnológico](#-stack-tecnológico)
- [Esquema de Base de Datos](#-esquema-de-base-de-datos)
- [Validación Clínica y Metrología](#-validación-clínica-y-metrología)
- [Ciclo de Vida del Software](#-ciclo-de-vida-del-software)
- [Instalación y Configuración](#-instalación-y-configuración)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Licencia y Créditos](#-licencia-y-créditos)

---

## Acerca del Proyecto

El monitoreo tradicional de glucosa impone barreras significativas en la calidad de vida de personas con diabetes: dolor diario por punciones capilares, riesgo de infecciones y un alto costo recurrente en tiras reactivas y parches subcutáneos.

**INTACTUS** aborda este desafío mediante la integración de **espectroscopía infrarroja cercana y de onda corta (NIR/SWIR)** en una pulsera inteligente. El dispositivo analiza la interacción de haces de luz infrarroja ($850\text{ nm} - 1550\text{ nm}$) con el lecho vascular epidérmico en la muñeca, procesa la señal mediante un AFE de 24 bits y transmite los resultados en tiempo real a una aplicación móvil vía Bluetooth Low Energy (BLE).

---

## Propuesta de Valor

| Métrica / Aspecto | Glucómetro Tradicional | Parches Invasivos (CGM) | Pulsera INTACTUS |
| :--- | :---: | :---: | :---: |
| **Método** | Invasivo (Pinchazo) | Minimamente Invasivo (Cánula) | **Óptico No Invasivo** |
| **Insumos Recurrentes** | Tiras y lanzetas ($$$) \vert{} Reemplazo cada 10-14 días ($$) | **Cero insumos ($0)** |
| **Respuesta ante Emergencias** | Sin alertas automáticas | Alarmas locales | **Red SOS con GPS por SMS** |
| **Frecuencia de Lectura** | Manual (4-6 veces/día) | Continua | **Continua ($24/7$)** |
