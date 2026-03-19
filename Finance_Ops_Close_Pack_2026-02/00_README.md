# Mock Close Pack — Iberia Services S.L. — 2026-02

## Scope
Cierre simulado mensual para una sola compañía española de tamaño mediano, con base contable en EUR y fecha de cierre 2026-02-28.

## Objetivo
Unir en una sola rutina de cierre los pasos clave:
1. Revisar integridad del periodo
2. Correr reportes ERP críticos
3. Ejecutar tie-outs de AR, AP, Bank, VAT y TB
4. Abrir y gestionar incidencias
5. Preparar y registrar JEs de cierre
6. Actualizar checklist
7. Dejar pendientes trazados
8. Preparar signoff

## Resultado del mock close
- Tie-outs post-ajuste cerrados: **6/6**
- Issues cerradas: **5**
- Pendientes abiertos: **1** (bajo riesgo, sin impacto material en 2026-02)
- JEs de cierre preparados/posteados: **6**
- Recomendación final: **Listo para signoff con 1 pendiente no bloqueante**

## Estructura
- `01_Integrity/`: control de prerrequisitos y completitud
- `02_Reports/`: índice de reportes ERP utilizados
- `03_Tieouts/`: conciliaciones base y resumen de diferencias
- `04_Issues/`: log de incidencias y root cause
- `05_JE/`: JE log y soportes
- `06_Checklist/`: checklist de close y estado
- `07_Pending/`: memo de pendientes
- `08_Signoff/`: memo de signoff
- `09_Evidence/`: índice de evidencias

## Perfil de la entidad simulada
- Entidad: Iberia Services S.L.
- País: España
- Tamaño: mediano
- Moneda funcional: EUR
- Modelo: servicios B2B con AR, AP, tesorería, R2R y VAT operativo
