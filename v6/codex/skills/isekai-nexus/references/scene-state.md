# Scene state agreement

Keep active campaign state separate from fixed helper tables, intake sketches, proposed builds, and accepted builds. Read [loop protocol](loop-protocol.md), [character record](character-record.md), and [arrival state](arrival-state.md). Session state supports continuity; durable persistence requires an actual supported write.

| Field | Content |
|---|---|
| Campaign/world | Campaign identity, complete world identity/version, visited-world histories, accepted local access |
| Character | Identity, accepted revision, current earned record, starting allocation reference |
| Position | Location, local time, scene facts, elapsed-time basis, ongoing conditions |
| Resources | Established HP/MP or descriptive health, funds, inventory, capacity, commitments and recovery |
| Participants | Present NPCs, actual intentions, affiliations, companions, accepted relationships, per-NPC dismissal beat and one optional deliberate-persona reset |
| Interface | Accepted display style, introduction flag, latest completed update |
| Active loops | Loop identity, objective, stage, evidence, commitments, linked objectives |
| Pending choice | Unresolved action, evolution, allocation, bargain, or stopping condition |
| Attempt | Identity, declared intent, participating loops, incoming revision, actual outcome, elapsed time |
| Effects | Identity, owning procedure, trigger/evidence, proposed/applied state, before/after value |
| Progression | EXP convention/curve, current progress and threshold, available points, skills, cultivation, titles, Authorities |
| Continuity | Arrival episode, interruption return position, pending owner handoffs, fictional save snapshot/timeline |

One declaration creates one attempt. A compound action can have several distinct effects under that attempt; retain causal order. If later actions depend on prior consequences, resolve successive attempts using the updated state. Administrative questions, quoted commands, and corrections do not consume fictional time. Record actual progress before interrupting; resume pending work rather than replay completed work.

Resolution adjudicates costs and owns physical outcome, health/MP changes, conditions, and elapsed time. Commit each effect through its owner below. Owners exchange effects with identities before commitment. Keep pending effects if interrupted; an applied identity prevents duplication. An outcome is not applied merely because it was drafted or narrated speculatively. Do not claim a transaction system exists if only conversation state is available.

Arrival completion creates no reward. A new-world entry preserves earned character state and confirmed access restrictions. World-local clocks, NPC histories, obligations, and property remain attached to the visited world. Re-entering does not reset them. [Montage](../../isekai-montage/SKILL.md) reuses these attempts and owners over the agreed interval; repeated prose is not an additional award event.

Expose only meaningful fictional results, useful in-world information, and choices. State keys and bookkeeping stay internal. Provide the full status record when requested. If context loss makes an important state uncertain, ask for that fact or read the supported record before applying an irreversible fictional consequence; do not invent continuity.

## Effect ownership

| Effect type | Commit owner |
|---|---|
| Causal outcome, HP/MP, physical conditions, elapsed time | Resolution |
| Inventory acquisition/consumption/transfer and funds payment/income | Craft-Trade/Economy, using Resolution's same cost/outcome proposal |
| EXP, levels, points, skills, class/talents, cultivation, titles, Authorities | Progression |
| Relationships, reputation, companion affinity | Social/Companions |
| Domain project state, development, income eligibility | Domain; actual funds movement belongs to Economy |
| Loop objective, stage, completion evidence | Corresponding activity cover |

A consumed potion has one inventory decrement owned by Economy and one health effect owned by Resolution under the same attempt. A domain income entitlement has one Domain eligibility result and one Economy funds movement. Resolution does not also decrement stock or funds. If an owner handoff remains pending, preserve its identified effect without silently applying a second owner's version.
