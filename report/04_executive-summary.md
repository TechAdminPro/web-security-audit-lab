# Resumen ejecutivo

## Visión general

Se ha realizado una auditoría de seguridad web sobre la aplicación DVWA (Damn Vulnerable Web Application) en un entorno de laboratorio controlado, con el objetivo de identificar vulnerabilidades y evaluar su impacto en términos de seguridad.

El análisis ha seguido un enfoque estructurado basado en estándares del sector, permitiendo simular un escenario real de evaluación de vulnerabilidades.

## Principales resultados

Durante la auditoría se han identificado múltiples vulnerabilidades críticas que afectan directamente a la seguridad del sistema.

Entre los hallazgos más relevantes destacan:

- Ausencia de mecanismos de protección frente a ataques de fuerza bruta  
- Posibilidad de ejecución de comandos del sistema (Command Injection)  
- Inclusión de archivos sin validación adecuada (File Inclusion)  
- Subida de archivos sin control de seguridad (File Upload)  
- Vulnerabilidad de SQL Injection (Blind)  
- Uso de mecanismos criptográficos débiles  

Estas vulnerabilidades permiten a un atacante comprometer la confidencialidad, integridad y disponibilidad del sistema.

## Nivel de riesgo

La mayoría de las vulnerabilidades identificadas presentan un nivel de riesgo **alto o crítico**, según su evaluación mediante CVSS.

Esto implica que, en un entorno real, podrían ser explotadas para:

- Obtener acceso no autorizado  
- Ejecutar código en el servidor  
- Extraer información sensible  
- Comprometer completamente la aplicación  

## Impacto potencial

El impacto global del sistema evaluado es **crítico**, ya que múltiples vulnerabilidades permiten:

- Control total del sistema  
- Acceso a datos sensibles  
- Escalada de privilegios  
- Ejecución remota de comandos  

## Recomendación general

Se recomienda implementar medidas de seguridad de forma prioritaria, incluyendo:

- Validación estricta de entradas  
- Uso de consultas parametrizadas  
- Implementación de controles de autenticación robustos  
- Aplicación de buenas prácticas criptográficas  
- Configuración segura del sistema  

## Conclusión

La auditoría demuestra la importancia de aplicar controles de seguridad adecuados en aplicaciones web.

Aunque el análisis se ha realizado en un entorno de laboratorio, las vulnerabilidades identificadas reflejan problemas comunes en entornos reales, por lo que su mitigación resulta fundamental para garantizar la seguridad del sistema.