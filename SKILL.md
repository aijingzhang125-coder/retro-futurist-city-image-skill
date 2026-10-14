---
name: retro-futurist-city-image
description: Generate original Victorian industrial retro-futurist city images, especially when a reference image should guide mood without copying composition.
---

# Retro Futurist City Image

Use this skill when the user wants an image, prompt, or visual direction for a 19th-century industrial, Victorian, steampunk, retro-futurist, or monumental city scene. It is especially useful when the user provides a reference image and wants "something similar" but expects a clearly original result.

## Core Direction

Preserve the genre and atmosphere, not the reference layout. Treat reference images as mood boards unless the user explicitly asks for a direct edit.

Good outputs usually combine:

- Victorian or Belle Epoque stone architecture with industrial ironwork.
- Massive transit infrastructure: elevated railways, viaducts, stations, canals, cranes, elevators, market arcades, or glass roofs.
- Human scale cues: small crowds, engineers, travelers, porters, carriages, boats, lamps, or market stalls.
- Cool fog or rain-washed atmosphere contrasted with warm amber gaslight.
- Strong depth and readable architectural hierarchy.

Avoid near-copying a reference image's camera position, central landmark, dominant bridge angle, foreground figure placement, clock-tower placement, or exact skyline rhythm. If an output resembles the reference at first glance, generate a new version with a different viewpoint and city function.

## Workflow

1. Decide whether this is a new image or an edit. Most requests for "similar" images should be new generations, not edits.
3. Choose a different scene function from the reference: canal district, orbital rail exchange, foundry plaza, market quay, archive tower, power station, underground concourse, observatory terrace, bridge-city, or transit atrium.
4. Choose a different camera strategy: aerial balcony view, canal-level view, interior station hall, rooftop panorama, side-street reveal, market arcade view, or cross-section-like layered city view.
5. Use the image generation tool when the user asks for a raster image. Ask for no text, captions, watermarks, or logos unless the user explicitly wants them.
6. After generation, inspect whether it is too close to the reference. If so, rerun with a stronger composition change before presenting it as final.

For detailed prompt patterns, composition swaps, and quality checks, read [references/prompt-recipes.md](references/prompt-recipes.md) when creating a polished output or repairing a too-similar result.

## Prompt Anchors

Use concise, concrete visual language. A strong prompt usually names:

- Era and genre: "19th-century industrial-era retro-futurist city".
- City function: "canal locks and circular railway exchange" or "foundry plaza under iron viaducts".
- Composition: "elevated balcony looking diagonally down" or "interior glass-roofed station hall".
- Lighting: "cool blue-gray fog with warm amber gaslight".
- Materials: "rivet iron, soot-darkened limestone, brass, glass, wet cobblestone".
- Constraints: "original composition; no text; no watermark; no modern vehicles; do not reuse the reference's central station, lone foreground figure, or diagonal bridge layout."

## Quality Bar

Before finishing, check:

- The image reads as the requested genre within one glance.
- It is visibly different from any provided reference in viewpoint, main landmark, foreground structure, and major movement lines.
- The scene has scale cues and layered depth.
- Lighting is dramatic but not muddy.
- There is no unwanted text, watermark, logo, modern vehicle, or malformed dominant figure.
