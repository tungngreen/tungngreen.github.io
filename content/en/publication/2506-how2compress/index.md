---
title: 'How2Compress: Scalable and Efficient Edge Video Analytics via Adaptive Granular Video Compression'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuheng Wu
  - admin
  - Lucas Liebe
  - Nhat-Quang Tau
  - Pablo Espinosa
  - Jinghan Cheng
  - Dongman Lee

# Author notes (optional)

date: '2025-07-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 33rd ACM International Conference on Multimedia (MM 2025, CORE A\*)*
publication_short: In *The 33rd ACM International Conference on Multimedia (MM 2025, CORE A\*)*

abstract: With the rapid proliferation of the Internet of Things, video analytics has become a cornerstone application in wireless multimedia sensor networks. To support such applications under bandwidth constraints, learning-based adaptive quantization for video compression have demonstrated strong potential in reducing bitrate while maintaining analytical accuracy. However, existing frameworks often fail to fully exploit the fine-grained quality control enabled by modern blockbased video codecs, leaving significant compression efficiency untapped. In this paper, we present How2Compress, a simple yet effective framework designed to enhance video compression efficiency through precise, fine-grained quality control at the macroblock level. How2Compress is a plug-and-play module and can be seamlessly integrated into any existing edge video analytics pipelines. We implement How2Compress on the H.264 codec and evaluate its performance across diverse real-world scenarios. Experimental results show that How2Compress achieves up to 50.4% bitrate savings and outperforms baselines by up to 3.01× without compromising accuracy, demonstrating its practical effectiveness and efficiency. Code is available at link and a reproducible docker image at link.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- video analytics,
- video compression,
- video streaming


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
  caption: 'OctopInf''s Operational Architecture'
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
