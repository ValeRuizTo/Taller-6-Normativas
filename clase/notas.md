# 🗒️ Registro de Trabajo en Clase - Taller 6

## 📆 Fecha de la sesión
_21/03/2026_

## 👥 Integrantes presentes
- Valentina Ruiz
- Darek Aljuri 
- Santiago Soler

## 🧠 Actividades realizadas en clase

Describa brevemente qué se hizo durante la sesión:

- ¿Qué se discutió con el equipo?
  
Durante la sesión de trabajo en equipo se realizó la verificación de los aspectos legales, normativos y de cumplimiento aplicables al sistema GobData (Portal de Trámites Ciudadanos). Se aplicó una checklist estructurada basada en la Constitución Política de Colombia (Artículo 15), la Ley 1581 de 2012, y algunos otros decretos y resoluciones del MinTIC y la norma internacional ISO/IEC 27001.
Se discutieron los principales requisitos normativos que aplican a GobData por tratar datos personales y datos sensibles (identidad, historial clínico, antecedentes y certificados digitales). Se analizaron las categorías clave: principios rectores del tratamiento, consentimiento y autorización, derechos de los titulares (Habeas Data), seguridad de la información y protección contra fugas, retención y supresión de datos, roles y responsabilidades, y auditoría con mejora continua. Se identificaron brechas comunes en entidades públicas como la formalización documental, la implementación completa del SGSI y la necesidad de consentimiento granular para datos sensibles.


- ¿Qué decisiones de modelado se tomaron?
  
Se decidió estructurar el análisis por categorías funcionales en lugar de tablas, para facilitar la lectura y el enfoque en cada requisito normativo. Se acordó evaluar cada criterio con cuatro campos claros: Criterio de cumplimiento, Nivel de cumplimiento (Cumple / Parcial / Brecha potencial), Evidencia/Justificación y Recomendación. También se definió que todas las justificaciones se basarían exclusivamente en la normativa colombiana y en la alineación con ISO/IEC 27001:2022 a través del MSPI del MinTIC. Se priorizaron las brechas más críticas relacionadas con seguridad y documentación.
  
- ¿Qué herramientas se usaron (papel, pizarra, draw.io, Astah)?
  
Se utilizo excel para llenar la tabla del checklist general y brechas identificadas

- ¿Qué parte del trabajo se alcanzó a desarrollar?

Se completó el análisis completo de las siete categorías de cumplimiento, se identificaron los niveles de cumplimiento (mayormente Parcial), se justificaron las brechas con base en el tipo de datos sensibles que maneja GobData y se formularon recomendaciones concretas alineadas con la Ley 1581 y la ISO/IEC 27001:2022. Quedó listo el documento principal de verificación normativa. Falta aún desarrollar y organizar la plantilla y el plan de acción detallado para cerrar las brechas identificadas.


## 🧩 Boceto inicial del modelo

### Checklist de cumplimiento normativo

<img width="1544" height="657" alt="image" src="https://github.com/user-attachments/assets/2552c592-9a02-4659-a8c2-c3eca1c5370d" />

<img width="1540" height="640" alt="image" src="https://github.com/user-attachments/assets/0c8219a0-ea33-4beb-ba7f-fec48d2ef50d" />

<img width="1542" height="655" alt="image" src="https://github.com/user-attachments/assets/5e5ad1ff-b674-45b9-a6d6-49ef357c72fd" />

<img width="1550" height="641" alt="image" src="https://github.com/user-attachments/assets/e9680330-db2e-4291-87f1-6ee4e448a7bf" />

<img width="1546" height="665" alt="image" src="https://github.com/user-attachments/assets/b464c400-85ee-4961-a97a-707b24e045b9" />

<img width="1547" height="665" alt="image" src="https://github.com/user-attachments/assets/d1a990c5-16f7-4db0-82ab-f455b8dc36fe" />

Durante la sesión se elaboró y analizó una tabla de checklist de cumplimiento normativo integral para el portal GobData. Esta tabla organiza de manera sistemática todos los controles evaluados, agrupándolos en cuatro grandes categorías: Consentimiento Informado, Aviso de Privacidad, Retención y Eliminación, Transferencia de Datos, ISO/IEC 27001 – SGSI, Protección contra Fugas de Datos (DLP) y Roles y Responsabilidades.
Cada fila de la tabla corresponde a un control específico (identificado con códigos como A1, A2, B1, C1, D1, etc.) y contiene la siguiente información:

- Criterio / Requisito: Describe el requisito normativo exacto que debe cumplirse, haciendo referencia directa a la Ley 1581 de 2012, el Decreto 1377 de 2013 o a controles específicos de la norma ISO/IEC 27001:2022.
- Estado actual del sistema: Presenta una evaluación objetiva de cómo GobData cumple (o no) con ese requisito en su estado actual, destacando fortalezas o deficiencias observadas.
- Brecha identificada: Detalla de forma clara las fallas o ausencias encontradas en el portal.
- Recomendación: Propone acciones concretas y prácticas para cerrar la brecha detectada.

La tabla utiliza un código de colores visual para facilitar su lectura:

✅ Verde indica controles que se cumplen satisfactoriamente.
⚠️ Amarillo señala cumplimiento parcial o brechas moderadas.
❌ Rojo identifica brechas críticas o incumplimientos graves.

Esta checklist combina los requisitos legales colombianos (principalmente la Ley 1581 y sus decretos reglamentarios) con los controles internacionales de la ISO/IEC 27001:2022, adaptados al contexto del Modelo de Seguridad y Privacidad de la Información (MSPI) del MinTIC. Su propósito es ofrecer una visión completa y estructurada del nivel de cumplimiento actual de GobData, permitiendo identificar rápidamente las áreas de mayor riesgo y priorizar las acciones correctivas necesarias.

### Brechas identificadas

<img width="1599" height="647" alt="image" src="https://github.com/user-attachments/assets/39b2d250-9d5e-4c8a-bbc6-94ea61c22fe9" />

<img width="1609" height="653" alt="image" src="https://github.com/user-attachments/assets/6fa3b6c4-5af8-4b9a-b800-b678545ac032" />

<img width="1614" height="553" alt="image" src="https://github.com/user-attachments/assets/75131f49-b593-4fc9-bf0c-7ee8fbed7872" />

La tabla está organizada en las siguientes columnas:

- Categoría: Agrupa las brechas según el tema normativo al que pertenecen (Consentimiento Informado, Retención y Eliminación de Datos, Control de Acceso Privilegiado, Prevención de Fugas (DLP), Vigilancia Normativa, Gestión de Proveedores, Designación del Oficial de Protección de Datos, Gestión de Incidentes, Continuidad del Negocio y Monitoreo SIEM).
- Brecha Identificada: Describe de manera concreta y específica el incumplimiento o la deficiencia encontrada en el sistema.
- Riesgo Asociado: Explica las consecuencias que puede generar cada brecha, tanto desde el punto de vista legal y regulatorio (posibles sanciones de la SIC), operativo, reputacional como de seguridad (fugas de datos, exposición masiva de información sensible de los ciudadanos).
- Recomendación Prioritaria: Propone acciones correctivas claras, realizables y con plazos sugeridos para mitigar o eliminar la brecha.
Nivel de Prioridad: Clasifica cada brecha según su urgencia e impacto en tres niveles: ALTA (crítica), MEDIA o BAJA, permitiendo al equipo y a la entidad priorizar los esfuerzos de remediación.

Esta tabla destaca especialmente las brechas de mayor riesgo, entre las que se encuentran la ausencia de consentimiento diferenciado para datos sensibles, la falta de una política formal de retención y eliminación de datos, la inexistencia de controles DLP (Data Loss Prevention), cuentas privilegiadas sin autenticación multifactor (MFA), y la falta de designación formal del Oficial de Protección de Datos (DPO).

La tabla de brechas sirve como herramienta de gestión y priorización, ya que permite visualizar rápidamente las áreas críticas que requieren atención inmediata para garantizar el cumplimiento de la Ley 1581 de 2012, el Decreto 1377 de 2013 y los controles de la norma ISO/IEC 27001:2022, alineados con el Modelo de Seguridad y Privacidad de la Información (MSPI) del MinTIC.

## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Tablas en excel | Darek Aljuri 1 | 9/04 |
| Redacción del informe     | Valentina Ruiz | 09/04 |
| Investigación y referencias | Santiago Soler | 09/04 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller X en el curso AREM - Universidad de La Sabana._
