# Goose of Mischief

[简体中文](README.zh-CN.md)

An image-editing skill that transforms a supplied image into a strong pastoral low-poly storybook scene while preserving the original composition and integrating exactly one mischievous goose at a physically plausible scale.

## What it does

- Requires a user-supplied reference image.
- Preserves the original aspect ratio, crop, camera, perspective, subjects, spatial relationships, and scene identity.
- Reconstructs the full image with simplified object-level low-poly geometry, matte flat-painted materials, restrained source-derived pastoral colors, soft ambient light, and clear silhouettes.
- Inserts exactly one goose performing a harmless, context-aware prank.
- Automatically chooses an obvious, subtle, or hidden placement.
- Uses nearby real-world objects to determine believable goose scale.
- Uses distance, partial occlusion, or edge cropping when a full-body goose cannot fit naturally.
- Avoids the common failure mode of applying a uniform triangular polygon filter over the photo.

The visual system does not copy commercial-game maps, models, assets, UI, logos, screenshots, task lists, or title treatments.

## Method

The skill follows five stages:

1. **Deconstruct** — identify subjects, scale, perspective, depth, overlap, lighting, colors, and protected regions.
2. **Selective preservation** — lock composition, camera, subject placement, focal hierarchy, and scene identity.
3. **Style reconstruction** — rebuild the scene as a clean pastoral low-poly storybook world.
4. **Goose integration** — choose depth, support surface, realistic scale, occlusion, visibility, and one harmless prank.
5. **Quality gate** — reject weak styling, composition drift, polygon-filter artifacts, pasted-on placement, or incorrect goose scale.

## Visual examples

Curated reference images may be placed directly in [`assets/examples/`](assets/examples).

Keep this simple:

- add a small set of strong final outputs
- the skill inspects only one to three relevant images
- examples guide style strength, goose proportions, and physical integration
- examples never override the user's image and must not be copied literally

No manifest or separate style-anchor directory is required.

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
Use $goose-of-mischief on this pet photo. Keep the goose at a realistic scale and make the prank subtle.
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
├── assets/
│   └── examples/
├── examples/
│   └── README.md
└── LICENSE
```

## License

MIT. See [LICENSE](LICENSE).
