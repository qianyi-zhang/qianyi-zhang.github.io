---
title: 'P2EG: Prediction and Planning Integrated Robust Decision-Making for Automated Vehicle Negotiating in Narrow Lane with Explorative Game'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiao Li
  - Ethan He
  - Shuguang Ding
  - Naizheng Wang
  - Jingtai Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS2022*

abstract: In the narrow lane scene of autonomous driving, it is critical for the ego car to recognize the intentions of social vehicles and cooperate with them. However, cooperating with social vehicles is challenging due to insufficient information. This paper proposes an Explorative Game that adopts Participant Game and Perfect Bayesian Equilibrium to exploratively perform some aggressive actions to obtain additional information, thus the autonomous vehicle can cooperate robustly and efficiently. Explorative Game assumes each vehicle maintains a unique belief about the current situation and attributes insecurity and instability to the conflict of various Perfect Bayesian Equilibriums formed by various beliefs. Aggressive actions enable the ego car to proactively guide social vehicles to cooperate as it expects and encourage them to express their intentions as quickly and clearly as possible so that the equilibriums can converge and the conflict can be eliminated. Additional information reduces the error between the actual intentions of social vehicles and the estimated intentions from the ego car, helping rationally prune potential interactions and update parameters of the reward function. We demonstrate our algorithm on recorded data as well as virtual environments with manually controlled social vehicles to prove the efficiency of cooperation and the robustness of decision-making. And it has been running for more than 20 kilometers in the real world.

# Summary. An optional shortened abstract.
summary: In the narrow lane scene of autonomous driving, it is critical for the ego car to recognize the intentions of social vehicles and cooperate with them. However, cooperating with social vehicles is challenging due to insufficient information. This paper proposes an Explorative Game that adopts Participant Game and Perfect Bayesian Equilibrium to exploratively perform some aggressive actions to obtain additional information, thus the autonomous vehicle can cooperate robustly and efficiently. Explorative Game assumes each vehicle maintains a unique belief about the current situation and attributes insecurity and instability to the conflict of various Perfect Bayesian Equilibriums formed by various beliefs. Aggressive actions enable the ego car to proactively guide social vehicles to cooperate as it expects and encourage them to express their intentions as quickly and clearly as possible so that the equilibriums can converge and the conflict can be eliminated. Additional information reduces the error between the actual intentions of social vehicles and the estimated intentions from the ego car, helping rationally prune potential interactions and update parameters of the reward function. We demonstrate our algorithm on recorded data as well as virtual environments with manually controlled social vehicles to prove the efficiency of cooperation and the robustness of decision-making. And it has been running for more than 20 kilometers in the real world.

tags:
  - Navigation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://ieeexplore.ieee.org/document/9981332
url_code: 'https://github.com/Chris-Arvin/CG3_The-Human-Gaze-Helps-Robots-Run-Bravely-and-Efficiently-in-Crowds'
url_video: 'https://youtu.be/Dt9DNDKVRGE'

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