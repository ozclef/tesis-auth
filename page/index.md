# Tesis: Arquitectura ética y técnica para servicios de mensajería efímera y gestión pública segura

## Título provisional
Arquitectura ética y técnica para sistemas efímeros de comunicación y gestión de datos en servicios públicos: un caso de estudio aplicado a México

## Resumen (abstract)
Breve resumen (200–300 palabras) explicando objetivo, metodología, implementación (MVP) y conclusiones.

## Índice propuesto
1. Introducción
2. Planteamiento del problema
3. Marco teórico y legal
4. Estado del arte
5. Metodología
6. Diseño y arquitectura propuesta
7. Implementación (MVP)
8. Evaluación y resultados
9. Riesgos, mitigaciones y consideraciones legales
10. Conclusiones y trabajo futuro
11. Anexos (código, scripts, consentimiento, entrevistas)

---

## Capítulos (contenido guía)

### 1. Introducción
- Contexto general (gobierno digital, gestión pública en México).
- Problema concreto: fugas de información, uso de dispositivos personales, ausencia de RLS, poca capacitación.
- Objetivos generales y específicos.
- Hipótesis de trabajo.

### 2. Planteamiento del problema
- Descripción técnica y social del problema.
- Impacto potencial en privacidad y seguridad.
- Alcance y limitaciones de la tesis.

### 3. Marco teórico y legal
- Principios de ética en computación (confidencialidad, integridad, disponibilidad).
- Ley Federal de Protección de Datos Personales (LFPDPPP): requisitos y responsabilidades.
- Legislación aplicable (código penal, normativa sobre firmas electrónicas, etc).
- Conceptos técnicos: RLS, JWT, TLS, cifrado en reposo, anonimización.

### 4. Estado del arte
- Sistemas existentes (Supabase, Firebase, soluciones govtech).
- Estudios y casos de éxito/fracaso en mensajería efímera y gestión pública.
- Revisión de artículos académicos y documentación técnica.

### 5. Metodología
- Diseño de investigación técnica (ingeniería experimental): desarrollo de un MVP + pruebas de seguridad + entrevistas/encuestas con usuarios (si aplica).
- Herramientas y tecnologías utilizadas.
- Métricas e índices de evaluación (TI, latencia, número de vulnerabilidades, cumplimiento de normativas).

### 6. Diseño y arquitectura propuesta
- Diagrama de alto nivel (frontend, backend, DB, worker, RLS, IA).
- Modelado de datos (ERD).
- Políticas de acceso y roles.
- Estrategia para data residency y anonimización.

### 7. Implementación (MVP)
- Descripción de componentes implementados: auth, chat efímero, RLS, worker de expiración, banca simulada, integración IA (anonimización).
- Fragmentos de código relevantes.
- Scripts de despliegue (CI/CD).

### 8. Evaluación y resultados
- Resultados de pruebas funcionales.
- Pruebas de seguridad (scans, pruebas RLS, accesos indebidos simulados con permiso).
- Test de usabilidad (feedback de usuarios).
- Comparativa contra requisitos legales.

### 9. Riesgos, mitigaciones y consideraciones legales
- Riesgos identificados y plan de mitigación.
- Recomendaciones de políticas internas y capacitación.
- Requisitos para auditoría y continuidad.

### 10. Conclusiones y trabajo futuro
- Conclusiones principales.
- Limitaciones.
- Propuestas de extensión (IA local, criptografía avanzada, integración con sistemas gov).

### 11. Anexos
- Código completo del MVP (links).
- Scripts SQL.
- Scripts de despliegue y configuración (YAML).
- Consent forms y plantillas de entrevista.
