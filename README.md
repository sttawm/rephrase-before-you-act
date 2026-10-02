# Rephrase Before You Act — project site (named version)

Live at https://sttawm.github.io/rephrase-before-you-act/ (GitHub Pages, branch `main`, path `/`).
Edit `index.html`, push to `main`, and the page redeploys within about a minute.

This is the **non-anonymous** site, for the arXiv version of the paper. The anonymous site for the
conference submission is separate and must stay separate until the decision: do not link to it from
here, do not link here from it, and do not copy this repo's history into it.

## Finishing touches (for the authors)

- [ ] Author line (`<p class="authors">`): confirm the author list and order, add affiliations and
      personal/lab links.
- [ ] Paper link: replace "arXiv preprint coming soon" in the author line with the arXiv link once
      posted; add the same link to the footer. (The submission PDF is deliberately not hosted here.)
- [ ] BibTeX (`<pre id="bibtex">`): confirm names, add the arXiv identifier (`eprint`/`archivePrefix`)
      and drop the "Under review" note when appropriate.
- [ ] Acknowledgments, if wanted on the site: Fig. 1 design (Amber Kleiner); code written with Claude
      under the authors' direction and review.
- [ ] Code links: the footer and the swing-set links point to https://github.com/sttawm/phrase-rl;
      change them if the code moves.

## What is here

`index.html` (the page), `assets/` (charts, scene thumbnails, eleven rollout-grid clips with poster
frames), `rules.html` (rule snapshots), `survey/` (static replica of the human-phrasing survey with the
task clips respondents saw).
