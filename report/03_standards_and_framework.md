# Marcos de referencia y evaluación

## Introducción

Para la clasificación y evaluación de las vulnerabilidades identificadas durante la auditoría, se han utilizado marcos de referencia ampliamente reconocidos en el ámbito de la ciberseguridad.

El uso de estos estándares permite estructurar los hallazgos de forma objetiva, facilitar su comprensión y priorizar adecuadamente los riesgos.

## OWASP Top 10 (2025)

La clasificación de las vulnerabilidades se ha realizado tomando como referencia el **OWASP Top 10 (2025)**, que recoge las principales categorías de riesgos en aplicaciones web.

OWASP proporciona un marco estandarizado para identificar y agrupar vulnerabilidades comunes, tales como:

- Fallos de autenticación  
- Inyecciones  
- Configuraciones inseguras  
- Fallos criptográficos  

Cada vulnerabilidad detectada en la aplicación ha sido mapeada a su categoría correspondiente dentro del OWASP Top 10, lo que permite contextualizar los hallazgos dentro de riesgos reconocidos a nivel internacional.

## CVSS (Common Vulnerability Scoring System)

Para evaluar la severidad de cada vulnerabilidad se ha utilizado el sistema **CVSS (versión 3.1)**.

Este sistema permite asignar una puntuación numérica en función de múltiples factores, entre los que destacan:

- Vector de ataque (AV)  
- Complejidad del ataque (AC)  
- Privilegios requeridos (PR)  
- Interacción del usuario (UI)  
- Impacto sobre:
  - Confidencialidad (C)  
  - Integridad (I)  
  - Disponibilidad (A)  

La puntuación resultante permite clasificar las vulnerabilidades en niveles de gravedad: baja, media, alta o crítica.

Esto facilita la priorización de los riesgos y la toma de decisiones en la fase de mitigación.

## CVE (Common Vulnerabilities and Exposures)

En los casos en los que la vulnerabilidad identificada se encuentra documentada públicamente, se ha utilizado la referencia **CVE (Common Vulnerabilities and Exposures)**.

El uso de identificadores CVE permite:

- Relacionar los hallazgos con vulnerabilidades conocidas  
- Facilitar su trazabilidad técnica  
- Comparar los resultados con bases de datos globales de seguridad  

## Integración de los marcos

La combinación de OWASP, CVSS y CVE proporciona un enfoque completo para el análisis de vulnerabilidades:

- **OWASP** → Clasificación del tipo de vulnerabilidad  
- **CVSS** → Evaluación de la severidad  
- **CVE** → Identificación y referencia global  

Este enfoque permite alinear la auditoría con estándares profesionales y facilita la interpretación de los resultados en un contexto real.