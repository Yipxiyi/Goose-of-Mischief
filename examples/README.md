# Example and Acceptance Cases

These cases are intended for manual testing of the skill. Every test requires a source image.

## 1. Wide garden scene

**Request**

```text
Use $goose-of-mischief to transform this image. Decide the goose visibility automatically.
```

**Expected behavior**

- Preserve the garden layout, paths, people, plants, and camera.
- Choose a prominent or medium-prominence goose if open ground is available.
- Use an existing garden object, such as a glove, watering can, hose, flower, or small tool.
- Match the ground plane and cast a soft contact shadow.

## 2. Close portrait

**Request**

```text
用 $goose-of-mischief 处理这张人物照，鹅不要太明显。
```

**Expected behavior**

- Preserve crop, pose, clothing, and subject placement.
- Do not cover or substantially alter the face.
- Use a subtle goose near the bottom edge, beside a chair or bag, or partially behind an object.
- The prank should use a visible secondary accessory when possible.

## 3. Pet photo

**Request**

```text
保留宠物的姿势和花纹，让鹅进行一个无害的小恶作剧。
```

**Expected behavior**

- Preserve the pet as the primary subject and retain species, markings, and pose.
- Do not turn the pet into a goose or introduce aggression.
- Let the goose move a toy, blanket corner, leash, bowl-side object, or another safe prop.
- Keep the interaction playful and non-distressing.

## 4. Product image

**Request**

```text
Use $goose-of-mischief on this product image. Do not cover the product or label.
```

**Expected behavior**

- Preserve product geometry, arrangement, label placement, and lighting hierarchy.
- Use a subtle goose at the base or edge of the composition.
- Interact only with a secondary accessory such as ribbon, paper, tag, or packaging insert.
- Keep important branding and text unobstructed.

## 5. Dense city or travel scene

**Request**

```text
把这张旅行照转换成绘本质感，鹅可以藏得像彩蛋。
```

**Expected behavior**

- Preserve location identity, skyline, buildings, vehicles, and people count.
- Choose a hidden or distant goose.
- Place it at a doorway, pavement edge, market stall, path, or behind foreground street furniture.
- Do not create traffic danger or a new crowd reaction.

## 6. Food image

**Request**

```text
用 $goose-of-mischief 改造这张食物照片，不要破坏摆盘。
```

**Expected behavior**

- Preserve the dish, plate, framing, and plating.
- Use a small goose reaching toward a garnish, napkin, spoon, or loose ingredient.
- Keep the food clean and appetizing.
- Do not block the main dish.

## 7. Text-heavy poster or interface

**Request**

```text
处理这张海报，保留主要文字区域，让鹅只在边缘捣乱。
```

**Expected behavior**

- Treat important text and UI regions as protected zones.
- Preserve layout and legibility as much as the editing model permits.
- Put the goose in a margin, empty panel, or nonessential decorative area.
- Do not rewrite, cover, or parody important text.

## Failure conditions

A result fails if any of the following occurs:

- the source image is no longer recognizable
- the crop, camera, or major composition changes without permission
- a primary subject is moved, removed, duplicated, or replaced
- there is no goose, or there is more than one goose without request
- the goose covers a face, label, important text, UI, or focal object
- the goose has incorrect scale, perspective, lighting, occlusion, or shadow
- the goose appears pasted on rather than embedded
- the prank is harmful, destructive, aggressive, or impossible to understand
- the scene is replaced with a generic countryside environment
- the output copies recognizable commercial game assets, maps, UI, or branding
