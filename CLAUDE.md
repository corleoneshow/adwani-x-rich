# AI Influencer Project — Claude Instructions

## FIRST THING EVERY SESSION
Run `git log --oneline --since="7 days ago" --pretty=format:"%h %an: %s (%ar)"` and give a brief 2-3 sentence summary of what the other collaborator has pushed since the last session. Address it to whoever is currently working (Richie or Jon — check `git config user.name` to find out). Keep it casual and tight — just what changed and why it matters.

## What This Is
A collaborative project between Richie (richardisho) and Jon (corleoneshow) to build and run an AI-generated influencer across Instagram, TikTok, Twitter, and OnlyFans. Image/video generation is done via ComfyUI with custom LoRAs.

## Collaborators
- **Richie** — richardisho@gmail.com
- **Jon** — corleoneshow on GitHub

## Stack
- **Image generation:** ComfyUI (workflows in `workflows/`)
- **Models:** Stable Diffusion + custom character LoRA (tracked in `character/lora-notes.md`)
- **Automation scripts:** `scripts/` folder
- **Large files (images, videos, models):** Google Drive — NOT committed to git

## Repo Structure
```
character/        # Style guide, LoRA notes, reference prompts — the character bible
prompts/          # Image prompts, caption libraries, negative prompts
workflows/        # ComfyUI JSON workflow files
scripts/          # Automation (posting, scheduling, etc.)
```

## Key Rules
- NEVER commit generated images, videos, or model files — these go to Google Drive only
- Large binary files belong in Drive, not the repo
- Workflows go in `workflows/` as JSON exports from ComfyUI
- Always pull before starting work (`git pull`)
- Use pull requests — do not push directly to `main`

## Google Drive
Shared folder: https://drive.google.com/drive/folders/1fl7aoTQ5EK_FowpB90CoPVGT3XOA1Yki

Structure:
- `Generated Images/Approved/` — ready to post
- `Generated Images/Drafts/` — work in progress
- `Models/LoRAs/` — character and style LoRAs
- `Models/Checkpoints/` — base models

## Platforms
- Instagram, TikTok, Twitter, OnlyFans

## When Working on This Project
- Check `character/style-guide.md` first — character consistency is everything
- Check `character/lora-notes.md` for current model versions and settings
- Proven prompts live in `prompts/image-prompts.md` — start there before writing new ones
- New ComfyUI workflows get exported as JSON and committed to `workflows/`
