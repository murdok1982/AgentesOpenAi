# 🪟 Windows Admin Pro (`windows_product_admin_agent_v1`)

GPT Especializado: [Windows Admin Pro](https://chatgpt.com/g/g-681b6e6cae30819193b79212935d8f3b-windows-admin-pro)

> **Senior Windows Systems Administrator & Microsoft Security Specialist**  
> Orientado fuertemente a entornos *enterprise*: on-prem, híbrido y cloud-native.

---

## 📌 Descripción del Agente

`Windows Admin Pro` es un agente de Inteligencia Artificial especializado en la administración avanzada y operativa técnica integral de entornos corporativos de Microsoft. Está diseñado para actuar como tu **Senior Systems Administrator**, proporcionando soporte técnico profundo, herramientas de automatización, directrices de hardening y resolución de problemas (troubleshooting) en infraestructuras Windows y cloud computing sobre Microsoft Azure.

Integra nativamente buenas prácticas dictadas por estándares y marcos internacionales de seguridad industrial como **ENS, CIS y NIST**, alineándose rigurosamente con documentación certificada como las guías **CCN-STIC** (p. ej., configuración segura y bastionado de Windows Server y ecosistema Defender).

---

## 🚀 Capacidades Principales

### 🖥️ Administración Técnica de Windows Server
- Servicios de Dominio de Active Directory (AD DS, protocolos LDAP, Kerberos).
- Administración, troubleshooting y Hardening de *Group Policy* (GPOs).
- Configuración y mantenimiento de arquitecturas DNS / DHCP / IIS / PKI empresariales.
- Hipervisores y virtualización corporativa nativa con **Hyper-V**.
- Máximo dominio integral desde Windows Server 2012 hasta Windows Server 2022 (incluyendo arquitecturas *Secure Core*).

> 📚 *Totalmente basado en prácticas del mundo real para el despliegue y la operación continua de servicios altamente críticos.*

### ☁️ Entornos Híbridos y Microsoft Azure
- Gestión de Azure VMs, escalado de Networking y Storage.
- Administración y bastionado de **Microsoft Entra ID** (anteriormente Azure AD).
- Implementación de ecosistemas híbridos robustos utilizando **Azure Arc**.
- Políticas de de acceso estricto, Conditional Access y modelado Zero Trust Network Access.
- Automatización mediante flujos, Runbooks, plantillas ARM y código Bicep.

### 🛡️ Seguridad Avanzada (Core Strength)
- Operativa maestra con el ecosistema de **Microsoft Defender**:
  - Microsoft Defender for Endpoint (EDR/XDR).
  - Microsoft Defender for Identity.
  - Microsoft Defender for Cloud (CSPM/CWPP).
- Bastionado (Hardening) de sistemas estandarizado según rigurosas normativas:
  - ENS (Esquema Nacional de Seguridad).
  - Listas de control del CCN-STIC.
  - Benchmarks CIS.

> 📌 **Ejemplo de especialización:** Explotar todas las capacidades de *Defender for Endpoint* para prevenir, asilar, detectar anomalías persistentes y responder agresivamente a ciberamenazas avanzadas en los *endpoints* afectados de la organización.

### 🔐 Cumplimiento y Gobernanza de Seguridad
- Diseño e implementación imperativa de políticas orgánicas:
  - Principio de Mínimo Privilegio (Least Privilege).
  - Arquitecturas Zero Trust reales.
  - Multi-Factor Authentication (MFA) & Conditional Access adaptativo.
- Infraestructuras de auditoría profunda y logging centralizado en toda la flota.
- Envío e integración de telemetría a plataformas de análisis rápido (SIEM / SOC).
- Configuración de envío seguro de gestión de eventos (Windows Event Forwarding, WinRM remoto securizado).

### ⚙️ Automatización e Infraestructura como Código (IaC)
- Operaciones nativas en **PowerShell avanzado** (su habilidad primaria/core).
- Declaraciones mediante Windows Desired State Configuration (DSC).
- Automatización CI/CD para despliegue ininterrumpido a escala de componentes del SO.
- Extensiva creación de scripts orientados al hardening agresivo, auditoría completa o remediación automatizada con zero-touch.

---

## 💻 Ejemplos Prácticos
El agente siempre ilustrará sus explicaciones entregándote los comandos más limpios, seguros y asertivos, listos para tu consola, ejemplo:

```powershell
# Comprobar meticulosamente el estado y módulo de seguridad activo de Defender
Get-MpComputerStatus

# Listar exhaustivamente los objetos de políticas (GPOs) aplicadas exitosamente sobre un objeto/usuario
gpresult /R
```
