---
name: goose-of-mischief
description: Transform a user-supplied image into a strongly recognizable pastoral low-poly storybook scene inspired by the broad visual language of Untitled Goose Game, while preserving the source composition and scene identity. Integrate exactly one mischievous white goose at a physically plausible real-world scale, with correct perspective, support surface, lighting, shadow, and occlusion. Goose visibility may be obvious, subtle, or hidden, but must never be achieved through unrealistic enlargement.
---

# Goose of Mischief

Transform one uploaded image into a **strongly stylized pastoral low-poly storybook scene** and integrate **exactly one mischievous goose** into the original composition.

A usable source image is required. If no image is available in the current conversation, ask the user to upload one before generating anything.

The result should clearly evoke the broad visual qualities associated with *Untitled Goose Game*: simplified low-poly forms, matte flat-painted surfaces, gentle pastoral colors, soft ambient light, faceless human figures, readable silhouettes, uncluttered staging, and dry physical comedy.

The style must be unmistakable. It must not remain a lightly filtered photograph.

Do not reproduce a commercial game's exact map, character mesh, level layout, prop arrangement, logo, title treatment, UI, task list, or screenshot.

## Core Contract

Every successful transformation must satisfy all four requirements:

1. **Preserve the source composition.** Keep its crop, camera, perspective, primary subject placement, spatial relationships, focal hierarchy, and scene meaning recognizable.
2. **Apply a strong global style reconstruction.** Rebuild the whole image using clean pastoral low-poly storybook geometry and matte flat-painted materials.
3. **Insert exactly one mischievous goose.** The goose performs one harmless, context-aware prank using the existing scene whenever possible.
4. **Maintain physical plausibility.** The goose must have believable real-world size, depth, support, lighting, contact shadow, and occlusion.

Composition is locked. Style is global. Goose insertion is local.

## Required Method

Use this internal sequence:

**DECONSTRUCT → SELECTIVE PRESERVATION → STYLE RECONSTRUCTION → GOOSE INTEGRATION → QUALITY GATE**

### 1. Deconstruct

Identify three to six decisive visual facts:

- primary and secondary subjects
- relative scale
- dominant horizontal, vertical, or diagonal axes
- foreground, middle-ground, and background layers
- overlap and occlusion relationships
- negative space and visual intervals
- light direction and shadow softness
- key source colors and accents
- protected faces, labels, screens, text, or focal objects

### 2. Selective Preservation

Preserve the relationships that make the source image recognizable:

- subject count and identity
- primary poses and gestures
- camera angle, crop, and perspective
- relative placement and depth
- recognizable color cues
- scene topology and object relationships

Simplify high-frequency photographic detail, surface noise, tiny decorations, realistic texture, and unnecessary background clutter.

### 3. Style Reconstruction

Reconstruct—not merely filter—the complete scene using the mandatory visual language below.

### 4. Goose Integration

Choose a plausible depth plane, support surface, scale anchors, placement, occlusion, and one harmless prank.

### 5. Quality Gate

Reject and regenerate once if the style is weak, the composition drifts, or the goose has incorrect scale or pasted-on appearance.

## Mandatory Visual Language

### Object-Level Low-Poly Reconstruction

Use:

- simplified low-poly or softly faceted **object geometry**
- broad, clean color planes
- softened chunky proportions
- clear silhouettes readable at thumbnail size
- matte, chalky, hand-painted surfaces
- minimal texture maps and micro-detail
- simplified architecture and props that retain their function
- vegetation as broad clustered masses rather than individual leaves
- quiet, carefully separated scene elements

The transformation must feel like a purpose-built low-poly storybook world.

### Critical Anti-Filter Rule

Do **not** create a uniform triangular mosaic over the photograph.

Avoid:

- visible triangular facets covering every surface equally
- stained-glass polygon filters
- crystalline or origami-like fragmentation
- photo-to-vector posterization without object reconstruction
- realistic photography beneath a transparent polygon texture

Low-poly style must come from simplified modeled forms, silhouettes, materials, and lighting—not from overlaying triangles on the source pixels.

### Palette

Derive key colors from the source, then harmonize them into a restrained pastoral storybook palette.

Preferred families:

- warm off-white and muted cream
- sage, moss, and soft grass green
- stone beige and pale gray-blue
- weathered wood brown
- muted terracotta and dusty orange
- brick red and mustard yellow
- soft charcoal used sparingly

Rules:

- retain important source color identity
- reduce excessive saturation and visual noise
- use a small number of broad color roles
- keep one or two source-derived accents
- avoid neon, glossy gradients, black-heavy grading, and cinematic teal-orange treatment

Do not replace every setting with a generic British village.

### Lighting

Use:

- broad ambient daylight
- soft overcast, morning, or calm afternoon illumination
- low-to-medium contrast
- short, soft-edged contact shadows
- gentle atmospheric softness
- little or no specular shine

Avoid dramatic rim lights, hard spotlights, volumetric beams, strong bloom, glossy ray-traced realism, and cinematic depth of field.

### Camera

Preserve the source camera, crop, and perspective by default.

Do not force every image into an elevated isometric or three-quarter diorama view. The rendering language changes strongly while the original composition remains recognizable.

### People

When people already exist:

- preserve number, placement, pose, clothing silhouette, and important accessories
- simplify them into anonymous faceless storybook figures
- use blank face planes, tiny minimal marks, or no visible features
- communicate emotion through posture, hands, head angle, and spacing
- do not add new villagers merely to react to the goose

### Other Animals

When pets or other animals already exist:

- preserve species, count, markings, pose, and primary-subject status
- simplify fur, feathers, and patterns into broad matte regions
- never replace another animal with the goose
- avoid aggression or distress

## Mandatory Goose Design

Insert exactly one goose unless the user explicitly requests more.

Default goose:

- white body made from clean simplified volumes
- long curved neck
- flat orange beak
- orange webbed feet
- one tiny dark eye when visible
- matte material consistent with the scene
- readable silhouette
- anatomically plausible domestic-goose proportions

Avoid realistic feather detail, mascot proportions, toy scale, giant monster scale, costumes, human expressions, eyelashes, hands, teeth, or anthropomorphic anatomy.

## Physical Scale Engine — Hard Constraint

Do not size the goose using a percentage of the image dimensions. Image-space size is not physical scale.

Before placing the goose, determine internally:

```yaml
goose_depth_plane: foreground | middle-ground | background
goose_support_surface: floor | ground | tabletop | path | shelf | water | other
goose_scale_anchor_1: ""
goose_scale_anchor_2: ""
goose_full_body_fits: yes/no
goose_occlusion_plan: ""
```

### Scale Anchoring

Estimate goose size using at least two nearby objects with understandable real-world scale, such as:

- a cat or dog
- chair seat or chair leg
- table height and tabletop depth
- cup, glass, bottle, plate, or container
- door, cabinet, appliance, or shelf
- floor tile, paving stone, stair, curb, or path width
- human legs, shoes, hands, or bags

Treat the goose as a real medium-sized domestic bird—not a miniature toy and not a mascot.

### Support-Surface Rule

A fully visible goose may appear only when the selected surface has enough plausible physical footprint for its body and feet.

If a full-body goose cannot fit naturally:

- place it farther back on another valid depth plane
- show it partly hidden behind an existing object
- let only its head and neck enter from behind or beyond an edge
- crop part of its body naturally at the image boundary
- use a doorway, floor gap, path, chair gap, or background opening

Never shrink the goose into a toy merely to fit an impossible space. Never enlarge it merely to make the joke more visible.

### Visibility Without Scale Cheating

Choose **obvious**, **subtle**, or **hidden** based on composition.

Control visibility through:

- placement near or away from the focal path
- silhouette contrast
- neck direction and gesture
- interaction with an existing object
- partial occlusion
- foreground, middle-ground, or background depth
- negative-space use

Do not control visibility through unrealistic size.

### Perspective and Contact

The goose must match:

- source perspective and vanishing direction
- selected depth plane
- support-surface angle
- camera height
- light direction and color temperature
- local shadow softness
- depth-of-field treatment
- overlap and occlusion order

Feet must contact the support surface when visible. Add a soft contact shadow appropriate to the scene.

The goose must look as though it was always present in the reconstructed world—not pasted on afterward.

## Goose Placement Engine

### Protect the Main Subject

Do not cover:

- a person's face or essential gesture
- the primary pet or animal
- the main product or artwork
- important text, label, sign, screen, or UI
- a landmark or key object
- the central relationship that defines the image

### Natural Entry Points

Prefer:

1. open floor or ground with reliable scale anchors
2. a path, doorway, cabinet gap, chair gap, shelf opening, or landscape edge
3. partial occlusion behind furniture, bags, plants, boxes, fences, or architecture
4. a plausible background location
5. a cropped edge-of-frame entry when space is limited
6. a tabletop only when the physical surface genuinely fits a real goose

### Pet Coexistence

When a pet is present:

- preserve it as the primary animal
- compare goose scale directly with the pet and nearby furniture
- use the goose as a secondary intruder
- do not make the goose arbitrarily larger than the pet for emphasis
- avoid threatening poses or distress

## Mischief Selection Engine

Use an existing secondary object whenever possible.

Examples:

- tugging a loose cable, strap, ribbon, scarf, shoelace, hose, or cloth edge
- carrying away a sock, glove, key, spoon, brush, toy, paper, flower, snack, or small tool
- nudging a cup, basket, ball, shoe, cushion, sign, or small container
- rearranging a tidy row or display
- peeking from behind an object while reaching for something nearby
- blocking a path or doorway
- lightly photobombing from a plausible depth layer

Keep the prank harmless, simple, scene-aware, physically readable, local, and understandable without captions.

Do not invent a new prop when an existing object can support the joke.

## Visual Reference Assets

The repository may contain curated visual references under `assets/`.

### Roles

- `assets/style-anchors/` defines the shared rendering grammar: object-level simplification, matte materials, palette restraint, lighting, faceless people, goose anatomy, and dry comedy.
- `assets/examples/` contains approved source/result pairs demonstrating composition preservation, physical scale, support, depth, occlusion, and prank integration.

### Runtime Selection

Before compiling the prompt:

1. inspect `assets/examples/manifest.yaml`
2. select at most one paired example with the closest scene type or compositional problem
3. select at most two or three complementary style anchors
4. read the selected case metadata before using its images

Do not load every image. Too many references can average away the intended style or import unrelated content.

### Reference Priority

Use this priority order:

1. user-supplied image and request
2. source composition, scale, and protected regions
3. this skill and the detailed reference prompts
4. curated visual assets

Assets never override the source image.

### Learn, Do Not Copy

Use references only to learn:

- style strength
- geometry simplification
- matte material treatment
- lighting softness
- goose proportions
- scale reasoning
- occlusion and contact
- visibility strategies

Never copy a reference image's subjects, exact composition, location, palette, prop arrangement, protected commercial asset, or exact prank.

### Runtime Limitation

If the active image tool cannot receive repository images as visual references, use their metadata and documented lessons only. Do not claim that an image reference was used when it was not actually supplied to the model.

### Curation Standard

Only use approved images that pass the Quality Gate. Low-quality examples should be removed rather than retained for quantity.

Use only original, purpose-generated, public-domain, or properly licensed assets. Do not include private photographs, personal information, commercial-game screenshots, or copied protected assets.

## Scene-Specific Guidance

### Portraits

- preserve crop, pose, clothes, and face region
- keep the goose secondary
- use floor space, furniture gaps, bags, or lower-edge occlusion
- never place a tiny toy goose on a shoulder unless explicitly requested

### Pets

- preserve the pet's exact pose, markings, and subject priority
- anchor goose scale against the pet and furniture
- use a nearby toy, blanket edge, cable, bowl-side object, or bag strap

### Products and Still Life

- preserve product shape, label, arrangement, and lighting hierarchy
- do not block the product
- use floor or background space or a physically plausible edge location
- do not shrink a full goose onto a small tabletop

### Food

- preserve dish and plating
- use a distant, partially hidden, or edge-entering goose when tabletop space is insufficient
- keep food clean and appetizing

### Landscapes and Architecture

- preserve skyline, paths, terrain, and buildings
- use realistic distance scaling
- a background goose may be small because it is distant, not because it is toy-sized

### Text-Heavy Images, Screens, and UI

- treat important text and interface regions as protected
- preserve layout and legibility as much as possible
- place the goose in margins or nonessential regions
- do not rewrite or parody text unless requested

## Prompt Compiler

Compile the editing prompt in five compact sections.

### 1. Source Deconstruction

State three to six decisive spatial facts: subjects, scale relations, axes, depth, overlap, focal hierarchy, lighting, key colors, and protected regions.

### 2. Composition Lock

Include language equivalent to:

> Preserve the original aspect ratio, crop, camera angle, perspective, primary subject placement, depth relationships, and scene identity. Do not move, remove, replace, or duplicate existing primary subjects.

### 3. Strong Style Reconstruction

Include language equivalent to:

> Reconstruct the entire image as a strongly recognizable pastoral low-poly storybook world inspired by the broad visual language of Untitled Goose Game: clean simplified object geometry, matte flat-painted surfaces, soft ambient daylight, restrained source-derived pastoral colors, broad low-detail forms, clear silhouettes, and dry visual comedy. This must be a full object-level reconstruction, not a subtle filter and not a triangular polygon mosaic.

### 4. Goose Integration Plan

Specify:

- exactly one goose
- obvious, subtle, or hidden visibility
- selected depth plane and support surface
- two scale anchors
- whether full body fits
- exact placement and occlusion plan
- one existing object used for the harmless prank
- perspective, lighting, shadow, and surface integration

Include language equivalent to:

> Keep the goose at a physically plausible adult domestic-goose scale relative to the named nearby objects. Never enlarge it for emphasis or shrink it to toy size. If a full body cannot fit naturally, use distance, partial occlusion, or a cropped edge entry instead.

### 5. Negative Constraints

State:

- no extra geese
- no new reaction characters
- no scene redesign or altered camera
- no covered faces, labels, UI, or focal subjects
- no photorealism or realistic feather texture
- no glossy 3D or cinematic lighting
- no triangular mosaic filter
- no anime, chibi, or thick outlines
- no copied game maps, assets, logos, UI, or title treatment

## Internal Planning Schema

Before generating, determine internally:

```yaml
source_scene: photo | illustration | screenshot | poster | other
decisive_visual_facts: []
primary_subjects: []
secondary_subjects: []
protected_regions: []
camera_and_perspective: ""
depth_layers: []
light_direction: ""
source_color_roles: []
negative_space_candidates: []
usable_mischief_props: []
selected_style_anchors: []
selected_paired_example: ""
goose_visibility: obvious | subtle | hidden
goose_depth_plane: foreground | middle-ground | background
goose_support_surface: ""
goose_scale_anchor_1: ""
goose_scale_anchor_2: ""
goose_full_body_fits: yes/no
goose_placement: ""
goose_occlusion_plan: ""
goose_action: ""
local_changes_only: true
```

Do not expose this schema unless the user asks for the analysis.

## Workflow

1. Confirm a usable source image is present.
2. Deconstruct the source into decisive visual facts.
3. Lock composition, subjects, scale relationships, and protected regions.
4. Inspect the visual asset manifest and select only relevant approved references.
5. Plan a strong global pastoral low-poly storybook reconstruction.
6. Select goose visibility based on composition—not desired image-space size.
7. Select depth plane, support surface, and at least two scale anchors.
8. Decide whether a full-body goose physically fits.
9. Choose one harmless prank using an existing object whenever possible.
10. Compile the five-section editing prompt.
11. Edit the supplied image using the built-in image-editing capability.
12. Inspect the result against the Quality Gate.
13. Regenerate once with stronger constraints when needed.
14. Return the edited image. Do not provide a long explanation unless requested.

## Hard Avoids

Always avoid:

- generating without a source image
- weak style transfer that remains mostly photographic
- generic painterly, editorial, watercolor, or vector-poster styling replacing the required look
- uniform triangular faceting over the whole photo
- changing crop, camera, or major composition
- moving, deleting, duplicating, or redesigning primary subjects
- more than one goose without explicit request
- giant mascot goose or miniature toy goose
- a full-body goose on a surface too small to support it
- floating feet or missing contact shadow
- inconsistent perspective, lighting, or occlusion
- pasted-on appearance
- covering faces, labels, text, UI, or focal objects
- harmful, dangerous, destructive, or cruel pranks
- copying subjects or composition from asset examples
- exact reproduction of protected game maps, models, UI, screenshots, or branding

## Quality Gate

### Composition

- Is the source immediately recognizable?
- Are crop, camera, perspective, focal hierarchy, and spatial relationships preserved?
- Are primary subject count, placement, pose, and identity cues intact?

### Style Strength

- Does the image unmistakably read as a pastoral low-poly storybook world?
- Are objects rebuilt as clean simplified forms rather than merely filtered?
- Are materials matte and flat-painted?
- Are colors restrained and source-derived?
- Is lighting soft and non-cinematic?
- Are detailed faces and photographic micro-texture removed?
- Is the result free of uniform triangular mosaic artifacts?

### Goose Scale and Integration

- Is there exactly one goose?
- Were at least two scale anchors used?
- Is its adult physical size plausible for the selected depth plane?
- Does the support surface have enough footprint?
- If not, was partial occlusion, distance, or edge cropping used instead?
- Does it match perspective, light, shadow, depth, and occlusion?
- Is visibility achieved without unrealistic enlargement or shrinking?
- Does it look native to the scene rather than pasted in?

### Mischief

- Is one harmless prank readable?
- Does it use an existing object when possible?
- Does it add dry humor without replacing the source narrative?

### Reference Discipline

- Were only relevant approved references selected?
- Did the source image remain the dominant content authority?
- Did the output avoid copying a reference's subject, composition, palette, or prank?

### Mandatory Regeneration Conditions

Regenerate once if:

- the result still looks substantially photographic
- the result becomes a triangular polygon-filter image
- the pastoral low-poly storybook style is weak or generic
- the composition or camera changes
- the goose is too large, too small, floating, or unsupported
- the goose feels pasted in
- the prank is unrelated or unreadable
- a protected subject or label is obscured
- an example image's content has leaked into the result

## Reference Prompts

Read the detailed prompt guidance before producing the image:

- Chinese: [references/goose-of-mischief-prompt.zh-CN.md](references/goose-of-mischief-prompt.zh-CN.md)
- English: [references/goose-of-mischief-prompt.en.md](references/goose-of-mischief-prompt.en.md)

## Output Behavior

Default response:

1. return the edited image
2. optionally include one concise line naming goose visibility, scale anchors, and prank

Do not provide the full prompt or internal analysis unless the user asks.

## Example Requests

- `用 $goose-of-mischief 改造这张图片，保留原本构图，并自动判断鹅应该有多明显。`
- `用 $goose-of-mischief 处理这张宠物照片，强烈保留低多边形田园绘本风格，鹅的尺寸必须符合真实比例。`
- `把这张旅行照转换成 Untitled Goose Game 气质的低多边形绘本场景，并让鹅在远处进行一个小恶作剧。`
- `处理这张产品图，不要挡住标签。如果没有足够空间放完整的鹅，就只让鹅从画面边缘探头。`
