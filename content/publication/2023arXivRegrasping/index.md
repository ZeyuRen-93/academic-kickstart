---
title: "In-Hand Re-grasp Manipulation with Passive Dynamic Actions via Imitation Learning"
authors:
- Dehao Wei
- Guokang Sun
- Zeyu Ren
- Shuang Li
- Zhufeng Shao
- Xiang Li
- Nikos Tsagarakis
- Shaohua Ma
date: "2023-05-30T00:00:00"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:2309.15455*
publication_short: In *arXiv preprint arXiv:2309.15455*

abstract: Re-grasp manipulation leverages on ergonomic tools to assist humans in accomplishing diverse tasks. In certain scenarios, humans often employ external forces to effortlessly and precisely re-grasp tools like a hammer. Previous development on controllers for in-grasp sliding motion using passive dynamic actions (e.g.,gravity) relies on apprehension of finger-object contact information, and requires customized design for individual objects with varied geometry and weight distribution. It limits their adaptability to diverse objects. In this paper, we propose an end-to-end sliding motion controller based on imitation learning (IL) that necessitates minimal prior knowledge of object mechanics, relying solely on object position information. To expedite training convergence, we utilize a data glove to collect expert data trajectories and train the policy through Generative Adversarial Imitation Learning (GAIL). Simulation results demonstrate the controller's versatility in performing in-hand sliding tasks with objects of varying friction coefficients, geometric shapes, and masses. By migrating to a physical system using visual position estimation, the controller demonstrated an average success rate of 86%, surpassing the baseline algorithm's success rate of 35% of Behavior Cloning(BC) and 20% of Proximal Policy Optimization (PPO).


# Summary. An optional shortened abstract.
# summary:  In this paper we present a novel implementation of hardware synergies realized on the actuation level by leveraging on a novel adjustable electric actuation topology principle.

tags:
- Source Themes
featured: true

# links:
# - name: DEMO
#   url: https://www.youtube.com/watch?v=iJ8emk2EeOA
# - name: RESEARCH-GATE  
#   url: https://www.researchgate.net/publication/344610670_On_the_efficient_control_of_series-parallel_compliant_articulated_robots
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---


