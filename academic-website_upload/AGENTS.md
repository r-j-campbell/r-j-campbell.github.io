# Website maintenance

This is Ryan Campbell’s academic website, primarily for prospective PhD students. Edit the HTML files directly; shared presentation lives in `assets/styles.css`. There is no build step, package installation, framework or runtime JavaScript.

## Factual accuracy
- Never invent publications, software, projects, funding, deadlines, eligibility, collaborators, achievements or supervision commitments.
- Ask Ryan for missing facts. Keep unconfirmed information visibly unconfirmed until he supplies it.
- Ryan has confirmed his name, role as a solar physicist and lecturer at Queen’s University Belfast, spectropolarimetry and AI-based atmospheric inference interests, contact details and the potential research directions currently listed.
- Ryan has confirmed willingness to supervise observational and computational solar physics PhDs and welcomes enquiries about projects and funding. This does not establish funded vacancies or admission guarantees.
- Profile links do not authorise importing unverified publication records. Confirm any curated bibliography with Ryan.
- Keep recruitment information current; record confirmed deadlines with year, time zone and authoritative application links.

## Editing and design
- Pages: `index.html`, `research.html`, `phd.html`, `publications.html`.
- Keep navigation and footer consistent across all four pages. Set exactly one `aria-current="page"` link per page.
- Use relative asset and page links so GitHub Pages project subpaths work.
- Use semantic HTML, one h1 per page, visible keyboard focus and descriptive link labels.
- Preserve the mobile layout, accessible contrast and skip link. Avoid external fonts, analytics and new dependencies without a clear need.
- Replace figure slots with Ryan-approved figures in `assets/`. Provide accurate alt text, captions, provenance and any required credit; do not present generated illustrations as scientific results.
- The Home illustration is decorative CSS, not data. Preserve that label.
- Add publications only with confirmed title, authors, year, venue and DOI or stable URL. Add software only with confirmed name, repository and description.

## Verification and publication
- Serve the site locally and inspect all pages at desktop and mobile widths after layout changes.
- Check relative links, email and profile URLs, heading structure and keyboard navigation.
- No automated tests or build are required for routine copy edits.
- This version is a draft. Do not publish until Ryan has reviewed it and authorised publication. Keep draft status in maintenance documentation, not visible page content.
- GitHub Pages can serve these files directly from a repository root. Preserve `.nojekyll`.

## Updated source and design decisions — 10 October 2026
- Ryan requested an Apple-inspired aesthetic. Use system sans-serif type, white and soft grey surfaces, rounded panels, QUB-inspired red links (#d6000d) and generous whitespace.
- Ryan authorised checking ORCID. Publication records were read from the public ORCID v3 API on 10 October 2026. `data/publications.json` preserves metadata; HTML is pre-rendered and does not fetch the API at runtime. Refresh metadata and matching HTML together. ORCID coverage is not necessarily exhaustive.
- The GitHub profile URL is supplied by the July 2025 CV. No repository-specific software claims have been added.
- `assets/sunrise-inference.png` is Figure 2 extracted from Ryan’s B1 draft, rendered from the embedded EMF. The original EMF is retained. Do not alter scientific panels or imply that the ERC proposal has been funded. Ryan requested its inclusion in the draft; confirm public-release suitability before publication.
- The decorative Home illustration has been replaced by the scientific figure.

- Remove B1 extraction provenance from visible captions as requested by Ryan; retain source provenance here.
- Home includes DKIST granulation from https://nso.edu/telescopes/dkist/first-light-full-image/ . Original: https://nso1.b-cdn.net/wp-content/uploads/2020/01/full_image_high.jpg (7320 × 7320); a resized 1800px JPEG is served inline. Preserve visible NSO/NSF/AURA credit, source and CC BY 4.0 link. No crop was made. This is processed promotional imagery, not calibrated science data. The source also notes approval requirements for scientific/outreach use of Science Verification Phase data; review intended public use before deployment.

## Visitor-facing copy
- Ryan requests no architectural or production artefacts in visible content. Keep resizing, extraction, source-check dates, implementation details and draft status in maintenance files. Preserve scientific descriptions, visible image credits and licence links. Phrase missing recruitment details as a contact invitation without implying funding availability. The site remains unpublished pending review.

- Flare research wording is “Spectropolarimetric and spectroscopic diagnostics of solar flares”.
- Ryan requested arXiv:2608.03776. Metadata checked against https://arxiv.org/abs/2608.03776 on 10 October 2026; submitted 4 August 2026, listed as submitted to A&A. Keep it clearly labelled a preprint unless its publication status is verified. It is stored in the separate preprints array in data/publications.json.

- Visible publication and preprint author lists show the first two authors, followed by “et al.” only when there are more than two. Keep complete author lists in data/publications.json.

- Preferred public display name is Ryan J. Campbell. Use this in headings, page titles, metadata and footers. Preserve publication author names as recorded in their sources. Include the current website link in every completion response.
`n- The top-left brand initials are RJC on every page.
- Home portrait is the photo supplied by Ryan on 10 October 2026, stored in assets/ryan-campbell.png. Preserve the original image; its circular appearance is CSS only.
- Sunrise inference figure is now rendered at 7200 pixels wide from the original embedded EMF. Do not apply AI enhancement to scientific maps; higher rendering resolution does not recover detail absent from the embedded original.

- Ryan confirms PhD projects are usually advertised in November; do not turn this usual timing into a specific deadline or confirmed vacancy.
- Preferred recruitment wording is “I am open to supervising”. Ryan meets students weekly or fortnightly, expects independent literature reading and deep thinking, encourages critically interrogated AI as a co-pilot, expects willingness to travel to conferences and research stays abroad, and welcomes ambition. Do not imply travel funding is guaranteed.
- Ryan is also open to interdisciplinary PhD projects; include this alongside observational and computational solar physics supervision interests.
- Ryan encourages a healthy approach to work-life balance; retain this in the supervision section.

- PhD hero image: official DKIST first sunspot image, https://nso.edu/telescopes/dkist/inouye-first-sunspot/ . Source credit NSO/NSF/AURA, CC BY 4.0. Preserve visible credit and licence link. Image taken 28 January 2020 at 530 nm, displayed in a warm false-colour palette. Source Science Verification Phase conditions match the Home granulation image; do not use as calibrated scientific data.
- The 26.5 MB original granulation JPEG is excluded from the publishing package. Full-resolution links point to the NSO original; the local display JPEG remains in assets. Keep individual files below GitHub browser upload limits.
