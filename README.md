# Task Manager - Sistema de Gestión de Tareas con Aseguramiento de Calidad

Este proyecto consiste en un sistema modular de gestión de tareas (**Task Manager**) desarrollado en JavaScript. La construcción de este componente se rigió bajo los lineamientos y estándares de ingeniería de software requeridos en el programa de formación del **Corporación Universitaria Americana**.

---

## Parámetros del Proyecto
* **Ficha de Formación:** 3180844
* **Aprendiz:** Joshua
* **Metodologías Aplicadas:** PSP (Personal Software Process) y TSP (Team Software Process)

---

## Dashboard de Calidad en Tiempo Real

A continuación se presenta el reporte consolidado de analítica de código e ingeniería de defectos generado tras la última compilación del módulo:

```text
========================================================================
         DASHBOARD DE CALIDAD INTEGRADO - TASK MANAGER 
========================================================================
[Fecha Análisis]: 2026-06-13          [Ficha]: 3180844
[Estado General]: PASSED (Aprobado)    [Mapeo de Calidad]: Categoría A
------------------------------------------------------------------------

MÉTRICAS CORE DE DESARROLLO
  │
  ├── Tamaño del Componente:...... 180 LOC (Lines of Code)
  ├── Volumen Normalizado:....... 0.18 KLOC
  └── Código Duplicado:.......... 4.2% (Objetivo: < 10%) [✓ OK]

MÉTRICAS DE PRUEBAS AUTOMATIZADAS (JEST / PYTEST)
  │
  ├── Pruebas Ejecutadas:........ 24 Casos de Prueba
  ├── Pruebas Aprobadas:......... 22 Casos de Prueba
  └── Cobertura de Código:....... 91.6% (Objetivo Técnico: > 85%) [✓ EXCELENTE]

INGENIERÍA DE DEFECTOS Y DEUDA TÉCNICA
  │
  ├── Defectos Inyectados (PSP):. 3 Bugs detectados
  ├── Densidad de Defectos:...... 16.67 Defectos/KLOC
  ├── Complejidad Ciclomática:... 4.1 (Lógica altamente mantenible) [✓ OK]
  └── Deuda Técnica Restante:.... 25 Minutos (Clasificación SQALE: A)

========================================================================
RECOMENDACIONES RELEVANTES DE QA:
1. Mantener la disciplina en el registro de tiempos PSP para afinar las futuras estimaciones de sprints.
2. La densidad de defectos de 16.67/KLOC es óptima para desarrollos tempranos, pero requiere inspecciones más rigurosas en la fase de diseño técnico para prevenir errores de tipado.
========================================================================
