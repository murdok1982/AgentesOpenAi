# 🏭 Cyber Industrial Expert (ICS/OT Security)

GPT Especializado: [Cyber Industrial Expert](https://chatgpt.com/g/g-68165162e8ec8191ada432d1c5221995-cyber-industrial-expert)

---

## 🧠 Descripción del Agente

**Cyber Industrial Expert** es un asistente avanzado centrado exclusivamente en la ciberseguridad industrial y operativa. Se especializa en la protección, auditoría y mitigación de amenazas en sistemas **ICS (Industrial Control Systems), SCADA y entornos OT (Operational Technology)**.

A diferencia de la ciberseguridad corporativa (IT), este agente entiende que en el mundo industrial la **disponibilidad y la seguridad física (Safety)** son la máxima prioridad, operando siempre bajo la premisa de no interrumpir los procesos críticos.

---

## 🚀 Capacidades Principales

### ⚙️ Arquitectura Industrial y Marcos de Trabajo
- Diseño y segmentación de redes basado en el **Modelo Purdue** (Reference Architecture).
- Implementación y cumplimiento de normativas clave: **ISA/IEC 62443, NIST SP 800-82, NERC CIP**.
- Asistencia en la integración segura entre capas IT y OT, reduciendo el área de exposición técnica.

### 🛡️ Seguridad OT/SCADA
- Hardening activo en componentes físicos: **PLC, RTU, controladores DCS**.
- Aseguramiento de interfaces hombre-máquina (**HMI**) y estaciones de ingeniería (EWS).
- Análisis profundo de protocolos industriales (Modbus TCP, DNP3, OPC UA, S7 Comm, BACnet).
- Gestión de entornos "Air-gapped" y diodos de datos para aislamientos físicos.

### 🔬 Evaluación de Amenazas e Incidentes Industriales
- Conocimiento técnico de malware diseñado contra ICS (e.g., *Stuxnet, Industroyer, Triton*).
- Análisis de vectores de ataque por actualizaciones falsas, ingeniería social a operadores o brechas en la cadena de suministro de hardware.
- Estrategias de visibilidad y monitoreo pasivo (Passive asset discovery) mediante análisis de tráfico industrial.

---

## 🛠️ Ejemplos de Casos de Uso

**Entrada del Usuario:**
> *"Tengo una red de variadores que operan vía Modbus TCP conectados sin segmentar a la red IT. ¿Cómo puedo securizar la planta sin apagar los PLCs?"*

**Análisis del Agente:**
1. Evaluará el riesgo crítico (Modbus carece de autenticación nativa).
2. Propondrá una estrategia de micro-segmentación (Firewalls industriales, DMZ).
3. Detallará el despliegue del Modelo Purdue pasivo.
4. Mostrará controles compensatorios de red (Monitoreo de red pasivo/IDS industrial).

---

## ⚠️ Filosofía: Safety First
Toda sugerencia, script o táctica entregada por el agente considera **primero la seguridad humana e industrial**. Evita categóricamente sugerir escaneos activos agresivos (como un escaneo de puertos masivo con Nmap) sobre un entorno OT, ya que podrían colgar los PLC y causar incidentes catastróficos.
