# Pasos de Instalación y Configuración del Servidor

Este documento describe los pasos realizados para la instalación y configuración
del servidor Windows Server 2022 que actúa como Controlador de Dominio del entorno
educativo basado en el dominio *colegio.dm*.

> Nota: El dominio y el bosque ya se encontraban implementados al momento de
> documentar este proyecto. Por ello, los pasos aquí descritos corresponden
> al proceso real ejecutado previamente y verificado durante el laboratorio.

---

## 1. Instalación del sistema operativo
- Instalación de Windows Server 2022 (Desktop Experience)
- Asignación de nombre al servidor
- Configuración de dirección IP estática
- Configuración inicial del sistema

📸 Evidencia:
- Server Manager – Dashboard
<img width="1363" height="631" alt="image" src="https://github.com/user-attachments/assets/06beec76-e81a-436b-bc11-6d79922b3298" />

---

## 2. Instalación de roles y características
Roles instalados:
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server

📸 Evidencia:
- Roles visibles en Server Manager
<img width="1252" height="523" alt="image" src="https://github.com/user-attachments/assets/e99b557f-77d2-40df-9a2b-7855b3081daa" />

---

## 3. Promoción a Controlador de Dominio
- Creación del nuevo bosque
- Dominio configurado: **colegio.dm**
- Nivel funcional por defecto

📸 Evidencia:
- Dominio visible en Active Directory Users and Computers
<img width="751" height="531" alt="image" src="https://github.com/user-attachments/assets/763eb76d-c57a-46f3-80bb-378ebc00d7e5" />

---

## 4. Configuración del servicio DNS
- Zona directa creada automáticamente: `colegio.dm`
- Verificación de registros del servidor

📸 Evidencia:
- Zona DNS
<img width="924" height="525" alt="image" src="https://github.com/user-attachments/assets/86996163-8ce6-4a6b-9e43-56ce04c991b0" />

---

## 5. Configuración del servicio DHCP
- Creación del ámbito de red
- Asignación automática de direcciones IP
- Configuración de gateway y DNS

📸 Evidencia:
- Scope DHCP activo

---

## 6. Verificación del entorno
- Servicios operativos correctamente
- Servidor funcionando como Controlador de Dominio

📸 Evidencia:
- Server Manager sin alertas

