---
title: 'MetaWeather: Few-Shot Weather-Degraded Image Restoration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Youngrae Kim*
  - Younggeol Cho*
  - admin
  - Seunghoon Hong
  - Dongman Lee

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 18th European Conference on Computer Vision ECCV 2024 (ECCV 2024)
publication_short: The 18th European Conference on Computer Vision ECCV 2024 (ECCV 2024)

abstract: Real-world weather conditions are intricate and often occur concurrently. However, most existing restoration approaches are limited in their applicability to specific weather conditions in training data and struggle to generalize to unseen weather types, including real-world weather conditions. To address this issue, we introduce MetaWeather, a universal approach that can handle diverse and novel weather conditions with a single unified model. Extending a powerful meta-learning framework, MetaWeather formulates the task of weather-degraded image restoration as a few-shot adaptation problem that predicts the degradation pattern of a query image, and learns to adapt to unseen weather conditions through a novel spatial-channel matching algorithm. Experimental results on the BID Task II.A, SPA-Data, and RealSnow datasets demonstrate that the proposed method can adapt to unseen weather conditions, significantly outperforming the state-of-the-art multi-weather image restoration methods. Code is available at https://github.com/RangeWING/MetaWeather.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Meta Learning
  - Image Restoration
  - Few-shot Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/RangeWING/MetaWeather'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://eccv.ecva.net/virtual/2024/poster/2530'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'MetaWeathe''s Architecture'
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
