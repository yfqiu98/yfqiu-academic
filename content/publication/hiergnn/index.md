---
title: "Abstractive Summarization Guided by Latent Hierarchical Document Structure
"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shay Cohen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 2022 Conference on Empirical Methods in Natural Language Processing*
publication_short: In *EMNLP 2022*

abstract: In this paper, we present DuReader-retrieval, a large-scale Chinese dataset for passage retrieval. DuReader-retrieval contains more than 90K queries and over 8M unique passages from Baidu search. To ensure the quality of our benchmark and address the shortcomings in other existing datasets, we (1) reduce the false negatives in development and testing sets by pooling the results from multiple retrievers with human annotations, (2) and remove the training queries that are semantically similar to the development and testing queries. Additionally, we provide two out-of-domain testing sets for cross-domain evaluation, as well as a cross-lingual set that has been manually translated for cross-lingual retrieval. The experiments demonstrate that DuReader-retrieval is challenging and there is still plenty of room for improvement, e.g. salient phrase and syntax mismatch between query and paragraph. These experimental results show that the dense retriever does not generalize well across domains, and cross-lingual retrieval is essentially challenging. DuReader-retrieval is publicly available.

# Summary. An optional shortened abstract.
summary: We propose a large-scale Chinese passage retrieval dataset. We mainly try to improve the problems that exist in popular English dataset, such as false negatives and testing data leakage, which have been proved to hinder the evaluation of neural retrieval models based on pre-trained language models. In addition, we select and provide two out-of-domain evaluation sets and a Chinese-English cross-lingual retrieval set to facilitate the evaluation of corresponding subtasks. Experiments and analyses of baselines show that passage retrieval is still challenging, e.g., weak domain generalization, factual consistency, grammatical consistency, etc. are still challenging for the recent neural retrieval models.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2203.10232'
url_code: 'https://github.com/baidu/DuReader/tree/master/DuReader-Retrieval'
url_dataset: 'https://github.com/baidu/DuReader/tree/master/DuReader-Retrieval'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Summarization

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
