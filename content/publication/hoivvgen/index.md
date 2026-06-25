---
title: 'HOI-VVGen: HOI Volumetric Video Generation by Bridging Generative Motion with Video Diffusion Priors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Leipeng Hu
  - Fei Zha
  - Lebin Zhu
  - Chengzhi Ye
  - Yudong Guo
  - Juyong Zhang



# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2026-01-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: Arxiv Preprint 2510.01640
# publication_short: Arxiv Preprint 2510.01640

abstract: Generating physically plausible volumetric videos of human-object interactions (HOI) from text remains a significant challenge. While recent motion generation methods excel at producing valid skeletal dynamics, they often lack integrated rendering capabilities, creating a substantial disconnect between kinematic motion and high-quality volumetric content. Conversely, video diffusion models generate impressive visuals but frequently suffer from hallucinated physics and temporal inconsistencies due to the absence of explicit 3D structural constraints. To bridge this gap, we present HOI-VVGen, a novel framework for high-fidelity volumetric video generation that harmonizes the structural control of generative motion priors with the rich visual priors of video diffusion models. Our approach treats 4D interaction as a decoupled yet synergistic process. We first generate interaction trajectories using a generative motion backbone, which subsequently drives decoupled 3D Gaussian Splatting (3DGS) representations for humans and objects. Crucially, to enforce spatial coherence and volumetric consistency, we introduce a hybrid strategy that distills geometric priors from pre-trained video diffusion models to optimize motions. Furthermore, to address the scarcity of high-quality HOI data, we introduce a comprehensive multi-view HOI dataset alongside a robust marker-free 4D reconstruction pipeline. Experiments demonstrate that HOI-VVGen outperforms existing baselines, producing 4D volumetric sequences that seamlessly combine physical plausibility with exceptional visual detail and temporal stability.

# Summary. An optional shortened abstract.
summary: We introduce HOI-VVGen, a framework for text-to-4D HOI volumetric video generation by combining 3D motion generation with video diffusion visual priors, and a newly introduced multi-view HOI dataset.
tags:
  - Human-Object Interaction
  - 3D Generation
  - 3DGS
  - Score Distillation Sampling
  - Dataset

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
