# Arrival state agreement

Arrival is a scene state between accepted evaluation and ongoing play. It adapts source `TRANSPOSITION.STEP` and the first-breath, interface, contact, and opportunity functions of `IGNITION.GUIDE`. Evaluation already owns the accepted synthesis and starting allocation. Player action and downstream resolution govern combat, completion, payment, loot, and progression.

## Episode record

| Field | Content and authority |
|---|---|
| Episode identity | Unique identity for this entry; retained through interruption and revision |
| Character | Continuing character identity and accepted build revision |
| Destination | Complete world identity/version and selected start or accepted transfer situation |
| Lifecycle | `ready`, `entered`, `awaiting_action`, or `complete` |
| Position | Current location, local time, immediate situation, and relevant scene facts |
| Relationships | Actual contacts, affiliations, and their current intentions |
| Pending decision | Opportunity offered and any unresolved player choice |
| Interface reveal | Whether the first in-world introduction has occurred; accepted style and system terms |
| Allocation reference | Evaluation's existing allocation identity; no arrival-owned duplicate grant |
| Handoff | Declared player intent, relevant scene state, and applicable play-loop route |

Keep these fields in available session state. Claim durable persistence only after an actual supported write. The episode record is internal; player output contains its fictional consequences.

## Lifecycle

| State | Entry condition | Next transition |
|---|---|---|
| `ready` | Full world, selected start, and accepted character or local-access record exist | Begin this entry once, then `entered` |
| `entered` | Entry has occurred and its position is recorded | Present the immediate opportunity, then `awaiting_action` |
| `awaiting_action` | A concrete scene and pending choice have been presented | An actionable player response hands off to play and sets `complete` |
| `complete` | Arrival has handed the player action to ongoing play | Continue the existing scene under its relevant procedures |

One opening response can move from `ready` through `entered` to `awaiting_action`. Record entry before continuing a partially interrupted response. An informational or administrative question retains the present state. Completion records the handoff, not success, elapsed time, a reward, or a level-up.

## Shared boundaries

- **Evaluation overlap:** read the accepted revision and its allocation identity. Reveal powers and gear already granted; allocate nothing. A defining conflict suspends scene advancement until reevaluation is accepted. Resume the same episode and retain scene facts already established.
- **World overlap:** read the actual complete world instance and selected start. Summary cards cannot support arrival. Generated local detail fits that instance and does not rewrite fixed world facts.
- **System overlap:** preserve the character's accepted benefits, conditions, interface, and agency. Personality shapes dialogue; it never changes operative terms during arrival.
- **Play overlap:** pass one declared action and one incoming state to the applicable loop. Arrival never awards a second effect for that action. No mandatory guild, combat, quest, or cultivation sequence follows from the label of a start.
- **Transfer overlap:** accepted entry into a different world creates a new episode, not a new character. Preserve earned power and assets, apply confirmed local-access conditions, and avoid reapplying starting allocations or the original transport-origin benefits. Revisiting a world preserves its campaign history; a new entry scene is not a world reset.
- **Interruption overlap:** preserve location, time, contacts, interface-reveal flag, and pending decision. Returning does not trigger another arrival, replay a death, spend resources, or move the player.

Tailoring changes scene composition while shared facts remain consistent. The same Academy and Hunter procedures draw different openings from their accepted records; neither procedure dictates the player's first action.
