# Goose of Mischief

[简体中文](README.zh-CN.md)

An image-editing skill that transforms a supplied image into a **strong pastoral low-poly storybook scene** inspired by the broad visual language of *Untitled Goose Game*, while preserving the original composition and integrating exactly one mischievous goose at a physically plausible scale.

## What it does

- Requires a user-supplied reference image.
- Preserves the original aspect ratio, crop, camera, perspective, primary subjects, spatial relationships, and scene identity.
- Reconstructs the full image with simplified object-level low-poly geometry, matte flat-painted materials, restrained source-derived pastoral colors, soft ambient daylight, and clear storybook silhouettes.
- Inserts exactly one goose performing one harmless, context-aware prank.
- Automatically chooses an **obvious**, **subtle**, or **hidden** goose based on the composition.
- Uses nearby real-world objects as scale anchors so the goose fits the scene physically.
- Uses partial occlusion, distance, or edge cropping when a full-body goose cannot fit naturally.

The style should be immediately recognizable. It must not remain a lightly filtered photograph.

The visual system does not copy a commercial game's exact maps, character mesh, assets, UI, logos, screenshots, task list, or title treatment.

## Core method

The skill follows five stages:

1. **Deconstruct** — identify the decisive subjects, scale relationships, axes, depth layers, overlap, lighting, colors, and protected regions.
2. **Selective preservation** — lock composition, camera, subject placement, focal hierarchy, and scene identity.
3. **Style reconstruction** — rebuild all objects as a clean pastoral low-poly storybook world.
4. **Goose integration** — select depth, support surface, scale anchors, occlusion, visibility, and one harmless prank.
5. **Quality gate** — reject weak styling, polygon-filter artifacts, composition drift, pasted-on placement, or incorrect goose scale.

This workflow adapts the relationship-first prompt architecture used by photo-derived editorial systems, but the final rendering remains strongly pastoral, low-poly, and game-storybook-like.

## Strong style rules

Use:

- simplified low-poly object geometry
- broad clean color planes
- matte chalky hand-painted surfaces
- slightly chunky proportions
- broad vegetation masses
- faceless human figures when people are present
- soft ambient daylight
- short soft-edged contact shadows
- restrained cream, sage, moss, stone, pale-blue, weathered-brown, terracotta, brick-red, and mustard color roles

Do not use:

- a subtle photo filter
- a uniform triangular mosaic
- stained-glass, crystal, or origami fragmentation
- glossy 3D rendering
- cinematic lighting
- generic watercolor, painterly, vector-poster, or abstract-editorial styling in place of the required look

## Goose scale and visibility

Goose size is never based on a percentage of the image dimensions.

The skill must:

1. choose a foreground, middle-ground, or background depth plane
2. identify a valid support surface
3. use at least two nearby objects as real-world scale anchors
4. decide whether a full adult goose physically fits
5. use partial occlusion, distance, or edge cropping when it does not

Visibility is controlled through placement, silhouette, contrast, gesture, interaction, depth, and occlusion—never through unrealistic enlargement or toy-like shrinking.

## Install

### Codex

```bash
git clone https://github.com/Yipxiyi/Goose-of-Mischief.git \
  ~/.codex/skills/goose-of-mischief
```

### Other skill-compatible agents

Clone the repository into the agent's skills directory and ensure `SKILL.md` is discoverable.

## Usage

Attach an image, then ask:

```text
Use $goose-of-mischief to transform this image. Preserve the composition and decide how visible the goose should be.
```

```text
Use $goose-of-mischief on this pet photo. Strongly preserve the pastoral low-poly storybook look, and keep the goose at a realistic scale.
```

```text
Use $goose-of-mischief on this product image. Do not cover the label. If a full goose cannot fit, let it enter partially from the edge.
```

## Repository structure

```text
.
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── references/
│   ├── goose-of-mischief-prompt.en.md
│   └── goose-of-mischief-prompt.zh-CN.md
├── examples/
│   └── README.md
└── LICENSE
```

## License

MIT. See [LICENSE](LICENSE).
