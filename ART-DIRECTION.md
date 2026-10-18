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

# Two additional chapters — 2026-10-19

Built-in image generation was used for all four new source paintings; no fallback CLI. The bakery image was supplied only as a style/character reference for NEW original compositions. Edited scenes used their own corresponding original as the edit target. JPEG quality93 conversions retain dimensions; runtime SVG masks preserve the unchanged painting outside the five differences.

## Prompt set — chapter 02
Original: Illustration-story, one 1536×1024 landscape painting for The Glasshouse Florist. Match reference’s intricate tactile gouache/colored-pencil storybook realism, sage/teal/terracotta/cream with readable non-neon contrast. Lush Victorian glasshouse with curved iron-and-glass roof, rabbit florist at wooden potting bench, courtyard beyond, individually rendered flowers, seed drawers, pots, tools, patterned tiles and bird. Same orange fox PIP, cream muzzle, teal coat, terracotta scarf, satchel, one striped sock and magnifier-loop tail in lower-right. New composition. Five detail zones distributed: watering can with two narrow engraved bands front-left, brass wall clock upper-left, butterfly on upper-center hanging pot, blue pot with five-petal white flower center-right, garden glove with three buttons lower-center. No words/UI/watermark, one painting not collage.

Edit: Preserve exact canvas/framing/identity/lighting. Only five changes: clock short hour hand from upper-left to lower-left; remove lower of two close gold bands on watering can; remove largest pale lower-right butterfly wing spot; remove lower-left white petal from blue-pot flower; remove middle of three glove buttons, restoring knitted fabric. No other objects changed. Runtime masks restrict the resulting repaint to these areas.

## Prompt set — chapter 03
Original: Illustration-story, new1536×1024 Stargazer’s Attic. Bakery reference for style/character only. Exquisite gouache/colored-pencil storybook realism. Cozy attic observatory with wooden rafters and celestial mobiles, huge round window showing blue-hour stars and harbor rooftops. Warm amber lamps balanced with muted deep teal, readable contrast. Friendly owl astronomer on left with star charts; brass telescope right-center; worn books, celestial globe, rugs, teapot. Same PIP lower-center-right. Five detail zones: crescent brass ornament upper-left with three star holes; globe with white ringed-planet emblem left-center; closed red book lower-left with three pairs of gold bands; cup lower-center with two navy bands; thin brass rings near telescope eyepiece. No text/UI/watermark, one full painting.

Edit: Preserve exact1536×1024 frame/positions/lighting. Only five changes: fill middle star hole of crescent near134,149 with brass; remove orbital ring of planet emblem near500,340 leaving round planet; remove middle pair of red-book gold bands near145,615; remove lower blue cup band near510,750; remove raised telescope eyepiece collar near980,405. No other changes. Runtime uses only small clipped edited regions.

## Additional saved assets
- assets/garden-original.png and garden-altered.png — generated source paintings,1536×1024.
- assets/attic-original.png and attic-altered.png — generated source paintings,1536×1024.
- assets/garden-original.jpg, garden-altered.jpg, attic-original.jpg, attic-altered.jpg — runtime JPEG conversions.

All final source images are saved in this project. The previous bakery paintings and transparent mascot are retained unchanged.
