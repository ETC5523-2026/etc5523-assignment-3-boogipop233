# COVID-19 Evidence Explained

A personal Quarto website by Xijun Wei for ETC5523: Communicating with Data at Monash University.

- **Author:** Xijun Wei
- **GitHub:** <https://github.com/Boogipop233>

## Intended audience

This blog is for non-specialist readers interested in public health who know the basics of COVID-19, vaccination and quarantine and want to understand how these measures affect border and community risk.

## Website content

- `index.qmd`: the homepage and article listing.
- `about.qmd`: the author's biography, circular portrait and GitHub link.
- `posts/vaccination-border-quarantine/index.qmd`: the article, including a figure, table, cross-references and academic citations.
- `_quarto.yml` and `styles.css`: shared site configuration and visual design.
- `_site/`: the rendered HTML website.

## Evidence and references

The article adapts the Assignment 2 report on Zachreson et al. (2022). Its figure and table select published model outputs from Figure 3 of that paper. The relative exposures are multiplied by 100 and rounded for display, with the unvaccinated pre-Delta benchmark set to 100. They are exposure indices, not case counts or outbreak probabilities. No new epidemiological simulations were conducted.

The article folder contains `figure-data.csv`, the SVG chart, and bibliographic metadata in `references.bib` and `references.json`. Quarto uses the JSON metadata and `apa.csl` to format APA seventh-edition citations. The CSL file comes from the [Citation Style Language repository](https://github.com/citation-style-language/styles/blob/master/apa.csl) and retains its embedded CC BY-SA licence.

He et al. (2021), DOI `10.1002/mco2.95`, provides background on Delta. Torres et al. (2022), DOI `10.1002/jmv.27799`, provides a population-specific example of breakthrough infections among nursing-home residents. Zachreson et al. (2022), DOI `10.1126/sciadv.abm3624`, remains the source of the model comparisons.

## Communication and design

The article introduces the research through travel and community risk, then uses selected comparisons to explain vaccine efficacy, viral transmissibility and community coverage. The conclusion returns to the opening question. Source notes and qualifications accompany the evidence.

The site uses a warm off-white background, dark teal headings, consistent navigation and responsive layouts. Directly labelled bars, a common baseline and an interpretation column support comparisons. Reading width and spacing are increased on desktop, while smaller screens adapt to available space.

## Build

```powershell
quarto preview
```

```powershell
quarto render
```

## Generative AI declaration

I did not use generative AI tools in preparing this assignment.
