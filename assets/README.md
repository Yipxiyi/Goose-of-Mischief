# Visual Reference Assets

This directory contains curated visual references used to stabilize the skill's output.

A directory of images does not improve quality by itself. The images must be deliberately selected, documented, and explicitly used by the skill as visual anchors.

## Structure

```text
assets/
├── style-anchors/
│   └── README.md
└── examples/
    ├── README.md
    └── manifest.yaml
```

## Two different roles

### `style-anchors/`

Finished images that define the shared rendering language:

- object-level low-poly simplification
- matte flat-painted materials
- restrained pastoral colors
- soft ambient lighting
- faceless human treatment
- readable goose anatomy
- dry physical comedy

They define **how the result should look**, not what subjects or composition it should contain.

### `examples/`

Approved source/result pairs demonstrating:

- preservation of the uploaded composition
- strong style reconstruction
- realistic goose scale
- support surface and contact shadow
- correct occlusion and depth
- obvious, subtle, and hidden goose placement

They define **how a source image should be transformed**.

## Usage priority

1. user-supplied image and request
2. source composition, scale, and protected regions
3. `SKILL.md` and detailed prompt rules
4. curated visual assets

Assets must never override the user's source image.

## Copyright and privacy

Only include images that are original, generated for this repository, public-domain, or appropriately licensed. Do not include private photographs, recognizable personal information, commercial-game screenshots, or copied protected assets.
