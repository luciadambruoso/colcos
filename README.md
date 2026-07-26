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
- Action agenda as it appears on the live page
- Dedication text
- Liverpool presentation PDF (linked on the live story, not in the Wix export)

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

## Substituted images

Two stock photographs on the live Evidence page were not in the Wix export:
the forensic investigator on Evidence Reviews and the sky on Action Agenda.
Standing in: the first page of Evidence Brief 1, and the second abstract image
from the export. Swap them in `evidence.html` when originals are available.
