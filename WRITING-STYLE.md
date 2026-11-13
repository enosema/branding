# Standards writing style

This document defines the standards writing style of the Enosema
Foundation ("ES"). It applies to every ES publication: standards (EFS),
directives (EFD), guides (EFG) and reports (EFR), in all their rendered
forms. The style is observed in the corpora that the Foundation
maintains, and it follows the drafting practice of ISO/IEC Directives,
Part 2, as applied in documents the office authors — ISO 19135:2025,
*Geographic information — Registration and register governance*, in
particular. A companion document, `NARRATIVE-WRITING-STYLE.md`, defines
the narrative style of the website and the blog; where the two styles
disagree, the disagreement is deliberate, because a standard addresses
a reviewer and a website addresses a visitor.

Every sentence written for a standard follows the rules in this
document. A sentence that cannot satisfy a rule is rewritten until it
can; the rules are ordered so that the rewrite is usually local.

## Part I — the sentence

1. **Every sentence is a complete sentence.** Each sentence carries a
   subject and a verb and states something. Fragments used for rhythm —
   "Silent absence is the dominant failure.", "Discipline beats
   heroics." — are not used, whatever their punch, because a standard
   is consulted, not performed.

2. **A sentence may be long, and length is not a fault.** Requirements
   and their conditions travel together in one sentence, joined by
   subordinate clauses introduced by "that", "which", "where" and
   "including". The model, from ISO 19135:2025:

   > The register enables its managed content to be accessed. Units of
   > such managed content are addressable by unique and persistent
   > identifiers and accessible through a well-defined and consistent
   > addressing scheme.

3. **A term is written in full at first use, followed by its
   abbreviation in parentheses; the abbreviation is used thereafter.**
   For example, "registration authority (RA)" at first use and "RA"
   from that point onward. An abbreviation that is better known than
   its expansion in the domain may lead, with the expansion following.

4. **Claims are grounded.** A statement of fact names its evidence: the
   corpus, the count, the document, the clause, the date.
   Quantitative claims carry their sample and their measure ("4 662
   sampled entries", "median 16 words"). Judgements without a named
   ground are rewritten as observations or deleted.

5. **A referenced entity is introduced before it is relied upon.**
   When a clause depends on a mechanism, a role or a document, the
   sentence that introduces the dependence first defines the entity,
   or cites the document and clause that defines it.

6. **The reader is not addressed.** Descriptive prose uses the third
   person: "the reviewer", "the organization", "the register".
   Imperatives appear only in procedural annexes that instruct an
   operator step by step. Rhetorical questions are not used; the
   question is restated as the issue it raises.

## Part II — normative language

7. **The normative verbs are disciplined.** `shall` states a
   requirement; `should` states a recommendation whose escape is
   documented; `may` states a permission; `can` states an ability.
   `must` is not used in normative prose (DIR 2, 3.3.3). Statements of
   fact use the indicative and carry no modal. Definitions never
   contain normative verbs (see Part III, rule 17).

8. **The artifact is the subject of scope and capability statements.**
   The document declares itself in the declarative, after the pattern
   of ISO 19135:2025:

   > This document defines a framework for the extensible registration
   > of information — an approach used to manage an information
   > register.

   ES declarations follow the same form: "This document specifies
   requirements for…", "This document gives guidance for…", "This
   document describes…".

9. **Requirements carry stable identifiers where the document builds a
   traceability scheme.** Grouped requirements use the identifier
   pattern of EFS 2522 (D-1, N-2, C-3): the identifier is stable, is
   cited by checklists and scoring criteria, and survives editions.

10. **Boundaries are stated in sentences.** What the document excludes
    is written out, after the ISO 19135 pattern: "The following
    considerations are out of scope of this document:" followed by
    parallel items. Exclusion by omission is not exclusion.

11. **Notes are informative; examples are instances.** A note
    supplements the text and never states a requirement; an example
    is an instance of the concept or the rule. Requirements displaced
    into notes, and notes that argue the case of the text, are
    rewritten.

12. **Prose convention discipline.** The em dash marks a parenthetical
    and nothing else; ellipses do not end sentences; contractions are
    not used; exclamations do not appear. Possessives are not formed
    on clause numbers: write "the procedures of clause 7", not
    "clause 7's procedures".

## Part III — terminology

13. **Terms are defined in the terms clause, in entry form.** The
    entry follows ISO 10241-1: term entry number, genus first, no
    article, singular for countable nouns, `SOURCE:` attribution where
    the definition is adopted, and the substitution test applied
    before the entry is accepted (EFS 2522, Group N).

14. **A definition never uses the term it defines, never contains
    requirements language, and never begins with an article.** These
    are the corpus's most frequent defects and the easiest to detect
    (EFS 2522, anti-patterns AP-03, AP-05, AP-07).

15. **Concepts used before they are defined are cited, not assumed.**
    Where clause 3 does not define a concept that the text relies on,
    the text cites the document that defines it, at the point of use.

## Part IV — structure

16. **The document opens the problem before the mechanism.** The
    introduction states the challenge in declarative paragraphs and
    only then introduces what the document does about it (EFG 2519
    shows the pattern; its revision shows the failures to avoid).

17. **Formal enumerations are grammatically parallel.** A list
    introduced by "in a manner that:" or "the following
    considerations:" continues with items that share one grammatical
    structure, and each item carries its cross-reference, after the
    ISO 19135 model:

    > . enables persistent identification and access to its content
    > (<<persistent-identification-and-access>>);
    > . supports evolution of its content through time
    > (<<evolution-support>>);

18. **Every section lead is a sentence.** A clause that maps to
    another document opens with the complete sentence that says so:
    "This clause gives guidance for the requirements of EFS 2513,
    clause 5." — not the label "Guidance for EFS 2513, clause 5."

19. **Cross-references are precise.** Documents are cited by
    identifier and, where a clause is meant, by clause: "EFS 2513,
    clause 7". Possessive and demonstrative references ("see above",
    "the relevant standard") are defects.

## Part V — the multilingual document

20. **English is the authoritative language of ES publications.** The
    authoritative language carries the definitions; localizations
    follow the declared localization model of the register or document
    (EFS 2504; EFS 2522, Group C). Where a corpus demands bilingual
    titles, the document carries both title sets, after the ISO 19135
    pattern (`:title-intro-fr:`, `:title-main-fr:`).

21. **Proper nouns, standard identifiers and quoted terms are not
    translated.** An English definition may cite "ISO 19135:2025" and
    a French localization keeps the citation unchanged.

## Part VI — what this style excludes

- Fragments written for rhythm: "Silent absence is the dominant
  failure.", "Discipline beats heroics.", "Never, by policy:".
- Colloquialism and metaphor in place of statement: "sets any of that
  up on a Monday morning", "without archaeology", "is decoration",
  "is treading water", "the value is in the *why*".
- Coined compound labels standing in for a sentence.
- Second person in descriptive prose; rhetorical questions.
- Ungated superlatives: "the premier", "the deepest", "the best"
  unless the sentence states the measure that grounds them.
- Em dashes as dramatic pauses; ellipses; exclamations; contractions.

## A worked example

Before (found in the first edition of EFG 2519:2026):

> When do references break? Never, by policy: identifiers resolve
> forever (EFS 2513, 7.6.4).

After (house style):

> References to published items do not break. Identifiers are issued
> once and resolve for the operational life of the published records,
> either to the current record or to the retired record together with
> its successor information (EFS 2513, clause 7).

Before:

> Write one decision record per decision (Annex B). The record's value
> is in the *why*: a register's decision log is the reason new
> volunteers can understand the register without archaeology.

After:

> The control body records one decision record for each decision
> (Annex B). The rationale in the decision record is its most valuable
> field: a decision log that states grounds allows a new contributor to
> understand the register without reading its meeting history.
