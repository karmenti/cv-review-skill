# CV Template Recommendations

Only use this if the user asks for a template. Don't push templates by default; the content matters more than the template.

Visual format preferences vary by market and industry. There is no single "correct" CV template. The guidance below is general; weigh it against what the candidate's target market actually expects.

## What tends to work well

- **Readable typography.** Sans-serif body font (Inter, Helvetica, Arial, Source Sans), 10 to 11pt body, 14 to 16pt headers. Anything legible on screen and on paper.
- **Generous whitespace.** Margins around 1.5cm or more. Don't cram to fit one page; cut content instead.
- **Consistent formatting.** Same date format throughout, consistent bullet style, consistent capitalisation in headers.
- **PDF for sending.** Word documents render differently on different machines.

## On layout choices

**Single column vs two column.** Single column tends to parse most reliably across ATS systems and reads quickly in scan mode. Two-column layouts (including dark sidebar designs) are widely used and work fine in many cases, especially in markets where humans review CVs first. In Estonia, for example, most CVs are reviewed by a human before any automated filtering, and visually designed CVs are common and accepted across many roles. If the user is applying to large multinational employers with strict ATS pipelines, single column is the safer choice; for local Estonian employers, the layout matters less than the content.

**Photos.** Whether to include a photo depends on market and context, it's not a universal rule. See the photo guidance in `SKILL.md`: a photo can help when the candidate has met the recruiter (career fair, event) or in markets where it's standard, and works against them in international or ATS-heavy pipelines. Don't reflexively strip a photo from a template; advise based on where the candidate is applying.

## Concrete options

### For developers and technical roles

**Awesome CV (LaTeX).** Clean, single-column, well-suited for technical CVs.
- Source: https://github.com/posquit0/Awesome-CV
- Pros: looks polished, parses well, easy to customise once familiar with LaTeX.
- Cons: requires LaTeX, which is a barrier for many.

**Overleaf "Deedy CV".** Compact two-column variant.

**Markdown to PDF (via Pandoc or Typst).** Full control without LaTeX overhead. Typst is friendlier than LaTeX.

### For everyone else (no LaTeX)

**Google Docs / Microsoft Word** with a simple, manually structured layout. Avoid the gallery defaults; they tend to be over-designed. Start blank, structure manually, export to PDF. This is what most candidates use.

**Notion CV templates.** Easy to maintain, exports to PDF. Several free, clean ones exist.

**Canva.** Widely used and acceptable in many markets, including Estonia. The risk is picking a designer-portfolio template that buries content behind decoration. If using Canva, choose a minimal "resume" template with clear hierarchy, plain fonts, and a single readable column or a clean two-column layout. The output is fine for human reviewers; if the candidate is also applying through strict ATS pipelines, a parallel single-column version is worth keeping.

## What to avoid regardless of market

- **Europass for tech roles.** Verbose and harder to scan than alternatives.
- **Skill rating bars** ("HTML ████████░░ 80%"). Recruiters cannot interpret these; they look gimmicky.
- **Highly decorative fonts** (Comic Sans, Papyrus, Brush Script, anything ornate).
- **Skill clouds and word art.** Visual noise without information value.
- **Templates so visually busy that the content is hard to find.** This is the real test, regardless of platform.
