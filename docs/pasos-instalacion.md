# Pasos de Instalación y Configuración

Este documento describe el proceso de instalación y configuración
de un servidor Windows Server 2022 utilizado como Controlador de Dominio
en un entorno educativo de laboratorio.

## 1. Instalación del sistema operativo
Se realizó la instalación de Windows Server 2022 (Desktop Experience),
seguida de la configuración inicial del servidor.

Acciones principales:
- Asignación de nombre al servidor
- Configuración de dirección IP estática
- Ajustes iniciales del sistema

## 2. Instalación de roles y características
Se instalaron los roles necesarios para la administración centralizada
del dominio.

Roles instalados:
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server

## 3. Promoción a Controlador de Dominio
El servidor fue promovido a Controlador de Dominio, creando un nuevo bosque
para el entorno educativo.

Configuración realizada:
- Creación de un nuevo bosque
- Dominio: colegiodm.local
- Nivel funcional por defecto

## 4. Configuración del servicio DNS
Durante la promoción del dominio se creó automáticamente la zona DNS
integrada con Active Directory, utilizada para la resolución de nombres
interna del dominio.

## 5. Configuración del servicio DHCP
Se configuró el servicio DHCP para la asignación automática de direcciones IP
a los equipos del dominio.

Acciones realizadas:
- Creación de un ámbito DHCP
- Definición de rango de direcciones
- Configuración de gateway y servidor DNS

## 6. Verificación del entorno
Se verificó el correcto funcionamiento de los servicios instalados,
confirmando que el servidor opera correctamente como Controlador de Dominio.
