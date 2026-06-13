# Power Platform & Copilot Studio Environment Strategy - Quick Assessment

![Version](https://img.shields.io/badge/version-1.0-5552B4)
![License](https://img.shields.io/badge/license-MIT-27B8C6)
![Languages](https://img.shields.io/badge/languages-es--AR%20%7C%20en--US-3895FF)
![Application](https://img.shields.io/badge/application-single--file%20HTML-FFC000)
![Processing](https://img.shields.io/badge/assessment%20processing-local-BD47BD)

A bilingual, browser-based open-source assessment that helps organizations determine whether their Power Platform and Copilot Studio environment strategy is sufficiently defined, comprehensive, approved, communicated, actionable, and current. It produces weighted results, coverage findings, prioritized recommendations, and a downloadable executive PDF report without storing or transmitting assessment responses.

**Public assessment version: 1.0**

[Español](#español) · [English](#english)

---


## About this project

**Power Platform & Copilot Studio Environment Strategy - Quick Assessment** is a community-driven, bilingual self-assessment designed to help organizations evaluate the quality of their environment strategy as a formal, actionable, and continuously maintained governance artifact.

The assessment goes beyond asking whether individual technical controls exist. It examines whether the organization has documented the decisions that shape its Power Platform and Copilot Studio environment model, whether those decisions are approved and communicated, and whether the strategy remains current as the platform, operating model, licensing landscape, business priorities, and regulatory context evolve.

The tool is intentionally lightweight: it runs directly in a web browser, does not require installation or authentication, and can be published as a static website. It is suitable for an initial health check, a CoE workshop, an architecture review, or a structured conversation between platform owners, architects, security teams, operations teams, and business stakeholders.

### What the assessment provides

After completing the questionnaire, the user receives:

- an overall strategy score from 0 to 100;
- a strategy health level;
- weighted results across six assessment domains;
- a question-level coverage map;
- an independent strategy currency indicator;
- an independent documentation and communication indicator;
- key gaps and strengths;
- up to five prioritized actions;
- contextual recommendations based on organizational scale, licensing visibility, products in use, and planned capabilities;
- a downloadable executive PDF report.

### Downloadable PDF report

The final results page includes an option to generate and download a PDF report. The report is created in the browser from the responses provided during the assessment.

The PDF is intended to support:

- internal discussions with CoE, architecture, security, and governance teams;
- strategy review workshops;
- prioritization and roadmap planning;
- executive or steering committee conversations;
- documentation of an initial baseline;
- comparison with future assessment results.

Depending on the answers provided, the report contains the overall score, domain results, strategy currency, documentation and communication status, coverage findings, key dates, priority actions, the response scale, disclaimers, and related community resources.

### Privacy by design

The assessment is designed to process responses locally in the browser.

It does **not** require:

- a user account;
- a Microsoft tenant connection;
- an email address;
- a backend service;
- a database;
- cookies;
- analytics;
- submission of responses to the author.

The answers are not automatically stored, transmitted, or uploaded. They remain in the current browser session unless the user voluntarily downloads or shares the generated PDF report.

External requests used to load fonts, the PDF library, book links, or other static resources do not include the assessment responses.

> This project is a self-assessment and guidance tool. It does not replace a technical tenant review, security assessment, compliance audit, licensing review, or Microsoft certification.

---

# Español

## Descripción

**Power Platform & Copilot Studio Environment Strategy - Quick Assessment** es una herramienta web bilingüe de autoevaluación creada para la comunidad de Power Platform.

Permite analizar si la estrategia de entornos de una organización existe como un artefacto formal y vivo, si cubre las principales decisiones de arquitectura y gobierno, si fue documentada y comunicada correctamente y si se mantiene vigente frente a cambios en la plataforma, el negocio y el contexto regulatorio.

El assessment está orientado a:

- responsables de Power Platform y Copilot Studio;
- líderes y miembros de Centros de Excelencia;
- arquitectos de soluciones y enterprise architects;
- equipos de gobierno, seguridad y compliance;
- administradores de plataforma;
- responsables de adopción, enablement y operaciones.

La herramienta no inspecciona automáticamente el tenant. Evalúa la calidad de la estrategia declarada por la organización y funciona como punto de entrada para revisiones técnicas, de arquitectura, seguridad o gobierno más profundas.


## Cómo funciona el assessment

El usuario recorre un flujo guiado compuesto por cuatro tipos de información:

1. **Perfil organizacional:** permite interpretar el resultado según el tamaño de la organización, la población habilitada, la cantidad de makers, los productos utilizados, las capacidades previstas y el modelo de licenciamiento.
2. **Datos de la estrategia:** captura el estado del documento, las fechas relevantes, la versión, el owner, la frecuencia de revisión y la ubicación oficial.
3. **Preguntas puntuadas:** evalúa la calidad de la estrategia en seis dimensiones ponderadas.
4. **Módulos condicionales:** profundiza en Copilot Studio, Power Pages y workloads regulados o sensibles cuando esos escenarios forman parte del contexto de la organización.

Las respuestas del perfil no se utilizan para inflar o reducir artificialmente el score. Sirven para contextualizar el resultado, activar preguntas relevantes y advertir cuando la escala de adopción o licenciamiento no es coherente con el nivel de formalización de la estrategia.

El flujo completo puede completarse normalmente en aproximadamente diez minutos. Cuando se activan todos los módulos condicionales, puede requerir algunos minutos adicionales.

## Objetivo del assessment

El objetivo principal es ayudar a una organización a responder una pregunta concreta:

> ¿Contamos con una estrategia de entornos suficientemente completa, aprobada, comunicada y vigente como para utilizarla como referencia confiable para Power Platform y Copilot Studio?

Para responderla, la herramienta separa cuatro aspectos que no deberían confundirse:

- **Cobertura:** si la estrategia aborda las decisiones necesarias.
- **Calidad documental:** si existe una referencia oficial, trazable y aprobada.
- **Comunicación y adopción:** si las audiencias relevantes conocen la estrategia y la utilizan.
- **Vigencia:** si el contenido se revisa y actualiza con una frecuencia adecuada.

Esta separación evita que una estrategia bien redactada, pero desactualizada o desconocida por la comunidad, obtenga una valoración artificialmente alta. También evita confundir la existencia de controles técnicos con la existencia de una estrategia formal.

## Qué recibe el usuario al finalizar

Al completar el assessment, la página de resultados presenta:

- score general de 0 a 100;
- nivel de salud de la estrategia;
- resultado porcentual de cada dominio;
- estado de vigencia;
- estado de documentación y comunicación;
- mapa de cobertura por pregunta;
- áreas no cubiertas o insuficientemente definidas;
- principales fortalezas;
- fechas clave;
- hasta cinco acciones prioritarias;
- recomendaciones adaptadas al contexto declarado.

### Reporte PDF descargable

La página final permite descargar un reporte ejecutivo en PDF generado directamente en el navegador.

El reporte puede utilizarse como:

- evidencia de un diagnóstico inicial;
- material de trabajo para un workshop;
- insumo para una revisión de arquitectura;
- resumen para un comité de gobierno;
- base para un backlog de mejoras;
- referencia para comparar futuras evaluaciones.

El PDF incluye, según corresponda:

- nombre y versión del assessment;
- fecha de generación;
- score general y nivel de salud;
- resultados por dominio;
- estado de vigencia;
- estado de documentación y comunicación;
- mapa de cobertura;
- fechas relevantes de la estrategia;
- fortalezas y brechas;
- plan de acciones prioritarias;
- definiciones de la escala;
- disclaimer;
- enlace al perfil de LinkedIn del autor;
- recursos y libros relacionados.

El archivo PDF se crea localmente a partir de las respuestas introducidas. La descarga no implica el envío de datos a un servidor.

## Privacidad y tratamiento de datos

La privacidad es un principio de diseño del assessment.

La herramienta:

- procesa las respuestas localmente en el navegador;
- no requiere login;
- no solicita correo electrónico;
- no se conecta al tenant de Microsoft;
- no utiliza una base de datos;
- no guarda respuestas en el repositorio;
- no utiliza cookies para almacenar el assessment;
- no incorpora analítica de comportamiento;
- no envía las respuestas al autor ni a terceros.

Las respuestas existen únicamente durante la sesión del navegador. Al cerrar o recargar la página pueden perderse, salvo que el usuario haya descargado el PDF u otro resultado disponible.

La aplicación puede realizar solicitudes externas para cargar fuentes, librerías de generación de PDF o enlaces de recursos. Esas solicitudes no contienen las respuestas del assessment.

Para una implementación completamente aislada u offline, las dependencias externas pueden alojarse localmente.


## Objetivos

El assessment ayuda a determinar:

1. Si existe una estrategia formal de entornos.
2. Si su propósito, alcance, audiencia y ownership están claramente definidos.
3. Si cubre el modelo de entornos y sus ciclos de vida.
4. Si contempla seguridad, DLP, datos, ALM, operaciones y workloads especiales.
5. Si existe una versión oficial, aprobada, versionada y trazable.
6. Si fue publicada, comunicada e integrada en los procesos del CoE.
7. Si está vigente y cuenta con un ciclo de revisión.
8. Qué áreas no están cubiertas o requieren mayor definición.
9. Qué acciones deberían priorizarse durante los próximos meses.

## Qué evalúa

- Existencia, propósito y alcance de la estrategia.
- Principios y criterios de decisión.
- Ownership y derechos de decisión.
- Taxonomía y propósito de los entornos.
- Default Environment y entornos personales.
- Topologías y ciclos mínimos de desarrollo.
- Ciclo de vida de los entornos.
- Segmentación, transición y excepciones.
- Seguridad, acceso y separación de funciones.
- DLP, conectores y movimiento de datos.
- Dataverse y selección de backend.
- Managed Environments y servicios de plataforma.
- Operaciones, capacidad, backup, restauración y continuidad.
- Copilot Studio, Power Pages y workloads sensibles o regulados.
- Documentación, aprobación y trazabilidad.
- Comunicación, accesibilidad y adopción.
- Vigencia, revisión y mejora continua.

## Qué no evalúa

- Inspección automática del tenant.
- Validación técnica de políticas DLP.
- Revisión exhaustiva de configuraciones de seguridad.
- Auditoría de cumplimiento.
- Certificación de Microsoft.
- Validación detallada de cada aplicación, flujo, agente o sitio.
- Benchmarking frente a otras organizaciones.
- Sustitución de una revisión técnica o de arquitectura.

## Estructura del assessment

| Componente | Cantidad | Finalidad |
|---|---:|---|
| Perfil organizacional | 7 preguntas | Contextualizar escala, adopción, productos y licenciamiento |
| Datos de la estrategia | 9 campos | Capturar estado, versión, fechas, owner y ubicación oficial |
| Preguntas principales | 24 | Evaluar definición, cobertura, documentación, comunicación y vigencia |
| Módulos condicionales | Hasta 6 | Profundizar Copilot Studio, Power Pages y workloads sensibles |
| Resultado | N/A | Mostrar score, cobertura, vigencia, brechas y acciones |

Las preguntas de perfil no modifican artificialmente el score principal. Se utilizan para activar módulos condicionales, contextualizar recomendaciones y detectar riesgos relacionados con la escala o la falta de visibilidad sobre adopción y licencias.

## Dominios y ponderaciones

| Dominio | Peso |
|---|---:|
| Fundamentos, propósito y ownership | 15% |
| Modelo y ciclo de vida de entornos | 20% |
| Controles y workloads | 20% |
| Documentación, aprobación y trazabilidad | 15% |
| Comunicación, accesibilidad y adopción | 15% |
| Vigencia, revisión y mejora continua | 15% |
| **Total** | **100%** |

## Módulos condicionales

### Copilot Studio

Se activa cuando la organización utiliza o planea utilizar Copilot Studio.

Evalúa un modelo de gobierno por zonas:

- **Zone 1 — Citizen Development**
- **Zone 2 — Partnered Development**
- **Zone 3 — Professional Development**

También revisa criterios de clasificación y transición, entornos, knowledge sources, conectores, acciones, canales, seguridad, ALM, testing, aprobación, publicación, monitoreo, soporte y ownership.

Las zonas representan niveles de riesgo, complejidad, colaboración y control. No implican necesariamente una relación uno-a-uno con entornos físicos o Environment Groups.

### Power Pages

Se activa cuando la organización utiliza Power Pages o soluciones expuestas externamente.

Evalúa:

- modelo de entornos;
- ALM;
- entornos dedicados o de mayor control;
- acceso anónimo;
- identidades externas;
- table permissions;
- revisión de seguridad previa al go-live;
- monitoreo y soporte.

### Workloads regulados o sensibles

Se activa cuando la organización procesa información sensible, confidencial o regulada.

Evalúa:

- criterios para entornos dedicados;
- zonas de alta seguridad;
- controles reforzados;
- aprobaciones de seguridad, privacidad, compliance y arquitectura;
- documentación y gobierno de excepciones.

Los módulos que no se activan no se muestran y no afectan el cálculo del score.

## Escala de respuesta

| Valor | Respuesta | Interpretación |
|---:|---|---|
| 0 | No está cubierto o es desconocido | El tema no aparece en la estrategia o la persona que responde no puede confirmarlo. |
| 1 | Cubierto de manera informal o incompleta | Existen ideas o lineamientos parciales, pero no forman una definición suficiente. |
| 2 | Definido a alto nivel | La dirección está documentada, pero faltan criterios, detalle, aprobación o aplicabilidad. |
| 3 | Claramente documentado y aprobado | La definición es clara, accionable y formalmente aceptada. |
| 4 | Documentado, comunicado, aplicado y revisado | La definición está vinculada con procesos, es conocida por las audiencias relevantes y se revisa periódicamente. |

La falta de conocimiento se considera una brecha de documentación, comunicación o gobierno y puntúa como 0.

## Modelo de puntuación

El porcentaje de cada dominio se calcula sobre las preguntas visibles y aplicables:

```text
Porcentaje del dominio =
    Puntos obtenidos
    ---------------- × 100
    Máximo posible
```

La contribución de cada dominio se obtiene aplicando su ponderación:

```text
Contribución ponderada =
    Porcentaje del dominio × Peso del dominio
```

El score general es la suma de las contribuciones ponderadas y se redondea al entero más cercano.

| Score | Nivel | Interpretación |
|---:|---|---|
| 0–39 | No definida | No existe una estrategia formal o presenta brechas estructurales. |
| 40–59 | Incompleta | Existe una dirección general, pero faltan decisiones, documentación, aprobación, comunicación o mantenimiento. |
| 60–74 | Definida | La estrategia cubre los temas principales, aunque algunas áreas requieren mayor detalle, adopción o revisión. |
| 75–89 | Establecida | La estrategia está bien documentada y cubre la mayoría de las áreas relevantes. |
| 90–100 | Mantenida e integrada | La estrategia es completa, vigente, comunicada, aplicada y revisada continuamente. |

## Dependencias externas

La aplicación utiliza:

- [Google Fonts](https://fonts.google.com/) para `Space Grotesk` e `Inter`.
- [jsPDF 2.5.1](https://github.com/parallax/jsPDF) para generar el reporte PDF.
- Enlaces de Amazon para acceder a las ediciones de los libros.

Las portadas utilizadas en la herramienta cuentan con imágenes de respaldo embebidas en el HTML.

Para una distribución completamente offline, descargá y serví localmente Google Fonts y jsPDF, y actualizá las referencias del archivo HTML.

## Privacidad

Las respuestas:

- se procesan localmente en el navegador;
- no se almacenan en una base de datos;
- no se envían a un servidor;
- no requieren identificación;
- no utilizan cookies;
- no utilizan analítica;
- no requieren correo electrónico.

El usuario puede elegir voluntariamente descargar, guardar o compartir el reporte PDF.

Las solicitudes realizadas para cargar fuentes o librerías externas no contienen las respuestas del assessment.

## Libros relacionados

### Español

- [Definiendo la estructura marco para el Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Definiendo-estructura-Centro-Excelencia-Platform/dp/B0FSDWQMHW/ref=tmm_pap_swatch_0)
- [Copilot Studio y el futuro del Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0GZGL3T1K/ref=tmm_pap_swatch_0)

### English

- [Defining the Framework Structure for the Power Platform Center of Excellence](https://www.amazon.com/-/es/Defining-Framework-Structure-Platform-Excellence/dp/B0GDDRCD2C/ref=tmm_pap_swatch_0)
- [Copilot Studio and the Future of the Power Platform Center of Excellence](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0H2VTJZGR/ref=tmm_pap_swatch_0)

## Autor

**Nico Fernandez**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nico%20Fernandez-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nfernandezba)

## Licencia

El código fuente, la lógica del assessment y la documentación de este repositorio se distribuyen bajo la **MIT License**. Consultá el archivo [LICENSE](LICENSE).

La licencia MIT permite utilizar, copiar, modificar, combinar, publicar y distribuir el proyecto, siempre que se conserve el aviso de copyright y la licencia.

### Activos excluidos de la licencia MIT

Salvo indicación expresa, los siguientes activos no se distribuyen bajo la licencia MIT:

- nombre, logotipo e identidad visual personal de Nico Fernandez;
- portadas de libros;
- contenido de los libros;
- marcas, logotipos y activos de terceros;
- marcas registradas de Microsoft.

Su inclusión en la herramienta o en el repositorio no concede derechos independientes de reutilización, modificación, redistribución o explotación comercial.

Los forks y adaptaciones deberían reemplazar o eliminar estos activos cuando no cuenten con autorización para utilizarlos.

## Marcas registradas

Microsoft, Power Platform, Power Apps, Power Automate, Power BI, Power Pages, Copilot Studio, Dataverse, Microsoft 365 y Dynamics 365 son marcas del grupo de empresas Microsoft.

Este proyecto es un recurso independiente creado para la comunidad. No está afiliado, patrocinado, certificado ni respaldado por Microsoft.

## Disclaimer

Este assessment es una autoevaluación orientativa destinada a identificar áreas que podrían requerir definición o revisión.

No constituye:

- una certificación de Microsoft;
- una auditoría de cumplimiento;
- una evaluación de seguridad;
- asesoramiento legal;
- asesoramiento de licenciamiento;
- una garantía sobre la configuración del tenant;
- un sustituto de una revisión técnica o de arquitectura.

El uso de la herramienta y la interpretación de sus resultados son responsabilidad del usuario.

---

# English

## Overview

**Power Platform & Copilot Studio Environment Strategy - Quick Assessment** is a bilingual, browser-based open-source self-assessment created for the Power Platform community.

It evaluates whether an organization’s environment strategy exists as a formal and living artifact, covers the major architecture and governance decisions, is documented and communicated effectively, and remains current as the platform, business, and regulatory context evolve.

The assessment is intended for:

- Power Platform and Copilot Studio owners;
- Center of Excellence leaders and members;
- solution and enterprise architects;
- governance, security, privacy, and compliance teams;
- platform administrators;
- adoption, enablement, and operations teams.

The tool does not automatically inspect the tenant. It evaluates the declared quality of the strategy and acts as an entry point for deeper technical, security, governance, or architecture reviews.


## How the assessment works

The user follows a guided flow containing four types of information:

1. **Organizational profile:** provides context about organizational scale, enabled users, active makers, products in use, planned capabilities, and licensing models.
2. **Strategy metadata:** captures document status, relevant dates, version, ownership, review frequency, and official location.
3. **Scored questions:** evaluates the quality of the strategy across six weighted domains.
4. **Conditional modules:** extends the assessment for Copilot Studio, Power Pages, and regulated or sensitive workloads when those scenarios are relevant.

Profile responses do not artificially increase or reduce the primary score. They are used to contextualize findings, activate relevant modules, and highlight situations where adoption or licensing scale is inconsistent with the maturity of the strategy.

The core flow can usually be completed in approximately ten minutes. Activating every conditional module may add a few additional minutes.

## Assessment objective

The primary objective is to help an organization answer one practical question:

> Do we have an environment strategy that is sufficiently complete, approved, communicated, and current to serve as a reliable reference for Power Platform and Copilot Studio?

The tool separates four dimensions that should not be treated as equivalent:

- **Coverage:** whether the strategy addresses the required decisions.
- **Documentation quality:** whether an official, traceable, and approved reference exists.
- **Communication and adoption:** whether relevant audiences know and use the strategy.
- **Currency:** whether the strategy is reviewed and updated at an appropriate frequency.

This separation prevents a well-written but stale or poorly communicated document from receiving an artificially high result. It also distinguishes technical control implementation from the existence of a formal strategy.

## What the user receives

The final results page provides:

- an overall score from 0 to 100;
- a strategy health level;
- a percentage result for each domain;
- a currency status;
- a documentation and communication status;
- a question-level coverage map;
- missing or insufficiently defined areas;
- key strengths;
- key dates;
- up to five priority actions;
- context-aware recommendations.

### Downloadable PDF report

The final page allows the user to generate and download an executive PDF report directly in the browser.

The report can support:

- an initial baseline;
- CoE and architecture workshops;
- governance or steering committee discussions;
- improvement backlog creation;
- strategy roadmap planning;
- comparison with future assessments.

Depending on the responses, the PDF contains:

- assessment name and version;
- generation date;
- overall score and health level;
- domain results;
- currency status;
- documentation and communication status;
- coverage map;
- key strategy dates;
- strengths and gaps;
- prioritized actions;
- response scale definitions;
- disclaimer;
- author LinkedIn link;
- related books and community resources.

The PDF is created locally from the answers entered in the browser. Downloading the report does not submit the assessment data to a server.

## Privacy and data handling

Privacy is a core design principle.

The tool:

- processes answers locally in the browser;
- does not require authentication;
- does not request an email address;
- does not connect to a Microsoft tenant;
- does not use a database;
- does not store assessment answers in the repository;
- does not use cookies to persist responses;
- does not include behavioral analytics;
- does not send answers to the author or third parties.

Responses exist only within the current browser session. They may be lost when the page is refreshed or closed unless the user has downloaded the PDF or another available output.

The application may make external requests to load fonts, the PDF generation library, or resource links. Those requests do not include assessment responses.

For a fully isolated or offline deployment, external dependencies can be hosted locally.


## Objectives

The assessment helps determine:

1. Whether a formal environment strategy exists.
2. Whether purpose, scope, audience, and ownership are clearly defined.
3. Whether the environment model and lifecycle are sufficiently covered.
4. Whether security, DLP, data, ALM, operations, and special workloads are addressed.
5. Whether an official, approved, versioned, and traceable document exists.
6. Whether the strategy has been published, communicated, and embedded in CoE processes.
7. Whether the strategy is current and has a defined review cycle.
8. Which areas are missing or require further definition.
9. Which actions should be prioritized next.

## Assessment structure

| Component | Count | Purpose |
|---|---:|---|
| Organizational profile | 7 questions | Contextualize scale, adoption, products, and licensing |
| Strategy metadata | 9 fields | Capture status, version, dates, ownership, and official location |
| Core questions | 24 | Assess definition, coverage, documentation, communication, and currency |
| Conditional modules | Up to 6 | Extend Copilot Studio, Power Pages, and sensitive workload coverage |
| Results | N/A | Present score, coverage, currency, gaps, and actions |

Profile responses do not artificially change the primary score. They activate conditional modules, contextualize recommendations, and identify risks related to organizational scale or limited adoption and licensing visibility.

## Domains and weights

| Domain | Weight |
|---|---:|
| Foundations, purpose, and ownership | 15% |
| Environment model and lifecycle | 20% |
| Controls and workloads | 20% |
| Documentation, approval, and traceability | 15% |
| Communication, accessibility, and adoption | 15% |
| Currency, review, and continuous improvement | 15% |
| **Total** | **100%** |

## Conditional modules

### Copilot Studio

Activated when the organization uses or plans to use Copilot Studio.

It assesses a zoned governance model:

- **Zone 1 — Citizen Development**
- **Zone 2 — Partnered Development**
- **Zone 3 — Professional Development**

It also evaluates classification and transition criteria, environments, knowledge sources, connectors, actions, channels, security, ALM, testing, approval, publishing, monitoring, support, and ownership.

The zones represent levels of risk, complexity, collaboration, and control. They do not require a one-to-one relationship with physical environments or Environment Groups.

### Power Pages

Activated when the organization uses Power Pages or externally exposed solutions.

It evaluates the environment and ALM model, dedicated or higher-control environments, anonymous access, external identities, table permissions, pre-go-live security review, monitoring, and support.

### Regulated or sensitive workloads

Activated when the organization processes sensitive, confidential, or regulated information.

It evaluates dedicated environments, high-security zones, enhanced controls, security, privacy, compliance and architecture approvals, and exception governance.

Modules that are not activated are not displayed and do not affect scoring.

## Response scale

| Value | Response | Interpretation |
|---:|---|---|
| 0 | Not addressed or unknown | The topic is absent from the strategy, or the respondent cannot confirm it. |
| 1 | Informally or incompletely addressed | Partial guidance exists, but it is not sufficient. |
| 2 | Defined at a high level | Direction is documented, but criteria, detail, approval, or applicability are incomplete. |
| 3 | Clearly documented and approved | The definition is clear, actionable, and formally accepted. |
| 4 | Documented, communicated, applied, and reviewed | The definition is connected to processes, known by relevant audiences, and periodically reviewed. |

Unknown information is treated as a documentation, communication, or governance gap and scores 0.

## Scoring model

Each domain percentage is calculated from the visible and applicable questions:

```text
Domain percentage =
    Points obtained
    --------------- × 100
    Maximum points
```

The weighted contribution is then calculated:

```text
Weighted contribution =
    Domain percentage × Domain weight
```

The overall score is the sum of the weighted contributions and is rounded to the nearest whole number.

| Score | Level |
|---:|---|
| 0–39 | Undefined |
| 40–59 | Incomplete |
| 60–74 | Defined |
| 75–89 | Established |
| 90–100 | Maintained and Embedded |

## External dependencies

The application uses:

- [Google Fonts](https://fonts.google.com/) for `Space Grotesk` and `Inter`.
- [jsPDF 2.5.1](https://github.com/parallax/jsPDF) for PDF generation.
- Amazon links for related book editions.

Book covers have embedded fallback images in the HTML.

For a fully offline distribution, host Google Fonts and jsPDF locally and update the references in the HTML file.

## Privacy

Assessment responses:

- are processed locally in the browser;
- are not stored in a database;
- are not sent to a server;
- do not require identification;
- do not use cookies;
- do not use analytics;
- do not require an email address.

Users may voluntarily download, save, or share the generated PDF report.

Requests used to load external fonts or libraries do not include assessment responses.

## Related books

### English

- [Defining the Framework Structure for the Power Platform Center of Excellence](https://www.amazon.com/-/es/Defining-Framework-Structure-Platform-Excellence/dp/B0GDDRCD2C/ref=tmm_pap_swatch_0)
- [Copilot Studio and the Future of the Power Platform Center of Excellence](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0H2VTJZGR/ref=tmm_pap_swatch_0)

### Spanish

- [Definiendo la estructura marco para el Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Definiendo-estructura-Centro-Excelencia-Platform/dp/B0FSDWQMHW/ref=tmm_pap_swatch_0)
- [Copilot Studio y el futuro del Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0GZGL3T1K/ref=tmm_pap_swatch_0)

## Author

**Nico Fernandez**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nico%20Fernandez-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nfernandezba)

## License

The source code, assessment logic, and repository documentation are distributed under the **MIT License**. See [LICENSE](LICENSE).

The MIT License permits use, copying, modification, merging, publication, and distribution, provided that the copyright and license notice are preserved.

### Assets excluded from the MIT License

Unless expressly stated otherwise, the following assets are not distributed under the MIT License:

- Nico Fernandez’s name, personal logo, and visual identity;
- book covers;
- book content;
- third-party trademarks, logos, and assets;
- Microsoft trademarks.

Their inclusion in the application or repository does not independently grant permission for reuse, modification, redistribution, or commercial exploitation.

Forks and derivative versions should replace or remove these assets unless they have permission to use them.

## Trademarks

Microsoft, Power Platform, Power Apps, Power Automate, Power BI, Power Pages, Copilot Studio, Dataverse, Microsoft 365, and Dynamics 365 are trademarks of the Microsoft group of companies.

This project is an independent community resource. It is not affiliated with, sponsored by, certified by, or endorsed by Microsoft.

## Disclaimer

This assessment is a guidance-oriented self-assessment intended to identify areas that may require definition or review.

It is not:

- a Microsoft certification;
- a compliance audit;
- a security assessment;
- legal advice;
- licensing advice;
- a guarantee regarding tenant configuration;
- a substitute for a technical or architecture review.

Use of the tool and interpretation of its results remain the user’s responsibility.
