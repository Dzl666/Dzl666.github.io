---
title: '(BMVC 2025 Oral) MonoTracker: Monocular RGB-Only 6D Tracking of Unknown Object'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shaochang Tan
  - Zuria Bauer
  - Daniel Barath
  - Marc Pollefeys

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The Thirty Sixth British Machine Vision Conference*
publication_short: In *BMVC*

abstract: Estimating the six degrees of freedom (6D) pose of unknown objects using only monocular RGB images is a challenging task, especially when dealing with textureless and small objects. In this paper, we propose a novel pipeline, MonoTracker, for 6D object pose estimation and tracking that operates without any prior depth information. MonoTracker is a model-free, RGB-only, 6D detector that works on unseen objects. It leverages state-of-the-art pre-trained deep learning models, enabling zero-shot 6D pose estimation by jointly optimizing object poses and correcting scale inconsistencies in monocular depth predictions. We validate our method on three public datasets -- YCBInEOAT, HO3D, and BEHAVE -- demonstrating significant improvements over the state of the art. As a downstream application, we also show that the estimated camera poses can be used as input in NeRF pipelines, facilitating novel-view synthesis. Our results highlight the potential of monocular RGB inputs for accurate 6D object tracking and reconstruction in real-world scenarios. The code will be made public.

# Summary. An optional shortened abstract.
summary: Pose estimation and reconstruction of tiny, texture-less moving objects with RGB images and camera intrinsic as input;	Estimated object poses by a robust optimizer with mono-depth predictions with noisy and inconsistent scales; Reconstruction and post-refinement of the scale factors and poses during NeRF training.


tags:
  - 6D Pose Estimation
  - Object Reconstruction

# Display this page in the Featured widget?
featured: true

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
