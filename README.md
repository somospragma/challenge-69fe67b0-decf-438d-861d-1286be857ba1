# Implementación de un Pipeline de Integración Continua

Una empresa fintech necesita mejorar su proceso de desarrollo de software para un proyecto backend. El objetivo es implementar un pipeline de integración continua que incluya pruebas automatizadas para asegurar la calidad del código. El sistema debe ser capaz de detectar y reportar errores automáticamente, permitiendo a los desarrolladores corregirlos rápidamente.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | CI/CD |
| **Nivel** | junior-l2 |
| **Tipo** | mixed |
| **Tiempo estimado** | 4-5 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Exploración del Sistema Existente

**Objetivo:** Entender las necesidades y restricciones del sistema backend.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Investiga las funcionalidades actuales del sistema backend.
- Identifica las restricciones técnicas y de negocio que deben considerarse en el pipeline.

**Entregable:** Un informe con las necesidades y restricciones identificadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera tanto las limitaciones técnicas como las de negocio.
- Busca ejemplos de restricciones relevantes y triviales.

</details>

### Fase 2: Diseño del Pipeline de Integración Continua

**Objetivo:** Diseñar un pipeline que incluya pruebas automatizadas.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Define las etapas del pipeline (compilación, pruebas, despliegue, etc.).
- Identifica las pruebas automatizadas necesarias para el proyecto.

**Entregable:** Un diagrama del pipeline diseñado y una lista de pruebas automatizadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera la secuencia lógica de las etapas del pipeline.
- Piensa en diferentes tipos de pruebas (unitarias, de integración, etc.).

</details>

### Fase 3: Justificación de Decisiones de Diseño

**Objetivo:** Justificar las decisiones tomadas en el diseño del pipeline.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Evalúa las opciones disponibles para cada etapa del pipeline.
- Justifica las decisiones tomadas con argumentos sólidos.

**Entregable:** Un documento que justifique las decisiones de diseño del pipeline.

<details>
<summary>Pistas de conocimiento</summary>

- Considera los trade-offs entre diferentes opciones.
- Argumenta por qué elegiste una opción sobre otra.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un pipeline de integración continua y por qué es importante para el proyecto?
- **paraQueSirve**: ¿Para qué sirven las pruebas automatizadas en el pipeline?
- **comoSeUsa**: ¿Cómo se usan las diferentes etapas del pipeline para mejorar el proceso de desarrollo?
- **erroresComunes**: ¿Qué errores comunes se pueden encontrar al implementar un pipeline de integración continua?
- **queDecisionesImplica**: ¿Qué decisiones importantes debes tomar al diseñar un pipeline de integración continua?

## Criterios de Evaluacion

- Identificar las necesidades y restricciones del sistema backend.
- Diseñar un pipeline de integración continua con pruebas automatizadas.
- Justificar las decisiones de diseño del pipeline.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
