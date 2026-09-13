# Arquitectura del laboratorio

## Objetivo
Describir las máquinas virtuales, los recursos asignados y la red del SOC HomeLab.

## Máquinas virtuales previstas

|   Máquina   |    Sistema operativo    | RAM  | CPU virtuales | Disco máximo dinámico |
|-------------|-------------------------|------|---------------|-----------------------|
| Splunk-SOC  | Ubuntu Server 24.04 LTS | 4 GB |       2       |         40 GB         |
| Windows-SOC | Windows 11              | 4 GB |       2       |         64 GB         |

## Estructura
El equipo Windows generará registros de seguridad y eventos de Sysmon.
Splunk Universal Forwarder los enviará al servidor Splunk para su indexación, búsqueda y análisis.




























