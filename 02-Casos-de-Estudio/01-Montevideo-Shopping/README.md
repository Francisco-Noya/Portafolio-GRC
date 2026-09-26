# Montevideo Shopping — Cybersecurity Risk Assessment & Operational Resilience

**Clasificación: Proyecto de portafolio / caso de estudio aplicado**

## Naturaleza del proyecto

Este caso de estudio **no constituye una auditoría oficial, evaluación autorizada ni diagnóstico de Montevideo Shopping**.

El análisis fue desarrollado sin acceso interno a la organización, sin autorización de Montevideo Shopping y sin participación de personal interno. Se utilizaron **información pública, observación externa, patrones generales de la industria y supuestos metodológicos**, con fines de aprendizaje, demostración de metodología y desarrollo de portafolio profesional.

Los resultados no deben interpretarse como una evaluación del nivel real de seguridad, riesgo, continuidad o resiliencia de la organización.

## Contexto

Montevideo Shopping fue seleccionado como caso de estudio por tratarse de un centro comercial de gran escala, con múltiples dominios operativos relevantes para un análisis integrado de **seguridad de la información, ciberseguridad, gestión de riesgos y resiliencia operativa**.

El análisis considera conceptualmente diferentes áreas y servicios que pueden resultar relevantes para la continuidad de una operación de este tipo, incluyendo:

- Administración.
- Atención al cliente.
- Estacionamiento.
- Energía y respaldo eléctrico.
- Conectividad.
- CCTV.
- Control de acceso.
- Servicios tecnológicos y sistemas administrativos.

## Alcance

El proyecto contempla un ejercicio de **Cybersecurity Risk Assessment** complementado con un análisis conceptual de continuidad y resiliencia operativa.

El trabajo incluye:

- Identificación conceptual de aproximadamente 120 activos.
- Clasificación de activos por dominio operativo.
- Identificación y priorización de un Top 15 de riesgos.
- Evaluación mediante heatmap de riesgo.
- Identificación conceptual de controles y medidas de tratamiento.
- Desarrollo de un roadmap de mitigación ilustrativo.
- Identificación conceptual de servicios críticos.
- Análisis de impacto al negocio (BIA) a nivel ilustrativo.
- Definición metodológica de RTO, RPO y MTPD.
- Análisis de escenarios de interrupción.
- Estrategias conceptuales de continuidad y recuperación.
- Procedimientos conceptuales de respuesta y recuperación.
- Consideraciones sobre pruebas y ejercicios de continuidad.

## Dominios considerados

- Parking.
- Energía y respaldo eléctrico.
- Conectividad.
- Administración.
- CCTV.
- Control de acceso.
- Atención al cliente.
- Servicios tecnológicos.
- Continuidad operativa.

## Metodología

El análisis se desarrolló utilizando como referencias metodológicas:

- **ISO/IEC 27001** — Gestión de la seguridad de la información.
- **ISO 31000:2018** — Gestión de riesgos.
- **NIST Cybersecurity Framework (CSF) 2.0** — Gestión del riesgo de ciberseguridad.
- **CIS Controls v8** — Referencia para controles de seguridad.
- **ISO 22301** — Gestión de continuidad del negocio.

La metodología combinó identificación conceptual de activos, análisis de riesgos, priorización, identificación de controles, evaluación conceptual de impactos y definición de medidas de tratamiento y continuidad.

## Supuestos

Los elementos que no pudieron ser verificados mediante información pública se presentan como **supuestos ilustrativos, hipótesis de análisis o recomendaciones metodológicas**.

En particular:

- Los activos, controles y niveles de madurez descritos son conceptuales.
- No se asume acceso a documentación interna, configuraciones reales ni personal de la organización.
- Los valores de probabilidad e impacto utilizados en el análisis de riesgos son ilustrativos.
- Los valores económicos utilizados en el análisis de impacto no representan ingresos, costos ni métricas financieras reales de Montevideo Shopping.
- Los tiempos de recuperación, capacidades técnicas, mecanismos de redundancia y configuraciones que no se encuentran disponibles públicamente se presentan como supuestos o recomendaciones.
- Las estrategias propuestas no implican que actualmente se encuentren implementadas por la organización.

## Limitaciones

Debido a la ausencia de acceso interno:

- No fue posible validar controles realmente implementados.
- No fue posible verificar configuraciones técnicas o arquitecturas internas.
- No fue posible entrevistar a responsables de las áreas involucradas.
- No fue posible validar los niveles reales de riesgo.
- No fue posible verificar los tiempos reales de recuperación de los servicios.
- No fue posible realizar pruebas técnicas, auditorías, pentesting o ejercicios reales de continuidad.

Por lo tanto, los resultados deben interpretarse como un **ejercicio demostrativo de metodología GRC**, y no como una evaluación certificada, auditoría o diagnóstico oficial de Montevideo Shopping.

## Estructura del análisis

1. Contexto y alcance.
2. Metodología y supuestos.
3. Identificación conceptual de activos por dominio.
4. Identificación y priorización de riesgos.
5. Heatmap de riesgo.
6. Evaluación de continuidad y resiliencia operativa.
7. Análisis de impacto al negocio (BIA).
8. Definición de RTO, RPO y MTPD.
9. Escenarios de interrupción.
10. Estrategias de continuidad y recuperación.
11. Procedimientos conceptuales de respuesta y recuperación.
12. Roadmap de mitigación y mejora.
13. Conclusiones y limitaciones.

## Documentación detallada

El desarrollo completo del caso de estudio se encuentra disponible en los siguientes documentos.

### 1. Evaluación de Riesgos y Resiliencia Operativa

Incluye el análisis conceptual de activos, identificación y priorización de riesgos, heatmap, controles de referencia y roadmap de mitigación.

📄 [Evaluación de Riesgos y Resiliencia Operativa — Montevideo Shopping](./Evaluacion-de-Riesgos-y-Resiliencia-Operativa.pdf)

### 2. Plan de Continuidad Operativa y Recuperación ante Incidentes

Como extensión del análisis de riesgos, se desarrolló un ejercicio conceptual de continuidad operativa y recuperación ante incidentes.

El documento aborda:

- Identificación conceptual de servicios críticos.
- Análisis de impacto al negocio (BIA).
- RTO, RPO y MTPD.
- Escenarios de interrupción.
- Estrategias de continuidad y redundancia.
- Respuesta inicial ante incidentes.
- Recuperación priorizada de servicios.
- Roles y responsabilidades propuestos.
- Comunicaciones durante incidentes.
- Pruebas y ejercicios.
- Recomendaciones de mejora.

📄 [Plan de Continuidad Operativa y Recuperación ante Incidentes](./Plan-de-Continuidad-Operativa-y-Recuperacion-ante-Incidentes.pdf)

## Relación entre los documentos

Los dos documentos forman parte de un mismo ejercicio de análisis:

**Identificación de activos → Evaluación de riesgos → Priorización → Tratamiento → Continuidad → Recuperación → Mejora**

El **Assessment de Riesgos** establece la base para identificar y priorizar escenarios relevantes, mientras que el **Plan de Continuidad Operativa** extiende el análisis hacia la disponibilidad de servicios críticos, impacto de interrupciones, objetivos de recuperación y estrategias conceptuales de respuesta y recuperación.

## Nota de confidencialidad y naturaleza del caso

Este material fue desarrollado exclusivamente con fines de **portafolio profesional, aprendizaje y demostración metodológica**.

No se contó con acceso a información confidencial, infraestructura interna, documentación privada, sistemas, configuraciones ni procedimientos internos de Montevideo Shopping.

El contenido no representa la posición oficial, arquitectura, controles, capacidades, riesgos ni procedimientos reales de la organización.

Cuando se utilizan valores, capacidades técnicas, tiempos, costos o mecanismos de redundancia que no pudieron verificarse públicamente, estos deben interpretarse como **supuestos ilustrativos o recomendaciones de diseño**.

---

**Autor:** Francisco Noya  
**Área:** Governance, Risk & Compliance (GRC) | Ciberseguridad | Gestión de Riesgos | Continuidad Operativa  
**Año:** 2026
