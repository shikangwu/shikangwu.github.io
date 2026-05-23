# CLAUDE.md

This repository is Shikang Wu's GitHub Pages personal homepage.

## Publication entry convention

When adding or updating publications, use the current figure-card format:

- Put publication figures under `assets/images/` with concise lowercase filenames, e.g. `msn.png`, `mdl.png`, `tokenmixer-large.png`.
- Each publication with a figure should use a `.publication-card.with-figure` block.
- The figure link should use both `.publication-figure` and `.lightbox-trigger` so clicking opens the in-page lightbox instead of navigating to the raw image.
- Keep the paper information on the right in `.publication-info`.
- Use short venue labels on the page, e.g. `KDD 2026`, `SIGIR 2026`, `CIKM 2026`, with the full venue name in the `title` tooltip.
- Use `.paper-status.accepted` for accepted papers and `.paper-status.submitted` for under-review/submitted papers.
- Preserve the concise academic homepage style: lightweight cards, compact spacing, and no long paper abstracts in the publication list.

Example structure:

```html
<div class="publication-card with-figure">
  <a href="assets/images/example.png" class="publication-figure lightbox-trigger"><img src="assets/images/example.png" alt="Example framework" class="publication-thumb"></a>
  <div class="publication-info">
    <papertitle>Paper Title.</papertitle>
    <br>
    Authors
    <br>
    <em title="Full Venue Name">VENUE 2026</em> <span class="paper-status accepted">Accepted</span><br>
    <a href="https://arxiv.org/abs/example">[arXiv]</a>
  </div>
</div>
```
