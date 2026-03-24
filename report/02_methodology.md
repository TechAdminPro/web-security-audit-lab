# Metodología

## Enfoque metodológico

La auditoría se ha llevado a cabo siguiendo un enfoque estructurado basado en buenas prácticas del sector de la ciberseguridad, con el objetivo de identificar vulnerabilidades de forma sistemática y evaluarlas en función de su impacto real.

Aunque el análisis se ha realizado en un entorno de laboratorio, la metodología aplicada simula un proceso de auditoría profesional.

## Estándares de referencia

La evaluación se ha alineado conceptualmente con los siguientes estándares internacionales:

- **ISO/IEC 27001** – Sistema de Gestión de Seguridad de la Información  
- **ISO/IEC 27002** – Controles de seguridad  
- **ISO/IEC 27005** – Gestión del riesgo  

Estos marcos proporcionan una base sólida para estructurar el análisis y priorizar los riesgos identificados.

## Fases de la auditoría

El proceso de auditoría se ha dividido en las siguientes fases:

### 1. Identificación de vulnerabilidades

Se realizó un análisis del comportamiento de la aplicación con el objetivo de detectar posibles fallos de seguridad.

En esta fase se analizaron:
- Entradas del usuario
- Parámetros en URL
- Formularios de autenticación
- Funcionalidades expuestas de la aplicación

### 2. Explotación controlada

Una vez identificadas las posibles vulnerabilidades, se procedió a su explotación en un entorno controlado.

El objetivo fue:
- Validar la existencia de la vulnerabilidad
- Comprobar su viabilidad real
- Analizar su impacto en el sistema

### 3. Evaluación del impacto

Cada vulnerabilidad fue analizada en función de su impacto sobre:

- Confidencialidad  
- Integridad  
- Disponibilidad  

Esto permitió determinar el nivel de riesgo asociado a cada hallazgo.

### 4. Propuesta de medidas correctivas

Para cada vulnerabilidad identificada se definieron recomendaciones orientadas a mitigar el riesgo.

Estas medidas están basadas en buenas prácticas de seguridad y estándares del sector.

## Enfoque basado en riesgo

La auditoría adopta un enfoque basado en riesgo, priorizando aquellas vulnerabilidades que presentan un mayor impacto potencial sobre el sistema.

Este enfoque permite centrar los esfuerzos en los fallos más críticos desde el punto de vista de seguridad.

## Contexto del análisis

El análisis se ha realizado sobre DVWA en nivel de seguridad bajo (Low), lo que permite identificar y explotar vulnerabilidades de forma controlada.

A pesar de tratarse de un entorno vulnerable por diseño, el enfoque aplicado sigue criterios realistas de auditoría técnica.