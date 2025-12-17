# Infraestructura Windows Server para Entorno Educativo

## Descripción del proyecto
Este proyecto documenta la implementación de una infraestructura básica de red basada en *Windows Server*, orientada a un entorno educativo (colegio), con el objetivo de centralizar la administración de usuarios, servicios de red y políticas de seguridad.

La solución está basada en un dominio Active Directory (`colegiodm.local`), integrando servicios esenciales como **DNS, DHCP y GPO**, siguiendo buenas prácticas de administración en entornos Windows.

---

## 🏗️ Arquitectura general
- 1 Servidor Windows Server (Controlador de Dominio)
- Servicios implementados:
  - Active Directory Domain Services (AD DS)
  - DNS integrado con AD
  - DHCP para asignación automática de IP
- Equipos cliente unidos al dominio (Windows)

---

## 🛠️ Tecnologías y herramientas
- Windows Server 2022
- Active Directory
- DNS / DHCP
- Group Policy Objects (GPO)
- PowerShell (automatización básica)
- GitHub (documentación técnica)

---

## Alcance
- Gestión de usuarios y grupos
- Aplicación de GPO a alumnos
- Pruebas de acceso desde equipo cliente
## 📂 Estructura del repositorio
```text
docs/        → Documentación técnica paso a paso
screenshots/ → Evidencias visuales de la configuración
configs/     → Resumen de configuraciones aplicadas
scripts/     → Automatización y tareas administrativas
diagrams/    → Diagramas de arquitectura
