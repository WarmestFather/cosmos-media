# The CosmOS Music Production Bible

Version 1.0 — 2026-11-02

## Mission

Build a coherent musical universe, not a disconnected playlist. Music must express the lived environments, cultures, characters, histories and experiences of The CosmOS. Source-of-truth lore and actual gameplay needs take precedence over genre stereotypes.

## Production principles

1. **Lore before composition.** Read the relevant current world and narrative sources before choosing a sound.
2. **Purpose before spectacle.** Score the intended listening or gameplay role; exploration must support sustained attention without demanding it.
3. **Cultural identity before convention.** Define a recognizable musical language for each place, culture and character.
4. **Contrast makes impact.** Silence, restraint and intimacy make climaxes meaningful.
5. **Continuity without repetition.** Carry motifs, harmonic traits and instrumentation forward deliberately, never mechanically.
6. **The environment is an instrument.** Keep spatial gameplay sound effects distinct from non-diegetic music unless a deliberate diegetic composition is required.

## Source-of-truth order

1. Approved CosmOS lore and narrative material.
2. Current implemented locations, gameplay and story sequences.
3. Approved album/track identity sheets and motif registry.
4. Approved environmental art and visual references.
5. Clearly labelled creative proposals.

If materials conflict, flag the disagreement instead of silently inventing canon. Do not imply that a proposed track has been generated, approved or shipped.

## Album-first process

For each album, establish:
- World, region, cultures and narrative route.
- Geographic, architectural, environmental and social grounding.
- Emotional arc and intended gameplay uses.
- Instrument palette, tempo/meter ranges, harmonic language, recurring motifs and exclusions.
- Tracklist, each track's precise role, and relationships among tracks.
- Cross-album continuity and intentional differences.

Common roles include arrival, settlement, departure, exploration, discovery, danger, combat, reflection, celebration, character and cinematic cues. **They are a vocabulary, not a mandatory checklist.** Number of tracks follows the location and story.

## Track brief

Before Suno generation record:

- Identity: title, album, location/character, role, lore evidence.
- Experience: player activity, feeling, energy, duration, replay and transitions.
- Composition: tempo, meter, instruments, melodic/harmonic language, rhythm, motifs and musical arc.
- Production: acoustic/electronic balance, ambience, vocal identity if applicable, mix, loop behavior, exclusions.

Every track must have a distinct reason to exist within its album.

## Suno authoring contract

**Style prompt: maximum 1,000 characters.** Specify production identity: role, tempo/groove, instruments, melodic/harmonic vocabulary, sound/space, emotional direction, vocal approach and essential exclusions. Be musically precise; avoid competing instructions and adjective overload.

**Lyrics / arrangement field: maximum 5,000 characters.** For sung music, provide intentional lyrics, performance and section directions. For instrumental music, provide section-by-section arrangement instructions with no fabricated sung text. Describe introduction, development, changes, motif return and outro/loop as appropriate, not mechanically.

The **style** says what the track is; the **arrangement** says how it moves. Validate consistency and character limits before each generation. Suno direction is a creative request, not a guarantee of output.

## Scoring for interactive worlds

- Exploration tracks: restrained, replayable, evolving slowly; resist relentless rhythmic activity, constant swells and over-obvious hooks.
- Departure tracks: forward movement and anticipation; may swell more than ambient world music.
- Cities/settlements: reflect everyday life, culture and architecture without collapsing into generic tavern folk.
- Danger: tension need not become combat.
- Combat: legible momentum while preserving space for important game audio.
- Narrative cues: score dramatic changes specifically; do not force them into every ambient loop.
- Environmental sounds (waves, tools, footsteps, crowds, machinery) generally belong to spatial audio and must not be baked repeatedly into all music.
- Specify zones/triggers, loop-versus-one-shot, crossfade, dialogue ducking, cooldowns and optional adaptive stems when relevant. Do not claim clean stems exist unless they actually do.

## Review loop

1. Generate against an explicit brief.
2. Listen and compare against lore fidelity, cultural identity, composition, arrangement, production, gameplay suitability and album cohesion.
3. Name specific strengths and defects (tempo, rhythm, musical language, dynamics, instrumentation, vocal delivery, etc.).
4. Change the smallest useful set of instructions; preserve what worked.
5. Generate alternatives; compare to the same brief.
6. **Approve, revise, repurpose or reject.** A great departure cue may be a poor exploration loop.
7. Record the decision and its reasoning.

**Never declare a track approved solely because its prompt looks good.** Hear the audio first.

## Status vocabulary

- **Proposed** — concept/tracklist only.
- **Drafted** — style and arrangement ready.
- **Generated** — audio exists.
- **In review** — being compared/revised.
- **Approved** — chosen recording fits its brief.
- **Implemented** — integrated into the experience.
- **Superseded** — retained but replaced.

Keep status separate from subjective enthusiasm.

## Decision and motif registries

Every significant alignment should be retained with **scope**, **decision**, **reason**, and **implications for later tracks**.

Examples:
- Avaloria exploration: avoid folk-dance energy; reserve it for settings that warrant it.
- `Beyond the Greenwood`: energetic enough to suit departure from the city rather than persistent wilderness ambience.
- Dwarven cultures: Stone-Root hill dwarves, Deeprock mountain dwarves, and Salt-Beard maritime dwarves require different palettes.
- General interactive audio: keep machine/forge/water sounds as positional world audio when practical.
- Avaloria album planning: use the VR narrative as the order of discovery.

Register any recurring musical motif with its intended meaning, source track, later appearances and variations. Preserve prior choices unless new lore or listening evidence justifies revision.

## Release/readiness review

A track is complete only when its lore basis, intended role, distinct musical voice, arrangement, real audition, album fit and version record are sound. Before implementation, verify asset format, naming, loudness/transition behavior and actual in-game suitability.

## Music documentation hierarchy

The [world index](WORLDS.md) links provisional world-level identity sheets. Each world owns cross-album culture and musical alignments; album sheets document a specific region, tracklist and musical voice; track records document prompts, auditions, versions and integration. Use the [album template](templates/ALBUM.md), [track template](templates/TRACK.md), [global decision registry](DECISIONS.md), and [motif registry](MOTIFS.md). Do not invent audio assets, approvals or motifs.

## Current programme

Start with the Avaloria story sequence. See [Avaloria — Kingshelm album plan](albums/AVALORIA_KINGSHELM.md) for the first planned nine-track city album.

**Core measure:** Every composition should make The CosmOS more alive, recognizable and emotionally meaningful.
