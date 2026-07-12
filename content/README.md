# HugoBlox publication bundles

This folder contains one HugoBlox publication page bundle per BibTeX entry.

Copy the `content/publications/` folder into the root of your HugoBlox site, merging with your existing `content/publications/`.

Each publication folder contains:

- `index.md`: the HugoBlox page metadata that the homepage `collection` block reads.
- `cite.bib`: the BibTeX citation file for that single publication.

I also included:

- `homepage_publications_block.md`: a homepage block you can paste into `content/_index.md`.
- `apa_citations_markdown.md`: a manual APA-style citation list with DOI links.

Note: The iScience entry in your uploaded BibTeX had a truncated title. I corrected it to:
“Low-frequency cortical activity reflects context-dependent parsing of word sequences”
based on the DOI metadata / PubMed and Cell page.
