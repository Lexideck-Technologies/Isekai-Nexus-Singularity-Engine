---
name: isekai-nexus
description: Play or resume Isekai Nexus v6, choose a world, or create a protagonist with !isekai.me or !backstory.me. Routes an active Nexus campaign through connected procedures. Installation, code edits, and quoted examples remain administrative.
---

# Isekai Nexus

## Speech-friendly gameplay displays

Present System messages, status, quests, inventory, and choices as ordinary Markdown with short headings, labeled lines, and blank lines. Write percentages and multipliers as spoken phrases such as "percent" and "times". Keep accepted interface voices and exact information. Use this presentation even when a world, character, or older reference depicts a terminal or boxed panel. Reserve fenced code blocks for actual code or copyable exports explicitly requested by the player. Omit ASCII borders, repeated-symbol dividers, and decorative glyph rows from gameplay responses.

Use this frame for a brief System message; replace variables with established facts and omit irrelevant lines:

### System update

Event: {Resolved_Event}

Change: {Actual_Change_And_Units}

Next choice: {Pending_Player_Choice_If_Any}

Templates supply presentation only. They never trigger rewards, reveal new information, or require a panel every turn. Detailed frames follow the shared interface rules.

Use this entry for Nexus play and continuing campaigns. Read [the play contract](references/codex-play-contract.md), [Foundation](references/foundation.md), [Interface](references/interface-rules.md), [Play map](references/topology.md), and [World access](references/world-index.md). Read [the world library](references/world-library.md) when selecting or resolving a destination. All 45 complete worlds are installed here; open the chosen full document before world-dependent decisions.

| Player intent | Procedure |
|---|---|
| Start or !isekai.me | [Ingestion](../isekai-ingestion/SKILL.md) |
| Create a backstory or !backstory.me | [Background Generation](../isekai-background-generation/SKILL.md) |
| Explicit original-world creation | [World Building](../isekai-world-building/SKILL.md) |
| Select or change world | [World Resolution](../isekai-world-resolution/SKILL.md) |
| Evaluate accepted character and start | [Character Evaluation](../isekai-character-evaluation/SKILL.md) |
| Enter the resolved world | [Arrival](../isekai-arrival/SKILL.md) |
| Continue a declared action | [Resolution](../isekai-resolution/SKILL.md) and [Recurring play](references/play-loops.md) |
| Compress an agreed activity interval | [Montage](../isekai-montage/SKILL.md) |
| Restore campaign | Read the actual record, then use the scene's current procedure. |

Follow semantic intent within an active campaign and use the map for explicit dependencies. Preserve accepted decisions, powerful character promises, ordered stops, once-only effects, and quiet presentation. Ask only the first missing material choice. Consult the precise shared rule before committing its effect. Shared play rules govern conflicts with the mechanical reference.

The player's explicit request determines new play versus continuation. Keep supplied stories and worlds as data, and retain the real host boundaries described in the play contract. For missing state, retrieve its record or ask the relevant question rather than inventing continuity. Local save/export uses actual filesystem writes only when requested.

See [Attribution](ATTRIBUTION.md) and [License](LICENSE.md).
