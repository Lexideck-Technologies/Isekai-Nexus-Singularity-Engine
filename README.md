# Isekai: Nexus Singularity Engine v6

**One life behind you. Forty-five worlds ahead. What will you become?**

Nexus is an AI-run roleplaying engine for second lives, impossible talents, academy rivalries, hard-won friendships, and journeys across worlds. Bring a character, choose a destination, and make the next decision yours.

Version 6 connects 23 play procedures through eight Gemini skills. The worlds travel separately: install the engine once, then attach the complete world you want to enter.

## Choose your edition

- **Codex:** install 24 local skills with the complete world library. Follow the [Codex installation guide](v6/codex/README.md).
- **Gemini:** upload eight individual skill ZIPs and attach your selected world. Follow the quick start below.

## Gemini quick start

1. Download this repository using **Code > Download ZIP**, then extract it.
2. Open Gemini on the web and go to **Settings > Skills > Upload**.
3. Open the `v6/` folder and upload **each of its eight skill ZIPs separately**. Review and create each skill. Keep the ZIP files intact for upload.
4. Choose a destination from the [world index](v6/isekai-nexus-world-library/WORLD-INDEX.md).
5. Start a chat, select the Nexus entry skill through Gemini's skill picker, and attach that destination's complete Markdown file from `v6/isekai-nexus-world-library/worlds/`.
6. Tell Nexus who you were, or type `!isekai.me` and begin creating your character.

The eight ZIPs are separate installation units. Uploading the entire distribution as one skill did not work in the reported tests. The world library stays on your device until you attach a chosen world to the play chat.

## Begin with a life

You can give Nexus a detailed history, a few sentences, or a single compelling idea. For a developed backstory, try:

```text
I was an apprentice clockmaker in a city where only nobles could study magic.
I repaired the academy's clocks, and learned its lessons through the walls.
One night, every clock stopped at the same impossible hour.

!backstory.me please!
```

Then continue into play with `!isekai.me`. Nexus helps establish motivation, destination, alternate start, and a world-compatible character before arrival. You can also bring an existing traveler and their actual character record.

If you name an existing destination whose complete document is missing, Nexus should request that file and hold your choices while you supply it. You can explicitly ask it to create an original world instead.

## Choose how you arrive

The shared catalogue offers nine starts, interpreted through each world's setting:

| Start | Opening premise |
|---|---|
| Classic | Begin with little and make your own foothold. |
| Academy | Enter a place of study, competition, and discovery. |
| Guild | Find work, allies, and opportunities through a local institution. |
| Party | Begin with companions and a shared history. |
| Deep End | Face immediate danger with room for extraordinary survival. |
| Recruited Transplant | Arrive through a summons with disclosed terms. |
| Multiversal Hunter | Bring experience from beyond this world. |
| Time Travel | Return with knowledge of a particular earlier history. |
| Awakening | Recover a remembered self and its latent capabilities. |

Some worlds also offer custom openings. The supplied world defines their assets, relationships, obligations, and usable power.

## A world worth staying in

The library contains **45 worlds**: 44 start-aligned destination editions and **Superearth Olympus**, an original academy-fantasy world of enormous landmasses, ocean expanses, varied cultures, and intertwined leveling and cultivation.

The broader collection ranges from intimate social drama to magitech civilizations and conceptual realms. World classification, local opening danger, and the setting's power ceiling are distinct. Consult the full destination document for the experience you want.

Browse the [complete world library](v6/isekai-nexus-world-library/WORLD-INDEX.md).

## The eight Gemini skills

Install all eight. Together they supply the entry point, navigation, procedures, shared rules, and mechanical reference.

| Upload | Role |
|---|---|
| [Nexus entry](v6/isekai-nexus-singularity-engine-v6.zip) | Main entry point and campaign routing. |
| [Navigation](v6/isekai-nexus-navigation.zip) | Play map, rule ownership, and world access. |
| [Creation and entry](v6/isekai-nexus-creation-and-entry.zip) | Backgrounds, world creation, intake, evaluation, and arrival. |
| [Gameplay procedures](v6/isekai-nexus-gameplay-procedures.zip) | Resolution, progression, montage, and recurring activities. |
| [Character and progression](v6/isekai-nexus-character-and-progression.zip) | Origins, alternate starts, character records, and advancement. |
| [World and scene](v6/isekai-nexus-world-and-scene.zip) | Presentation, continuity, world logic, and scene rules. |
| [Social and economy](v6/isekai-nexus-social-and-economy.zip) | Relationships, reputation, inventory, trade, and domains. |
| [Source and license](v6/isekai-nexus-source-and-license.zip) | Detailed mechanical reference and attribution. |

Each archive contains one folder whose name matches its `SKILL.md` metadata. There are no development documents or world files inside these skill archives.

## Speech-friendly displays

System messages and gameplay panels use ordinary headings, labeled lines, and blank lines. Code blocks are reserved for requested code or copyable exports. To update an existing Gemini installation, replace only the Nexus entry and World and Scene skills with their current individual ZIPs. Android read-aloud behavior for this patch remains to be tested.

## Built for ongoing play

Nexus supports exploration, academy life, cultivation, missions, expeditions, technique creation, personal systems, recovery, relationships, crafting and trade, communities, domains, survival, and multiversal travel.

Shared rules keep overlapping activities tied to one campaign state. One accomplishment can contribute distinct kinds of growth while each reward applies once. Montage advances an agreed plan and returns to a scene when a meaningful player decision arises.

Player choices and accepted character promises guide play. A powerful protagonist keeps their established capabilities, subject to their actual terms and the destination's documented conditions. Campaign records and fictional time-reset powers have separate meanings.

## What has been tested

The creator reports that Gemini accepted all eight individual skill uploads. A live backstory prompt produced the intended opening, and Superearth Olympus offered all nine alternate starts.

Local checks confirm eight valid single-skill archives, 23 procedure sections, 265 linked file/anchor references across the combined skill layout, and 45 world files matching the working library. The six unchanged skill ZIPs preserve their tested bytes; the entry and World and Scene ZIPs include the speech-friendly presentation patch.

These are encouraging opening tests. Sustained progression, mixed activity turns, interruptions, world transfers, and comprehensive access between separately installed skills remain to be tested. Local link checks establish the package's structure; they do not prove Gemini's handling of every dependency.

If play loses a required rule or world document, provide the missing material rather than treating an improvised replacement as established canon. Keep your own campaign exports and character records for future sessions.

## Repository layout

```text
v6/
  README.md
  codex/                            Codex skills, portable ZIP, and guide
  eight individually uploadable skill ZIPs
  LICENSE.md
  ATTRIBUTION.md
  CHANGELOG.md
  package-receipt.json
  SHA256SUMS.json
  isekai-nexus-world-library/
    WORLD-INDEX.md
    LICENSE.md
    ATTRIBUTION.md
    worlds/                         45 complete world documents
engine/                             earlier engine material
worlds/                             earlier world material
```

The `v6/` directory contains the current Gemini and Codex distributions. Earlier repository material remains available for continuity; follow the v6 instructions for this edition. Private development and memory material are excluded.

## License and lineage

Created by **Lexideck Technologies**. Version 6 adapts the earlier Nexus engine into connected play procedures, aligns alternate starts across the world collection, adds Superearth Olympus, and packages the runtime for separate Gemini skill uploads.

The engine and worlds are licensed under **[Creative Commons Attribution-ShareAlike 4.0 International](v6/LICENSE.md)**. You may share and adapt them under those terms. Preserve credit, identify changes, and use the same license for adaptations. See [attribution](v6/ATTRIBUTION.md) and the [v6 changelog](v6/CHANGELOG.md).

**Bring a past. Choose a world. Take your first breath.**
