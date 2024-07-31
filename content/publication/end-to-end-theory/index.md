---
title: 'End-to-End Learning of User Equilibrium with Implicit Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yafeng Yin




date: '2024-07-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: 'submitted'
#publication_short: In *Transportation Research Part C*

abstract: 'This paper establishes an end-to-end learning framework for constructing transportation network equilibrium models. The proposed framework directly learns supply and demand components as well as equilibrium states from multi-day traffic state observations. Specifically, it parametrizes unknown model components with neural networks and embeds them in an implicit layer to enforce user equilibrium conditions. By minimizing the differences between the predicted and observed traffic states, parameters for supply and demand components are simultaneously estimated. We demonstrate that the end-to-end framework is expressive: when parametrized with sufficiently large neural networks, it can replicate any unique, differentiable equilibrium state that solves a well-posed variational inequality. Moreover, it can generalize to new, unseen data when trained with sufficient observations. For efficient training, we design an auto-differentiation-based gradient descent algorithm that handles link-and path-based user equilibrium constraints and ensures local convergence. The proposed framework is demonstrated using three synthesized datasets.'

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - End-to-end Learning of User Equilibrium

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4908029'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
