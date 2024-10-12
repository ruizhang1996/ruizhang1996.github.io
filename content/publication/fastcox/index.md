---
title: "FastSurvival: Hidden Computational Blessings in Training Cox Proportional Hazards Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiachang Liu<sup>*</sup>
- admin<sup>*</sup>
- Cynthia Rudin

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems (NeurIPS), 2024*
publication_short: In *NeurIPS 2024*

abstract: Survival analysis is an important research topic with applications in healthcare, business, and manufacturing. One essential tool in this area is the Cox proportional hazards (CPH) model, which is widely used for its interpretability, flexibility, and predictive performance. However, for modern data science challenges such as high dimensionality (both n and p) and high feature correlations, current algorithms to train the CPH model have drawbacks, preventing us from using the CPH model at its full potential. The root cause is that the current algorithms, based on the Newton method, have trouble converging due to vanishing second order derivatives when outside the local region of the minimizer. To circumvent this problem, we propose new optimization methods by constructing and minimizing surrogate functions that exploit hidden mathematical structures of the CPH model. Our new methods are easy to implement and ensure monotonic loss decrease and global convergence. Empirically, we verify the computational efficiency of our methods. As a direct application, we show how our optimization methods can be used to solve the cardinality-constrained CPH problem, producing very sparse high-quality models that were not previously practical to construct. We list several extensions that our breakthrough enables, including optimization opportunities, theoretical questions on CPH's mathematical structure, as well as other CPH-related applications.
# Summary. An optional shortened abstract.
summary: We propose new optimization methods by constructing and minimizing surrogate functions that exploit hidden mathematical structures of the CPH model, producing very sparse high-quality models that were not previously practical to construct.

tags: 
- optimization
- cox
- survival analysis
- interpretability

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
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

