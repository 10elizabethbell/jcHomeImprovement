---
name: JC Home Improvement
description: A one-page contractor site built as a wall being tiled, navy glaze going down over combed thinset.
colors:
  glaze-navy: "#172a47"
  glaze-navy-deep: "#122139"
  ink: "#14213a"
  ink-soft: "#44506a"
  on-navy: "#f3f6fa"
  on-navy-soft: "#c3cfe0"
  tile-body: "#eef2f6"
  white: "#ffffff"
  thinset: "#a9a39a"
  bracket-gold: "#f2c624"
  bracket-gold-hover: "#ffd84a"
  brass-mid: "#b98f1c"
  brass-light: "#f4d465"
  brass-dark: "#a07a12"
  focus-blue: "#2f7cf6"
  field-line: "#c4ccd7"
  rule-line: "#cfd7e1"
  arrow-well: "#dfe5ec"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.45rem, 11.2vw, 5.6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.9rem, 7.4vw, 3.3rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "21px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(18px, 4.8vw, 22px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.55
rounded:
  tile: "2.5px"
  chip: "4px"
  control: "6px"
  round: "50%"
spacing:
  gutter-mobile: "16px"
  gutter-wide: "32px"
  band-mobile: "64px"
  band-wide: "104px"
  grout: "3px"
components:
  button-primary:
    backgroundColor: "{colors.bracket-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "56px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.bracket-gold-hover}"
    textColor: "{colors.ink}"
  button-outline-on-navy:
    backgroundColor: "transparent"
    textColor: "{colors.on-navy}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "56px"
  button-navy:
    backgroundColor: "{colors.glaze-navy}"
    textColor: "{colors.white}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  input-text:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "13px 14px"
    height: "54px"
  chip-choice:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.chip}"
    padding: "0 18px"
    height: "48px"
  chip-choice-selected:
    backgroundColor: "{colors.glaze-navy}"
    textColor: "{colors.white}"
  service-row-arrow:
    backgroundColor: "{colors.arrow-well}"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.bracket-gold}"
---

# Design System: JC Home Improvement

## Overview

**Creative North Star: "The Wall Going Up"**

The page is a wall the crew is tiling. Navy handmade-glaze subway tiles in running bond go down over grey notched-trowel thinset, edged with brass trim that is the logo's gold bracket made physical. Everything else on the page is the room around that wall: cool white tile-body sections, navy glazed sections, and heavy uppercase type that reads like a sign painted on a job-site van.

The surface is phone-first and plain-spoken. Sections are full-bleed bands that alternate tile-body white and glaze navy, stitched together by single courses of tile that lay themselves when scrolled to. Depth, texture and motion live inside the tile world (the live wall canvas and the course dividers); the interface around it is flat, solid and quiet so the one primary action never competes.

The world rejects the stock-kitchen-photo contractor template: no photography of finished rooms, no fake job gallery. The material itself is the imagery.

**Key Characteristics:**
- Navy glaze, cool white tile body, grey thinset, brass trim; nothing else carries colour except the gold action.
- Heavy uppercase system type (900 weight) for every section headline.
- Full-bleed alternating bands joined by self-laying tile courses with a brass top edge.
- Flat UI, textured world: shadows and grain exist only on tiles, thinset and the trowel.
- One live, touchable tile wall as the signature (hero, and a shorter strip above the footer).

## Colors

A two-ground palette (glaze navy and cool tile-body white) with grey thinset as the material middle and one hot accent, the logo's gold.

### Primary
- **Bracket Gold** (bracket-gold): the logo's bracket. Fills the primary action ("Get a free estimate", the form submit). Its hover lifts to **Bracket Gold, Lit** (bracket-gold-hover).
- **Brass Trim** (brass-light, brass-mid, brass-dark): the three stops of the brass edge gradient that caps every tile wall and tile course. Never used as flat fill.

### Secondary
- **Focus Blue** (focus-blue): the keyboard focus ring site-wide (3px, 3px offset) and the hover/focus outline of form controls (text inputs, textarea, select, chips, copy button, and the submit's border on hover). It is the interaction signal for the form, kept separate from the gold so the action colour is never diluted.

### Neutral
- **Glaze Navy** (glaze-navy): the hero ground, the navy band, the closing section, the selected chip, the Facebook button, the phone icon. Also the theme-color.
- **Glaze Navy, Deep Pool** (glaze-navy-deep): the footer ground only; the darkest ground in the system.
- **Ink** (ink): text on light grounds; text on gold.
- **Ink, Soft** (ink-soft): ledes and secondary notes on light grounds.
- **Glaze Highlight** (on-navy) and **Glaze Haze** (on-navy-soft): primary and secondary text on navy; the haze is also the resting border of the outlined button on navy.
- **Tile Body** (tile-body): the light band ground.
- **White** (white): the header, form field fills, idle chips.
- **Thinset Grey** (thinset): the mortar ground behind every tile wall and course, always carrying combed ridges.
- **Field Line** (field-line), **Rule Line** (rule-line), **Arrow Well** (arrow-well): input/chip borders, service-list hairlines, the resting arrow disc.
- **Error Red** (error-red): validation message text and invalid-field borders only.

### Named Rules
**The Bracket Rule.** Gold marks what you can act on and the brass trim; it is never a background for a section or a decorative fill. In the build it appears on the primary buttons, the trim gradient, the service-row arrow on hover, link hover on navy (phone numbers, footer links), the text selection and skip link, and the three step numerals on navy (the one static use).

**The No Black Ground Rule.** No section ground is black. The darkest surface is glaze-navy-deep in the footer. Black survives only as the logo's own line art.

**The Separate Signals Rule.** Gold says "do this"; blue says "you are here". Focus and form-control hover use Focus Blue, never gold.

## Typography

**Display Font:** system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same stack

**Character:** One family, pushed to its heaviest weight and set uppercase with tight tracking for headlines, so it reads as job-site signage; body stays at the platform's native text cut for speed and familiarity inside Facebook's in-app browser. This system stack is a deliberate house rule set by the site's builder, not a missing webfont.

### Hierarchy
- **Display** (900, clamp(2.45rem, 11.2vw, 5.6rem), 0.95, uppercase, -0.03em): the hero headline only.
- **Headline** (900, clamp(1.9rem, 7.4vw, 3.3rem), 1.02, uppercase, -0.02em, balanced wrap): every section h2. The closing brand name runs larger (clamp(2.2rem, 10vw, 5rem)); the "What we do" sub-heading runs smaller (clamp(1.3rem, 4.5vw, 1.6rem)) in the same treatment.
- **Title** (800, 21px, 1.2, -0.01em, sentence case): step titles.
- **Lede** (400, clamp(18px, 4.8vw, 22px), 1.5, max 34ch, pretty wrap): the paragraph under a section headline, in ink-soft or on-navy-soft.
- **Body** (400, 17px, 1.55): running text and form input text (17px, which also prevents iOS zoom).
- **Label** (800, 16px): form labels and legends; all buttons use 800 at 17px.
- **Numerals:** phone numbers and step numbers use tabular figures at 800 to 900 weight; the step numeral is 54px gold.

### Named Rules
**The Sign-Painter Rule.** Headlines are uppercase, weight 900, negatively tracked. Everything below headline level is sentence case at 800 or 400; no uppercase labels, no letter-spaced small caps.

**The Weight Ladder Rule.** Three weights only: 900 (headlines, numerals), 800 (titles, labels, buttons, service rows, phone links), 400 body. 700 is reserved for chips and inline note links; 600 for error text.

## Layout

A single centred column (max 1160px) inside full-bleed bands. Side gutter is 16px under 700px and 32px from 700px up. Bands pad 64px vertically on phones and 104px from 700px.

Breakpoints: 700px (gutter, band padding, tile size and header height step up) and 1024px (multi-column). Under 1024px everything stacks in one column. At 1024px the hero becomes two columns (copy 1.05fr, live wall 1fr, wall edged by a brass left border instead of a top border), content splits run 1fr/1fr with an 80px gap, the estimate band runs form 1.35fr with the "Licensed and local" block sticky on the right, the steps run three across, and the footer runs three columns.

The hero fills the first viewport (100svh minus the header) on phones, with the live wall taking whatever height the copy leaves; on desktop it is capped at 860px.

Bands are separated by tile courses: a single row of tiles (46x23px under 700px, 60x30px above) on thinset with 3px grout and a 5px brass top edge, offset by half a tile like running bond.

## Elevation & Depth

The interface is flat: no card shadows, no lifted panels, no blurred overlays. Depth exists only inside the tile world, where it is physical rather than UI: each tile carries an inner glaze glow, a dark joint edge and a 1-2px drop shadow onto the thinset; the trowel casts a soft shadow as it passes. Hierarchy between sections comes from ground colour alternation, not elevation.

### Shadow Vocabulary
- **Set tile** (`box-shadow: inset 0 0 3px 1px rgba(110,140,190,.32), inset 0 -1px 0 rgba(4,10,24,.45), 0 1.2px 2.5px rgba(8,16,32,.45)`): every course tile; the canvas tiles draw the same recipe.
- **Field focus halo** (`box-shadow: 0 0 0 3px rgba(47,124,246,.25)`): text inputs, textarea and select on focus. A ring, not elevation.

### Named Rules
**The Flat Room, Physical Wall Rule.** UI elements never cast shadows. Only tiles, thinset and tools do, because they are objects in the world.

## Shapes

Gently softened, not rounded: 6px on buttons, inputs and the message panel; 4px on choice chips; 2.5px on tiles (the glaze breaking over a rounded edge). The only full circle is the 44px arrow disc on service rows. Borders are 2px on interactive controls and 1px hairlines between service rows. The brass trim is a 5-6px gradient edge, always on the side where the wall meets the page.

## Components

### Buttons
Solid, wide and tall: thumb-sized on phones and confident on desktop.
- **Shape:** softened corners (6px), 2px border, 56px minimum height, 0 24px padding, 800 weight at 17px, optional 20px stroke icon left of the label.
- **Primary (gold):** Bracket Gold fill and border, ink text. Hover lifts to the lit gold; active nudges down 1px. Full width on phones, auto width from 700px (the submit) or side by side from 1024px (hero).
- **Outline on navy:** transparent with a Glaze Haze border and Glaze Highlight text; hover turns the border gold and the text white. Used for the secondary channel (WhatsApp).
- **Navy solid:** Glaze Navy fill, white text, 22px padding, hover to #22406b. Used for the outbound Facebook link on light grounds.
- **Form submit:** the gold primary, whose border turns Focus Blue on hover, matching the other form controls.
- **Quiet (copy):** white with a Field Line border, ink text, 50px tall; hover border Focus Blue.

### Chips
- **Style:** radio choices styled as 48px-tall tiles: white fill, 2px Field Line border, 4px radius, 700 weight, 18px horizontal padding, 10px gap, wrapping.
- **State:** hover border Focus Blue; selected becomes Glaze Navy fill and border with white text and a 0.42s overshoot "set" animation (drops in from 5px above at 1.08 scale), like a tile pressed into thinset. Keyboard focus draws the 3px blue ring.

### Inputs / Fields
- **Style:** white fill, 2px Field Line border, 6px radius, 13px 14px padding, 54px minimum height (textarea 120px, vertical resize), ink text at 17px. Label above in 800 at 16px with an 8px gap; optional marker in 500 ink-soft.
- **Hover / Focus:** border turns Focus Blue on hover; on focus the border is blue and a 3px translucent blue halo appears.
- **Error:** border Error Red, message below in 600 weight 15px Error Red; it clears as soon as the field is fixed.

### Navigation
There is no menu. The header is white, 68px tall (84px from 700px) with the logo at left (46px, 58px wide screens, 40px under 375px) and the phone number at right in 800 weight with a navy phone icon; hover underlines it.

### Service Rows
A list of large tap targets (72px minimum, 800 weight at clamp(20px, 5.4vw, 26px)) separated by 1px Rule Line hairlines, each ending in a 44px Arrow Well disc with an arrow. On hover or focus only the disc changes: it turns gold, and on keyboard focus it also gets the blue ring. The row itself never changes background, underline or shadow.

### Tile Course (signature)
A one-row strip of tiles on combed thinset under a brass edge, placed between every pair of bands. Tiles are drawn from eight navy glaze values so the course reads handmade. When it scrolls 60% into view, tiles drop in left to right, 32ms apart, with a 0.55s overshoot (cubic-bezier(.34,1.56,.64,1)) from 12px above at 1.16 scale. Reduced motion shows the course already laid.

### Live Tile Wall (signature)
A canvas wall in the hero (starting 42% tiled) and a 170px strip above the footer (230px from 1024px, starting 30% tiled). Bare thinset is combed in trowel-arc ridges with sand grain and damp patches; tiles in running bond carry twelve glaze variants with pale edge breaks and darker pooling, each sitting a hair off-grid. A finger or cursor lays tiles where it passes and nudges set tiles on springs; left idle, the wall tiles itself bottom course first, grouts the joints when full, holds, then a steel notched trowel sweeps band by band to reset it. Tiles are pulled off whole, never faded. All tuning constants (tile size, grout, idle timings, trowel pass, spring physics, DPR cap) live in the `C` object at the top of the "Tile wall" script. Under reduced motion the wall renders 90% tiled and static.

## Do's and Don'ts

### Do:
- **Do** put the gold only on the primary action, the brass trim, and hover signals of actionable things.
- **Do** set every section headline uppercase at weight 900 with negative tracking, in the system stack.
- **Do** alternate tile-body and glaze-navy bands and join them with a tile course under a brass edge.
- **Do** use Focus Blue (3px ring, 3px offset) for keyboard focus everywhere and for form-control hover and focus.
- **Do** keep tap targets at 44px minimum; primary buttons at 56px.
- **Do** keep texture, grain and shadow inside the tile world (tiles, thinset, trowel).
- **Do** tune the wall through the constants at the top of the "Tile wall" script, not by editing the drawing code.
- **Do** honour prefers-reduced-motion: courses pre-laid, wall static, no chip animation.

### Don't:
- **Don't** use a black ground anywhere; glaze-navy-deep is the floor.
- **Don't** use gold for focus, for section fills, or for decorative text beyond the step numerals.
- **Don't** change a service row's background, underline or shadow on hover; only the arrow disc changes.
- **Don't** add shadows, blur or lifted cards to UI elements.
- **Don't** add stock photography of finished rooms or kitchens; the tile material is the imagery.
- **Don't** fade tiles in or out on the wall; tiles are set and pulled off whole.
