# Alcance de la auditoría

## Descripción del proyecto

Este proyecto documenta una auditoría de seguridad web realizada sobre la aplicación DVWA (Damn Vulnerable Web Application) en un entorno de laboratorio controlado.

La auditoría tiene como finalidad simular un escenario real de evaluación de vulnerabilidades, aplicando metodologías profesionales para identificar, analizar y documentar fallos de seguridad en aplicaciones web.

## Objetivo de la auditoría

El objetivo principal de esta auditoría es:

- Identificar vulnerabilidades explotables en la aplicación
- Validar su impacto en términos de confidencialidad, integridad y disponibilidad
- Evaluar el nivel de riesgo asociado
- Proponer medidas correctivas alineadas con buenas prácticas del sector

## Entorno de análisis

El entorno evaluado presenta las siguientes características:

- Aplicación: DVWA (Damn Vulnerable Web Application)
- Sistema operativo: Kali Linux
- Despliegue: Localhost
- Nivel de seguridad: Low (entorno vulnerable controlado)

Este entorno permite la simulación de múltiples escenarios de ataque en condiciones seguras.

## Tipo de auditoría

La auditoría realizada corresponde a un **pentesting técnico ofensivo**, centrado en la identificación y explotación controlada de vulnerabilidades en una aplicación web.

## Modelo de evaluación

Se ha seguido un enfoque de tipo **caja blanca (White Box)**, ya que el auditor dispone de acceso completo al entorno evaluado, incluyendo:

- Acceso al código fuente de la aplicación
- Acceso a directorios internos (como `/var/www/html/dvwa`)
- Acceso a configuraciones del sistema
- Control del despliegue del entorno

Este nivel de acceso permite un análisis profundo del comportamiento de la aplicación y sus debilidades de seguridad.

## Alcance

La auditoría se ha limitado exclusivamente a:

- La aplicación DVWA desplegada en entorno local
- La identificación y explotación controlada de vulnerabilidades
- El análisis técnico de los fallos detectados

No se han evaluado:

- Sistemas externos
- Infraestructuras de terceros
- Entornos en producción

## Limitaciones

El análisis se ha realizado en un entorno de laboratorio, por lo que los resultados deben interpretarse dentro de este contexto controlado.

Aunque se simulan escenarios realistas, las condiciones no reflejan completamente un entorno productivo real.

## Consideraciones éticas

Todas las actividades se han realizado en un entorno autorizado, aislado y con fines exclusivamente educativos.

La auditoría sigue los principios del hacking ético, garantizando que no se ha comprometido ningún sistema real ni información sensible.