# R&D Evidence Classification Framework — NSF HERD Survey

An interactive, five-level evidence hierarchy for classifying sponsored awards as R&D (Research & Development) for the NSF HERD Survey. Built by the Office of Research Administration at Morgan State University.

**Live site:** https://ayomide1400.github.io/msu-herd-survey/
**Policy reference:** https://ayomide1400.github.io/msu-herd-survey/policy-reference.html

## What's here

| File | What it is |
|---|---|
| `index.html` | The interactive site — framework explainer, evidence ladder, reliability/validity explainer, and a step-by-step classifier wizard. Single self-contained file (no build step). |
| `policy-reference.html` | The same framework content formatted as a formal institutional policy document — read online, or download the identical content as Word below. |
| `assets/RD-Classification-Framework.docx` | The framework as a downloadable Word document. |
| `LICENSE.md` | CC BY 4.0 — see below. |

Both HTML files are plain HTML/CSS/JS with no dependencies beyond two Google Fonts imports — clone the repo, open `index.html`, and it works.

## Using this framework at your institution

This repository is a **GitHub template** — click **"Use this template"** on the repo page to get your own copy, or fork it directly.

The five-level evidence hierarchy (Notice of Award → Funding Opportunity Announcement → ALN/CFDA → Supporting Documentation → Institutional Record), the reliability/validity framing, the glossary, and the classifier wizard logic are all institution-agnostic — they follow NSF, Frascati Manual, and Uniform Guidance definitions, not anything specific to Morgan State. You should be able to use those as-is.

What **is** Morgan State–specific and should be replaced before publishing your own copy:

- **Institution name and branding** — "Morgan State University" and "Office of Research Administration (ORA)" appear throughout both HTML files; search-and-replace with your institution's name and the office responsible for HERD reporting at your school.
- **Authorship/byline** — "Ayomide Ajibola" and "Rebecca Steiner" credits in the hero, footer, and docx title page.
- **PI Handbook citation** (`policy-reference.html`, Section 2.3) — this quotes Morgan State's own PI Handbook (Part 5, Definition D) as one of the framework's sources. Replace with your institution's equivalent policy definition of R&D, if one exists, or omit the section if it doesn't.
- **Carnegie Classification reference** (Section 3.1 / "Why It Matters") — references Morgan State's specific classification; update to your institution's.
- **Brand colors** — both HTML files define colors as CSS custom properties at the top of the `<style>` block (`--navy`, `--orange`, etc.). Change these two or three variables to reinstyle the whole site in your institution's colors.
- **Favicon** — an inline SVG data URI in each file's `<link rel="icon">`, using the same color variables.

Everything else — the wizard's decision logic, the definitions glossary, the ladder visualization, the reliability/validity diagrams — reflects federal definitions (NSF, OECD Frascati Manual, 2 CFR Part 200) and should transfer directly.

## License

CC BY 4.0 — see [LICENSE.md](LICENSE.md). Share and adapt freely, with attribution.

## Background

This framework was developed to bring a consistent, document-anchored methodology to a process that, at most institutions, currently relies on informal judgment or sponsor-name shortcuts. The full rationale is in the [policy reference page](https://ayomide1400.github.io/msu-herd-survey/policy-reference.html).
