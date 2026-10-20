# Mod guidance

- Air Mobile I, II, and III use absolute paradrop limits of 2, 4, and 7 tiles. Keep `<in [{Friendly} {Land}] tiles>` so origin tiles must be both friendly and land.
- Martyr uses `Can generate a large amount of culture`; Unciv creates the action and consumes the unit.
- Check edits with `git diff --check`. This repository has no configured build or test command; `UnitPromotions.json` has existing trailing commas, so strict JSON parsers will reject the file.
