# 07 - Conclusión

## Resumen global

Durante la auditoría de seguridad realizada sobre la aplicación DVWA se han identificado múltiples vulnerabilidades de distinta naturaleza, incluyendo fallos críticos como:

- SQL Injection  
- Command Injection  
- File Upload inseguro  
- Inclusión de archivos  
- Autenticación débil  
- Uso incorrecto de criptografía  

Estas vulnerabilidades permiten, en conjunto, comprometer completamente la seguridad de la aplicación.



## Nivel de riesgo

El nivel de riesgo global se considera **CRÍTICO**, ya que varias de las vulnerabilidades detectadas permiten:

- Ejecución remota de código  
- Acceso no autorizado  
- Compromiso de la base de datos  
- Escalada de privilegios  

La explotación encadenada de estas vulnerabilidades podría derivar en el control total del sistema.



## Evaluación profesional

La aplicación auditada presenta deficiencias graves en:

- Validación de entradas  
- Control de acceso  
- Gestión de sesiones  
- Seguridad en base de datos  
- Uso de mecanismos criptográficos  

Esto indica la ausencia de prácticas seguras en el desarrollo de la aplicación.



## Recomendación final

Se recomienda abordar de forma prioritaria las vulnerabilidades críticas identificadas y aplicar un enfoque de desarrollo seguro basado en estándares como OWASP.

Además, se sugiere implementar revisiones periódicas de seguridad y pruebas de penetración para detectar y corregir vulnerabilidades de forma continua.



## Cierre

Este informe refleja la importancia de integrar la seguridad desde las primeras fases del desarrollo, ya que la acumulación de vulnerabilidades puede derivar en compromisos graves del sistema.

La aplicación de buenas prácticas y controles adecuados permitirá mejorar significativamente la postura de seguridad.