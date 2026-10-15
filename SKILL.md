---
name: no-ai-slop
description: Cosmetically edit casual, technical, and scientific drafts to remove formulaic AI wording while preserving voice, facts, and claim strength. Use for less AI-sounding writing, light copyediting, or a style audit without rewriting. Research manuscripts receive conservative sentence-level edits, not substantive revision.
---

# No AI slop

Remove formulaic wording with the smallest useful edit. Preserve the author's meaning, personal voice, and genre. A clean draft may need no changes. Cosmetic editing is the default; becoming more persuasive, opinionated, concise, or accessible is not permission to change substance.

## Modes and scope

**Edit (default):** Return the edited draft and a brief **What changed** note. Apply the preservation rules before any stylistic preference.

**Detect:** When asked to audit or flag writing without rewriting, quote the relevant passage, name the pattern, and briefly explain a possible cosmetic fix. Do not rewrite the draft, assign an AI probability, or infer authorship. Familiar phrases alone are not evidence that AI wrote a text.

Use the draft and request to infer audience, language, and register. Ask for text if none is available. Ask about audience only when the answer is needed to avoid a consequential change. If a passage is ambiguous, leave it unchanged, flag the specific ambiguity, and continue safe edits elsewhere.

## Meaning comes first

These rules override every pattern and word preference below, in every genre:

- Do not invent facts, examples, measurements, mechanisms, opinions, sources, or takeaways to make prose more concrete. Use only what the supplied text already establishes.
- Preserve who did what, to whom, when, why, and under which conditions. Keep negation, comparison, chronology, exceptions, and the distinction between possibility, observation, interpretation, and established fact.
- Preserve claims even when they sound inflated or unsupported. Remove only empty framing around them. Flag a questionable assertion separately; deleting, weakening, strengthening, or correcting it requires a substantive editing request.
- Keep the writer's language, dialect, spelling convention, formality, humor, bluntness, uncertainty, and intentional fragments. Do not add slang, errors, anecdotes, contrived variation, or opinions to simulate a human voice.
- No word, punctuation mark, or sentence shape is banned outright. Keep technical terms, purposeful repetition, real contrasts, and distinctive phrasing. Replace a word only when the alternative means the same thing in context.
- Prefer direct verbs when they help. Keep passive voice when the actor is unknown, immaterial, or conventionally omitted. Subjects such as algorithms and instruments can legitimately perform actions.

## Research and technical protection

Automatically use **cosmetic-only manuscript editing** for research papers, abstracts, theses, scientific passages, and publication submissions, even if the user simply says “remove slop.” Apply the same protections to technical claims inside other genres.

1. **Freeze protected content.** Keep numbers, precision, signs, units, ranges, uncertainty intervals, statistical notation, variable names, equations, chemical expressions, code, identifiers, entity names, versions, quotations, and citation markers byte-identical unless explicitly asked to edit them. Preserve reference entries, URLs, DOIs, labels, cross-references, and their ordering. A suspected typo inside protected content is a flag, not a silent fix.
2. **Preserve fact binding.** Every measurement, attribution, comparison, and conclusion must remain attached to its original subject, population, material, dataset, run, method, and conditions. Matching the numbers alone is insufficient. Do not merge or reorder across subject boundaries. Check sentence splits against the original, including pronoun antecedents and citation scope.
3. **Freeze scientific force.** Preserve causality versus association, observed versus simulated results, relative versus absolute change, statistical versus practical significance, and absence of evidence versus evidence of absence. Retain scope, assumptions, limitations, exceptions, quantifiers, and uncertainty. Do not change “may” to “does,” “suggests” to “demonstrates,” or “not statistically significant” to “no effect.”
4. **Respect terminology.** Keep established and author-defined terms, acronym definitions, and distinctions between quantities. “Robust,” “significant,” “novel,” “leverage,” and “noise” can carry precise meanings. Do not substitute synonyms merely to reduce repetition, or unify terms unless their identity is explicit in the source.
5. **Keep publication structure.** Preserve sections, paragraph order, headings, tables, figure contents, captions' factual content, and required abstract/discussion/conclusion structure. Edit prose within that structure. Keep LaTeX commands, environments, math, citation keys, and document markup intact; edit only clearly identified prose spans. Do not reflow the entire source file.
6. **Stay local.** Prefer a word or clause change. Do not compress a paragraph into a summary, remove a limitation, or add interpretation. Preserve meaningful repeated information across an abstract, results section, and conclusion. If equivalence requires scientific judgment, keep the original and flag it.

For a file edit, retain a recoverable original or a reviewable diff before writing. Do not accept or erase existing tracked changes or comments. Use native tracked changes when available and appropriate to the requested format; otherwise provide a separate comparison. Never describe a wording check as scientific validation.

## Style patterns to inspect

These are candidates, not automatic deletion rules. Edit only when they add no meaning or replaceable wording has the same meaning.

- **Throat-clearing and inflated diction:** Trim empty introductory phrases and replace unnecessarily elaborate words with ordinary equivalents. Preserve genuine emphasis and the author's spoken rhythm.
- **Importance puffery and superficial analysis:** Inspect grand significance claims and trailing clauses that announce impact without explaining it. Cut empty emphasis; retain or flag any actual assertion rather than quietly removing it. Never replace puffery with a newly invented benefit.
- **Vague attribution:** Flag unnamed authorities or unsupported consensus. Do not invent a source, strip the attribution to turn an opinion into fact, or remove an attached citation. Name a source only when already unambiguously supplied.
- **Dramatic contrast:** Simplify empty “not X, but Y” framing only if both the excluded X and asserted Y retain their meaning. Keep scientific exclusions and corrections of actual misconceptions.
- **Faux insight and rhetorical reveals:** Trim generic expertise claims, self-answered questions, and theatrical colon setups when they contribute nothing. Preserve genuine questions, purposeful labels, and the author's humor.
- **Padded rhythm:** Reduce redundant adjective clusters, forced triplets, repeated sentence templates, and choppy fragments. Keep real three-item lists and intentional cadence; do not randomize sentence lengths.
- **Synonym cycling and elaborate verbs:** Use stable terminology and plain verbs where equivalent. “Serves as” can describe a function rather than an identity, so “is” is not always interchangeable.
- **Stock endings:** Remove empty recaps or decorative closing lines only if they carry no claim and the format does not need them. Preserve real limitations, future work, conclusions, and next steps. Do not write a new moral or takeaway.
- **Decorative formatting:** Reduce distracting bold, emoji, tiny sections, unnecessary lists, and dash clusters when appropriate to the genre. Keep useful lists, casual emoji, typographic conventions, and required formatting. No dash quota.
- **Chat residue:** Remove an unmistakable assistant preamble or offer accidentally pasted into the draft. Preserve quotations of such text. Flag placeholders, broken citations, and uncertain artifacts; do not guess missing content or delete evidence of a citation problem.

Watch words include delve, foster, leverage, utilize, facilitate, empower, streamline, robust, tapestry, realm, pivotal, transformative, intricate, and ever-evolving. Watch phrases include “it's worth noting,” “at its core,” “in today's world,” and “going forward.” Inspect their function rather than applying search-and-replace.

## Safe examples

- Cosmetic: “It is worth noting that the assay may detect X at 5 mg/L.” → “The assay may detect X at 5 mg/L.” Keep both the uncertainty and the value.
- Leave alone: “We used robust regression. The difference was not statistically significant.” Both terms carry scientific meaning.
- Preserve binding: “Material A lost 8% of its mass. Material B was stable at 400 K.” Keep separate subjects; never imply that A's measurement occurred at B's temperature.
- Preserve a real contrast: “The signal reflects adsorption, not absorption.” Do not remove the exclusion as a rhetorical pattern.
- Flag substance: “This groundbreaking method proves causality.” Replacing “proves” with “suggests” or deleting the claim is not cosmetic. Leave the substantive wording and flag the concern.
- Preserve voice: “Honestly, that was a mess. I'm still annoyed.” Do not automatically delete the adverb or smooth away the frustration.

## Workflow and output

1. Read the full supplied passage before editing. Identify its purpose, voice, genre, and protected content. If only an excerpt is available, preserve unresolved references and limit verification to that excerpt.
2. In detect mode, report findings and stop. Otherwise make local edits under the preservation rules.
3. Compare the result directly with the original, not from memory. Use [eval.md](eval.md). Check both unchanged protected strings and the relationships around them. Revert any edit whose equivalence is uncertain; flag it instead of repeatedly rewriting.
4. Return the complete edited passage in its original format, or the edited file and comparison when working on a document. Separate editorial notes from the draft.
5. In **What changed**, briefly summarize cosmetic edits. For manuscripts, include a before → after record for **every changed sentence**, including deletions and splits, with section/paragraph location when available. A complete tracked diff can serve as this record. For other technical drafts, record each changed sentence containing a factual claim, protected content, or attribution. Include any unresolved substantive concerns under a short separate note. Do not claim unchanged sentences are scientifically verified.
6. Honor an explicit request for revised text only or another review format. Keep the preservation checks internal even when the change log is omitted. If no edit is warranted, say so briefly rather than manufacturing changes.

## Reference and limits

Informed by [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), consulted 2026-10-04. Its observations are context-dependent editing prompts, not authorship tests or a universal style guide. Apply the relevant patterns without importing Wikipedia-specific formatting rules into research or casual writing. No need to browse the page for every edit. The preservation rules above govern this skill; no prompt can guarantee perfect semantic preservation or make a manuscript publication-ready without author review.
