# Prompts utilizados

Se uso NotebookLM para construir la conceptualización, el modelo de negocio y la arquitectura del sistema LTI:

## prompts para crear el contexto en NotebookLM

### Dominio del Problema

**1. Prompts para entender el Ecosistema y los "Dolores" de Recursos Humanos**
El primer paso para definir el dominio del problema es identificar las tareas que consumen tiempo y generan frustración en los clientes:
*   "¿Qué es un sistema ATS (Applicant Tracking System) y cuáles son las principales fricciones en su uso diario?".
*   "¿Cuáles son los mayores retos de productividad y pérdida de tiempo que sufren los departamentos de RR. HH. en la selección de personal?"
*   "Cómo afecta la mala experiencia del candidato (candidate experience) durante el proceso de postulación a las empresas."
*   "¿Qué alternativas o soluciones rudimentarias usan actualmente las empresas para el emparejamiento de talento cuando no tienen un ATS moderno?".

**2. Prompts para investigar la problemática de la Inteligencia Artificial (Sesgos y "Caja Negra")**
Uno de los problemas centrales que LTI busca resolver es la falta de ética y transparencia en la tecnología actual:
*   "Riesgos de sesgo algorítmico y discriminación en el uso de Inteligencia Artificial para el reclutamiento de talento".
*   "¿Qué es el problema de la 'caja negra' en los algoritmos de aprendizaje profundo aplicados a Recursos Humanos?".
*   "Diferencias entre la IA tradicional y la IA Explicable (XAI) para mitigar decisiones arbitrarias en la selección de personal".
*   "Casos de estudio sobre algoritmos de contratación que han mostrado sesgos contra mujeres o minorías".

**3. Prompts para delimitar las Restricciones Legales y de Privacidad de Datos**
El dominio del problema también está delimitado por el marco regulatorio en el que operará el software:
*   "¿Cuáles son las obligaciones legales y de cumplimiento del RGPD (Reglamento General de Protección de Datos) para las plataformas de software ATS?".
*   "Privacidad de datos en la contratación: gestión del consentimiento y derechos de los candidatos frente a la toma de decisiones automatizada".
*   "Requisitos de la Ley de Inteligencia Artificial de la UE para sistemas de IA de alto riesgo aplicados al empleo".

**4. Prompts para la Metodología de Validación del Problema**
Para estructurar el análisis del dominio del problema desde la perspectiva del emprendimiento y la ingeniería de software:
*   "Cómo diseñar entrevistas de problema y validación de clientes según la metodología Running Lean de Ash Maurya".
*   "Cómo identificar a los 'Early Adopters' (primeros usuarios) que padecen el problema de manera más crítica en un modelo de negocio B2B".
*   "Técnicas de abstracción en el modelado de sistemas para separar el dominio del problema de los detalles de la solución de software".

### Base Técnica

**1. Prompts sobre Arquitectura de Software y Diseño de Alto Nivel**
Para definir la estructura base del sistema, el aislamiento de la lógica de negocio y la comunicación entre los servicios:
* "¿Cuáles son las diferencias entre Clean Architecture y Arquitectura Hexagonal, y cuándo conviene usar cada una?".
* "Cómo integrar el Diseño Guiado por el Dominio (DDD) dentro de una Arquitectura Hexagonal definiendo entidades, puertos y adaptadores".
* "Patrones de observabilidad y diseño resiliente en arquitecturas de microservicios".
* "Mejores prácticas para implementar arquitecturas orientadas a eventos (Event-Driven) y microservicios modernos".

**2. Prompts sobre UML y Casos de Uso**
Para establecer los requisitos funcionales y entender las interacciones de los actores con el sistema:
* "Mejores prácticas, tutoriales y ejemplos para diseñar diagramas de casos de uso efectivos".
* "Definición formal y diferencias entre las relaciones 'include' y 'extend' en los diagramas de casos de uso de UML".
* "¿Es útil seguir utilizando casos de uso y diagramas UML en proyectos con metodologías ágiles o Scrum?".

**3. Prompts sobre Modelado de Bases de Datos**
Para diseñar la estructura de persistencia políglota y asegurar la integridad de la información:
* "Cómo definir e identificar correctamente entidades, atributos y relaciones en el diseño de bases de datos".
* "Guía paso a paso para crear un diagrama Entidad-Relación (ER) y documentar restricciones y supuestos".
* "Cómo aplicar las reglas de Codd y el proceso de normalización de bases de datos usando claves primarias y dependencias funcionales".
* "Reglas para la transformación de un modelo conceptual Entidad-Relación a un modelo relacional físico".

**4. Prompts sobre el Modelo C4**
Para visualizar la arquitectura desde una perspectiva de alto nivel (contexto) hasta el detalle de los componentes:
* "¿Qué es el modelo C4 de Simon Brown, cuáles son sus 4 niveles principales de abstracción y sus componentes?".
* "Comparación entre el Modelo C4 y UML: ¿cuál elegir para documentar sistemas de software modernos?".
* "Cómo pensar y preparar la arquitectura de software usando las abstracciones del modelo C4 antes de empezar a dibujar los diagramas".
* "Cómo documentar arquitecturas en la nube integrando el Modelo C4 con AWS y Terraform".
* "El uso de diagramas de soporte (panorama, despliegue y dinámicos) para complementar el modelo C4".

**5. Prompts sobre Herramientas Técnicas y Diagramas como Código (DaC)**
Para automatizar la documentación y elegir las mejores plataformas de dibujo arquitectónico:
* "¿Cuáles son las mejores herramientas de software para crear y compartir diagramas de arquitectura C4?".
* "Guía práctica y sintaxis para crear diagramas del modelo C4 utilizando el lenguaje de marcado Mermaid.js".
* "Cómo documentar arquitectura de software combinando el modelo C4 con PlantUML (C4-PlantUML)".
* "Generación y visualización de diagramas del modelo C4 utilizando herramientas impulsadas por Inteligencia Artificial".


## Prompts para el modelo de negocio y tecnicos

1. **"Se creara un software relacionado con ATS llamado LTI, genera una breve descripcion, valor ananido y las ventajas competitivas."**
2. **"Actúa como Product Manager Senior. Necesito un PRD del proyecto LTI."**
3. **"En tu rol analista de software experto. Enumera y describe los tres casos de uso más importantes a implementar para lograr una funcionalidad básica, usa las buenas practicas uml, los Dac realizalos en el marcado Marmaid."**
4. **"En tu rol analista de software experto. Enumera y describe los tres casos de uso principales a implementar para lograr una funcionalidad básica, usa las buenas practicas uml, los Dac realizalos en el marcado Marmaid."**
5. **"En tu rol analista de software experto. Enumera y describe los tres casos de uso más importantes cada uno con su diagragma, usa las buenas practicas uml, los Dac realizalos en el marcado Marmaid."**
6. **"En tu rol analista de software experto. Enumera y describe los tres casos de uso más importantes cada uno con su diagragma para el sistema LTI, usa las buenas practicas uml, los Dac realizalos en el marcado Marmaid."**
7. **"Actúa como un DBA y Arquitecto de Software Senior. realiza el Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones, del proyecto LTI."**
18. **"pasemos al diseno del sistema y arquitectura de alto nivel."**
19. **"en arquitectura hexagonal?"**
20. **"Diseño del sistema a alto nivel, usando arquitectura heagonal, tanto explicado como diagrama adjunto"**
21. **"Diseño del sistema de LTI a alto nivel, usando arquitectura heagonal, tanto explicado como diagrama adjunto"**
22. **"Diagrama C4 que llegue en profundidad a uno de los componentes mas importantes del sistema, el que prefieras."**
23. **"prompts para recopilar información del dominio del problema"**
24. **"promps de fuetes para la arquitectura, casos de uso, c4, y demas detalles tecnicos"**
25. **"promps de fuetes para la arquitectura, casos de uso, modelo de datos, Diseño del sistema a alto nivel,  c4, y demas detalles tecnicos"**

## Prompts mejorados por la IA

Basado en los prompts anteriores, se le pidio a la ia que los mejorara, el resultado fue el siguiente:

26. **"Mejora los prompts antes listados"**

### 1. Prompts para Producto y Modelo de Negocio (PRD y Lean Canvas)
*En lugar de pedir solo "una breve descripción", le damos el rol de Product Manager y le exigimos un formato estructurado.*

> **Prompt Mejorado:** "Actúa como un Product Manager Senior. Estamos diseñando un Applicant Tracking System (ATS) impulsado por Inteligencia Artificial Agéntica llamado 'LTI'. Tu objetivo es crear un Documento de Requisitos del Producto (PRD) y un diagrama Lean Canvas estructurado. Detalla claramente el problema del mercado, nuestra Propuesta de Valor Única (basada en IA explicable y análisis multimodal) y nuestra ventaja competitiva. Para el Lean Canvas, presenta el resultado en una tabla clara y orientada a modelos B2B."

### 2. Prompts para Casos de Uso y UML
*Para evitar diseños genéricos, introducimos las reglas formales de UML y le indicamos a la IA cómo debe programar el diagrama para que no falle.*

> **Prompt Mejorado:** "Actúa como un Analista de Software Experto. Para el sistema ATS 'LTI', describe los 3 casos de uso principales. Utiliza estrictamente las buenas prácticas de UML: aplica relaciones de inclusión (`<<include>>`) para comportamientos obligatorios que se re-usan y relaciones de extensión (`<<extend>>`) para secuencias alternativas o excepciones. Genera el diagrama de Casos de Uso como código (Diagrams as Code) utilizando Mermaid.js. **Importante:** Utiliza identificadores de nodos cortos, alfanuméricos y sin espacios para evitar errores de renderizado (ej. usa `UC1` en lugar de textos largos en las conexiones)."

### 3. Prompts para Modelado de Bases de Datos
*Aquí aplicamos principios de ingeniería de datos para asegurar que la IA separe correctamente las entidades de los atributos y aplique las formas normales.*

> **Prompt Mejorado:** "Actúa como un Administrador de Bases de Datos (DBA) y Arquitecto Senior. Diseña el modelo de datos relacional para el proyecto LTI aplicando las reglas de normalización hasta la Tercera Forma Normal (3NF). Identifica correctamente las entidades (sustantivos con existencia propia) y atributos (adjetivos o propiedades), evitando guardar atributos derivados. Genera el código estructural en sintaxis estricta DBML con tipos de datos nativos de PostgreSQL, e incluye también el Diagrama Entidad-Relación (ERD) en Mermaid.js usando la notación Crow's Foot."

### 4. Prompts para Diseño del Sistema a Alto Nivel (C4 y Hexagonal)
*El error común es pedir arquitectura sin especificar el nivel de profundidad. Usamos el modelo C4 como herramienta de pensamiento estructural* *y definimos el patrón esperado.*

> **Prompt Mejorado:** "Actúa como Arquitecto de Software Cloud. Diseña la arquitectura del sistema LTI utilizando el Modelo C4 de Simon Brown integrado con los principios de la Arquitectura Hexagonal (Puertos y Adaptadores) para aislar la lógica de negocio. 
> 1. Explica cómo interactúan el núcleo del dominio, los puertos y los adaptadores de entrada/salida.
> 2. Genera un diagrama C4 de Nivel 2 (Contenedores) o Nivel 3 (Componentes) utilizando sintaxis Mermaid.js.
> Asegúrate de detallar el uso de persistencia políglota y una comunicación basada en eventos asíncronos (Event-Driven) para el ecosistema de IA."

---
