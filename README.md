# COLCOS — Cost of Living / Cost of Smoking

Static rebuild of cost-of-smoking.org. Plain HTML and CSS. No framework, no build step,
no JavaScript, no third-party requests (fonts are self-hosted).

## Structure

```
index.html                 Home
about.html                 About, research question, objectives, team, partners
evidence.html              The six forms of evidence (index)
  problem-statement.html     01  Problem tree
  stakeholder-analysis.html  03  Stakeholder analysis
  photovoice.html            05  Photovoice plates
  action-agenda.html         06  Action agenda
resources.html             Reports, briefs, slides, publication
news.html                  News and events
dedication.html            Dedication
assets/css/colcos.css      The whole stylesheet
assets/fonts/              Newsreader, IBM Plex Sans, IBM Plex Mono (woff2)
assets/img/                site, team, partners, evidence, photovoice
assets/files/              PDFs
```

## Publishing

Settings → Pages → Deploy from a branch → `main` / root.
The `.nojekyll` file is required; leave it in place.

The Wix site stays live until the DNS for cost-of-smoking.org is repointed.

## Still to add

- Problem statement narrative
- Photovoice captions (18 plates) and confirmation of the plate titles
- Action agenda content
- News entries
- Dedication text
- Full author list for the Social Policy & Administration paper

Placeholders for these are marked in the HTML with `class="todo"` and are visible on the
page, so nothing can be published by accident without being noticed.

## Corrections applied to the original copy

- "cesation" → cessation
- "amke informed decions" → make informed decisions
- "adminsitrative" → administrative
- "socailly" → socially
- "build power community in public health" → build community power in public health
- page slug `probelm-statement` → `problem-statement`
- Copyright line no longer fixed to 2023
