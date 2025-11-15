---
title: '$L_0$-Sampler: An $L_0$ Model Guided Volume Sampling for NeRF'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Juyong Zhang

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition 2024 (pp. 21390-21400)
publication_short: In CVPR 2024

abstract: Since its proposal, Neural Radiance Fields (NeRF) has achieved great success in related tasks, mainly adopting the hierarchical volume sampling (HVS) strategy for volume rendering. However, the HVS of NeRF approximates distributions using piecewise constant functions, which provides a relatively rough estimation. Based on the observation that a well-trained weight function $w(t)$ and the $L_0$ distance between points and the surface have very high similarity, we propose $L_0$-Sampler by incorporating the $L_0$ model into $w(t)$ to guide the sampling process. Specifically, we propose using piecewise exponential functions rather than piecewise constant functions for interpolation, which can not only approximate quasi-$L_0$ weight distributions along rays quite well but can be easily implemented with a few lines of code change without additional computational burden. Stable performance improvements can be achieved by applying $L_0$-Sampler to NeRF and related tasks like 3D reconstruction. 

# Summary. An optional shortened abstract.
summary: We propose $L_0$-Sampler, a NeRF sampling strategy that replaces piecewise constant functions through better approximating $L_0$-like weight distributions, achieving stable improvements in rendering and 3D reconstruction with minimal code changes.
tags:
  - Volume Rendering

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/USTC3DV/L0-Sampler-code'
url_dataset: ''
url_poster: ''
url_project: 'https://ustc3dv.github.io/L0-Sampler/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=uBc1kqpXq9M'

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

<!-- the following parts need to change -->
<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
