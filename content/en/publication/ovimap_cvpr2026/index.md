---
title: '(CVPR 2026 Highlight) OVI-MAP: Open-Vocabulary Instance-Semantic Mapping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Federico Tombari
  - Marc Pollefeys
  - Johanna Wald
  - Daniel Barath

# Author notes (optional)
author_notes:
  - 
  - 
  -
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

abstract: Incremental open-vocabulary 3D instance-semantic mapping is essential for autonomous agents operating in complex everyday environments. However, it remains challenging due to the need for robust instance segmentation, real-time processing, and flexible open-set reasoning. Existing methods often rely on the closed-set assumption or dense per-pixel language fusion, which limits scalability and temporal consistency. We introduce OVI-MAP that decouples instance reconstruction from semantic inference. We propose to build a class-agnostic 3D instance map that is incrementally constructed from RGB-D input, while semantic features are extracted only from a small set of automatically selected views using vision-language models. This design enables stable instance tracking and zero-shot semantic labeling throughout online exploration. Our system operates in real time and outperforms state-of-the-art open-vocabulary mapping baselines on standard benchmarks. 

# Summary. An optional shortened abstract.
summary: 


tags:
  - Instance Mapping
  - Semantic Mapping
  - Open-Vocabulary

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2603.26541'
url_code: 'https://github.com/OVI-MAP/OVI-MAP'
url_dataset: ''
url_poster: ''
url_project: 'https://ovi-map.github.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Main Pipeline'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
