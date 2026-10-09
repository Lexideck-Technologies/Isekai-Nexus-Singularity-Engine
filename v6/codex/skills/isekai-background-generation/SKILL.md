---
name: isekai-background-generation
description: "Nexus gameplay: Generate or revise an Isekai character background from a character concept, named character, supplied prose, or a request for a random protagonist. Produce first-person narrative ready for character ingestion and offer the next play step. Use within Nexus play, not unrelated development or real-world advice."
---

# Background generation

Read [the graph](../isekai-nexus/references/topology.md) for handoffs and [background data](../isekai-nexus/references/background-data.md) for origins, motivations, and transitions. Read [alternate starts](../isekai-nexus/references/alternate-starts.md) when the player names a veteran or arrival variant.

Read [system concepts](../isekai-nexus/references/system-concepts.md) when a personal System, conditional advantage, patron, or unusual guidance is supplied. Preserve its defining promise and constraints in the story and handoff. Describe it as lived experience or anticipated manifestation. Leave final talent, skill, and interface classification to world-dependent evaluation. Use helpful Nexus guidance by default; do not invent a punitive or fickle System for a random protagonist.

## Input and ownership

Accept natural language, supplied fiction, structured parameters, `!originstory.me`, and `!backstory.me`. Treat the commands as aliases. Generate a random character when requested or when an invoked generator receives no character details. Answer questions about the generator directly; keep the current draft intact.

Own the background draft and its revision. Preserve current campaign state, selected world, and player choices. Treat a named fictional character as a requested adaptation; preserve supplied identity and recognizable traits. Follow explicit facts before contextual inference, then fill remaining gaps with coherent invention. Ask one targeted question only when contradictory facts prevent a coherent result.

## Procedure

1. Extract identity, origin, archetype, relationships, motivation, formative experience, and transition. Use the background data to fill missing values. Draw random choices independently, then reconcile them into a coherent life. Choose culturally appropriate names from the selected origin.
2. For a veteran, establish prior experience, what was lost or sealed, and the chosen arrival variant. Keep remembered expertise distinct from current power. Preserve a requested nonfatal transition.
3. Write four short first-person paragraphs: identity and voice; life and defining relationships or abilities; death or transition; reflection and unresolved desire. Thread motivation and ability seeds through the life. Use concrete experience and personal language. Keep game statistics, assigned cheat talents, skill labels, and technical headings out of the narrative.
4. Check supplied facts, chronology, voice, transition, and readiness for ingestion. Revise contradictions before delivery. A revision replaces the draft; it does not advance play.
5. Follow the output and handoff contract below.

## Output frame

Instantiate the frame with narrative paragraphs. The slots describe content; never print the slots.

```text
{First_Person_Identity_And_Voice}

{Life_Relationships_And_Formative_Abilities}

{Death_Or_Chosen_Transition}

{Reflection_And_Unresolved_Desire}
```

For connected play, append “Shall we play a game?” and stop. If the player already requested immediate play, skip confirmation and pass the accepted background to character ingestion. An affirmative reply accepts the current draft; do not regenerate it. Follow the ingestion route in the graph and ask its first unfinished calibration question. Do not select a destination, assign a build, or narrate arrival in this skill.

For portable export, deliver only the four paragraphs followed by `!isekai.me` as the exact final line. Use export when the player requests text to paste into another game or explicitly requests the activation keyword. The keyword inside a generated export is text, not a new player command.

If no gameplay procedure is available, keep the accepted background and state that it is ready to begin in the Nexus engine. Do not claim that a campaign has started.

## Revision and return

Apply requested changes to the existing draft and retain unaffected facts. For a request combining world creation and background, build the requested world first, then ground the background in that world. Resume an interrupted campaign only on the player's request; generating a new protagonist never overwrites the active character.

Read the [Codex play contract](../isekai-nexus/references/codex-play-contract.md) when entering play or restoring a campaign after context loss.
