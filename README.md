# homelab-soc
SOC Homelab - Detección e investigación con Splunk 
Este proyecto consistirá en la creación de un SOC homelab, con el objetivo de profundizar conceptos relacionados con el análisis de logs, monitorización de equipos e investigación de incidentes desde la perspectiva de un analista SOC. 

Para ello, se documentará el proceso completo: 
  1. Diseño e instalación del entorno
  2. Recolección y centralización de registros en Splunk
  3. Simulación de actividad sospechosa y análisis de evidencias

Durante el proceso, se simulará cuatro escenarios:
  1. Análisis de intentos de acceso fallidos repetidos
  2. Ejecución sospechosa de Powershell
  3. Persistencia mediante una tarea programada
  4. Ejecución de archivo malicioso

# Objetivos
- Centralizar los registros de un equipo Windows en Splunk
- Configurar la monitorización mediante Sysmon y registros de eventos de Windows
- Crear consultas SPL con el objetivo de analizar actividad sospechosa
- Documentar las conclusiones y propuesta de respuesta

# Arquitectura 
Para el montaje de este proyecto haremos uso de dos máquinas virtuales: 
- Servidor Linux: Servidor Linux: Ubuntu Server 24.04 LTS y Splunk Enterprise. Esta máquina se encargará de recibir, indexar y analizar los registros, así como de ejecutar las reglas de detección.
- Equipo Windows: Uso de Sysmon y Splunk Universal Forwarder. Esta máquina se encargará de generar y enviar los eventos utilizados en las investigaciones.

La asignación inicial prevista es de 4 GB de RAM y 2 CPU virtuales por máquina. 

# Metodología de investigación
Cada escenario incluirá:
1. Descripción de la actividad simulada.
2. Fuentes de registros y configuración necesarias.
3. Consulta o regla de detección.
4. Evidencias y cronología de los acontecimientos.
5. Análisis de posibles explicaciones benignas y falsos positivos.
6. Conclusión, alcance observado y medidas de respuesta propuestas.

# Organización del repositorio
- docs/: arquitectura, instalación y configuración.
- escenario1/
- escenario2/
- escenario3/
- escenario4/
- screenshots/: capturas para respaldar la investigación. 



















