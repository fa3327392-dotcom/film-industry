# Film Production Repository

This repository contains the film-production assistant Skill, established film bible, shot-prompt templates, and an inventory of the project's visual reference assets.

## Contents
- `.claude/skills/film-production-assistant/SKILL.md` — production Skill.
- `.claude/skills/film-production-assistant/references/film-bible.md` — established film canon.
- `.claude/skills/film-production-assistant/references/asset-inventory-template.md` — asset tracking template.
- `.claude/skills/film-production-assistant/templates/shot-prompt-template.md` — shot prompt template.
- `Film-References/ASSET-INVENTORY.md` — list of 18 visual reference files awaiting binary upload.

## Reference images
The 18 original reference images are listed in `Film-References/ASSET-INVENTORY.md`, but have not yet been uploaded to this repository. Add the original files under `Film-References/Film Industry DR/` while preserving their folder structure and filenames.

## Use
Open this repository in a compatible Claude Code project with the repository available. The Skill checks `Film-References/`, verifies required assets, and prepares scenes in 60-second batches. It does not itself provide video-generation access or free credits.
