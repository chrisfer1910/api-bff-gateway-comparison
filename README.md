# API-BFF Gateway Comparison

Este repositorio complementa la investigación de tesis orientada a la comparación empírico-experimental entre los **patrones de arquitectura API Gateway y Backend for Frontend (BFF)** en entornos multicanal.

El objetivo principal de este trabajo es analizar el **rendimiento, la escalabilidad y el consumo de recursos** de ambos patrones mediante una **Prueba de Concepto (PoC)** desarrollada con herramientas modernas de desarrollo y contenedores.

---

## Objetivo del proyecto

Evaluar comparativamente los patrones **API Gateway** y **BFF**, identificando sus fortalezas y limitaciones técnicas cuando se exponen a distintos escenarios de carga controlada, simulando un entorno multicanal con interacciones entre clientes y microservicios.

---

## Metodología experimental

El diseño experimental se basó en la implementación de dos arquitecturas con funcionalidades equivalentes, desarrolladas bajo el mismo *stack* tecnológico:

- **Backend:** Node.js
- **Frontend:** React  
- **Contenedores:** Docker / Docker Compose  
- **Pruebas funcionales y de carga:** Postman  

Ambas arquitecturas fueron desplegadas en un entorno local con condiciones de red y hardware equivalentes, asegurando que las diferencias observadas en los resultados se atribuyan exclusivamente al patrón arquitectónico implementado.

---
