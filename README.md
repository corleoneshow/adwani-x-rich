# AI Influencer Project

Collaborative workspace for creating and managing an AI influencer across Instagram, TikTok, Twitter, and OnlyFans.

## Project Structure

```
ai-influencer-project/
├── character/           # Character definition and style
│   ├── style-guide.md   # Her look, personality, voice
│   ├── reference-prompts.md  # Proven prompts that work
│   └── lora-notes.md    # LoRA settings and versions
├── workflows/           # ComfyUI workflow files
│   ├── portrait-workflow.json
│   ├── video-workflow.json
│   └── README.md
├── prompts/             # Prompt libraries
│   ├── instagram-captions.md
│   ├── image-prompts.md
│   └── negative-prompts.md
└── scripts/             # Automation scripts
```

## Shared Resources

### Google Drive Structure
Large files (images, videos, models) are stored in shared Google Drive:

```
AI Influencer/
├── Generated Images/
│   ├── Approved/        # Final, ready to post
│   ├── Drafts/          # Work in progress
│   └── Archive/         # Old/unused
├── Generated Videos/
│   ├── Approved/
│   ├── Drafts/
│   └── Raw Clips/
├── Models/
│   ├── LoRAs/
│   └── Checkpoints/
└── Reference/           # Inspiration, style refs
```

**Drive Link:** https://drive.google.com/drive/folders/1fl7aoTQ5EK_FowpB90CoPVGT3XOA1Yki

## Quick Start

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/ai-influencer-project.git
cd ai-influencer-project

# After making changes
git add .
git commit -m "Your commit message"
git push

# Get latest changes
git pull
```

## Workflow

1. Create/update ComfyUI workflow → push JSON to `workflows/`
2. Generate images using workflow
3. Upload approved images to Drive (`Generated Images/Approved/`)
4. Update content calendar with what's ready to post

## Collaborators

- [Your Name]
- Richard

## Platforms

- Instagram
- TikTok
- Twitter
- OnlyFans
