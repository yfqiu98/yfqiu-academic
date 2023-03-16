---
title: "Position-Aware Neural Attentive Graph Networks for Multi-hop Question Answering
"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anda Zhou
- Ege Ersü

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-10-06T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: Techical Report
publication_short: Techical Report

abstract: Recently, graph neural networks (GNN) based multi-hop question answering (QA) has been studied extensively, as such graph representation can express rich dependencies in language explicitly. However, graph representation suffers from the loss of sequential information, and hardness in representing global semantic information with specific to downstream tasks. In this work, we propose the \textit{query-attention mechanism} to enhance the GNN-QA system by utilizing both global and local contextual information. We also explore injecting the positional information into the graph as to complement the sequential information. We experiment our idea in Entity Relational-Graph Convolutional Networks \cite{decao2019questionansweringRGCN} on part of WikiHop dataset. We identify the existence of \textit{position bias} in the dataset, and the experiment results with ablation study confirmed that our proposed modules improve baseline to achieve higher generalization accuracy with 1.43\%.

# # Summary. An optional shortened abstract.
# summary: We propose a novel architecture

tags: [Question Answering]

# Display this page in the Featured widget?
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://arxiv.org/abs/2203.10232'
url_pdf: 'mlp_cw4.pdf'
url_code: 'https://github.com/yfqiu98/Multihop-GNN'
# url_dataset: 'https://github.com/baidu/DuReader/tree/master/DuReader-Retrieval'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - Summarization

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
