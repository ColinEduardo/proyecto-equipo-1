🧩 Proyecto Equipo 1 – Seguridad en Kubernetes

Este proyecto demuestra cómo integrar **Trivy**, **Cosign** y **Connaisseur** en un clúster de Kubernetes para garantizar que solo se desplieguen **imágenes firmadas y verificadas**.  
Forma parte de una práctica sobre **seguridad en la cadena de suministro (supply chain security)** dentro de entornos DevSecOps.

🎯 Objetivo

Implementar un flujo de validación de imágenes que:

- Detecte vulnerabilidades con **Trivy** 🐳  
- Firme imágenes con **Cosign** 🔏  
- Verifique las firmas mediante **Connaisseur** 🔒  
- Rechace automáticamente imágenes no firmadas o alteradas 
