---
title: 'NavG: Risk-Aware Navigation in Crowded Environments Based on Reinforcement Learning with Guidance Points'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wentao Luo
  - Boyi Liu
  - Ziyang Zhang
  - Yaoyuan Wang
  - Jingtai Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS2025, under review*

abstract: Motion planning in navigation systems is highly susceptible to upstream perceptual errors, particularly in human detection and tracking. To mitigate this issue, the concept of guidance points—a novel directional cue within a reinforcement learning-based framework—is introduced. A structured method for identifying guidance points is developed, consisting of obstacle boundary extraction, potential guidance point detection, and redundancy elimination. To integrate guidance points into the navigation pipeline, a perception- to-planning mapping strategy is proposed, unifying guidance points with other perceptual inputs and enabling the RL agent to effectively leverage the complementary relationships among raw laser data, human detection and tracking, and guidance points. Qualitative and quantitative simulations demonstrate that the proposed approach achieves the highest success rate and near-optimal travel times, greatly improving both safety and efficiency. Furthermore, real-world experiments in dynamic corridors and lobbies validate the robot’s ability to confidently navigate around obstacles and robustly avoid pedestrians.

# Summary. An optional shortened abstract.
summary: Motion planning in navigation systems is highly susceptible to upstream perceptual errors, particularly in human detection and tracking. To mitigate this issue, the concept of guidance points—a novel directional cue within a reinforcement learning-based framework—is introduced. A structured method for identifying guidance points is developed, consisting of obstacle boundary extraction, potential guidance point detection, and redundancy elimination. To integrate guidance points into the navigation pipeline, a perception- to-planning mapping strategy is proposed, unifying guidance points with other perceptual inputs and enabling the RL agent to effectively leverage the complementary relationships among raw laser data, human detection and tracking, and guidance points. Qualitative and quantitative simulations demonstrate that the proposed approach achieves the highest success rate and near-optimal travel times, greatly improving both safety and efficiency. Furthermore, real-world experiments in dynamic corridors and lobbies validate the robot’s ability to confidently navigate around obstacles and robustly avoid pedestrians.

tags:
  - Navigation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: https://arxiv.org/abs/2409.10009
# url_code: 'https://github.com/Chris-Arvin/GraphicTEB-series'
# url_dataset: ''
# url_poster: 'https://ga-teb.github.io'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?v=1K7Klxig8CU'

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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---