---
title: "‘under-reported’security defects in kubernetes manifests"
authors:
- Dibyendu Brinto Bose
- Akond Rahman
- admin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated pu*Journal of Source Themes, 1*(1)blication name.
publication: "2021 IEEE/ACM 2nd International Workshop on Engineering and Cybersecurity of Critical Systems (EnCyCriS)"
publication_short: ""

abstract: With the advent of the fourth industrial revolution, industry practitioners are moving towards container-based infrastructure for managing their digital workloads. Kubernetes, a container orchestration tool, is reported to help industry practitioners in automated management of cloud infrastructure and rapid deployment of software services. Despite reported benefits, Kubernetes installations are susceptible to security defects, as it occurred for Tesla in 2018. Understanding how frequently security defects appear in Kubernetes installations can help cybersecurity researchers to investigate security-related vulnerabilities for Kubernetes and generate security best practices to avoid them. In this position paper, we first quantify how frequently security defects appear in Kubernetes manifests, i.e., configuration files that are use to install and manage Kubernetes. Next, we lay out a list of future research directions that researchers can pursue. We apply qualitative analysis on 5,193 commits collected from 38 open source repositories and observe that 0.79% of the 5,193 commits are security-related. Based on our findings, we posit that security-related defects are under-reported and advocate for rigorous research that can systematically identify undiscovered security defects that exist in Kubernetes manifests. We predict that the increasing use of Kubernetes with unresolved security defects can lead to large-scale security breaches.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: https://arxiv.org/pdf/2006.15275.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
