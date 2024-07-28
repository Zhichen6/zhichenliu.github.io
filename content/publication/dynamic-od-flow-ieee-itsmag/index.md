---
title: 'Dynamic origin-destination flow prediction using spatial-temporal graph convolution network with mobile phone data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhiyuan Liu
  - Xiao Fu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-06-23T00:00:00Z'
doi: '10.1109/MITS.2021.3082397'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Transportation Systems Magazine*
#publication_short: In *ICW*

abstract: Massive mobile phone data provide continuous and large-scale dynamic origin–destination (OD) flow information for multiple modes of transportation. In this study, we represent the dynamic OD flows obtained from mobile phone data as time-dependent graphs and propose two novel spatial-temporal graph convolutional network (STGCN)-based models to predict dynamic OD flows. Both models directly operate on the graph-structured OD flows, capture correlations among OD flows far apart in the Euclidean space, and fully explore the complex spatial-temporal features. We first formulate OD flows as explicit edges that specify the travels between two locations and propose an edge-focused STGCN. The edge-focused STGCN applies a novel three-step strategy to effectively update edge features in large-scale graphs. Second, we formulate OD flows as vertices in graph and propose a vertex-focused STGCN. The vertex-focused STGCN infers the relations among OD flows by establishing an adjacency matrix based on the temporal similarity between OD flows. The proposed models were validated using real-world mobile phone data collected in Kunshan, China. OD flows in the next hour were predicted, and the mean absolute percent errors of the edge-focused STGCN and the vertex-focused STGCN were 1.755% and 1.672%, respectively; both were significantly lower than the current baseline models.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - AI-enabled Network Modeling

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'h'

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
