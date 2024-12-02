---
title: "Comparative Analysis of Multi-Agent Reinforcement Learning Policies for Crop Planning Decision Support"
authors:
- admin
- Shreya Hegde
- Ethan Shay
- Daniel Wu
- Aviva Prins
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: >
'In India, the majority of farmers are classified as small or marginal, making their livelihoods particularly vulnerable to economic losses due to market saturation and climate risks. Effective crop planning can significantly impact their expected income, yet existing decision support systems (DSS) often provide generic recommendations that fail to account for real-time market dynamics and the interactions among multiple farmers. In this paper, we evaluate the viability of three multi-agent reinforcement learning (MARL) approaches for optimizing total farmer income and promoting fairness in crop planning: Independent Q-Learning (IQL), where each farmer acts independently without coordination, Agent-by-Agent (ABA), which sequentially optimizes each farmer's policy in relation to the others, and the Multi-agent Rollout Policy, which jointly optimizes all farmers' actions for global reward maximization. Our results demonstrate that while IQL offers computational efficiency with linear runtime, it struggles with coordination among agents, leading to lower total rewards and an unequal distribution of income. Conversely, the Multi-agent Rollout policy achieves the highest total rewards and promotes equitable income distribution among farmers but requires significantly more computational resources, making it less practical for large numbers of agents. ABA strikes a balance between runtime efficiency and reward optimization, offering reasonable total rewards with acceptable fairness and scalability. These findings highlight the importance of selecting appropriate MARL approaches in DSS to provide personalized and equitable crop planning recommendations, advancing the development of more adaptive and farmer-centric agricultural decision-making systems.'

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example

#This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
---
