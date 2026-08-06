---
name: goose-of-mischief
description: Transform a user-supplied image into a strongly recognizable pastoral low-poly storybook scene while preserving its composition and scene identity. Integrate exactly one mischievous white goose at a physically plausible real-world scale, with correct perspective, support, lighting, shadow, and occlusion.
---

# Goose of Mischief

Transform one uploaded image into a **strong pastoral low-poly storybook scene** and integrate **exactly one mischievous goose** into the original composition.

A usable source image is required. If none is available in the current conversation, ask the user to upload one.

The result should strongly express:

- simplified low-poly object forms
- matte flat-painted surfaces
- gentle pastoral colors
- soft ambient daylight
- clear readable silhouettes
- faceless human figures when people are present
- uncluttered staging
- dry physical comedy

The result must not remain a lightly filtered photograph. However, do not copy any commercial game's exact maps, character meshes, assets, UI, logo, task list, title treatment, or screenshots.

## Core Contract

Every transformation must satisfy four requirements:

1. **Preserve the source composition.** Keep the original aspect ratio, crop, camera, perspective, subject placement, depth relationships, focal hierarchy, and scene identity recognizable.
2. **Reconstruct the whole image in the target style.** Use object-level simplification rather than a surface filter.
3. **Insert exactly one mischievous goose.** The goose performs one harmless, scene-aware prank.
4. **Maintain physical plausibility.** The goose must have believable size, support, perspective, lighting, contact shadow, and occlusion.

Composition is locked. Style transformation is global. Goose insertion is local.

## Method

Use this internal sequence:

**DECONSTRUCT → SELECTIVE PRESERVATION → STYLE RECONSTRUCTION → GOOSE INTEGRATION → QUALITY GATE**

### 1. Deconstruct

Identify the source image's decisive facts:

- primary and secondary subjects
- relative scale
- camera angle and perspective
- foreground, middle-ground, and background
- overlap and occlusion
- negative space
- light direction and shadow softness
- key colors
- protected faces, labels, screens, text, and focal objects

### 2. Selective Preservation

Preserve:

- subject count and identity
- poses and gestures
- crop, camera, and perspective
- relative position and depth
- recognizable color cues
- scene topology and object relationships

Simplify photographic texture, tiny decoration, surface noise, and unnecessary detail.

### 3. Style Reconstruction

Rebuild the scene using the mandatory visual language below. Do not merely overlay a stylizing filter.

### 4. Goose Integration

Choose a valid depth plane, support surface, realistic scale, placement, occlusion, and one harmless prank.

### 5. Quality Gate

Regenerate once if the style is weak, the composition drifts, or the goose looks incorrectly scaled or pasted on.

## Visual Reference Images

Use images in [`assets/examples/`](assets/examples) as visual references when available.

- Inspect only the most relevant one to three examples.
- Learn the shared rendering language, goose proportions, physical integration, and level of simplification.
- Do not copy an example's subject matter, exact composition, palette, location, props, or prank.
- The user's uploaded image and instructions always take priority.
- If the active image tool cannot receive repository images as visual references, follow the written rules instead and do not claim the images were used.

## Mandatory Visual Language

### Object-Level Low-Poly Reconstruction

Use:

- simplified low-poly or softly faceted object geometry
- broad clean color planes
- slightly chunky, softened proportions
- clear silhouettes readable at thumbnail size
- matte, chalky, hand-painted surfaces
- minimal micro-detail and texture maps
- simplified architecture and props that retain their function
- vegetation represented as broad clustered masses
- quiet separation between scene elements

The image should feel like a purpose-built low-poly storybook world.

### Anti-Filter Rule

Do not create a uniform triangular mosaic over the photograph.

Avoid:

- identical triangular facets across every surface
- stained-glass or crystalline fragmentation
- origami-like polygon shards
- photo posterization without object reconstruction
- realistic photography visible beneath a polygon overlay

Low-poly style must come from simplified forms, silhouettes, materials, and lighting—not from covering the original pixels with triangles.

### Palette

Derive important colors from the source, then harmonize them into a restrained pastoral palette.

Preferred color roles include:

- warm off-white and muted cream
- sage, moss, and soft grass green
- stone beige and pale gray-blue
- weathered wood brown
- muted terracotta and dusty orange
- brick red and mustard yellow
- soft charcoal used sparingly

Retain important source colors. Reduce excessive saturation and visual noise. Use a small number of broad color roles and one or two source-derived accents.

Do not replace every setting with a generic countryside village.

### Lighting

Use broad ambient light, low-to-medium contrast, little specular shine, and short soft-edged contact shadows.

Avoid dramatic rim lights, hard spotlights, volumetric beams, strong bloom, glossy ray-traced materials, and cinematic depth of field.

### Camera

Preserve the source camera and perspective. Do not force every image into an isometric or elevated diorama view.

### People

When people are present:

- preserve their number, placement, pose, clothing silhouette, and important accessories
- simplify them into anonymous faceless storybook figures
- communicate emotion through posture, hands, head angle, and spacing
- do not add new villagers merely to react to the goose

### Other Animals

When pets or other animals are present:

- preserve species, count, markings, pose, and subject priority
- simplify fur, feathers, and patterns into broad matte regions
- never replace another animal with the goose
- avoid aggression or distress

## Goose Design

Insert exactly one goose unless the user explicitly requests otherwise.

The goose should have:

- a white body built from clean simplified volumes
- a long curved neck
- a flat orange beak
- orange webbed feet
- one tiny dark eye when visible
- matte materials consistent with the scene
- a readable silhouette
- plausible domestic-goose anatomy

Avoid realistic feather detail, mascot proportions, miniature toy scale, giant scale, costumes, eyelashes, hands, teeth, or human expressions.

## Physical Scale and Integration

Do not size the goose using a percentage of the image dimensions. Image-space size is not physical scale.

Before placing it, determine internally:

```yaml
goose_depth_plane: foreground | middle-ground | background
goose_support_surface: floor | ground | path | water | tabletop | other
goose_scale_anchor_1: ""
goose_scale_anchor_2: ""
goose_full_body_fits: yes/no
goose_occlusion_plan: ""
```

### Scale Anchoring

Estimate goose size using at least two nearby objects with understandable real-world scale, such as:

- a person or pet
- chair or table dimensions
- cup, glass, bottle, or plate
- door, cabinet, appliance, or shelf
- floor tile, paving stone, stair, curb, or path width
- shoes, hands, or bags

Treat it as a real medium-sized domestic bird—not a toy and not a mascot.

### Support-Surface Rule

A fully visible goose may appear only when the selected surface plausibly fits its body and feet.

When a full goose cannot fit naturally:

- place it farther back on another depth plane
- hide part of it behind an existing object
- show only its head and neck entering from behind an edge
- crop part of its body naturally at the frame edge
- use a doorway, floor gap, path, furniture gap, or background opening

Never shrink it to fit an impossible surface. Never enlarge it merely to make the joke more obvious.

### Visibility

Choose **obvious**, **subtle**, or **hidden** based on the source composition.

Control visibility through:

- placement
- silhouette contrast
- neck direction and gesture
- interaction with an object
- depth
- partial occlusion
- use of negative space

Do not control visibility through unrealistic scale.

### Perspective and Contact

Match the source image's:

- perspective and vanishing direction
- depth plane
- support-surface angle
- camera height
- light direction and color temperature
- shadow softness
- depth-of-field treatment
- overlap and occlusion order

Visible feet must contact the support surface. Add an appropriate soft contact shadow.

The goose should look native to the reconstructed scene, not pasted on afterward.

## Placement Rules

Protect:

- faces and essential gestures
- the primary pet or animal
- the main product or artwork
- important labels, text, screens, signs, and UI
- key landmarks and focal objects

Prefer placement on:

1. open floor or ground
2. paths, doorways, furniture gaps, or landscape edges
3. partially hidden positions behind existing objects
4. plausible background locations
5. a cropped frame edge when space is limited
6. a tabletop only when it genuinely fits a real goose

## Mischief Rules

Prefer using an existing secondary object.

Suitable actions include:

- tugging a cable, strap, ribbon, shoelace, hose, or cloth edge
- carrying away a sock, glove, key, spoon, toy, paper, flower, snack, or small tool
- nudging a cup, basket, ball, shoe, cushion, sign, or small container
- rearranging a tidy row or display
- peeking from behind an object while reaching for something
- blocking a path or doorway
- quietly photobombing from a plausible depth layer

The prank must be harmless, simple, local, physically readable, and understandable without captions.

Do not invent a new prop when an existing object can support the joke.

## Prompt Compiler

Compile the image-editing prompt in five compact sections.

### 1. Source Facts

State the decisive subjects, scale relations, depth, overlap, lighting, colors, and protected areas.

### 2. Composition Lock

Include language equivalent to:

> Preserve the original aspect ratio, crop, camera angle, perspective, primary subject placement, depth relationships, and scene identity. Do not move, remove, replace, or duplicate existing primary subjects.

### 3. Style Reconstruction

Include language equivalent to:

> Reconstruct the complete image as a strong pastoral low-poly storybook world using clean simplified object geometry, matte flat-painted surfaces, soft ambient light, restrained source-derived colors, broad low-detail forms, clear silhouettes, and dry visual comedy. This must be an object-level reconstruction, not a subtle filter or triangular polygon mosaic.

### 4. Goose Integration

Specify:

- exactly one goose
- visibility level
- depth plane and support surface
- two scale anchors
- whether the full body fits
- placement and occlusion
- the existing object used for the prank
- perspective, lighting, shadow, and material integration

Include language equivalent to:

> Keep the goose at a physically plausible adult domestic-goose scale relative to the named nearby objects. Never enlarge it for emphasis or shrink it to toy size. If a full body cannot fit naturally, use distance, partial occlusion, or a cropped edge entry.

### 5. Negative Constraints

Include:

- no extra geese
- no new reaction characters
- no scene redesign or altered camera
- no covered faces, labels, UI, or focal subjects
- no photorealistic texture or realistic feathers
- no glossy 3D or cinematic lighting
- no triangular mosaic filter
- no anime, chibi, or thick outlines
- no copied commercial maps, models, assets, logos, UI, or title treatments

## Workflow

1. Confirm a usable source image is present.
2. Inspect one to three relevant images in `assets/examples/` when available.
3. Deconstruct the source into decisive visual facts.
4. Lock composition, subjects, scale relationships, and protected regions.
5. Plan the global style reconstruction.
6. Choose goose visibility based on composition.
7. Choose a depth plane, support surface, and two scale anchors.
8. Decide whether a full-body goose physically fits.
9. Choose one harmless prank using an existing object when possible.
10. Compile the editing prompt.
11. Edit the supplied image.
12. Inspect the result against the Quality Gate.
13. Regenerate once when a mandatory failure occurs.
14. Return the edited image without a long explanation unless requested.

## Quality Gate

### Composition

- Is the source immediately recognizable?
- Are crop, camera, perspective, focal hierarchy, and spatial relationships preserved?
- Are subject count, placement, pose, and identity cues intact?

### Style

- Does the image unmistakably read as a pastoral low-poly storybook world?
- Are objects rebuilt as simplified forms rather than merely filtered?
- Are materials matte and flat-painted?
- Are colors restrained and source-derived?
- Is lighting soft and non-cinematic?
- Is the result free of uniform triangular mosaic artifacts?

### Goose

- Is there exactly one goose?
- Were at least two scale anchors used?
- Is its physical size plausible at the selected depth?
- Does the support surface fit it?
- Does it match perspective, light, shadow, depth, and occlusion?
- Is visibility achieved without unrealistic enlargement or shrinking?
- Does it look embedded rather than pasted on?

### Mischief

- Is one harmless prank readable?
- Does it use an existing object when possible?
- Does it add humor without replacing the original narrative?

Regenerate once if the style is weak, the image becomes a triangular filter, the composition changes, the goose is incorrectly scaled or unsupported, the goose feels pasted in, or a protected subject is obscured.

## Output Behavior

Return the edited image. Optionally include one concise line describing the goose's visibility and prank.

Do not provide the full prompt or internal analysis unless the user asks.
