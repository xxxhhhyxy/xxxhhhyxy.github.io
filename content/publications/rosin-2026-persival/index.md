---
title: 'PerSiVal: Deep Neural Networks for Pervasive Simulation of An Activation-Driven Continuum-Mechanical Upper Limb Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- David Rosin
- Johannes Kässinger
- Xingyao Yu
- Michael Sedlmair
- Okan Avci
- Christian Bleiler
- Oliver Röhrle

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-01-10T00:00:00Z'
doi: 'https://doi.org/10.1007/s11517-026-03519-x'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Medical & Biological Engineering & Computing*
#publication_short: In *ACM CHI*

abstract: This paper introduces a novel densely connected neural network architecture designed for the pervasive visualisation of musculoskeletal system simulations. These simulations are built upon continuum-mechanical frameworks, which effectively integrate the diverse structural and physiological properties of the musculoskeletal system. A significant drawback of continuum-mechanical musculoskeletal models is their substantial computational resource requirement, making them difficult to transfer to/visualise the results on resource-poor systems like augmented reality or mobile devices. Such technologies, however, will be crucial for future advancements in human-machine interaction, surgical support tools, or physiotherapy. We use an activation-driven five-muscle continuum-mechanical upper limb model to obtain the activation-induced deformations of the respective muscles. Exemplified on the m. biceps brachii, we fit a sparse grid surrogate to capture the surface deformation and train a deep learning model that is subsequently used in our real-time visualisation. Based on the activation levels of the five muscles, the result of our trained neural network leads to an average positional error of 0.97±0.16 mm, or 0.57±0.10% for the 2809 mesh nodes of the m. biceps brachii’s surface. With the novel deep neural network model, we achieved evaluation times for the m. biceps brachii’s surface deformation of 9.88 ms on CPU-only architectures and 3.48 ms on architectures with GPU support. This leads to theoretical frame rates of 101 fps and 287 fps, respectively. The combination of surrogates and deep neural networks presented here succeeds as a proof-of-concept for real-time visualisation of a complex musculoskeletal system model, and does not rely on the inherent characteristics of the musculoskeletal system, and, hence, is also applicable to other real-time visualisations of complex meshed models in other applications.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - On-Body Visualization

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: './rosin-2026-persival.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
