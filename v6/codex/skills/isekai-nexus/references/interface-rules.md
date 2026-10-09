# In-world interface

Source: the preserved core's six INTERFACE nodes and shared behavior. Use [character record](character-record.md) for values, [Progression](../../isekai-progression/SKILL.md) for earned changes, and [foundation](foundation.md) for presentation priorities. Presentation never creates a benefit or changes a value.

## Speech-friendly output frames

Use ordinary Markdown headings, labeled lines, and blank lines for all gameplay interfaces, including tactical panels and fictional System windows. Preserve each accepted fact, number, cost, condition, and interface voice. Express percentages as "percent", ratios as "of", and multipliers as "times" where appropriate for natural speech. Reserve fenced code blocks for actual code or copyable exports explicitly requested by the player. Omit ASCII boxes, repeated-symbol borders, horizontal-rule dividers, and decorative glyph rows. This display rule governs older source examples and world-specific terminal styling.

These frames are structural templates. Replace variables with established facts, omit irrelevant fields, and repeat item sections only for actual items. Do not output placeholder text. Display only information already available to the character. These frames change presentation, not mechanics, reveal timing, or full-card gates.

### Status frame

#### {Accepted_Interface_Title}

Name: {Character_Name}

Class: {Accepted_Class_And_Tier}

Level: {Current_Level_Or_Conceptual_State}

Health: {Current_Health_And_Units_Or_Descriptive_Condition}

Active effect: {Established_Effect_And_Exact_Terms}

### Contract or item frame

#### {Contract_Or_Item_Name}

Objective or use: {Known_Objective_Or_Effect}

Hazard or cost: {Known_Risk_Or_Cost}

Reward or quantity: {Offered_Reward_Or_Actual_Quantity}

Terms: {Known_Conditions}

Next choice: {Available_Player_Decision}

### Resolved update frame

#### System update

Event: {Completed_Event}

Change: {Committed_Reward_Or_State_Change_With_Exact_Units}

Condition: {Relevant_Activation_Condition_If_Any}

Next choice: {Pending_Player_Choice_If_Any}

For a single brief alert, use one ordinary prose line such as "Skill acquired: {Actual_Skill_Name}." Keep fiction flowing; use a panel only when it helps the current turn.

## Style and first reveal

Choose a style matching world, character, and player preference. The player can change it. Record the choice and whether its introduction occurred in arrival state.

| Style | Presentation |
|---|---|
| Classic RPG | Plain quantified values and tiers, suited to game-like and magitech worlds. |
| Scribe's ledger | An understandable in-world account of equivalent abilities and condition, suited to literary and medieval worlds. |
| Esoteric oracle | Brief paths and meaningful signs, suited to conceptual and horror worlds; state actionable effects and costs clearly. |

Introduce the accepted interface once after entry, when Arrival calls for its reveal or the character first asks about status or abilities. Speak through the accepted in-world voice. Later queries show current information without repeating the introduction. Before arrival, evaluation can show a proposed build; that proposal is not an in-world reveal.

Use clean key-value pairs, short prose, or simple lists. Show name, race, class and its tier, level or conceptual state, HP/MP or descriptive condition, EXP and the accepted threshold where numeric, STR/VIT/AGI/DEX/INT/LCK, skills and levels, talents and terms, titles, and relevant available points. Use existing values. Do not manufacture a numeric grid for a descriptive build or conceal a material cost behind a cryptic glyph.

## Updates and announcements

Complete the chosen action first. Then calculate its EXP changes, determine all earned levels, skills, conditions, and titles, and emit the relevant brief alert. Apply exact progression amounts; the source's example for Level 2 to 3 is not an arithmetic authority. Do not interrupt resolution with a full status card. Full cards appear on an explicit status request or first arrival reveal.

Use concise ordinary prose announcements by default, within the narrative after their effect is resolved. Detail appears on request. A player-selected interface style can express the same facts in its accepted voice.

Skill acquired: {Skill_Name}.

Title earned: {Title_Name}.

Quest complete: {Quest_Name}.

Class evolution available: {Class_Name}.

System: Level increased from {Old_Level} to {New_Level}. {Actual_Available_Points}.

System anomaly detected.

An anomaly signals an actual earned hidden manifestation; it does not create one. On a skill-detail request show `{Skill_Name}, Level {Skill_Level}: {Actual_Effect}. Cost: {Actual_Cost_Or_Accepted_Descriptive_Terms}.` Explain limits needed for an informed action.

## Surface agreement

Formatted text is the portable default. If the platform actually supports a canvas or artifact and the player wants a graphical display, use a readable surface; white text on dark blue is the source palette. Highlight changed values. Update after completed significant changes while respecting the full-card display gate. Never claim a graphical surface or persistent update that was not created. Avoid decoration lines, repeated glyphs, and dense UI clutter.

Replace the compulsory Canvas-first preference with a supported, player-suited surface. Preserve display fields, selectable styles, one-time introduction, brief announcements, and ordered updates. Replace Oracle glyph clutter with legible equivalent information. Resolve source full-card conflicts in favor of the specific display gate.
