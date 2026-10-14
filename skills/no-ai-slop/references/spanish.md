# Spanish AI slop

Load this when the draft is in Spanish. Everything in `SKILL.md` still applies. This file gives the Spanish form of its word lists and patterns, adds the slop that only shows up in Spanish, and ends with checks to run before returning the draft.

Edit in Spanish. Do not translate the draft to English and back. Keep the writer's regional variety (Spain, Mexico, Argentina, and so on) and form of address (tú, usted, vos, vosotros, ustedes). Do not "correct" ordenador into computadora, voseo into tuteo, or ustedes into vosotros.

## Before applying anything below

**Check the register first.** Some patterns below come from persuasive Spanish: posts, newsletters, landing pages, announcements. On technical documentation, a specification, a report, meeting minutes or a legal text, switch off exactly these six: binary contrasts, throat-clearing and hooks, colon reveals, robotic rhythm, formatting slop, and recap endings. For that draft they also override the em dash, rhythm and formatting rules in `SKILL.md` and the matching checks in `eval.md`. Legal and administrative Spanish has fixed formulas ("a los efectos oportunos", "por la presente"); leave them alone in a legal or administrative text. Anywhere else they are filler.

Everything else stays on. Filler phrases, puffery, weasel attribution, calques and empty verb phrases are more common in a report than in a blog post, not less.

**Never edit inside a verbatim quote.** Quotes, code, UI strings, error messages and product names keep their own wording.

**Keep terms of art.** "Ecosistema" in biology or software, "robusto" in statistics, "optimizar" in SEO or engineering, "potenciar" in pharmacology. These are the right word in their field.

**Ask, never invent.** Many rules below ask for a fact, number, actor or source the draft may not have. When it is missing, say so and ask the writer. Do not supply a plausible one.

## Words to cut

Inflated vocabulary: sumergirse (sumérgete, sumerjámonos), adentrarse (adentrémonos), fomentar, aprovechar al máximo, de vanguardia, revolucionario, revolucionar, transformador, cambio de paradigma, un antes y un después, elevar ("eleva tu marca"), embarcarse, desbloquear o liberar el potencial, llevar al siguiente nivel, tapiz, faro, crisol, multifacético, meticuloso, intrincado, primordial, en constante evolución, sinergia, holístico. "Ecosistema", "panorama" and "potenciar" only when figurative and outside their field.

Often-empty adverbs: realmente, simplemente, literalmente, verdaderamente, fundamentalmente, esencialmente, básicamente, totalmente, absolutamente, claramente, sin duda, sin lugar a dudas. Cut them when they add nothing. Keep them when they carry emphasis, doubt or the writer's spoken rhythm.

Often-empty phrases: cabe destacar que, cabe señalar que, es importante destacar que, es importante tener en cuenta que, vale la pena mencionar, al fin y al cabo, en lo que respecta a, a la hora de ("a la hora de elegir" becomes "al elegir"), con el fin de or a fin de (when "para" works), en el mundo actual, hoy en día (as an opener), en la era digital, en el dinámico mundo de, la realidad es que, la verdad es que, de cara al futuro, en este artículo te contamos, todo lo que necesitas saber, guía definitiva, sin más preámbulos, ¡vamos allá!

Empty verb phrases: "realizar la implementación de" becomes "implementar", "llevar a cabo una revisión" becomes "revisar", "proceder a enviar" becomes "enviar", "hacer uso de" becomes "usar".

## Patterns to cut

**Binary contrasts.** Only the rhetorical forms: a negation split across two sentences ("No es una herramienta. Es un cambio de mentalidad."), the hype opener ("La clave no es X, sino Y"), the escalation ("No es solo X, es Y", "Más que X, es Y"), or a negative list ("No es la tecnología. No es el presupuesto. Son las personas."). State Y directly. "La clave no es el precio, sino el plazo" becomes "El plazo pesa más que el precio." Keep "no es X, sino Y" when the negated half does work: correcting an assumption the reader already holds ("Este error no viene del servidor, sino de la caché") or warning that a name misleads. "Sino" is ordinary Spanish coordination; do not delete it on sight.

**Throat-clearing openers and hooks.** "Seamos claros", "Vamos al grano", "Te lo digo sin rodeos", "La cruda realidad es que", "Lo que nadie te cuenta", "El error que comete la mayoría", "Aquí viene lo interesante", "Y aquí está el truco". Cut the setup and let the claim stand.

**Colon reveals.** "La clave: un buen diagnóstico." / "El secreto: la constancia." Write it as a plain sentence: "Todo depende de un buen diagnóstico." Spanish writes lowercase after a colon except after a letter's salutation, before a quote, or before a proper noun. That replaces the sentence-case rule in `SKILL.md`. Colons for lists, labels and quotes are fine.

**Superficial analysis.** In Spanish this is the trailing gerund of a later or separate action (gerundio de posterioridad), which the RAE also considers incorrect: "…, reflejando / destacando / subrayando / evidenciando / poniendo de manifiesto…". "La clínica amplió su horario hasta las 21:00, reflejando su compromiso con los pacientes" becomes "La clínica abre hasta las 21:00."

**Importance puffery.** "Marca un antes y un después", "se erige como", "se posiciona como referente", "desempeña un papel fundamental", "juega un papel clave", "supone un hito", "pone de manifiesto la importancia de". State the fact the draft gives. "Con 2.000 pacientes al año, la clínica se erige como referente en Barcelona" becomes "La clínica atiende a 2.000 pacientes al año en Barcelona." If the draft gives no fact, ask.

**Interpretive metadiscourse.** "Como puedes ver", "Lo importante aquí es", "Esto es clave", "Y esto importa más de lo que parece", a redundant "Dicho de otro modo" or "Es decir". Delete it, or replace it with the fact that supports the point.

**Weasel attribution.** "Los expertos coinciden", "Según diversos estudios", "Está demostrado que", "Cada vez más empresas", "Muchos especialistas". Name the source or cut the claim.

**Fake-strong verbs.** "Se erige como", "se configura como", "actúa como", "constituye", "supone", "representa". Prefer "es" and "tiene". "La app se configura como un centro neurálgico para patrocinadores, borradores y plazos" becomes "La app reúne patrocinadores, borradores y plazos."

**Synonym cycling.** Spanish schooling teaches writers to avoid repetition, and AI overdoes it: "la clínica… el centro… la institución… el establecimiento". If the clear word is right, repeat it, or let the subject drop: Spanish does not need it in every sentence.

**Rhetorical setups.** "¿Y si te dijera que…?", "Piénsalo:", "Spoiler:", and self-answered pairs: "¿El resultado? …", "¿La clave? …", "¿Por qué? Porque…". Drop the question and make the point.

**Robotic rhythm and dramatic fragments.** Sentences of the same length and shape, triads in every paragraph ("rápido, sencillo y eficaz"), stacked fragments: "Y punto.", "Así de simple.", "Sin más.", "Sin trampa ni cartón." Vary length and structure within the writer's register.

**Fake-profound endings and recaps.** "Porque al final, lo que importa es…", "Y eso lo cambia todo.", and recap openers: "En conclusión", "En resumen", "En definitiva", "Para concluir", "En pocas palabras", "Recapitulando". Delete them and end on the last concrete point or next step. A wry, concrete last line in the writer's own voice is not a kicker; keep it.

**Formatting slop and dashes.** Everything in `SKILL.md`, plus: Spanish uses the raya for incisos, attached to the inserted words and spaced outside ("el equipo —tres personas— lo hizo"). That is standard orthography. The tell is the English-style rhythm dash ("lo hizo — y funcionó"). When an inciso works with commas or parentheses, prefer them.

## Spanish-only tells

**English Title Case in headings.** "Cómo Elegir El Mejor Dentista" is wrong in Spanish. Use sentence case: "Cómo elegir el mejor dentista". Proper nouns keep their capitals.

**Calques from English.** "Al final del día" becomes "a fin de cuentas". "Hace sentido" becomes "tiene sentido". "Aplicar a un puesto" becomes "solicitar un puesto" or "presentarse". "Eventualmente" meaning "finally" becomes "finalmente" ("eventual" means possible). "Asumo que lo sabes" becomes "supongo que lo sabes". "En orden a" becomes "para". "Es por eso que" becomes "por eso".

**Periphrastic passive.** "El estudio fue realizado por el equipo" reads translated. Use the active voice ("El equipo hizo el estudio") or the pasiva refleja ("Se hizo el estudio"). Leave it when the actor is unknown or beside the point.

**English possessives.** Spanish drops possessives when the owner is obvious: "Levanta tu mano" becomes "Levanta la mano"; "Lávate tus manos" becomes "Lávate las manos".

**Gerund titles.** "Mejorando tu web", "Entendiendo el SEO local" copy English -ing titles. Use "Cómo mejorar tu web", "Mejora tu web" or a noun phrase.

**Mixed forms of address.** Tú and usted, or vosotros and ustedes, mixed in the writer's own sentences. Pick the writer's form and hold it. Quoted text keeps its own.

## Eval cases

Run these after editing a Spanish draft, in addition to the checks in `eval.md`.

1. Si es documentación técnica, una especificación, un informe, un acta o un texto legal, ¿has desactivado solo los seis patrones de la sección de registro y has mantenido el resto?
2. ¿Has dejado intactas las citas, el código, los textos de interfaz, los mensajes de error y las fórmulas legales?
3. ¿Has respetado la variedad regional y la forma de tratamiento del autor (tú, usted, vos, vosotros, ustedes)?
4. ¿Has evitado inventar cifras, nombres o fuentes? Si faltaba un dato, ¿se lo has preguntado al autor?
5. ¿Han desaparecido los gerundios de posterioridad, los calcos y la pasiva perifrástica innecesaria?
6. ¿Siguen ahí las frases «no es X, sino Y» que corrigen una suposición del lector?
7. ¿Los encabezados van en minúscula salvo la inicial y los nombres propios, y después de dos puntos hay minúscula cuando corresponde?
8. ¿La raya solo marca incisos, y ninguna se usa como recurso de ritmo?
9. ¿El texto termina en un dato concreto, una conclusión o el siguiente paso, y no en una frase lapidaria ni en un resumen?
