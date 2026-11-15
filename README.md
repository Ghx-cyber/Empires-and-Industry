# Empires & Industry — v0.1.0

An extension mod for Unciv's **Civ V - Gods & Kings** ruleset.

## Design goals
- Deepen city economies and industrial specialization.
- Keep the original ruleset and overall Unciv feel intact.
- Add content instead of replacing existing units, technologies, civilizations, or buildings.
- Avoid hard dependencies on other mods.

## Included in v0.1.0
- **E&I Trade Depot** — unlocked with Currency; +2 Gold, +1 Production; 1 Gold maintenance.
- **E&I Industrial Works** — unlocked with Industrialization and requires a Workshop; +3 Production and +10% Production; 3 Gold maintenance.
- **E&I Logistics Hub** — unlocked with Railroads; +2 Gold and +2 Production; 3 Gold maintenance.

These are first-pass balance values and need in-game testing.

## Compatibility
This is intended as an **extension mod**, not a base-ruleset replacement. It adds only three uniquely named buildings and does not edit existing ruleset objects.

Compatibility with other extension mods is best-effort, not guaranteed. Mods can still conflict if they define the same object names, alter required technologies/buildings, or change the base ruleset. The target base ruleset is **Civ V - Gods & Kings**.

## Installation
Place the `Empires-and-Industry` folder in Unciv's `mods` directory, then enable it alongside **Civ V - Gods & Kings** when starting a new game.

On Android, the usual user-accessible location is:
`Android/data/com.unciv.app/files/mods`

## Testing status
This is a starter package. It has been checked for valid JSON syntax, but it has **not** been run through Unciv's in-game Ruleset Validator or tested in a live game yet.
