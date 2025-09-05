# The Light of Israel — AGENTS Guide

Purpose: This file instructs Codex (and any contributing agent) how to write, revise, and maintain continuity for the novel “The Light of Israel”. Treat it as the single source of truth for voice, structure, scope, and workflow. When in doubt, ask for confirmation before deviating.

—

1) Project Overview
- Working Title: The Light of Israel
- Genre: Historical/Contemporary literary fiction with spiritual themes (confirm or update).
- Core Themes: faith under pressure, identity and belonging, exile and homecoming, moral courage, memory and responsibility (edit as needed).
- Audience/Rating: General audience, PG–13 boundary by default.
- One‑Sentence Premise (owner to confirm): TBD. Add a concise logline here and keep it current.


2) Narrative Defaults (editable but consistent)
- POV: Close third‑person, limited. Rotate POV by chapter/scene; one POV per scene.
- Tense: Past tense by default unless otherwise specified.
- Voice: Lyrical‑contemporary, concrete sensory detail, restrained sentiment, no purple prose.
- Tone: Reverent yet human; hopeful under tension; avoid cynicism and sermonizing.
- Pacing: Character‑driven with propulsive stakes; scene goals clear; frequent micro‑turns.
- Dialogue: Subtext > exposition. Use beats and actions to ground speech.
- Language/Terms: Prefer plain English with precise nouns/verbs. For Hebrew or culturally specific terms, include the first instance in English with transliteration in parentheses, then add to Glossary.


3) Scope & Boundaries
- Content Safety: Avoid gratuitous violence; no explicit sexual content; avoid derogatory stereotypes; treat faith/culture with respect and nuance.
- Claims & Facts: If historical claims are introduced, flag with an inline editorial note and add to a Research TODO list. Do not invent real quotations.
- Sensitivity: Represent diverse characters thoughtfully; avoid tokenism; prefer specificity over generalities.


4) Manuscript Structure
- Chapters: 2,000–3,500 words target; end with a meaningful turn or open question.
- Scenes: 600–1,800 words; one clear objective, conflict, and shift in value.
- Scene Breaks: Use `***` on its own line.
- Chapter Header Template:
  # Chapter NN — POVName
  Location (optional) • Date (optional)

  Opening hook paragraph...

- File Layout (choose one and stick to it; update here):
  • Single‑file mode: `manuscript/novel.md`
  • Multi‑file mode: `manuscript/chapters/ch-XX-title.md` and an index `manuscript/novel.md` that concatenates via build script (if used).
  Current mode: TBD. Set once decided.


5) Continuity & World Bible
- Character Sheets: Maintain a profile per major character (see template below). Record age, backstory, wants, wounds, contradictions, diction tells, timeline of appearances.
- Locations: Track sensory anchors, cultural/historical notes, and recurring motifs per location.
- Timeline: Keep a dated ledger of key events. If era is historical, cross‑check calendaring.
- Glossary: Define terms, transliterations, and preferred spellings. Use a single, consistent spelling throughout the manuscript.
- Foreshadowing Map: When planting, note payoff chapter/scene; when paying off, reference plant.
- Suggested files (create when ready):
  • `docs/continuity/characters.md`
  • `docs/continuity/locations.md`
  • `docs/continuity/timeline.md`
  • `docs/continuity/glossary.md`
  • `docs/continuity/foreshadowing.md`


6) Working Rules for Codex
- Always read the previous chapter and this guide before writing.
- Confirm plan: propose a brief outline (beats, POV, scene goals) before drafting new material.
- Keep changes scoped: do not rewrite earlier chapters unless explicitly asked or you have flagged a continuity issue and proposed a surgical fix.
- Preserve voice: match narrative defaults; if the existing chapter deviates, mirror the established local voice unless this guide has been updated.
- Notes vs. Manuscript: Place editorial notes as HTML comments `<!-- NOTE: ... -->`. Never ship notes in plain text.
- Consistency: Add new names/terms to the Glossary and Character sheets as you introduce them.


7) Chapter/Scene Checklists
- Chapter Draft Checklist:
  1. Clear POV and want established in first 2–3 paragraphs.
  2. Setting grounded with 2–3 sensory specifics (sight + one non‑visual).
  3. Conflict escalates; at least one meaningful micro‑turn.
  4. No info‑dump: weave exposition into action and dialogue.
  5. End with a value shift and a forward‑looking hook.
  6. Update continuity artifacts (timeline, glossary, character arcs).

- Scene Revision Pass:
  • Cut throat‑clearing and redundancy; tighten beats.
  • Replace weak verbs/adverbs with concrete actions.
  • Check pronoun/antecedent clarity and spatial blocking.
  • Verify dialogue attribution minimal and clear.
  • Remove filler words; vary sentence rhythm.


8) Character/Location Templates
- Character Template (paste into `docs/continuity/characters.md`):
  ## Name (Primary)
  Aliases/Spellings: 
  Age(s)/Timeline: 
  Role/Archetype: 
  Core Want vs Need: 
  Wound/Backstory Highlights: 
  Contradictions: 
  Diction Tells/Voice: 
  Relationships: 
  First Appearance (ch/scene): 
  Major Beats/Arc (setup → midpoint → crisis → climax → resolution): 
  Sensitivity Notes/Boundaries: 

- Location Template (paste into `docs/continuity/locations.md`):
  ## Location Name
  Era/Date Range: 
  Sensory Anchors (3–5): 
  Historical/Cultural Notes: 
  Recurring Motifs: 
  Key Scenes: 

- Glossary Term Template (paste into `docs/continuity/glossary.md`):
  - Term (Transliteration): definition; usage note; preferred spelling.


9) Prompts & Tasks for Codex
- Draft a New Chapter:
  “Using agents.md, outline and then draft Chapter NN from POVName, goal X, conflict Y, ending with Z. Maintain voice, add 2–3 new sensory details, and update continuity notes.”
- Revise for Pacing:
  “Tighten Chapter NN by 10–15% without losing key beats. Maintain voice, preserve subtext, and ensure each scene has a clear goal, conflict, and reversal.”
- Continuity Audit:
  “Scan Chapters A–B for timeline/name discrepancies and glossary issues; propose a list of surgical fixes with exact line ranges.”


10) Editorial Notes & Research
- Use `<!-- NOTE: type=research -->` for claims that need verification; collect them in `docs/research/todo.md` (create when needed).
- Cite sources informally inside notes; do not include citations in the manuscript text unless stylistically required.


11) File Hygiene & Versioning
- Markdown only; UTF‑8; Unix newlines.
- One blank line between paragraphs; use `***` for scene breaks; no trailing spaces.
- Commit messages (if using VCS):
  • Draft: `feat(chapter): ch-07 — title (POVName)`
  • Revise: `refactor(prose): tighten ch-07 pacing`
  • Fix: `fix(continuity): align timeline ch-03/07`


12) Open Decisions (fill in and keep current)
- Era/Setting: TBD
- Protagonist(s) and initial POV roster: TBD
- Ending shape (tragedy/comedy/revelation): TBD
- Multi‑file vs single‑file manuscript: TBD
- Specific transliteration standard (e.g., SBL vs common): TBD


13) Quality Bar (Definition of Done for a Chapter)
- Meets narrative defaults or approved deviation.
- Passes Chapter Draft Checklist and Scene Revision Pass.
- Continuity updated with no broken references.
- Closing beat creates forward momentum into the next chapter.
- Owner sign‑off or explicit TODOs documented in notes.


How to Use This Guide
- Read once per session to reset voice and rules.
- If a rule blocks a better choice for this story, propose the change explicitly and update this file upon approval.
- Keep this document short, living, and authoritative.

