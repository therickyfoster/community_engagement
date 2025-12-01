README.md — Narrative Unlock Engine

Project Codename: Hearthscript Chronicle System
Primary Domain: Story Fragment Unlocks Based on Real-World Steward Actions
Theme: ❄️ Winter Mythos • Ember Lore • Mnemonic Echoes
Version: Draft v0.1
Length: ~4k words equivalent

❄️ 1. Animated Title Schema (Design Notes)

The Hearthscript Chronicle System adopts an aesthetic of embers revealing forgotten stories.
Fragments drift into view like sparks rising from a fire.

Title Animation Concept
• 0–0.8s: smoldering ember glow under letters
• 0.8–1.2s: drifting ash particles form into text outlines
• 1.2–1.5s: letters solidify as if quenched in snow
• 2.5s+: gentle ember pulse

Color & Texture Scheme
• Hearth Amber (#DFAE48)
• Snow Ash (#F3F5F8)
• Iron Gray (#474C53)
• Campfire Red (#C45B4C)
• Winter Myr (#2D3139)

Ambient Design
Subtle crackling ember audio (optional)
Slow rising sparks across the top third of the screen
Faint winter wind beneath the UI

The entire UI should feel like a fire-lit book in a cold world, where each fragment is a spark of meaning.

❄️ 2. Purpose of the Narrative Unlock System

Human behavior is shaped not merely by goals, but by stories — the myths we carry, the tales we live by, and the narratives that whisper guidance at crossroads.

The Hearthscript Chronicle System uses story fragments to:

• guide stewards gently
• reward real actions with mythic resonance
• create emotional continuity
• make kindness feel part of ancient tradition
• tie mnemonic vows to narrative arcs
• deepen identity in a zero-surveillance way

Every fragment is earned, not granted.
Every story is personal, not competitive.
Every chronicle becomes a memory-map of generosity.

❄️ 3. Mythos Layer — The Ember Archive

In the lore of Winterborn, the Ember Archive is a collection of stories written not on paper but in kind deeds, preserved in the glow of shared fires.

Each steward’s actions create ripples.
Those ripples generate ember fragments.
Those fragments become the steward’s personal chronicle.

The Ember Archive is a living system:

• It remembers warmth.
• It listens for vows.
• It glows brighter when kindness is offered.
• It reveals stories based on resonance, not randomness.

By design, no steward ever sees the exact same narrative.
The Hearthscript is procedurally mythic, shaped by:

• seasonal role
• vow
• archetype
• seed trails discovered
• actions logged
• rare events encountered

This system treats myth as a quiet companion — not a game mechanic.

❄️ 4. Architecture of Story Unlocks (Technical)

The system generates narrative content through three interacting layers:

A. Chronicle Seeds (Core Layer)

Pre-written story fragments and mythic motifs that anchor the narrative.
Types include:

• origin tales
• winter spirits
• wandering stewards
• forest guardians
• frost trials
• ember rites
• seedpath legends
• ancestral echoes

These are written by creators and expand slowly over time.

B. Narrative Weaving Engine (Adaptive Layer)

This determines which fragment unlocks based on:

• user’s last action type
• seasonal role
• vow
• symbol progression state
• previous fragments
• the moon or solstice period (optional aesthetic)
• trailhead discoveries
• archetype

It ensures narrative feels personal and sensical.

C. Memory Hearth Ledger (IndexedDB Layer)

Stores:

• fragments unlocked
• timestamp
• corresponding real action
• symbol state at the moment of unlock
• trailhead context
• narrative branch identifiers

This turns the user’s journey into a quiet, emotionally rich scrapbook.

❄️ 5. Types of Narrative Unlocks

Each unlocked fragment falls into one of several categories.

These aren’t rigid — they blend like dream layers.

1. Ember Stories

Short, warm fragments tied to acts of kindness.

Example style:

“A traveling steward once carried a lantern carved of ice.
It never melted, for its flame fed on compassion.”

Triggered by:
• helping someone
• sharing warmth
• emotional support

2. Frost Trials

Fragments tied to courage or difficult actions.

Example:

“The frost spirit watches quietly.
Those who step into the cold without fear earn its silent bow.”

Triggered by:
• speaking up
• protecting someone
• facing hardship

3. Seedpath Legends

Fragments tied to planting, repairing, or nature care.

Example:

“Along a forgotten path, a steward once buried five apple seeds.
In time, a forest rose where no one expected life.”

Triggered by:
• planting
• cleanup
• restoration

4. Heart-Warmth Tales

Fragments tied to connection.

Example:

“The hearth remembers voices long gone.
Every shared story adds another spark to the flame.”

Triggered by:
• hosting gatherings
• campfire rituals
• storytelling nights

5. Memory Echoes

Rare, personal-feeling fragments that mirror the steward’s own life.

Triggered by:
• long inactivity followed by return
• repeated actions in the same place
• high emotional significance events

These fragments deepen meaning.

6. Constellation Lore

Unlocked when multiple stewards leave markers in the same region, creating a woven path.

They describe mythical constellations formed from frostmarks.

Example:

“When stewards walk together unknowingly,
the frostmarks above them align into patterns of destiny.”

Triggered by:
• overlapping Seed Trails
• community resonance

7. Solstice Chronicles

Rare fragments unlocked only during the winter solstice week.

These bind the steward’s pathway across years.

❄️ 6. How Narrative Unlocks Work (UX Flow)

When an action is logged, the UI flickers softly.
Snow pauses.
The hearth glows.

Then, a single line appears:

“An ember stirs in your memory.”

The user taps.

A story fragment appears, revealed like frost melting from an old parchment.

After reading, the steward can:

• send it to the Memory Ledger
• listen to an audio version (optional)
• let the frost reclaim the text

Fragments are not “kept” like items.
They live in the ledger naturally.

❄️ 7. Chronicle Maps (Visual Memory System)

Every unlocked fragment becomes a node in the steward’s Chronicle Map:

• nodes are embers
• connections are soft lines
• clusters form mythic constellations

The UI acts like a living cave painting:

• clusters around warmth
• clusters around courage
• clusters around restoration
• clusters around seasonal rites

This helps the steward see the arc of who they’re becoming.

❄️ 8. Seasonal Narrative Behavior

The narrative system changes based on season.

Winter

More frost trials.
More silence and introspection.

Spring

Growth tales, rebirth motifs.

Summer

Flowing, water-based lore.
More vibrant descriptions.

Autumn

Preparation stories.
Harvest spirits and twilight motifs.

This makes the system feel alive and natural.

❄️ 9. “Returning After Absence” Logic

If a steward leaves for weeks or months, the Chronicle System responds with gentleness.

Example unlock:

“The hearth had dimmed, but it never forgot you.
When you step close again, the embers breathe.”

This is designed to avoid guilt and evoke belonging.

Stewardship is not about performance — it’s about presence.

❄️ 10. Rare Event System

Rare events feel magical and unexpected.

Triggered by:

• planting multiple seeds in a single day
• helping someone in danger
• discovering a high-density Seed Trail area
• solstice rituals
• moon-based triggers
• mnemonic vow anniversaries

These unlock:

• aurora lore
• ancestral tales
• frost spirits
• multi-part myth arcs
• guardian-level fragments

These pieces feel like ancient secrets, encouraging long-term engagement.

❄️ 11. Developer Notes (Implementation)
A. Fragment Structure

Fragments should be ~50–200 words.
Poetic, sparse, winter-themed.
Never gamified.

B. Ledger Schema
{
  id,
  fragment_text,
  timestamp,
  action_context,
  symbol_state_snapshot,
  seasonal_role,
  vow,
  trail_context
}

C. Discovery Logic

Fragments are chosen based on weighted context:

• 40% action type
• 30% personal narrative history
• 20% seasonal effects
• 10% rare event chance

D. Whisper UI

Fragments drift in and out softly.
No hard transitions.
Fire-like flicker transitions are ideal.

❄️ 12. Zero-Harm License Notes

Stories must never:

• shame
• coerce
• manipulate
• track
• compare stewards
• gamify hardship
• exploit user emotional state

Narrative operates as comfort, guidance, and companionship — never control.

This is story as sanctuary.

❄️ 13. Closing Invocation

“Stories are embers that travel through winter nights.”

The Hearthscript Chronicle System exists to remind every steward that their actions are meaningful, ancient, and woven into a lineage of warmth.

Every act of kindness lights another ember.
Every seed planted writes another line.
Every trail followed keeps ancient stories alive.

The world becomes warmer one fragment at a time.
