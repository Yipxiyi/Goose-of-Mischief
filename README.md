# Goose of Mischief

[简体中文](README.zh-CN.md)

An image-editing skill that transforms a supplied image into an original pastoral low-poly storybook rendering while preserving its composition—and quietly inserts one white goose committing a context-aware act of harmless mischief.

## What it does

- Requires a user-supplied reference image.
- Preserves the original crop, camera, primary subjects, spatial relationships, and location identity.
- Restyles the full image with simplified softly faceted geometry, matte painted surfaces, restrained colors, and soft ambient light.
- Inserts exactly one goose into a compositionally appropriate foreground, middle-ground, background, or partially hidden position.
- Automatically chooses a **prominent**, **subtle**, or **hidden** goose based on the available space and scene hierarchy.
- Builds the prank around existing objects whenever possible, rather than redesigning the scene.

The visual system is original. It does not copy a commercial game's exact maps, character assets, UI, logos, screenshots, or title treatment.

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
Use $goose-of-mischief on this portrait. Keep the goose subtle and do not cover the face.
```

```text
Transform this travel photo with $goose-of-mischief. Make the prank immediately noticeable.
```

## Core behavior

The skill follows four stages:

1. **Preservation lock** — identifies primary subjects, camera, crop, protected regions, and scene identity.
2. **Style translation** — converts geometry, materials, colors, vegetation, and lighting into the pastoral storybook language.
3. **Goose insertion** — selects scale, depth, visibility, placement, and a harmless prank suited to the existing scene.
4. **Quality gate** — checks that the source remains recognizable and the goose matches perspective, light, shadow, and occlusion.

## Visibility modes

| Mode | Typical use | Approximate size |
| --- | --- | --- |
| Prominent | Wide scenes with generous negative space | 8–18% of the shorter image dimension |
| Subtle | Portraits, products, pets, interiors, food | 3–8% |
| Hidden | Dense, panoramic, architectural, or delicate scenes | 1–4% |

The user can override the automatic choice.

## Repository structure

```text
.
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── examples/
│   └── README.md
└── LICENSE
```

## License

MIT. See [LICENSE](LICENSE).
