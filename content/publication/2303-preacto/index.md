---
title: 'PreActo: Efficient Cross-Camera Object Tracking System in Video Analytics Edge Computing'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Siyoung Jang
  - Boyan Kodstadinov
  - Dongman Lee

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-03-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 21rd International Conference on Pervasive Computing and Communications (PerCom 2023)*
publication_short: In *The 21rd International Conference on Pervasive Computing and Communications (PerCom 2023)*

abstract: Cross-camera real-time object tracking is one of the important, yet challenging applications of video analytics in edge computing environments. To provide accurate and efficient real-time tracking, a tracking target''s future movements need to be predicted. Particularly, the destination camera and travel time of the target object are to be identified so that tracking duties can be handover-ed seamlessly. In this paper, we propose a collaborative cross-camera tracking system, called PreActo, with two key features (1) ResNet-based trajectory learning to exploit the rich spatio-temporal information embedded within objects'' moving patterns, which has not been utilized by the existing literature, and (2) collaboration between the edge server and the edge device for real-time trajectory prediction and tracking handover. To prove the validity of our proposed system, we evaluate PreActo on a video dataset leveraging real-world trajectories. Evaluation results show that the proposed system reduces up to 7× the number of processed frames for handover, with 2× lower latency while providing 1.5× tracking precision improvement compared to the state-of-the-art.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Cross-camera Tracking
  - Video Analytics
  - Multi-object Tracking

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
url_source: 'https://ieeexplore.ieee.org/document/10099298'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'PreActo''s Operational Architecture'
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
