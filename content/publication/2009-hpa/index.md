---
title: "Horizontal Pod Autoscaling in Kubernetes for Elastic Container Orchestration"
authors:
- admin
- Yu-jin Yeom
- Taehong Kim
- Dae-Heon Park
- Sehan Kim
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-07-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Sensors"
publication_short: ""

abstract: Kubernetes, an open-source container orchestration platform, enables high availability and scalability through diverse autoscaling mechanisms such as Horizontal Pod Autoscaler (HPA), Vertical Pod Autoscaler and Cluster Autoscaler. Amongst them, HPA helps provide seamless service by dynamically scaling up and down the number of resource units, called pods, without having to restart the whole system. Kubernetes monitors default Resource Metrics including CPU and memory usage of host machines and their pods. On the other hand, Custom Metrics, provided by external software such as Prometheus, are customizable to monitor a wide collection of metrics. In this paper, we investigate HPA through diverse experiments to provide critical knowledge on its operational behaviors. We also discuss the essential difference between Kubernetes Resource Metrics (KRM) and Prometheus Custom Metrics (PCM) and how they affect HPA’s performance. Lastly, we provide deeper insights and lessons on how to optimize the performance of HPA for researchers, developers, and system administrators working with Kubernetes in the future.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Edge Computing
- Kubernetes
- Horizontal Pod Autoscaling
- Cloud Computing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.mdpi.com/1424-8220/20/16/4621#'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Kubernetes HPA''s Architecture'
  focal_point: ""
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
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
