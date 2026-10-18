# Art direction and prompt set

Generated with the built-in OpenAI image generation tool. No third-party character or image was used as a reference. PIP is an original orange fox detective with teal coat, terracotta scarf, one striped sock and a magnifier-loop tail.

## Prompt 1 — scene
Premium mobile spot-the-difference illustration, one wide 3:2 frame. Original PIP’S HIDDEN TOWN: Apricot Bakery at Whisker Wharf. Richly furnished anthropomorphic European harbor bakery, gouache/colored-pencil tactile paper, controlled teal/terracotta/butter/sage/cream palette, no neon. Open arched bakery window left with hedgehog baker, kettle and pastries. Central teal door. Terrace and canal right, round café table, blue-striped teacup and checked cloth. Bread basket, ducks, cat, swallows and sailboat. Pip lower center-right, orange fur, expressive eyes, teal coat, scarf, satchel, one striped sock, tail with glass loop. Clear small detail zones: brass clock, clover beside door, teacup, door diamond. No UI, text or watermark.

## Prompt 2 — differences
Edit reference scene preserving exact 1536×1024 framing, colors, identity and texture. Change only five details: clock short hand from upper-left to lower-left; remove inner door diamond; remove lower teacup blue band; remove rightmost clover leaf; remove one middle navy sock stripe. No recomposition or other changes.

## Prompt 3 — mascot
Use the scene as identity/style reference. True transparent 3:2 sprite sheet, two equal cells, same full-body scale and baseline. Curious smiling Pip on left, delighted eyes-closed raised-paw Pip on right. Teal coat with brass buttons, terracotta scarf, satchel, ONE navy/cream striped sock, glass-loop tail. Gouache detail, generous padding, no environment, text or border.

## Saved assets
- assets/scene-original.png: generated source,1536×1024.
- assets/scene-altered.png: generated edited source,1536×1024.
- assets/pip-poses.png: generated transparent two-pose sheet,1536×1024.
- assets/scene-original.jpg and scene-altered.jpg: JPEG format conversions for runtime.

Runtime always uses the same original painting in both pictures. Only five tightly clipped ellipses display the edited painting, avoiding unintended differences from generative repainting outside those regions. Source PNGs are retained locally; published runtime includes JPEG scenes and the transparent mascot.
