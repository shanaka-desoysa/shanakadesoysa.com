---
draft: false
title: "Reliable Adaptive Multipath Provisioning with Bandwidth and Differential Delay Constraints"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiyi Zhang
  - Jian Tang
  - Chonggang Wang
  - admin

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: "2010-03-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2010-05-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2010 Proceedings IEEE INFOCOM*
publication_short: In *INFOCOM 2010*

abstract: Robustness and reliability are critical issues in network management. To provide resiliency, a popular protection scheme against network failures is the simultaneous routing along multiple disjoint paths. Most previous protection and restoration schemes were designed for all-or-nothing protection and thus, an overkill for data traffic. In this work, we study the Reliable Adaptive Multipath Provisioning (RAMP) problem with reliability and differential delay constraints. We aim to route the connections in a manner such that link failure does not shut down the entire stream but allows a continuing flow for a significant portion of the traffic along multiple (not necessary disjoint) paths, allowing the whole network to carry sufficient traffic even when link/node failure occurs. The flexibility enabled by a multipath scheme has the tradeoff of differential delay among the diversely routed paths. This requires increased memory in the destination node in order to buffer the traffic until the data arrives on all the paths. Increased buffer size will raise the network element cost and could cause buffer overflow and data corruption. Therefore, differential delay between the multiple paths should be bounded by containing the delay of a path in a range. We first prove that RAMP is an NP-hard problem. Then we present a pseudo-polynomial time solution to solve a special case of RAMP, representing edge delays as integers. Next, an (1 + e)-approximation algorithm is proposed to solve the optimization version of the RAMP problem. An efficient heuristic is also provided for the RAMP problem. We also present numerical results confirming the advantage of our schemes as the first solution for the RAMP problem.

# Summary. An optional shortened abstract.
summary: We study the Reliable Adaptive Multipath Provisioning (RAMP) problem with reliability and differential delay constraints.

tags: ["Multipath Routing", "Reliability", "Differential Delay"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
  - name: IEEE Xplore
    url: https://ieeexplore.ieee.org/abstract/document/5462042
  - name: INFOCOM 2010
    url: https://ieeexplore.ieee.org/xpl/conhome/5461675/proceeding

url_pdf: "https://ieeexplore.ieee.org/abstract/document/5462042"
# url_code: ""
# url_dataset: ""
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: ""
# url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/Q1p7bh3SHj8)"
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
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
