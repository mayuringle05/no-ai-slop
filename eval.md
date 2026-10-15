# No AI slop evaluation

Use after editing, comparing directly with the original. Preservation failures outrank style improvements: revert an uncertain edit, flag the passage, and continue elsewhere. Do not force changes to satisfy a pattern checklist.

## Preservation checks

- No claim, fact, example, source, mechanism, opinion, or takeaway was invented, removed, weakened, or strengthened.
- Numbers, units, precision, notation, names, quotations, citations, references, code, identifiers, and markup remain identical unless their change was explicitly requested.
- Facts still refer to the same subjects, methods, populations, conditions, and comparators. Citation scope and pronoun antecedents remain clear and unchanged in meaning.
- Negation, quantifiers, exceptions, uncertainty, causal force, and distinctions between measurement and interpretation remain intact.
- Technical terms retain their meanings. Distinct quantities remain distinct; repetition was not “fixed” with misleading synonyms.
- Manuscript sections, paragraph order, factual table/figure content, and required conclusions remain intact. No editorial note entered the manuscript itself.

## Style checks

- Each edit addresses an actual local problem; clear or distinctive sentences can remain unchanged.
- Voice, language, dialect, register, humor, and meaningful uncertainty are preserved.
- Watch words were evaluated in context. No blind word bans, forced active voice, punctuation quotas, invented details, or artificial “human” mistakes were used.
- Empty framing was reduced without suppressing meaningful contrasts, real lists, useful summaries, necessary limitations, or the author's claims.

## Output checks

- The full edited passage or requested file is supplied, with a concise change note unless the user requested otherwise.
- Every changed manuscript sentence is reviewable as before/after text or in a complete diff, including deleted and split sentences. Other technical edits expose each changed factual sentence.
- Ambiguous or substantive issues are separately flagged without speculative fixes. Preserving the original is acceptable.
- Any verification statement describes only checks actually performed; it does not promise scientific correctness or detector evasion.
- Detect-only output quotes patterns with a brief explanation, without rewriting or assigning authorship probabilities.

## Behavioral regression cases

Use these when changing the skill. Evaluate meaning and scope, not exact stylistic wording. These examples are fixtures, not facts to add to user drafts.

| Input or request | Required behavior |
| --- | --- |
| “It is important to note that treatment may reduce risk in adults aged 40–60 years (RR 0.82; 95% CI 0.67–1.01).” | May remove the opener; retain the modal, population, and statistical expression exactly. |
| “We used robust regression and inspected leverage values.” | Keep both technical terms; no mandatory edit. |
| “The effect was not statistically significant; equivalence was not established.” | Preserve both propositions; never rewrite as no effect or equivalence. |
| “A lost 8% of its mass. B was stable at 400 K.” | No fact transfer between subjects or inferred condition for A. |
| “The signal reflects adsorption, not absorption.” | Keep the exclusion and both distinct terms. |
| “In this simulation, X was associated with Y after adjustment for Z.” | Preserve simulation, association, and adjustment; no causal rewrite. |
| “The intervention reduced risk by 10%.” | Do not infer percentage points, baseline risk, or a relative/absolute interpretation. |
| “All samples except S3 were measured at 1 bar.” | Preserve the quantifier, exception, subject, and condition. |
| “This revolutionary method proves causality.” | Do not silently remove or downgrade substantive claims; flag the concern. |
| “Studies show X [7].” | Do not fabricate authors, remove [7], or turn an attributed assertion into an unattributed fact. |
| `We observed $x < 0$ (Fig.~\ref{fig:a}) \citep{Lee2024}.` | Preserve math, commands, keys, reference scope, and claim. |
| A paper with Abstract, Results, Limitations, and Conclusion repeating its principal result | Preserve required sections and meaningful repetition; no generic recap deletion. |
| “Honestly, that was a mess. I'm still annoyed 😂” in a casual message | Preserve emotion and register; no automatic formality or emoji removal. |
| “We measured mass, volume, and density.” | Preserve all three list items; a triplet is not itself padding. |
| `This result is established [INSERT DOI].` | Flag the placeholder; do not invent or silently remove a reference. |
| A quotation containing “delve,” or code using `robust` | Leave the protected text unchanged. |
| “Audit this only: In today's fast-paced world, our tool is a game changer.” | Quote and identify style concerns; no rewritten draft or AI-authorship verdict. |

Perform the evaluation directly; separate editor and evaluator agents are not required.
