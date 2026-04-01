# 🔍 ForensicMaster AI (Digital Forensics & IR)

GPT Especializado: [ForensicMaster AI](https://chatgpt.com/g/g-ySQhVkW2l-forensicmaster-ai)

---

## 🧠 Descripción del Agente

**ForensicMaster AI** es tu investigador forense digital en primera línea. Como analista especialista en **DFIR** (Digital Forensics and Incident Response), el agente está entrenado para reaccionar ante la post-explotación: encontrar qué ocurrió, cómo entró el atacante, qué se llevó y cómo erradicar la persistencia.

Se enfoca en mantener la integridad de la evidencia, asistir en responder incidentes críticos (ramsomware, APTs) y generar la cadena de mando lógica requerida en investigaciones corporativas y policiales o legales.

---

## 🚀 Capacidades Principales

### 🖥️ Análisis Forense en Sistemas (Host Forensics)
- **Windows Forensics:** Análisis profundo del Registro de Windows, Prefetch/Amcache, visor de eventos, MFT (Master File Table) y papeleras de reciclaje.
- **Linux Forensics:** Parsing de bash_history, logs granulares de autenticación, archivos ocultos y análisis de crontabs/persistencia.
- Volcado y examinación de memoria RAM para detectar malware *fileless*, inyecciones de código y credenciales residuales usando frameworks como **Volatility**.

### 📡 Análisis de Red e Inteligencia de Amenazas
- Inspección paquete a paquete mediante archivos capture (`.pcap` / `.pcapng`).
- Extracción activa de firmas, malware o binarios ofuscados a través del tráfico detectado (Wireshark/Tshark).
- Mapeo de exfiltración de datos, comando y control (C2) y *beaconing*.

### ⏳ Arquitectura de Incidentes (Incident Response)
- Diseño estocástico y lineal del tiempo computacional (Timeline Analysis) para recrear cada paso del atacante.
- Mitigación de brotes de Ransomware: Identificación de familia de cifrado y notas de rescate.
- Técnicas eficientes para aislamiento de sistemas y salvaguarda de la Cadena de Custodia técnica.

---

## 🛠️ Herramientas y Casos Prácticos

### Soporte Analítico de Tools
Ayuda o comandos listos para sacar provecho real a herramientas como:
- *Volatility 2/3*
- *Autopsy / Sleuth Kit*
- *FTK Imager*
- *Plaso (Log2Timeline)*

### Uso recomendado
**Ataque a una BD:** *"Mi servidor fue cifrado y tengo un volcado del disco .E01. ¿Cómo busco el entry point en los logs de RDP o IIS sin romper la evidencia?"*
El agente te entregará un paso-a-paso metodológico para proteger los hashes iniciales, cargar la evidencia como *Read-Only* y extraer las métricas exactas.

---

## ⚖️ Principio de Transparencia DFI
Todo procedimiento sugerido sigue protocolos formales. El objetivo es que la evidencia, al final del camino de extracción y análisis, sea defendible y auditable en cualquier tribunal lógico o revisión corporativa.
