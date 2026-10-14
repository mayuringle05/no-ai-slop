# Catalan AI slop

Load this when the draft is in Catalan. Everything in `SKILL.md` still applies. This file gives the Catalan form of its word lists and patterns, adds the slop that only shows up in Catalan, and ends with checks to run before returning the draft.

Edit in Catalan. Do not translate the draft to English or Spanish and back. Keep the writer's variety (central, valencià, balear, nord-occidental) and form of address (tu, vostè, vosaltres, vostès). Do not "correct" valencian forms such as "este", "meua" or "eixir", or the balearic article.

## Before applying anything below

**Check the register first.** Some patterns below come from persuasive Catalan: posts, newsletters, landing pages, announcements. On technical documentation, a specification, a report, meeting minutes or a legal text, switch off exactly these six: binary contrasts, throat-clearing and hooks, colon reveals, robotic rhythm, formatting slop, and recap endings. For that draft they also override the em dash, rhythm and formatting rules in `SKILL.md` and the matching checks in `eval.md`. Legal and administrative Catalan has fixed formulas ("als efectes oportuns", "per la present"); leave them alone in a legal or administrative text. Anywhere else they are filler.

Everything else stays on. Filler phrases, puffery, weasel attribution, calques and empty verb phrases are more common in a report than in a blog post, not less.

**Never edit inside a verbatim quote.** Quotes, code, UI strings, error messages and product names keep their own wording.

**Keep terms of art.** "Ecosistema" in biology or software, "robust" in statistics, "optimitzar" in SEO or engineering, "potenciar" in pharmacology. These are the right word in their field.

**Ask, never invent.** Many rules below ask for a fact, number, actor or source the draft may not have. When it is missing, say so and ask the writer. Do not supply a plausible one.

## Words to cut

Inflated vocabulary: endinsar-se (endinsem-nos), submergir-se (submergeix-te, submergim-nos), fomentar, aprofitar al màxim, d'avantguarda, revolucionari, revolucionar, transformador, canvi de paradigma, un abans i un després, elevar ("eleva la teva marca"), embarcar-se, desbloquejar o alliberar el potencial, portar al següent nivell, tapís, far, gresol, multifacètic, meticulós, intricat, primordial, en constant evolució, sinergia, holístic. "Ecosistema", "panorama" and "potenciar" only when figurative and outside their field.

Often-empty adverbs: realment, simplement, literalment, veritablement, fonamentalment, essencialment, bàsicament, totalment, absolutament, clarament, sens dubte, sense cap mena de dubte. Cut them when they add nothing. Keep them when they carry emphasis, doubt or the writer's spoken rhythm.

Often-empty phrases: cal destacar que, cal remarcar que, és important destacar que, és important tenir en compte que, val la pena esmentar, al cap i a la fi, pel que fa a, a l'hora de ("a l'hora de triar" becomes "en triar" or "quan triïs"), amb la finalitat de or amb l'objectiu de (when "per" works), en el món actual, avui dia (as an opener), en l'era digital, en el dinàmic món de, la realitat és que, la veritat és que, de cara al futur, en aquest article t'expliquem, tot el que necessites saber, guia definitiva, som-hi!

Empty verb phrases: "dur a terme la implementació de" becomes "implementar", "realitzar una revisió" becomes "revisar", "procedir a enviar" becomes "enviar", "fer ús de" becomes "fer servir".

## Patterns to cut

**Binary contrasts.** Only the rhetorical forms: a negation split across two sentences ("No és una eina. És un canvi de mentalitat."), the hype opener ("La clau no és X, sinó Y"), the escalation ("No és només X, és Y", "Més que X, és Y"), or a negative list ("No és la tecnologia. No és el pressupost. Són les persones."). State Y directly. "La clau no és el preu, sinó el termini" becomes "El termini pesa més que el preu." Keep "no és X, sinó Y" when the negated half does work: correcting an assumption the reader already holds ("Aquest error no ve del servidor, sinó de la memòria cau") or warning that a name misleads. "Sinó" is ordinary Catalan coordination; do not delete it on sight.

**Throat-clearing openers and hooks.** "Siguem clars", "Anem al gra", "T'ho dic sense embuts", "La crua realitat és que", "El que ningú no t'explica", "L'error que comet la majoria", "Aquí ve el més interessant", "I aquí hi ha el truc". Cut the setup and let the claim stand.

**Colon reveals.** "La clau: un bon diagnòstic." / "El secret: la constància." Write it as a plain sentence: "Tot depèn d'un bon diagnòstic." Catalan writes lowercase after a colon except after a letter's salutation, before a quote, or before a proper noun. That replaces the sentence-case rule in `SKILL.md`. Colons for lists, labels and quotes are fine.

**Superficial analysis.** In Catalan this is the trailing gerund of a later or separate action (gerundi de posterioritat), which the IEC also considers incorrect: "…, reflectint / destacant / subratllant / evidenciant / posant de manifest…". "La clínica va ampliar l'horari fins a les 21 h, reflectint el seu compromís amb els pacients" becomes "La clínica obre fins a les 21 h."

**Importance puffery.** "Marca un abans i un després", "s'erigeix com", "es posiciona com a referent", "té un paper fonamental", "suposa una fita", "posa de manifest la importància de". State the fact the draft gives. "Amb 2.000 pacients l'any, la clínica s'erigeix com a referent a Barcelona" becomes "La clínica atén 2.000 pacients l'any a Barcelona." If the draft gives no fact, ask.

**Interpretive metadiscourse.** "Com pots veure", "El que importa aquí és", "Això és clau", "I això importa més del que sembla", a redundant "Dit d'una altra manera" or "És a dir". Delete it, or replace it with the fact that supports the point.

**Weasel attribution.** "Els experts coincideixen", "Segons diversos estudis", "Està demostrat que", "Cada vegada més empreses", "Molts especialistes". Name the source or cut the claim.

**Fake-strong verbs.** "S'erigeix com", "es configura com", "actua com", "constitueix", "suposa", "representa". Prefer "és" and "té". "L'app es configura com un centre neuràlgic per a patrocinadors, esborranys i terminis" becomes "L'app reuneix patrocinadors, esborranys i terminis."

**Synonym cycling.** "La clínica… el centre… la institució… l'establiment". If the clear word is right, repeat it, let the subject drop, or use a weak pronoun (see below).

**Rhetorical setups.** "I si et digués que…?", "Pensa-hi:", "Spoiler:", and self-answered pairs: "El resultat? …", "La clau? …", "Per què? Perquè…". Drop the question and make the point.

**Robotic rhythm and dramatic fragments.** Sentences of the same length and shape, triads in every paragraph ("ràpid, senzill i eficaç"), stacked fragments: "I punt.", "Així de simple.", "Sense més.", "Ni més ni menys." Vary length and structure within the writer's register.

**Fake-profound endings and recaps.** "Perquè, al capdavall, el que importa és…", "I això ho canvia tot.", and recap openers: "En conclusió", "En resum", "En definitiva", "Per concloure", "En poques paraules", "Recapitulant". Delete them and end on the last concrete point or next step. A wry, concrete last line in the writer's own voice is not a kicker; keep it.

**Formatting slop and dashes.** Everything in `SKILL.md`, plus: Catalan uses the guió llarg for incisos, attached to the inserted words and spaced outside ("l'equip —tres persones— ho va fer"). That is standard orthography. The tell is the English-style rhythm dash ("ho va fer — i va funcionar"). When an inciso works with commas or parentheses, prefer them.

## Catalan-only tells

**English Title Case in headings.** "Com Triar El Millor Dentista" is wrong in Catalan. Use sentence case: "Com triar el millor dentista". Proper nouns keep their capitals.

**Calques from Spanish and English.** Machine Catalan is full of them, and most are normative errors, not style choices:

- "En base a" becomes "a partir de", "segons" or "d'acord amb".
- "A nivell de", when it is not a literal level, becomes "pel que fa a" or "en l'àmbit de".
- "Jugar un paper" becomes "fer un paper" or "tenir un paper".
- "Donar-se compte" becomes "adonar-se".
- "Tenir que" becomes "haver de": "tens que venir" becomes "has de venir".
- Neuter "lo": "lo més important" becomes "el més important"; "lo que vulguis" becomes "el que vulguis" or "allò que vulguis". The north-western article "lo" ("lo riu") is dialectal and correct; leave it.
- "Al final del dia" becomes "al capdavall" or "a la fi".
- "Eventualment" meaning "finally" becomes "finalment" ("eventual" means possible).
- "Assumeixo que ho saps" becomes "suposo que ho saps".
- "És per això que" becomes "per això".

**Missing weak pronouns.** Machine Catalan repeats the noun where a weak pronoun is natural: "Vam anar a Girona i a Girona vam veure…" becomes "Vam anar a Girona i hi vam veure…"; "Si vols informació, demana informació" becomes "Si vols informació, demana-la". Do not add pronouns that change the writer's register.

**Periphrastic passive.** "L'estudi va ser realitzat per l'equip" reads translated. Use the active voice ("L'equip va fer l'estudi") or the passiva pronominal ("Es va fer l'estudi"). Leave it when the actor is unknown or beside the point.

**English possessives.** Catalan drops possessives when the owner is obvious: "Aixeca la teva mà" becomes "Aixeca la mà"; "Renta't les teves mans" becomes "Renta't les mans".

**Gerund titles.** "Millorant la teva web", "Entenent el SEO local" copy English -ing titles. Use "Com millorar la teva web", "Millora la teva web" or a noun phrase.

**Mixed forms of address.** Tu and vostè, or vosaltres and vostès, mixed in the writer's own sentences. Pick the writer's form and hold it. Quoted text keeps its own.

## Eval cases

Run these after editing a Catalan draft, in addition to the checks in `eval.md`.

1. Si és documentació tècnica, una especificació, un informe, una acta o un text legal, has desactivat només els sis patrons de la secció de registre i has mantingut la resta?
2. Has deixat intactes les cites, el codi, els textos d'interfície, els missatges d'error i les fórmules legals?
3. Has respectat la varietat dialectal i la forma de tractament de l'autor (tu, vostè, vosaltres, vostès)?
4. Has evitat inventar xifres, noms o fonts? Si faltava una dada, l'hi has preguntat a l'autor?
5. Han desaparegut els gerundis de posterioritat, els calcs i la passiva perifràstica innecessària?
6. Hi són encara les frases «no és X, sinó Y» que corregeixen una suposició del lector?
7. Hi ha pronoms febles on el català els demana, sense canviar el registre de l'autor?
8. Els encapçalaments van en minúscula llevat de la inicial i els noms propis, i després de dos punts hi ha minúscula quan correspon?
9. El guió llarg només marca incisos, i cap no s'usa com a recurs de ritme?
10. El text acaba en una dada concreta, una conclusió o el pas següent, i no en una frase lapidària ni en un resum?
