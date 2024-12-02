---
title: What should we grow today to make money tomorrow?

event: Undergraduate Research Technology Conference
event_url: https://urtc.mit.edu/

location: Massachusetts Institute of Technology
address:
  street: 32 Vassar St
  city: Cambridge
  region: MA
  postcode: '02139'
  country: United States

#summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: >
  In India, the majority of farmers are classified as small or marginal, making their livelihoods particularly vulnerable to economic losses due to market saturation and climate risks. Effective crop planning can significantly impact their expected income, yet existing decision support systems (DSS) often provide generic recommendations that fail to account for real-time market dynamics and the interactions among multiple farmers. In this paper, we evaluate the viability of three multi-agent reinforcement learning (MARL) approaches for optimizing total farmer income and promoting fairness in crop planning: Independent Q-Learning (IQL), where each farmer acts independently without coordination, Agent-by-Agent (ABA), which sequentially optimizes each farmer's policy in relation to the others, and the Multi-agent Rollout Policy, which jointly optimizes all farmers' actions for global reward maximization. Our results demonstrate that while IQL offers computational efficiency with linear runtime, it struggles with coordination among agents, leading to lower total rewards and an unequal distribution of income. Conversely, the Multi-agent Rollout policy achieves the highest total rewards and promotes equitable income distribution among farmers but requires significantly more computational resources, making it less practical for large numbers of agents. ABA strikes a balance between runtime efficiency and reward optimization, offering reasonable total rewards with acceptable fairness and scalability. These findings highlight the importance of selecting appropriate MARL approaches in DSS to provide personalized and equitable crop planning recommendations, advancing the development of more adaptive and farmer-centric agricultural decision-making systems.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-10-13T10:45:00Z'
#date_end: '2024-11-09T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: 'https://github.com/VIP-SMUR/24Fa-EnergyInBuildings-Com'
#url_pdf: ''
url_slides: 'upload/What_Should_We_Grow_Today_to_make_Money_Tomorrow.pptx'
#url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
