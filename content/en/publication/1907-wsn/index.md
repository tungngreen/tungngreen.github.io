---
title: 'Distributed TDMA Scheduling Using Topological Ordering in Wireless Sensor Networks'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Linh-An Phan
  - Taejoon Kim
  - Taehong Kim
  - JaeSeang Lee
  - JaeHyun Ham

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2019-07-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 28th International Conference on Computer Communication and Networks (ICCCN 2019)*
publication_short: In *The 28th International Conference on Computer Communication and Networks (ICCCN 2019)*

abstract: Edge Video Analytics (EVA) has gained significant attention as a major application of pervasive computing, enabling real-time visual processing. EVA pipelines, composed of deep neural networks (DNNs), typically demand efficient inference serving under stringent latency requirements, which is challenging due to the dynamic Edge environments (e.g., workload variability and network instability). Moreover, EVA pipelines also face significant resource contention caused by resource (e.g., GPU) constraints at the Edge. In this paper, we introduce OCTOPINF, a novel resource-efficient and workload-aware inference serving system designed for real-time EVA. OCTOPINF tackles the unique challenges of dynamic edge environments through fine-grained resource allocation, adaptive batching, and workload balancing between edge devices and servers. Furthermore, we propose a spatiotemporal scheduling algorithm that optimizes the co-location of inference tasks on GPUs, improving performance and ensuring service-level objectives (SLOs) compliance. Extensive evaluations on a real-world testbed demonstrate the effectiveness of our approach. It achieves an effective throughput increase of up to 10x compared to the baselines and shows better robustness in challenging scenarios. OCTOPINF can be used for any DNN-based EVA inference task with minimal adaptation and is available at [https://github.com/tungngreen/PipelineScheduler](https://github.com/tungngreen/PipelineScheduler).

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- IoT Sensors
- Wireless Sensor Network
- Scheduling
- Topological Order

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/8847070'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Algorithm'
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
