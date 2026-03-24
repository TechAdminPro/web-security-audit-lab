

# 🔐 Web Security Audit Lab
![Pentesting](https://img.shields.io/badge/Pentesting-Web%20Security-0f172a?style=for-the-badge&logo=hackaday&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-Top%2010-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Offensive%20Security-3b82f6?style=for-the-badge)

## 📄 Descripción general

Este proyecto presenta una auditoría de seguridad web realizada en un entorno de laboratorio controlado utilizando **DVWA (Damn Vulnerable Web Application)**.

El objetivo de esta evaluación es simular un proceso real de auditoría de seguridad, aplicando metodologías estándar de la industria para identificar, analizar y documentar vulnerabilidades en una aplicación web.

---

## 🎯 Objetivo

- Identificar vulnerabilidades explotables en la aplicación objetivo  
- Evaluar su impacto mediante estándares como CVSS  
- Documentar los hallazgos de forma estructurada  
- Proponer medidas de mitigación  

---

## 📌 Enfoque profesional

Este proyecto refleja un flujo completo de auditoría de seguridad:

1. Reconocimiento y análisis  
2. Identificación de vulnerabilidades  
3. Explotación controlada  
4. Evaluación de impacto  
5. Propuesta de mitigaciones  

Este enfoque reproduce escenarios reales de pentesting en entornos profesionales.

---

## 🚨 Vulnerabilidades identificadas

| ID | Vulnerabilidad            | Severidad |
|----|--------------------------|----------|
| 01 | Brute Force              | 🟠 Alta |
| 02 | Command Injection        | 🔴 Crítica |
| 03 | File Inclusion           | 🔴 Crítica |
| 04 | File Upload              | 🔴 Crítica |
| 05 | SQL Injection (Blind)    | 🔴 Crítica |
| 06 | Criptografía débil       | 🟠 Alta |

---

## 📁 Estructura del proyecto

```bash
report/
├── 01_scope.md
├── 02_methodology.md
├── 03_standards_and_frameworks.md
├── 04_executive_summary.md
├── findings/
│   ├── 01_bruteforce.md
│   ├── 02_command_injection.md
│   ├── 03_file_inclusion.md
│   ├── 04_file_upload.md
│   ├── 05_sql_injection.md
│   └── 06_cryptography.md
├── 06_recommendations.md
└── 07_conclusion.md
```
## 🔍 Acceso directo a vulnerabilidades

- [Brute Force](report/findings/01_bruteforce.md)
- [Command Injection](report/findings/02_command_injection.md)
- [File Inclusion](report/findings/03_file_inclusion.md)
- [File Upload](report/findings/04_file_upload.md)
- [SQL Injection](report/findings/05_sql_injection.md)
- [Criptografía débil](report/findings/06_cryptography.md)