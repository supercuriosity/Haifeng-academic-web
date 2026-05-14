---
title: 'GPT4D: Generative Pre-training Transformer with Next-Scale Spatio-temporal Token Prediction for 4D Human Action Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiuming Liu*
  - Haifeng Sun*
  - Wentao Le*
  - Mengmeng Liu
  - Xuyi Hu
  - Per Ola Kristensson
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-03-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In submission to *NeurIPS 2026*
publication_short: In submission to *NeurIPS 2026*

abstract: 4D human point cloud videos capture both spatial geometry and temporal dynamics, revealing how people understand and interact with the evolving physical world. However, the inherent irregularity and sparsity of point clouds pose significant challenges to designing effective 4D backbones. Furthermore, existing supervised methods commonly suffer from labor-intensive 4D annotations. To address these challenges, we develop GPT4D, leveraging Generative Pre-training Transformers to autoregressively extract 4D spatio-temporal features for human action recognition. Compared to existing self-supervised approaches that resort to complicated contrastive learning or knowledge distillation, our method revisits GPT-style pre-training by simply serializing 4D tokens and then reconstructing original sequences through a generative extractor-generator pipeline. To capture multi-granularity dynamics, we also design a Next-Scale Motion Token Prediction strategy that progressively generates more fine-grained spatio-temporal structures from coarser ones. Compared to prior self-supervised methods, our GPT4D achieves state-of-the-art performance on both human action recognition (with 3.12% in MSR-Action3D), and gesture recognition tasks (with 3.7% 
 in SHREC'17 and 0.5% in NvGesture). We also demonstrate its promising semi-supervised learning potential. Only using half of the training set on large-scale NTU-RGBD dataset, our method still achieves 88.6% accuracy. In addition, GPT4D generalizes surprisingly well when transferred to different tasks. Code will be released upon publication.

# Summary. An optional shortened abstract.
summary: GPT4D is an autoregressive generative framework that reformulates 4D point cloud video understanding as next-token prediction, integrating long-range motion priors with local geometric details to achieve state-of-the-art performance on human action recognition benchmarks.

tags:
  - 4D point cloud understanding
  - human action recognition
  - Generative Pre-training Transformer
  - Next-Scale Motion Token Prediction
  - Spatial-Temporal Modeling


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/supercuriosity'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

