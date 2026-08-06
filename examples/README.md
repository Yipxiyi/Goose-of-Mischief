# Example and Acceptance Cases

These cases are intended for public manual testing. Every test requires a source image.

All successful results must satisfy three conditions simultaneously:

1. the source composition remains recognizable
2. the pastoral low-poly storybook style is strong and immediate
3. the goose has physically plausible scale, support, perspective, lighting, and occlusion

## 1. Wide garden scene

**Request**

```text
Use $goose-of-mischief to transform this image. Decide the goose visibility automatically.
```

**Expected behavior**

- Preserve the garden layout, paths, people, plants, and camera.
- Apply a strongly recognizable pastoral low-poly storybook reconstruction.
- Use open ground, a path, or another valid support plane.
- Anchor goose scale against paving stones, people, tools, garden furniture, or path width.
- Use an existing garden object such as a glove, watering can, hose, flower, or small tool.
- Match the ground plane and cast a soft contact shadow.

## 2. Close portrait

**Request**

```text
用 $goose-of-mischief 处理这张人物照，鹅不要太明显。
```

**Expected behavior**

- Preserve crop, pose, clothing, face region, and subject placement.
- Simplify the person into a faceless low-poly storybook figure without changing the composition.
- Do not cover the face or essential gesture.
- Use floor space, a chair gap, bag, doorway, or edge entry.
- Do not shrink a full goose onto a shoulder, narrow table, or tiny shelf.
- Use placement and partial occlusion—not toy scale—to keep the goose subtle.

## 3. Pet photo

**Request**

```text
保留宠物的姿势和花纹，让鹅进行一个无害的小恶作剧。
```

**Expected behavior**

- Preserve the pet as the primary subject and retain species, markings, pose, and scale.
- Reconstruct fur and markings as broad matte color regions.
- Use the pet plus nearby furniture or props as goose scale anchors.
- Do not arbitrarily make the goose larger than the pet for emphasis.
- Let the goose move a toy, blanket corner, leash, cable, or another safe existing prop.
- Keep the interaction playful and non-distressing.

## 4. Product image

**Request**

```text
Use $goose-of-mischief on this product image. Do not cover the product or label.
```

**Expected behavior**

- Preserve product geometry, arrangement, label placement, and lighting hierarchy.
- Strongly reconstruct the surrounding scene in the required low-poly storybook style.
- Treat the main product and label as protected regions.
- Use floor or background space when possible.
- If the surface cannot fit a real goose, show only a partially hidden or edge-entering goose.
- Never shrink a full goose into a decorative tabletop toy.

## 5. Dense city or travel scene

**Request**

```text
把这张旅行照转换成绘本质感，鹅可以藏得像彩蛋。
```

**Expected behavior**

- Preserve location identity, skyline, buildings, vehicles, people count, and camera.
- Use strongly simplified matte low-poly architecture and broad color planes.
- Choose a distant or partially hidden goose.
- Scale it using door height, paving, pedestrians, curb width, or street furniture.
- A small background goose is acceptable only because it is distant.
- Do not create traffic danger or a new crowd reaction.

## 6. Food image

**Request**

```text
用 $goose-of-mischief 改造这张食物照片，不要破坏摆盘。
```

**Expected behavior**

- Preserve the dish, plate, framing, and plating.
- Reconstruct food and tableware as clean matte low-poly forms while keeping them appetizing.
- Do not place a miniature full-body goose beside a plate.
- Use a correctly scaled goose on the floor, in the background, partly behind a table edge, or entering with only its head and neck.
- Let it reach toward a napkin, spoon, or loose safe prop without contaminating the food.

## 7. Text-heavy poster, screen, or interface

**Request**

```text
处理这张海报，保留主要文字区域，让鹅只在边缘捣乱。
```

**Expected behavior**

- Treat important text and UI regions as protected zones.
- Preserve layout and legibility as much as the editing model permits.
- Keep the required low-poly storybook style strong in surrounding objects and figures.
- Put the goose in a margin, empty panel, plausible depth opening, or edge crop.
- Do not rewrite, cover, or parody important text.

## Style failure conditions

A result fails if:

- the result remains substantially photographic
- the required pastoral low-poly storybook style is weak or replaced by generic editorial, painterly, watercolor, or vector styling
- the image is covered by a uniform triangular mosaic or stained-glass polygon filter
- realistic high-frequency texture remains dominant
- surfaces become glossy or lighting becomes cinematic
- the output copies recognizable commercial game assets, maps, UI, or branding

## Composition failure conditions

A result fails if:

- the source image is no longer recognizable
- crop, camera, perspective, or major composition changes without permission
- a primary subject is moved, removed, duplicated, or replaced
- a face, pet, product, label, important text, UI, or focal object is obscured
- the scene is replaced with a generic countryside environment

## Goose failure conditions

A result fails if:

- there is no goose or more than one goose without request
- no valid support surface is identifiable
- fewer than two meaningful scale anchors are used
- the goose is giant, mascot-sized, miniature, or toy-like
- a full-body goose is forced onto a physically impossible surface
- visibility is achieved by unrealistic enlargement or shrinking
- feet float or lack a plausible contact shadow
- perspective, depth, lighting, occlusion, or color temperature does not match
- the goose appears pasted on rather than embedded
- the prank is harmful, destructive, aggressive, unrelated, or impossible to understand
