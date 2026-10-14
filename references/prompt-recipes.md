# Prompt Recipes

Use these recipes only when the task needs a polished generated image, prompt pack, or repair pass. Mix and adapt; do not paste all details into every prompt.

## Base Prompt

```text
Use case: stylized-concept
Asset type: cinematic AI concept art, 16:9 wide image
Primary request: Create an original 19th-century industrial-era retro-futurist city scene with Victorian architecture, monumental infrastructure, warm gaslight, steam, and strong urban scale.
Reference handling: If a reference image is provided, use it for mood and genre only. Do not copy its camera angle, central building, bridge arrangement, foreground figure, clock placement, skyline silhouette, watermark, or text.
Scene/backdrop: <choose one distinct city function>
Subject: <small human scale cues and period transport>
Style/medium: highly detailed cinematic digital painting, realistic architectural concept art, refined steampunk atmosphere, not cartoonish.
Composition/framing: <choose one viewpoint and movement pattern unlike the reference>
Lighting/mood: cool fog or rain-washed air, warm amber windows and gas lamps, volumetric steam.
Materials/textures: riveted iron, soot-darkened stone, glass panes, brass, wet cobblestone, canvas awnings, canal water or polished platforms.
Constraints: original composition; no text, captions, watermark, logos, modern vehicles, neon, lasers, dominant airships, duplicated clock faces, or deformed prominent people.
```

## Scene Functions

Pick one function that differs from the reference image:

- Canal lock district: layered waterways, wet quays, cranes, boats, aqueduct bridges.
- Circular railway exchange: glass-domed hub, spiral tracks, balcony viewpoint.
- Foundry plaza: furnaces, overhead ore conveyors, soot, workers, brass valves.
- Underground concourse: vaulted iron ceiling, platforms, steam vents, light shafts.
- Observatory terrace: telescopes, clockwork instruments, city below, dawn fog.
- Market arcade: glass canopy, shops, trams, packed crowd, side-street reveal.
- Power station district: turbine halls, chimneys, cable gantries, glowing windows.
- Archive or ministry tower: monumental civic buildings, pneumatic tubes, elevated walkways.

## Composition Swaps

When a previous result is too close to a reference, change at least three of these:

- Viewpoint: street-level to balcony, rooftop, canal-level, interior hall, or aerial oblique.
- Main shape: central facade to circle, diagonal, vertical shaft, courtyard, crescent, or layered terraces.
- Motion lines: diagonal bridge to spiral rail, canal curve, vertical elevators, radial concourse, or parallel market aisles.
- Foreground: lone back-facing figure to group on balcony, boat crew, market stalls, platform crowd, or interior silhouettes.
- Landmark: clock tower to glass dome, foundry stack, canal lock, power hall, observatory, or archive tower.
- Time/weather: dusk to rainy morning, winter fog, golden dawn, interior lamplight, or storm-cleared evening.

## Ready-To-Use Variants

### Canal Balcony

```text
Scene/backdrop: A vast rain-washed canal district inside a vertical iron-and-glass metropolis. Terraced buildings surround canal locks, cargo cranes, arched aqueducts, market quays, and suspended pedestrian galleries.
Subject: Victorian engineers and travelers on a high balcony look down toward boats, carriages, and crowds below.
Composition/framing: elevated balcony viewpoint looking diagonally downward; circular glass railway exchange slightly off-center; spiral rail lines and curved waterways create the main movement.
```

### Foundry Crossing

```text
Scene/backdrop: A monumental foundry plaza under stacked iron viaducts, with glowing furnace halls, ore carts, brass pressure valves, overhead conveyors, and soot-stained neo-gothic civic buildings.
Subject: Workers, inspectors, and travelers cross wet stone platforms while a locomotive passes through steam on an upper rail.
Composition/framing: side-street reveal through a tall archway; the furnace glow is the visual anchor, not a central station facade.
```

### Interior Transit Hall

```text
Scene/backdrop: An immense glass-roofed Victorian transit atrium with layered platforms, suspended bridges, ticket galleries, clockwork signal boards, and steam rising through shafts of light.
Subject: A dense but readable crowd of porters, passengers, engineers, and horse-drawn luggage carts.
Composition/framing: interior wide shot from an upper gallery, looking across multiple levels rather than down a street canyon.
```

### Observatory City

```text
Scene/backdrop: A high observatory terrace above a retro-futurist industrial city, with brass telescopes, weather instruments, cable towers, rail loops, domes, and distant smoking power halls.
Subject: A small scientific crew studies maps and instruments while the city glows below.
Composition/framing: rooftop panorama with foreground instruments framing the view; the city is broad and layered rather than centered on one building.
```

## Repair Prompts

Use a repair prompt when the generated image is too close to a reference:

```text
Regenerate as a clearly different composition. Keep only the Victorian industrial retro-futurist mood, warm gaslight, steam, and monumental scale. Change the viewpoint, main landmark, foreground arrangement, and movement lines. Do not include a central cathedral-like station, a lone back-facing foreground figure, a dominant diagonal train bridge, or a large clock tower on the left. Use a <new viewpoint> and a <new city function> instead.
```

## Quality Review

Reject or rerun if:

- The first-glance silhouette matches the reference.
- The central building, major bridge, foreground figure, or dominant clock placement feels copied.
- The scene is visually busy but lacks a readable focal structure.
- Warm lights overwhelm the cool atmosphere or the image becomes uniformly orange.
- Text, captions, watermarks, fake signatures, modern vehicles, or neon appear.
- Important figures in the foreground have distorted faces, hands, or impossible clothing.

Accept when:

- The genre is immediately recognizable.
- The composition has a distinct viewpoint and city function.
- Scale is clear through people, vehicles, or architectural layering.
- The lighting has cool/warm contrast and plausible depth.
- The image feels inspired by the same genre, not derived from the same picture.
