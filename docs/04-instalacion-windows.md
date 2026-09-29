# Instalación de Windows

## Objetivo

El objetivo de esta fase es preparar una máquina virtual Windows que actuará como equipo monitorizado del SOC Homelab.

En ella se instalará:

- Sysmon: para registrar actividad del sistema.
- Splunk Universal Forwarder: para enviar los eventos al servidor Splunk.

Esta máquina también será utilizada para realizar las simulaciones de los escenarios de investigación.

## Configuración prevista

|           Recurso            |                   Asignación                  |
|------------------------------|-----------------------------------------------|
| Plataforma de virtualización |                   VirtualBox                  |
| Sistema operativo            |      Windows 11 Enterprise de evaluación      |
| Arquitectura                 |                     x86_64                    |
| Memoria RAM                  |                      4 GB                     |
| Procesadores virtuales       |                       2                       |
| Disco y red                  |           Pendientes de configurar            |

## Descarga del instalador
Para este laboratorio se ha elegido Windows 11 Enterprise de evaluación, con un periodo de uso de 90 días.
La descarga se realiza desde el siguiente enlace oficial:

[Centro de evaluación de Microsoft — Windows 11 Enterprise](https://www.microsoft.com/es-es/evalcenter/download-windows-11-enterprise)

Los pasos para obtener el instalador son:

1. Acceder a la página de Microsoft.
2. Seleccionar la ISO de Windows 11 Enterprise de 64 bits.
3. Elegir el idioma.
4. Guardar el archivo ISO en el equipo anfitrión.

La ISO se cargará en VirtualBox como medio de instalación de la nueva máquina virtual. No es necesario crear un USB de instalación.
