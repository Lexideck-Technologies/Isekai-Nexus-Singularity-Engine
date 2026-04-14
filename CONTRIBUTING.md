# Contributing to the Isekai: Nexus Singularity Engine

Welcome, fellow world-builder. This document explains how to create new worlds compatible with the Nexus Singularity Engine and contribute them to the project.

---

## Creating a New World

### Start with the Template

The file `engine/world-template.md` provides the standard structure for a world file. Copy it, rename it to `your-world-name-isekai.md`, and fill in each section.

### Required Sections

Every world file must include:

#### 1. World Classification

```markdown
# ISEKAI WORLD: [Your World Name]

## World Classification

**World Type:** [Rank] - [Category] ([Variant])
**Danger Level:** [Description of threats]
**Power Ceiling:** [Tier] ([What peak power looks like])
**Special Feature:** **[Unique Mechanic Name]** - [One-line description]
```

**World Ranks** determine the overall scale and danger:

| Rank | Scale | Examples |
|------|-------|---------|
| F | Mundane / survivable | High school, prehistoric survival |
| D | Dangerous / street-level | Street racing, frontier westerns |
| C | Hostile / systemic threats | Spy thriller, cyberpunk, noir |
| B | Lethal / civilizational stakes | Industrial war, divine politics, space opera |
| A | Extreme / continental threats | Utopian espionage, magitech |
| AA | Catastrophic / planetary | Superhero invasions, divine warfare |
| AAA | World-breaking / multiversal | Dimensional chaos, cosmic entropy |
| S | Existential / fundamental | Reality itself under threat |
| SS | Conceptual / abstract | Laws of physics are contested |
| SSS | Reality-defining | The nature of existence is at stake |

#### 2. World Overview

A 2-4 paragraph narrative description of the world. This sets the tone and communicates what makes the setting unique. Write it like the back cover of a novel, not like a technical specification.

#### 3. World-Specific Mechanics

This is where you hook into the engine. Define systems that interact with the core talent/class framework:

- **Unique progression mechanics** (e.g., "Bolter Boxing" combines ranged and melee into art forms)
- **World-specific resources or currencies**
- **Environmental rules** (gravity, magic behavior, technology constraints)
- **Faction structures** specific to this world

The engine provides the base RPG systems (stats, leveling, combat resolution, crafting). Your world file provides the flavor, constraints, and unique mechanics layered on top.

#### 4. Factions and Power Structures

Define 3-6 major factions with:
- Name and description
- Starting reputation (Hostile / Unfriendly / Neutral / Friendly / Exalted)
- Key NPCs associated with the faction
- What reputation with this faction unlocks

#### 5. Key Locations

At least 3-5 locations including:
- A **starting safe zone** (where the player arrives)
- A **hub** (where they register, take quests, interact with NPCs)
- One or more **adventure zones** (dungeons, wilderness, contested territories)

#### 6. Starting Conditions

Define how a transported soul enters this world:
- What do they see, hear, and feel on arrival?
- Who or what greets them?
- What is the immediate situation they must navigate?

---

## Style Guidelines

### Tone

Match the tone to the world's genre. A noir detective world should read like Raymond Chandler. A cosmic horror world should read like Lovecraft filtered through anime. A high school drama should read like a visual novel. The engine is genre-agnostic; your world file provides the voice.

### Naming Conventions

- File names use kebab-case: `your-world-name-isekai.md`
- World names in the header use title case
- Faction and location names should be evocative and memorable

### Length

Most worlds in the current collection are 12-30KB of markdown. This is a guideline, not a rule. The world needs to be detailed enough that an AI can run a complete multi-session adventure without inventing critical lore, but concise enough that it fits comfortably in a model's context window alongside the engine.

### Compatibility

Your world file should work with the engine's existing systems without modification. Specifically:

- Characters arrive via one of the engine's Transportation Origins
- The Talent and Class systems apply (your world can add world-specific classes)
- The Faction & Reputation tiers (Hostile through Exalted) are used as-is
- The dungeon generation, crafting, and companion systems can operate in your setting
- The nine-phase meta-instruction structure applies to pacing

If a world requires a mechanic that contradicts the core engine, document the override explicitly in the world file.

---

## Submitting a World

1. Fork this repository
2. Create your world file in the `worlds/` directory
3. (Optional) Add a world illustration to `media/` as a `.webp` or `.png` file with a matching filename
4. Open a pull request with a brief description of the world's genre, rank, and what makes it interesting

All contributions are accepted under the same CC BY-SA 4.0 license as the rest of the project.

---

## Creating World Illustrations

World illustrations are welcome but not required for a contribution. If you include one:

- Place it in the `media/` directory
- Name it to match the world file (e.g., `your-world-name-isekai.webp`)
- Any style is acceptable; the current collection ranges from painterly to digital art
- Aim for an image that captures the world's essence at a glance

---

## Questions?

Open an issue on this repository. The community and maintainers will help.

---

*Every world starts as a blank markdown file and a good idea. The engine handles the rest.*
