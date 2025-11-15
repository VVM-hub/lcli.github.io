---
title: 'Shape from Semantics: 3D Shape Generation from Multi-View Semantics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Caoliwen Wang
  - Yuqi Zhou
  - Bailin Deng
  - Juyong Zhang



# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2025-05-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint 2510.01640
publication_short: Arxiv Preprint 2510.01640

abstract: Existing 3D reconstruction and generation methods utilize guidances such as 2D images, shape contours and single semantics to recover the 3D models, which limits the creative exploration of 3D modeling for art and design. In this paper, we propose a novel 3D modeling task called ``Shape from Semantics'', which aims to create 3D models whose geometry and appearance are consistent with the given text semantics when viewed from different views. The reconstructed 3D models incorporate more than one semantic elements and are easy for observers to distinguish. We adopt generative models as priors and disentangle the connection between geometry and appearance to accomplish this challenging task. Specifically, we propose Local Geometry-Aware Distillation (LGAD), a strategy that employs multi-view normal-depth diffusion priors to complete partial geometries, ensuring realistic shape generation. We also integrate view-adaptive guidance scales to enable smooth semantic transitions across views. For appearance modeling, we adopt physically based rendering to generate high-quality material properties, which are subsequently baked into fabricable meshes. Extensive experimental results demonstrate that our method can generate meshes with well-structured, intricately detailed geometries, coherent textures, and smooth transitions, resulting in visually appealing 3D shape designs.

# Summary. An optional shortened abstract.
summary: We introduce "Shape from Semantics," a novel 3D modeling task that generates fabricable 3D shapes whose geometry and appearance are directly guided by and consistently reflect multiple text semantics across views.
tags:
  - 3D Generation
  - 3DGS
  - Score Distillation Sampling
  - Multi-view Art

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
