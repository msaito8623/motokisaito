---
title: "Tracing patterns of meaning in Japanese writing systems"

event: Tracing patterns across modalities --- similarities and differences in speaking, writing and signing (at the 48th annual meeting of the German Linguistic Society; DGfS)
event_url: https://tracingpatterns.phil.hhu.de/

location: University of Trier
address:
  street: Universitätsring 15
  # region: 
  postcode: '54296 Trier'
  # city: 
  country: Germany

# Displayed as a short summary in the overview page:
summary: 

# Will be displayed on the individual page:
# Turning off this option will also remove "Event" and "Location".
abstract: Semantics (co-)determines how Japanese words are written.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-02-24T00:00:00+0100' # "+0100" is the German standard (winter) time.
# date_end: '2030-06-01T15:00:00+0100'
all_day: true 

# Schedule page publish date (NOT talk date).
publishDate: '2024-11-02T00:00:00+0100'

authors:
  - admin

tags: ['Semantics', 'Discriminative Learning', 'Japanese', 'Orthography'] # The first tag shows up in the landing page.

# Is this a featured talk? (true/false)
featured: false 

image:
  caption: 'Image credit: [**Unsplash**](https://tracingpatterns.phil.hhu.de/)'
  focal_point: Right

# #links:
# #  - icon: twitter
# #    icon_pack: fab
# #    name: Follow
# #    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'uploads/20251031_Taiwan_slides.pdf'
# url_video: 'https://youtube.com'
# url_slides: 'uploads/20250307_DGfS_Slides_withoutAppendix.pdf'

# # Markdown Slides (optional).
# #   Associate this talk with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: ""

# # Projects (optional).
# #   Associate this post with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
# #   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!--- Comment out to display a highlighted block of text:
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}
-->

<!---
Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
-->


## Abstract:
Is meaning expressed in the details of the realization of words? This is some evidence that this is true (Schmitz & Baer-Henney, 2024, Berg et al., 2023). This leads one to expect that this should also hold for writing systems.

We focused on Japanese, which mixes three different writing systems. We hypothesized that if the choice of a writing system is affected by the meaning, we can predict a writing system of a word given its meaning.

We collected 383392 words from the Japanese CHILDES corpora (Miyata, 2012). For each word a contextualized embedding was calculated (Devlin et al., 2018). We tested our hypothesis by training a DLM model (Baayen et al., 2019) to predict the writing system of a word on the basis of its meaning.

The prediction accuracy of the model was 94.6%, and an LDA was performed to predict the writing system of each word given its meaning (Figure 1). Our analyses show that semantics has information affecting a word’s writing system.

![abcde](20250829_lda.png)

Figure 1: Coefficients of the LDA analysis. The red data points represent words written in kanji. The turquoise data points are words written in hiragana. The yellow-brown data points are words written in katakana.


## Notes:

This is a presentation about semantic effects on Japanese writing systems with Prof. Dr. Ruben van de Vijver (University of Düsseldorf).

