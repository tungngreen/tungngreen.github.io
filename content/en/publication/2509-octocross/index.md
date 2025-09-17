---
title: 'OctoCross: Workload-Aware Request Offloading Scheduling in Cross-Camera Collaboration'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jinghan Cheng
  - admin
  - Lucas Liebe
  - Yuheng Wu
  - Nhat-Quang Tau
  - Pablo Espinosa
  - Dongman Lee

# Author notes (optional)

date: '2025-09-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 23rd International Conference on Service-Oriented Computing (ICSOC 2025, CORE A, acceptance rate 20%)*
publication_short: In *The 23rd International Conference on Service-Oriented Computing (ICSOC 2025, CORE A, acceptance rate 20%)*

abstract: Cross-camera collaboration is emerging as a crucial strategy to support dynamic and heterogeneous real-world workloads in real-time video analytics (VA) systems. However, existing offloading methods lack the capability to jointly model spatial and temporal dynamics, which limits their offloading accuracy, leading to low system performances. We propose OctoCross, a spatiotemporal offloading framework for request offloading in mutli-camera VA systems. OctoCross introduces a novel spatiotemporal model that can jointly learns spatial and temporal dynamics to produce an actionable offloading plan in an end-to-end manner. Extensive evaluations on real-world multi-camera datasets show that OctoCross achieves up to 5.8× higher throughput and 3.2× lower latency compared to baselines, while maintaining high SLO compliance across diverse deployment scenarios. Our code is available at https://github.com/tungngreen/PipelineScheduler/tree/OctoCross-ICSOC2025.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- video analytics,
- cross-camera collaboration
- spatiotemporal learning
- task offloadin


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'OctoCross''s System Architecture'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
