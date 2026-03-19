# Finance Ops Mock Close Pack — Iberia Services S.L. | Simulación de Cierre Mensual | 2026-02

![Proyecto Portfolio](https://img.shields.io/badge/Proyecto_Portfolio-Finance_Ops-blue)
![Cierre Mensual](https://img.shields.io/badge/Cierre_Mensual-2026--02-1f6feb)
![Entidad](https://img.shields.io/badge/Entidad-Empresa_Espanola_Mediana-darkgreen)
![Cobertura](https://img.shields.io/badge/Cobertura-AR%20%7C%20AP%20%7C%20Tesoreria%20%7C%20R2R%20%7C%20IVA-orange)
![Estado](https://img.shields.io/badge/Estado-Listo_para_Signoff-success)

Simulación práctica de **cierre mensual** para una **única entidad española de tamaño mediano**, creada para demostrar capacidad operativa en **AR, AP, Tesorería, R2R e IVA** dentro de un entorno controlado de Finance Operations.

Este proyecto fue diseñado para mostrar cómo puede gestionarse un cierre con **controles de integridad, reporting ERP, tie-outs, gestión de incidencias, soporte de asientos contables, gobernanza del checklist de cierre, seguimiento de pendientes y lógica de signoff**.

---

## Tabla de Contenidos

- [Resumen Ejecutivo](#resumen-ejecutivo)
- [Alcance](#alcance)
- [Objetivo](#objetivo)
- [Qué Demuestra Este Proyecto](#qué-demuestra-este-proyecto)
- [Resultado del Mock Close](#resultado-del-mock-close)
- [Controles Clave Ejecutados](#controles-clave-ejecutados)
- [Incidencias Identificadas y Resueltas](#incidencias-identificadas-y-resueltas)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [Ruta Sugerida de Revisión](#ruta-sugerida-de-revisión)
- [Capturas](#capturas)
- [Competencias Demostradas](#competencias-demostradas)
- [Por Qué Esto Importa](#por-qué-esto-importa)
- [Notas para Recruiters](#notas-para-recruiters)
- [Descargo de Responsabilidad](#descargo-de-responsabilidad)

---

## Resumen Ejecutivo

Este repositorio contiene un **mock close pack de febrero de 2026** para **Iberia Services S.L.**, una entidad española B2B de servicios simulada con **moneda funcional EUR**.

El propósito del proyecto no es solo reproducir salidas contables, sino demostrar cómo un profesional de Finance Ops / R2R abordaría el cierre desde una perspectiva de **control, trazabilidad y resolución**:

- verificar la integridad del periodo antes de ejecutar el cierre
- ejecutar los reportes críticos del ERP
- reconciliar subledgers y cuentas de control
- identificar y clasificar discrepancias
- preparar y soportar los asientos contables de cierre
- actualizar el checklist de cierre
- documentar los pendientes y la responsabilidad de seguimiento
- preparar el soporte final para signoff

Este es un **caso práctico de control de cierre**, no solo un paquete de plantillas contables.

---

## Alcance

- **Entidad:** Iberia Services S.L.
- **País:** España
- **Tamaño de la entidad:** Mediana
- **Moneda funcional:** EUR
- **Fecha de cierre:** 2026-02-28
- **Cobertura de procesos:** AR / O2C, AP / P2P, Tesorería, R2R, IVA
- **Lógica ERP simulada:** reporting y controles de cierre estilo SAP FI / NetSuite / Odoo

---

## Objetivo

Reunir las actividades clave del cierre en una única rutina mensual controlada:

1. Revisar la integridad del periodo y los prerrequisitos del cierre  
2. Ejecutar los reportes críticos del ERP  
3. Realizar los tie-outs clave en AR, AP, Banco, IVA y TB  
4. Abrir y gestionar discrepancias mediante un issue log  
5. Preparar y soportar los asientos contables de cierre  
6. Actualizar el checklist de cierre y el estado de completitud  
7. Dar seguimiento a open items y pendientes no bloqueantes  
8. Preparar la documentación de signoff  

---

## Qué Demuestra Este Proyecto

Este proyecto está pensado para mostrar capacidad práctica en:

- **ejecución de cierre mensual**
- **lógica de conciliación subledger a GL**
- **identificación de incidencias y gestión de causa raíz**
- **preparación de asientos contables y disciplina de soporte**
- **gobernanza del checklist de cierre**
- **visibilidad y responsabilidad sobre pendientes**
- **preparación para signoff con evidencia y trazabilidad**

En otras palabras, este repositorio no trata solo de “saber contabilidad”. Trata de mostrar cómo un cierre es **controlado, documentado y llevado a término**.

---

## Resultado del Mock Close

| Métrica | Resultado |
|---|---:|
| Tie-outs cerrados post-ajuste | **6 / 6** |
| Incidencias resueltas | **5** |
| Pendientes abiertos | **1** |
| Evaluación del riesgo residual | **Bajo** |
| Impacto material en el cierre 2026-02 | **Ninguno** |
| Asientos de cierre preparados/posteados | **6** |
| Recomendación final | **Listo para signoff con 1 pendiente no bloqueante** |

---

## Controles Clave Ejecutados

El mock close incluye las siguientes conciliaciones y controles base:

- **Subledger AR vs GL**
- **Subledger AP vs GL**
- **Banco vs GL**
- **Libro de IVA vs GL**
- **TB vs totales GL**
- **Aging vs open items**

Cada control está respaldado por:

- un objetivo de revisión definido
- una lógica de control
- un resultado documentado
- una ruta de evidencia vinculada
- un resultado apto para signoff del revisor

---

## Incidencias Identificadas y Resueltas

Ejemplos de discrepancias incluidas en la simulación:

- cobro de cliente no aplicado que requería revisión de asignación
- factura AP bloqueada pendiente de validación
- partida bancaria no conciliada que requería aclaración
- incidencia de clasificación de IVA que requería reclasificación
- accrual faltante identificado durante la revisión de cierre
- un pendiente residual no bloqueante dejado abierto con owner y seguimiento documentados

La intención es mostrar no solo el resultado de la conciliación, sino también el **razonamiento operativo detrás de la ruta de resolución**.

---

## Estructura del Repositorio

```text
finance-ops-mock-close-spanish-entity-2026-02/
│
├── README.md
├── 01_Integrity/
│   └── close_integrity_check.xlsx
├── 02_Reports/
│   └── erp_report_index.xlsx
├── 03_Tieouts/
│   ├── AR_to_GL_tieout.xlsx
│   ├── AP_to_GL_tieout.xlsx
│   ├── Bank_to_GL_tieout.xlsx
│   ├── VAT_to_GL_tieout.xlsx
│   ├── TB_to_GL_totals.xlsx
│   └── Aging_vs_Open_Items.xlsx
├── 04_Issues/
│   └── Issue_Log.xlsx
├── 05_JE/
│   ├── JE_Log.xlsx
│   └── JE_Support/
├── 06_Checklist/
│   └── Close_Checklist.xlsx
├── 07_Pending/
│   └── Pending_Items_Memo.md
├── 08_Signoff/
│   └── Signoff_Memo.md
└── 09_Evidence/
    └── Evidence_Index.xlsx
```

---

## Ruta Sugerida de Revisión

Para una revisión rápida pero significativa del proyecto, sigue este orden:

revisión de integridad

índice de reportes ERP

tie-outs principales

issue log

JE log y soportes

checklist de cierre

memo de pendientes

memo de signoff

Esta secuencia refleja cómo un cierre controlado sería normalmente revisado por un team lead, controller, reviewer o hiring manager.

---

Capturas
Checklist de cierre

<img width="1329" height="187" alt="image" src="https://github.com/user-attachments/assets/d48feb32-40b4-46a1-8241-fa7c1429baef" />

Tie-out AR

<img width="476" height="240" alt="image" src="https://github.com/user-attachments/assets/0c78d0ae-dc01-4eb6-92d5-e2c35d1a87fb" />

Conciliación Bancaria 

<img width="464" height="254" alt="image" src="https://github.com/user-attachments/assets/38b94c45-0345-4f57-96a1-a7c66e50435d" />

Issue Log

<img width="1215" height="261" alt="image" src="https://github.com/user-attachments/assets/5a4ca920-a91a-482a-8525-1619318a3a59" />
<img width="1202" height="278" alt="image" src="https://github.com/user-attachments/assets/d245e95f-835c-4c0b-9e48-a0e1eac9d653" />

JE Log

<img width="1210" height="272" alt="image" src="https://github.com/user-attachments/assets/ba7d27d2-84fc-4631-a9a5-60d55924f549" />
<img width="1277" height="330" alt="image" src="https://github.com/user-attachments/assets/0dbff596-d005-462f-9b31-baa87c11c8f4" />

Memo Signoff

<img width="736" height="546" alt="image" src="https://github.com/user-attachments/assets/49d579f1-56ee-4840-af70-88173537ed39" />
<img width="1237" height="478" alt="image" src="https://github.com/user-attachments/assets/ef674c25-b1e4-45e9-9766-b4f7b1b92654" />

---

## Competencias Demostradas

Finance Operations / Contabilidad

lógica de cierre en AR, AP, Tesorería, R2R e IVA

conciliaciones subledger a GL

revisión de cuentas de control

soporte de accruals y reclasificaciones

análisis de discrepancias y clasificación de causa raíz

lógica de signoff y gobernanza de cierre

Proceso y Control

ownership de incidencias y lógica de escalado

disciplina de checklist de cierre

indexación de evidencia y trazabilidad

seguimiento de pendientes

distinción entre diferencias temporales y errores reales

documentación lista para revisión

Herramientas y Forma de Trabajo

packs de control basados en Excel

lógica de reporting ERP inspirada en SAP FI / NetSuite / Odoo

documentación estructurada de cierre

presentación de evidencia con nivel portfolio

---

## Por Qué Esto Importa

Este proyecto fue construido para demostrar el tipo de pensamiento estructurado que se espera en Finance Operations, R2R, GL close, AP, AR y roles de soporte contable:

comprensión del flujo end-to-end del proceso

capacidad para distinguir diferencias temporales de errores contables reales

foco en cuentas de control, evidencia de soporte y trazabilidad

disciplina para documentar ownership, acciones y estado de signoff

preparación para operar en un entorno de cierre controlado desde el primer día

---

## Notas para Recruiters

Este repositorio es especialmente relevante para roles como:

Finance Operations Analyst

R2R / GL Analyst

AP / AR Analyst

Junior Accountant / Accountant

Closing & Reconciliation Analyst

Accounting Operations Specialist

---

## Qué Demuestra Este Proyecto

puedo trabajar con una lógica de cierre estructurada

entiendo cómo las conciliaciones y los controles soportan un cierre correcto

sé documentar discrepancias, preparar JEs y dejar evidencia trazable

puedo explicar las actividades de cierre en términos de proceso, riesgo, control, prioridad y signoff

---

## Descargo de Responsabilidad

Este repositorio contiene una simulación de portfolio creada únicamente con fines de formación y demostración.

No contiene datos confidenciales, extractos reales de ERP en producción ni trabajo realizado para un empleador real.
La entidad, los saldos, las discrepancias y los resultados del cierre fueron creados para demostrar entendimiento práctico de un cierre mensual controlado en un contexto de Finance Ops.

---

## Nota Final

Este proyecto forma parte de un portfolio más amplio de Finance Ops / Contabilidad enfocado en construir evidencia práctica, orientada a auditoría y atractiva para recruiters, sobre capacidad operativa en entornos de cierre mensual.
