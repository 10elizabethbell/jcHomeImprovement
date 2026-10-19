# JC Home Improvement — handoff at ~60%

**Live:** https://10elizabethbell.github.io/jcHomeImprovement/ · **Repo:** https://github.com/10elizabethbell/jcHomeImprovement · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (found via the "New Jersey Small Business Network" Facebook group post)

## What's built
- One page, phone first: a white header with their real logo and (201) 838-5000 in the top right. The navy hero reads "Building your dreams." (their own tagline), the pitch line, a gold "Get a free estimate" button and an outlined "WhatsApp us" button.
- **World: tile setting.** The hero is a live wall of navy glazed subway tile going into combed grey thinset, with brass edge trim taken from the logo's gold bracket.
  - The wall tiles itself course by course, grouts itself when full, holds, then a notched trowel combs it clean and it starts again.
  - A finger or mouse lays tiles in any direction (vertical drags included) and nudges set ones.
  - The same tile courses lay themselves as dividers between sections, and a second wall strip sits at the close.
  - Tuning constants are at the top of the "Tile wall" script (speed, hold, tile size, push).
- **Sections:** "Got a quote already? We'll beat it." / "What we do" (3 rows that jump to the form with the project type picked) / "How it works" (3 steps) / "Licensed and local" with the Facebook button / the estimate form / the close with both numbers / the footer with the email, Facebook and Instagram.
- **Estimate form:** name, town, project type, details and best time. It opens a pre-filled **text message** to (201) 838-5000, with a copy-message fallback and a "Send it on WhatsApp" link carrying the same text.
- og image, favicon and iPhone home-screen icon all come from their logo.
- Impeccable: finish reviewer (fix round applied) plus an all-modes sweep (critique, audit, polish, bolder, quieter, distill, harden, animate, colorize, typeset, layout, delight, overdrive, clarify, adapt, optimize). The detector is clean, and its ignores are recorded with reasons in `.impeccable/config.json`.

## Assumptions I made
- **Name:** "JC Home Improvement" was confirmed from their logo and flyer. The "CHme" in the brief was an OCR misread of the stacked J/C.
- **Email:** `jcgchomeimprovement@outlook.com`, read off the flyer image. The brief's `jegchomeimprovement@outlook.co` was an OCR error. It appears in the footer only.
- **WhatsApp:** inferred from the WhatsApp icon printed next to both numbers on their flyer. I wired it to 838-5000.
- **Texts:** the form hands off by SMS, assuming 838-5000 is a mobile (the WhatsApp icon suggests it is). The brief says texting is unconfirmed, so calling stays in the header and close.
- **Colors:**
  - Navy (#172a47) as the non-black stand-in for their black logo.
  - Gold (#f2c624) sampled by eye from the logo's bracket and kept for the primary button and brass trim only.
  - Blue (#2f7cf6) as the form hover/focus outline.
- **Copy:** in "we" voice (a company with a crew). "We'll go over the job with you", "without cutting corners in your home" and "We treat your home like it's our own" are written attitude lines, not facts from them. Check the tone with the owner.
- **Their kitchen photo is not used.** The flyer's kitchen photo looks like a stock or AI render, not their job.
- **Services:** only what they list: General construction, Remodeling, Renovation. No kitchens, baths and so on, because they haven't said so.

## Placeholders and gaps
- **No photos of their work.** The page leans on the tile wall instead, and the Facebook button stands in for proof. Real job photos (and before/after pairs) would go under "Licensed and local", above the Facebook button.
- **"State-licensed" is their own claim.** No NJ Home Improvement Contractor (HIC) registration number has been verified. NJ requires the HIC number on contractor advertising, so get it from the owner and add it before handover.
- **Instagram @jc_home.improvement** comes off the flyer and wasn't checked live.
- No hours, owner name, street address, reviews or prices.
- **No service-area towns.** Only Bergenfield, NJ is known. Bergenfield isn't in the hero, because the finishing rules keep service area out of it.

## Questions for the owner
- What's your HIC registration number? It becomes a trust line ("NJ HIC #…").
- Can we have 6–10 photos of finished jobs, plus any before/afters?
- Do you take texts and WhatsApp on 838-5000? Which number should the form go to?
- Which jobs do you most want (kitchens, baths, basements, additions, decks)? Which towns do you cover?
- What's your first name, so the page can say who the customer will deal with?
- Is 681-8900 a second line or a partner's phone?

## Ideas not built (yours to pick)
- **Runner-up world:** a pencil-sketch house elevation built from the logo's hand-drawn roofline, which draws itself line by line ("Building your dreams"). The finger would add framing members.
- Photo frames done as tiles: their job photos set into the wall as large-format tiles, once they send some.
- A "Send us a photo of the space" step (WhatsApp makes that easy).
- Spanish version (Bergenfield has a large Spanish-speaking population). Only if the owner wants it.
- Grout colour picked by the visitor, or the hero tile colour changing with the project type.

## Not verified
- Real-device touch on iPhone and Android, including inside Facebook's in-app browser. It was simulated in Playwright WebKit and Chromium.
- The real SMS and WhatsApp handoff on a phone. The link bodies were checked to decode correctly.
- Frame rate on older phones. The canvas is capped at 2x, idle frames are skipped, and it pauses off screen.
- The Facebook link-preview card (og:image) as Facebook actually renders it.
