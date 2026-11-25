# Contributing

Thank you for your interest in contributing to COSIG! COSIG is designed to be a constantly-expanding, open source handbook for performing post publication peer review. Each guide can be downloaded [invididually as a PDF](https://osf.io/2kdez/files/osfstorage) and can stand on its own. A combined PDF with all guides included can be downloaded [here](https://osf.io/ynb8j).

If you have suggestions for a new guide, requested revisions or additions to an existing guide (including fixing typos) or questions, please [open an issue](https://github.com/reeserich/cosig/issues) and assign it a corresponding label. Before beginning work on a guide, check if an issue already exists, where others might have shared that they are already working on it.

COSIG's maintainers will evaluate all contributions and decide what to merge into the official COSIG version.

Contributors to COSIG are listed by name or pseudonym at the start of the full COSIG handbook. Note that this is not an authorship list in same style as an academic article; it is a way to thank and give credit to those that gave time to expand COSIG, equivalent to the contributors page on a open source software project ([example](https://github.com/rails/rails/graphs/contributors)). Those that contribute to COSIG are not responsible for all of COSIG's content. Please contact [admin@cosig.net](mailto:admin@cosig.net) to specify how you would like to be credited, providing your [ORCiD](https://orcid.org/) if available. If submitting a Pull Request, put this information in the description.

# Content and terminology

Guides should provide examples of lessons from the guide being applied to real published articles, such as PubPeer comments.
If there are no examples of retractions or at least expressions of concern due to a specific problem, that problem is likely not important enough for a COSIG guide.

Wherever possible, readers should be directed towards additional resources.

Use "venue" when referring to anywhere papers are published are published to encompass journals, conferences, and workshops, since different fields have different expectations in terms of what should be published where.
Only use a specific kind of venue when advice is truly specific to that venue, or when noting an exception such as workshop papers typically being shorted which can influence some red or green flags.

Try to use "article" when referring to scientific publications and "manuscript" when referring to papers that have been prepared or submitted but are not yet published.

Usually, the most accurate and most neutral way to describe problems in an article is "problematic", as opposed to "fraudulent", "bogus", "fake", etc.

# LaTeX

COSIG is compiled using [pdfLaTeX](https://www.math.rug.nl/~trentelman/jacob/pdflatex/pdflatex.html) in [Overleaf](https://www.overleaf.com/). Contributors to COSIG that are not familiar with writing in LaTeX but would like to contribute should consult a maintainer, who can help format your contribution appropriately (get in touch at admin@cosig.net).

# Style

A .tex template for guides is available [here](https://github.com/reeserich/cosig/blob/main/tex/_template.tex). Guides should be written in a neutral and professional tone for a diverse audience. 

For highly specialized guides (e.g., [verifying nucleotide sequence reagents](https://osf.io/2egvz)), it is helpful to provide background information for those new to the topic but not necessary to start from the very beginning of a topic (e.g., by explaining the [central dogma of molecular biology](https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology)). 

Text and graphics that are lifted from other sources should be appropriately attributed with a direct link (e.g., "Adapted from Figure S1 of [Zhang et al. (2023)](https://doi.org/10.1073/pnas.2302491120)"). 

If including images in a guide, try to make the image files as small as possible to reduce the PDF file size. Consider using [PNGOUT](https://advsys.net/ken/utils.htm) to losslessly compress .png figures. Wherever possible, use .pdf format for graphs.

If multiple terms are commonly used to refer to the same thing (e.g., [EDX/EDS/EDAX](https://osf.io/shfjy)), try to list as many as possible. Acronyms and initialisms should be written out in full the first time they are used.

Guides should link to other guides where appropriate. Contributors should avoid creating multiple guides on closely-related topics and should condense guides wherever possible.

The "Last updated" date at the start of a guide should reflect the last date of *any change* to the guide, including copy-editing changes. The "Last updated" date for COSIG as a whole should be equivalent to the most recent "Last updated" date for all guides.

Figures and tables should appear on the page immediately after the corresponding text section. This may require some `\pagebreak` commands to coax LaTeX into compiling correctly.
