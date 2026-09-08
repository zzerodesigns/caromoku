# Project Instructions & Rules

## Architectural Principles & ZeroG Specification
Always adhere strictly to the engineering rules and architectural standards defined in `/zerog-principles-v0.0.3.html`:
- **Single-File Architecture**: The complete game engine, logic, styling, procedural Web Audio, and canvas rendering must reside entirely inside `/index.html`. Do not split logic across separate folders, components, or modules.
- **Zero-Heap Hot Paths**: No object, array, or closure allocations inside animation ticks, event callbacks, or AI heuristics loops. Use module-level scratchpad registers and in-place mutations.
- **Procedural Audio**: All sound effects and audio cues must be synthesized at runtime via Web Audio API oscillators and gain envelopes with zero external media files (`.mp3`, `.wav`).
- **No Ghost Files**: Do not generate extraneous configuration files (such as `metadata.json`, `.env.example`, or tsconfigs) unless explicitly requested.

## Timestamp Requirement
Whenever editing `/index.html`, you MUST update the `data-tooltip` attribute of `#footer-clock` (in the footer) to reflect the current local time in ICT (Indochina Time, UTC+7, formatted as `data-tooltip="Updated: YYYY-MM-DD HH:MM ICT"`).

<!-- Checkpoint: Wed Sep 9 00:58 ~ -->
