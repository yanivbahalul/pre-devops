---
name: awesome-design
description: >-
  Curated library of DESIGN.md files extracted from 80+ real company websites (Apple, Stripe,
  Linear, Vercel, Figma, Airbnb, Notion, and more). Use when asked to build a page that looks
  like a specific known brand or site, to match an existing site's visual language, or when the
  user references a DESIGN.md / design system document by a company name.
metadata:
  source: https://github.com/VoltAgent/awesome-design-md
  license: see LICENSE in this folder
---

# Awesome DESIGN.md

A `DESIGN.md` is a plain-text design-system document (a concept introduced by Google Stitch,
see https://stitch.withgoogle.com/docs/design-md/overview/) that describes a site's visual
language — tokens, type, color, spacing, component patterns — in markdown an agent can read
directly, with no Figma export or JSON schema required.

This skill vendors the `design-md/` reference collection from
[VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md): one folder per
company under `references/design-md/<company>/`, each containing a `DESIGN.md` (the design
system analysis) and a `README.md` (summary/attribution).

## How to use it

1. When the user asks for a page "like \<company\>" or references a known brand's look, check
   `references/design-md/<company-slug>/DESIGN.md` first (slugs are lowercase, e.g. `apple`,
   `stripe`, `linear`, `figma`, `x.ai`, `notion`).
2. Read that `DESIGN.md` in full before writing any UI code — it defines the tokens, type scale,
   spacing rules and component patterns to follow.
3. Apply the described design language to the requested page/component. Treat the file as a
   style reference, not boilerplate to copy verbatim.
4. If no folder matches the requested company, say so — do not fabricate a design system. The
   user can request one at https://getdesign.md/request.

## Available companies

Run `ls references/design-md/` for the current list (80+ folders as of install), spanning AI/LLM
platforms, developer tools, backend/devops, productivity SaaS, design tools, fintech/crypto, and
e-commerce/retail.
