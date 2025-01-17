# Que es kubernetes?
- Es un sistema de orquestacion de contenedores de codigo abierto que facilita el despliegue, escalado y mantenimiento de contenedores
- Los contenedores dejan de ser elementos estaticos
- Kubernetes organiza los contendores en pods

> **Un pod es un contendores de contenedores, y puede tener mas de un contenedor**

- El cluster es un conjunto de maquinas que ejecutan aplicaciones y existen dos tipos de maquinas.
1. **Masters**: Conjunto que administra y controla el estado del worker
2. **Workers**: Ejecutan las aplicaciones y los pods definidos

## Caracteristicas de Kubernetes
- **Autocuracion**: Detecta faalos o anomalias en los contenedores y tomar acciones que solcuionen el problema automaticamente
- **Escalado Automatico**: Genera replicas o destruye segun la demanda de la aplicacion automaticamente
- **Despliegue y actualizaciones continuas**: Facilita el despliegue de nuevos cambios sin sacrificar disponiblidad o trafico.

