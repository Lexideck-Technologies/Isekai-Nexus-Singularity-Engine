# Isekai Nexus v6 for Codex

The Codex edition supplies one entry skill and 23 focused play procedures, all named `isekai-*`. Shared rules and 45 complete worlds are included. Install the collection together so every procedure can reach its dependencies.

## Install

1. Download this repository using **Code > Download ZIP** and extract it.
2. Choose the workspace in which you want to play.
3. Create its `.agents/skills/` directory if needed.
4. Copy all 24 folders from this directory's `skills/` into that workspace's `.agents/skills/`. Each folder must sit directly under `.agents/skills/`. Keep the entire `isekai-nexus` folder, including its references and worlds.
5. Open that workspace in Codex. If the new skills do not appear, start a fresh chat or restart Codex.

Alternatively, extract [isekai-nexus-v6-codex.zip](isekai-nexus-v6-codex.zip) directly into the workspace's `.agents/skills/` directory. Check for existing `isekai-*` folders before replacing an older installation; keep campaign records outside skill directories.

## Begin or continue

Select `isekai-nexus` in the skill picker, or type:

```text
$isekai-nexus Let's begin an adventure on Superearth Olympus.
```

For a protagonist:

```text
$isekai-background-generation Help me create a protagonist.
```

For an existing campaign, supply its actual character and scene record:

```text
$isekai-nexus Resume this campaign from the attached record.
```

All display names use the `isekai-` prefix. Codex supports `$skill-name` mentions; `/skills` opens the CLI/IDE picker. This collection does not register custom `/isekai-*` slash commands. The desktop app's selector can also select a skill.

The engine follows semantic intent inside an active Nexus campaign, then consults the play map and precise shared rules. Administrative requests and quoted commands stay outside play. Browse the [local world library](skills/isekai-nexus/references/world-library.md); Codex opens the selected complete world directly. Upload or paste a custom or revised world when desired.

## Architecture and continuity

The Codex port splits the tested Gemini runtime into its 23 procedure sections, keeping skill bodies focused and shared rules available on demand. UI metadata supplies matching names, representative invocation prompts, and semantic activation policy. `isekai-nexus` is the entry point and authoritative home for shared references.

The [play contract](skills/isekai-nexus/references/codex-play-contract.md) preserves player choices, separate attempt/effect ownership, and once-only rewards. Campaign exports use actual file writes when requested; restoration reads an actual saved record. Fictional System windows and game documents remain game data. Private assistant memory stays separate from campaign records.

No hooks, background service, new MCP connection, or global configuration change is required.

## Verification

- 24 native-valid skills and 311 resolved local links.
- 45 complete world documents preserved byte for byte.
- 128 installed runtime files match the build.
- A fresh Codex app-server 0.152.1 process detected all 24 skills enabled, with no Nexus discovery errors.
- Five clean-conversation simulations passed: new protagonist intake, veteran/Olympus selection, absent authored world, administrative quotation, and fictional authority with duplicate-reward handling. Two minor local-library inconsistencies were corrected and regression-checked.

These are structure, discovery, and simulated behavior checks. Sustained live Codex play remains to be tested. The successful Gemini opening reports apply to that edition; they are not presented as Codex gameplay evidence.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](skills/isekai-nexus/LICENSE.md). See [attribution](skills/isekai-nexus/ATTRIBUTION.md). This is the Codex distribution of v6; the version remains v6.
