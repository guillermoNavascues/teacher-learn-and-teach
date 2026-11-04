# Teacher: learn and teach

*[Read in English](README.md)*

Una skill para Claude que convierte cada conversación en práctica de idiomas. Usas Claude como siempre (para programar, estudiar, trabajar o charlar), pero en el idioma que estás aprendiendo. Claude te responde en ese idioma y, si te equivocas, te corrige al final de su respuesta.

Funciona con cualquier idioma: inglés, francés, alemán, italiano, portugués, japonés…

## Qué hace

- **Responde solo en el idioma que practicas**, adaptándose a tu nivel (lo calcula por cómo escribes).
- **Corrige tus errores al final de cada respuesta, solo si los hay**: gramática, ortografía, puntuación, frases poco naturales y palabras de otros idiomas. Cada corrección muestra lo que escribiste, la versión correcta y la regla en una línea.
- **No responde a mensajes en otro idioma.** Solo te recuerda que escribas en el idioma que practicas. Así te obliga a practicar, que es justo la idea.
- **Te avisa de los falsos amigos** (⚠️), palabras que se parecen a tu idioma pero significan otra cosa ("actually" ≠ "actualmente").
- **Te señala los errores que repites** (🔁) para que veas tus patrones.
- **Te dice lo que haces bien** (✓) cuando corriges un error antiguo o usas algo por encima de tu nivel.
- **Modos de práctica cuando los pides**: simulacros de entrevista de trabajo, ejercicios de escritura, comprensión lectora y quizzes de vocabulario.
- **Te ayuda con textos de trabajo y de programación**: emails, cartas de presentación, CVs, mensajes de commit, descripciones de pull requests y updates de standup.
- **Te avisa si usas un lenguaje demasiado informal** cuando tu objetivo es formal, como una entrevista de trabajo.
- **Te da vocabulario cuando se lo pides** ("teach me some words").

## Cómo funciona

1. **La primera vez:** Claude te pregunta tres cosas: qué idioma quieres practicar, cuál es tu lengua materna y cuál es tu objetivo (entrevista de trabajo, viajes, exámenes…).
2. **A partir de ahí:** escribe en ese idioma. Si tienes la memoria de Claude activada, recuerda tu configuración. Si no, te lo vuelve a preguntar en cada conversación nueva.
3. **Cambiar de idioma:** escribe "change language" (o "cambiar idioma") cuando quieras cambiar.

Si eres principiante (A1-A2), las explicaciones de las reglas te llegan en tu lengua materna. Desde B1, todo va en el idioma que practicas.

Tienes ejemplos en [examples/conversations.md](examples/conversations.md).

## Instalación

### Claude (claude.ai y app de escritorio)

1. Descarga [`teacher-learn-and-teach.zip`](teacher-learn-and-teach.zip) de este repositorio.
2. Comprueba que la ejecución de código está activada en los ajustes de Claude (las skills la necesitan).
3. Ve a **Customize → Skills**, pulsa **+**, luego **Create skill → Upload a skill** y elige el ZIP.
4. Abre un chat y escribe algo como: *"Use the teacher-learn-and-teach skill, I want to practice French."*

Los nombres de los menús pueden cambiar. Si no los encuentras, mira la guía de Anthropic: [Using Skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude).

### Claude Code

Copia la carpeta `teacher-learn-and-teach/` en `~/.claude/skills/` (para todos tus proyectos) o en `.claude/skills/` (para un solo proyecto).

## Consejos

- Claude carga las skills cuando cree que hacen falta. Si en un chat nuevo se olvida del modo práctica, vuelve a nombrar la skill.
- No tengas miedo a equivocarte: cuanto más escribas, más aprendes.

## Licencia

[MIT](LICENSE) © 2026 Guillermo Navascués Martínez
