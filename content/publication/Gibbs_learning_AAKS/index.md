---
title: "Sample-efficient learning of quantum many-body systems"
authors:
- Anurag Anshu
- Srinivasan Arunachalam
- Tomotaka Kuwahara
- admin
#date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ["1"]

# Publication name and optional abbreviated publication name.
#publication: In *Symposium on Theory of Computing (FOCS) 2020*
#publication_short: In *FOCS'20*

abstract: We study the problem of learning the Hamiltonian of a quantum many-body system given samples from its Gibbs (thermal) state. The classical analog of this problem, known as learning graphical models or Boltzmann machines, is a well-studied question in machine learning and statistics. In this work, we give the first sample-efficient algorithm for the quantum Hamiltonian learning problem. In particular, we prove that polynomially many samples in the number of particles (qudits) are necessary and sufficient for learning the parameters of a spatially local Hamiltonian in l_2-norm. Our main contribution is in establishing the strong convexity of the log-partition function of quantum many-body systems, which along with the maximum entropy estimation yields our sample-efficient algorithm. Classically, the strong convexity for partition functions follows from the Markov property of Gibbs distributions. This is, however, known to be violated in its exact form in the quantum case. We introduce several new ideas to obtain an unconditional result that avoids relying on the Markov property of quantum systems, at the cost of a slightly weaker bound. In particular, we prove a lower bound on the variance of quasi-local operators with respect to the Gibbs state, which might be of independent interest. Our work paves the way toward a more rigorous application of machine learning techniques to quantum many-body problems.

# Summary. An optional shortened abstract.
summary:   

#tags:
#- Source Themes
#featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2004.07266
url_pdf: http://arxiv.org/pdf/2004.07266.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: '/pdf/talks/counting_without_sampling_caltech.pdf'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  #focal_point: ""
  #preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
