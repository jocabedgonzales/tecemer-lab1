# Semana 09 - Simulación de robots UR10 con RoboDK

## Descripción del proyecto

Este proyecto desarrolla simulaciones de manipulación de cajas utilizando robots industriales UR10 mediante RoboDK y programación en Python.

Se trabaja con una estación de pick and place y una estación con dos robots UR10 para estudiar la transferencia de objetos.

## Objetivos

- Configurar estaciones robóticas en RoboDK.
- Simular operaciones de recogida y colocación de cajas.
- Crear objetivos de movimiento (Targets).
- Programar trayectorias mediante Python.
- Analizar una posible transferencia de cajas entre dos robots UR10.

## Herramientas utilizadas

- RoboDK
- Python
- Visual Studio Code
- Git y GitHub
- Robot industrial UR10
- Pinza RobotiQ 2F-85
- Pinza de vacío SMC ZXP7A01

## Archivos del proyecto

| Archivo | Descripción |
|---|---|
| `PICK1.rdk` | Primera estación de simulación en RoboDK. |
| `PICK2.rdk` | Segunda estación de simulación en RoboDK. |
| `DOS_UR10_OBJETIVOS_Y_TRANSFERENCIA.py` | Script de generación de objetivos y simulación de transferencia, si se incorpora a esta carpeta. |

## Procedimiento

1. Crear la estación en RoboDK.
2. Incorporar los robots UR10.
3. Añadir las herramientas de agarre.
4. Incorporar la mesa y la caja.
5. Configurar los objetivos de movimiento.
6. Ejecutar las simulaciones.
7. Verificar el alcance de los robots y revisar posibles colisiones.
8. Documentar los resultados.

## Resultados esperados

- Visualización de las estaciones robóticas.
- Generación automática de objetivos.
- Simulación de trayectorias de los robots.
- Evaluación de la transferencia de una caja entre dos UR10.

## Observaciones

La transferencia entre robots debe validarse en RoboDK. La simulación visual de sujeción no garantiza que el agarre físico sea viable.

## Autor

Proyecto académico de robótica industrial - Semana 09.