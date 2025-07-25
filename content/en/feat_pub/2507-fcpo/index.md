---
title: 'FCPO: Federated Continual Policy Optimization for Real-Time High-Throughput Edge Video Analytics'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: [admin, "Lucas Liebe (equally first)", "Dongman Lee"]

# Author notes (optional)
author_notes: ["*", "*", ""]


date: '2025-07-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: The growing complexity of Edge Video Analytics (EVA) facilitates new kind of intelligent applications, but creates challenges in real-time inference serving systems. State-of-the-art (SOTA) scheduling systems optimize global workload distributions for heterogeneous devices but often suffer from extended scheduling cycles, leading to sub-optimal processing in rapidly changing Edge environments. Local Reinforcement Learning (RL) enables quick adjustments between cycles but faces scalability, knowledge integration, and adaptability issues. Thus, we propose FCPO, which combines Continual RL (CRL) with Federated RL (FRL) to address these challenges. This integration dynamically adjusts inference batch sizes, input resolutions, and multi-threading during pre- and post-processing. CRL allows agents to learn from changing Markov Decision Processes, capturing dynamic environmental variations, while FRL improves generalization and convergence speed by integrating experiences across inference models. FCPO combines these via an agent-specific aggregation scheme and a diversity-aware experience buffer. Experiments on a real-world EVA testbed showed over 5 times improvement in effective throughput, 60\% reduced latency, and 20\% faster convergence with up to 10 times less memory consumption compared to SOTA RL-based approaches.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Inference Serving
  - Video Analytics
  - Continual Reinforcement Learning
  - Federated Reinforcement Learning
  - Dynamic Batching

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
  caption: 'FCPO''s learning architecture'
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
