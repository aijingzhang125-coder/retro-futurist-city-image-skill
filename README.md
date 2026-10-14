# Retro-Futurist City Image Skill

A Codex skill for generating original Victorian industrial retro-futurist city imagery while avoiding overly close copies of reference images.

It is designed for prompts like:

- "Make an image like this, but different."
- "Create a 19th-century industrial retro-futurist city scene."
- "Use this image as mood reference, but change the composition."

The skill includes:

- A reusable workflow for mood-reference image generation.
- Composition swaps to avoid copying a reference layout.
- Prompt recipes for canal districts, circular railway exchanges, foundries, transit halls, and observatory terraces.
- A quality checklist for rejecting results that are too similar, too muddy, or contain unwanted text/watermarks.

## Installation

Copy or clone this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/aijingzhang125-coder/retro-futurist-city-image-skill.git ~/.codex/skills/retro-futurist-city-image
```

Then invoke it explicitly:

```text
Use $retro-futurist-city-image to create an original Victorian industrial retro-futurist city image.
```

Codex may also discover it automatically for matching image-generation requests.

## License

MIT
