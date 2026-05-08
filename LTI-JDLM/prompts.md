# Prompts utilizados

Se uso NotebookLM para construir la conceptualización, el modelo de negocio y la arquitectura del sistema LTI:

## prompts para recopilar información del dominio del problema

**1. Sistemas de Seguimiento de Candidatos (ATS) y el mercado actual**
*   "¿Qué es un ATS (Applicant Tracking System) y cómo funciona en el reclutamiento?".
*   "Guía para elegir el mejor software ATS y aplicaciones móviles de contratación en 2026".
*   "¿Cuál es el mejor ATS para una startup pequeña con presupuesto limitado?".
*   "Importancia del multiposting y la integración de ATS con los sistemas centrales de RR. HH.".
*   "Cómo funcionan los ATS modernos: guía completa de filtrado y coincidencia semántica".

**2. Inteligencia Artificial en la Gestión del Talento**
*   "Tendencias de inteligencia artificial agéntica y sistemas multiagente para 2026".
*   "El rol de la IA en el proceso de reclutamiento y la mejora de la experiencia del candidato".
*   "Herramientas de IA para el análisis multimodal de sentimientos en video y detección de emociones".
*   "El futuro de las tecnologías de reclutamiento y el uso de automatización e IA según HR.com".

**3. Cumplimiento Legal, Ética y Privacidad (RGPD)**
*   "Obligaciones de cumplimiento del RGPD para herramientas de software ATS".
*   "Privacidad de datos en la contratación y gobernanza estratégica frente a leyes globales".
*   "Garantía de los derechos laborales y prevención de sesgos algorítmicos en la criba con IA".
*   "La importancia de la IA explicable (XAI) y la transparencia algorítmica para evitar la caja negra".

**4. Conceptualización y Modelos de Negocio (Lean Canvas)**
*   "Lienzo Lean Canvas explicado paso a paso con ejemplos prácticos".
*   "Cuadro comparativo y principales diferencias entre el Modelo Canvas y el Lean Canvas".
*   "Qué es y cómo definir la 'ventaja injusta' en una startup de producto".
*   "Metodología Running Lean y entrevistas a Ash Maurya sobre emprendimiento".

**5. Arquitectura de Software y Diagramas como Código (DaC)**
*   "¿Qué es el modelo C4 y cómo se utiliza para visualizar la arquitectura de software?".
*   "Las mejores herramientas para crear diagramas de arquitectura a partir de código (DaC)".
*   "Cómo hacer diagramas de flujo y arquitectura usando el lenguaje de marcado Mermaid.js".
*   "Cómo diseñar y exportar modelos de bases de datos relacionales con código DBML en dbdiagram.io".
*   "Mejores prácticas y guías prescriptivas de AWS para integración continua y entrega continua (CI/CD)".


## prompts para la construcción conceptual del sistema

1. **"que es un ats"** *(Para entender el concepto básico de un Applicant Tracking System).*

2. **"desglosa los pasos de la imagen adjunta"** *(Para conocer las etapas del flujo de reclutamiento).*

3. **"que ofecen las app actuales?"** *(Para investigar las características y estado actual del mercado).*

4. **"que valor ananido puedo analizar para aventajar a las app ya creadas?"** *(Para buscar diferenciadores competitivos, como la IA Agéntica y XAI).*

5. **"Asuma el rol de un analista de negocios, un experto en reclutamiento, asi como product manager de una startup de software, se creara un producto de software para reclutamiento llamado LTI, genera una breve descripcion, valor ananido y las ventajas competitivas."** *(Para bautizar el proyecto y definir su propuesta de valor).*

6. **"genera un diagrama Lean Canvas para entender el modelo de negocio de LTI, usando el lenguaje de marcado Mermaid.js"** *(Para obtener el código específico en Mermaid.js del diagrama de negocio).*

7. **"describa los 3 casos de uso principales, con el diagrama asociado a cada uno usando el lenguaje de marcado Mermaid.js"** *(Para modelar la interacción de los usuarios y la IA en la plataforma).*

8. **"Gnera los Modelos de datos que cubra entidades, atributos (nombre y tipo) y relaciones."** *(Para diseñar la base de datos relacional y el diagrama Entidad-Relación).*

11. **"Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto"** *(Para diseñar la arquitectura general de los microservicios y la IA en la nube).*

12. **"el visor genera este error al renderizar de diagrama de arquitectura de alto nivel: Parse error on line 63: ... [mensaje de error]"** *(Para corregir el error de sintaxis y renderizar exitosamente la arquitectura en Mermaid).*

13. **"genera Diagrama C4 que llegue en profundidad a uno de los componentes del sistema que tenga mas complejidad."** *(Para hacer un zoom detallado de Nivel 3 al motor de IA Agéntica y XAI).*