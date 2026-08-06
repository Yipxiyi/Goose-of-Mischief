# Paired Transformation Examples

Each approved case should use its own folder:

```text
assets/examples/case-01/
├── source.jpg
├── result.png
└── meta.yaml
```

## Required metadata

```yaml
id: case-01
scene_type: indoor | outdoor | portrait | pet | product | travel | food | text-heavy
goose_visibility: obvious | subtle | hidden
source_license: original | generated | public-domain | licensed
composition_facts:
  - ""
protected_regions:
  - ""
scale_anchors:
  - ""
  - ""
support_surface: ""
goose_action: ""
learn:
  - ""
do_not_copy:
  - source subjects
  - exact composition
  - exact palette
  - exact prank
```

## Recommended set

Maintain four to six high-quality pairs covering different source conditions rather than many mediocre examples.

At minimum include:

1. an open scene where a complete goose fits naturally
2. a dense scene using partial occlusion or distance
3. a portrait or pet photo where the primary subject remains dominant
4. a product or text-heavy image with protected regions

## Acceptance

Do not add a result until it passes all style, composition, physical-scale, and goose-integration checks in `SKILL.md`.

Source and result images are visual references only. They must not become templates whose subjects, arrangement, or color palette are copied into unrelated user images.
