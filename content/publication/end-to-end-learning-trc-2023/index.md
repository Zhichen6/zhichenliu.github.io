---
title: 'End-to-end learning of user equilibrium with implicit neural networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yafeng Yin
  - Fan Bai
  - Donald K Grimm



date: '2023-05'
doi: '10.1016/j.trc.2023.104085'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: 'In *Transportation Research Part C: Emerging Technologies*'
#publication_short: In *Transportation Research Part C*

abstract: This paper intends to transform the transportation network equilibrium modeling paradigm via an “end-to-end” framework that directly learns travel choice preferences and the equilibrium state from multi-day link flow observations. The centerpiece of the proposed framework is to use deep neural networks to represent travelers’ route choice preferences and then encapsulate the neural networks in a variational inequality that prescribes the user equilibrium flow distribution. The proposed neural network architecture ensures the existence of equilibrium and accommodates future changes in road network topology. The variational inequality is then embedded as an implicit layer in a learning framework, which takes the context features (e.g., road network and traveler characteristics) as input and outputs the user equilibrium flow distribution. By comparing computed equilibrium flows with observed flows, the neural networks can be trained. The proposed end-to-end framework is demonstrated and validated using synthesized data for the Sioux Falls network.

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

url_pdf: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4198835'
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
