# COLCOS — Cost of Living / Cost of Smoking

Static rebuild of cost-of-smoking.org. Plain HTML and CSS: no framework, no build
step, no JavaScript, no third-party requests. Fonts are self-hosted.

## Pages (17)

```
index.html                        Home
about.html                        About Us, partners, research question, team
evidence.html                     Data and Dialogue — six evidence cards
resources.html                    Assessment of the approach, publication, downloads
news.html                         News index
  roadshow-feb-2024.html            ASH Scotland Celebrates in Aberdeen
  banff-workshop-feb-2024.html      Reflections with Community Partners
  roundtable-and-webinar-jan-2024.html  National Roundtable and Webinar
  prp-nov-2023.html                 Prevention Research Edinburgh
  nhsg.html                         Engaging with NHS Grampian
  ncd-alliance-scotland.html        Policy Roundtable: NCD Alliance Scotland
  liverpool-hope-university.html    Sharing Learning in Liverpool
problem-statement.html            Problem Statement
stakeholder-analysis.html         Stakeholder Analysis
photovoice.html                   Visual Evidence — the nine selected plates
action-agenda.html                Action Agenda
dedication.html                   Dedication
```

News story slugs match the live site, so existing links keep working.

## Colours

Sampled from the live site: page ground `#202F6F`, panels `#07134B`,
accent `#FD6262`. All set as variables at the top of `assets/css/colcos.css`.

## Publishing

Settings → Pages → Deploy from a branch → `main` / root. Keep `.nojekyll`.
The Wix site stays live until DNS for cost-of-smoking.org is repointed.

## Still to come

- Problem statement narrative
- Liverpool presentation PDF (linked on the live story, not in the Wix export)
- The forensic photograph on the Evidence Reviews card (see below)

Marked in the HTML with `class="todo"` and visible on the page.

## Changes from the live site

- Partner logos appear on About only, as on the live site, and each is now
  normalised onto an identical 340x190 white canvas so they reproduce at a
  consistent optical size. Sources in `assets/img/partners/`.
- Funder logos are not shown; funders are credited in the footer text, as on
  the live site. The normalised files exist if you want a row added back.
- Added the Recovery Stories podcast series to Resources, cross-linked from
  Stakeholder Analysis where the peer support gap is named.

- "Coming Soon" removed from the three home page blocks; the descriptions stand alone.
- "Our Services" removed from Resources, replaced with an assessment of the six
  components of the approach. This is new writing and needs approval.
- Added the Social Policy & Administration paper (2024) to Home and Resources.
- Added a Downloads section to Resources.
- Photovoice shows only the nine plates the community selected and captioned.
- Corrected: "cesation" → cessation; "amke informed decions" → make informed
  decisions; "adminsitrative" → administrative; "socailly" → socially;
  "build power community" → build community power; "expereince" → experience;
  "statsitics" → statistics; "this man if filling" → is filling;
  "Asthmas and Lung UK" → Asthma and Lung UK; "commerical" → commercial.
- Slug `probelm-statement` → `problem-statement`.
- Navigation is flat: About, Evidence, Resources, News. The "More" menu is gone;
  sub-pages are reached from the Evidence page and the footer.
- Action agenda content taken from the roadshow deck (slides 12 and 15).
- Dedication text carried across from the live site.
- News gains two entries: the Social Policy & Administration publication
  (September 2024) and the Liverpool Hope Inequalities and Health Summit
  (October 2024). Latest story runs as a feature.

## Page banners

Every page carries a banner built from the study's own photographs, converted to
a blue duotone (`#07134B` to a light blue) so each page keeps its own image while
staying in the site's colour. Built by `banner()` in the build script; sources in
`assets/img/banner/`. The home hero comes from the roadshow deck.

## Substituted images

The forensic photograph on the Evidence Reviews card is Wix stock and could not
be retrieved. In its place is `assets/img/evidence/evidence-reviews.svg`, an
evidence-tape illustration in the site palette. Drop the original in and change
the `src` in the build script if you'd rather have the photograph.

The Liverpool Hope 2024 story reuses the 2023 Liverpool photograph. A picture
from the October 2024 summit would be better.
