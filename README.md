# COLCOS — Cost of Living / Cost of Smoking

Static rebuild of cost-of-smoking.org, staying close to the original site.
Plain HTML and CSS. No framework, no build step, no JavaScript, no third-party requests.

## Pages

```
index.html                 Home
about.html                 About Us, Partners, Research Question, Our Team
evidence.html              Data and Dialogue — the six evidence cards
resources.html             Our Services, Publication, Downloads
news.html                  News
problem-statement.html     Problem Statement
stakeholder-analysis.html  Stakeholder Analysis
photovoice.html            Visual Evidence (Photovoice)
action-agenda.html         Action Agenda
dedication.html            Dedication
```

Sub-pages sit under the "More" menu in the navigation, as on the original.

## Publishing

Settings → Pages → Deploy from a branch → `main` / root.
Keep the `.nojekyll` file. The Wix site stays live until the DNS for
cost-of-smoking.org is repointed.

## Still to come

- Problem statement narrative
- Photovoice captions (18 plates) and confirmation of plate titles
- Action agenda as it appears on the live page
- News entries
- Dedication text
- Whether Wendy Innocent should have a team profile

These are marked in the HTML with `class="todo"` and are visible on the page,
so nothing gets published half-finished without being noticed.

## Changes from the live site

- Added the published paper (Social Policy & Administration, 2024) to the home
  page and Resources, with links to the DOI and the open access version on AURA.
- Added a Downloads section on Resources for the PDFs already hosted on Evidence.
- Corrected: "cesation" → cessation; "amke informed decions" → make informed
  decisions; "adminsitrative" → administrative; "socailly" → socially;
  "build power community" → build community power.
- Page slug `probelm-statement` → `problem-statement`.
- Copyright line no longer fixed to 2023.

## Fonts

Open Sans, self-hosted in `assets/fonts/`. If the Wix site used a different
typeface, change the `--sans` variable at the top of `assets/css/colcos.css`
and swap the font files — nothing else needs to change.
