---
title:          "ACNMP: Skill Transfer and Task Extrapolation through Learning from Demonstration and Reinforcement Learning via Representation Sharing"
date:           2021-10-04 00:01:00 +0800
selected:       false
#pub:            "IROS"
# pub_pre:        "Submitted to "
# pub_post:       'Under review,'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">CoRL 2021 - Accepted</span> <span class="badge badge-pill badge-publication badge-primary">Oral Spotlight</span>'
#pub_date:       "2024"

abstract: >-
   To equip robots with dexterous skills, an effective approach is to first transfer the desired skill via Learning from Demonstration (LfD), then let the robot improve it by self-exploration via Reinforcement Learning (RL). In this paper, we propose a novel LfD+ RL framework, namely Adaptive Conditional Neural Movement Primitives (ACNMP), that allows efficient policy improvement in novel environments and effective skill transfer between different agents. This is achieved through exploiting the latent representation learned by the underlying Conditional Neural Process (CNP) model, and simultaneous training of the model with supervised learning (SL) for acquiring the demonstrated trajectories and via RL for new trajectory discovery. Through simulation experiments, we show that (i) ACNMP enables the system to extrapolate to situations where pure LfD fails;(ii) Simultaneous training of the system through SL and RL preserves the shape of demonstrations while adapting to novel situations due to the shared representations used by both learners;(iii) ACNMP enables order-of-magnitude sample-efficient RL in extrapolation of reaching tasks compared to the existing approaches;(iv) ACNMPs can be used to implement skill transfer between robots having different morphology, with competitive learning speeds and importantly with less number of assumptions compared to the state-of-the-art approaches. Finally, we show the real-world suitability of ACNMPs through real robot experiments that involve obstacle avoidance, pick and place and pouring actions.

short_abstract: This paper introduces Adaptive Conditional Neural Movement Primitives (ACNMPs)—a unified framework combining Learning from Demonstration and Reinforcement Learning for efficient skill adaptation and transfer. By jointly training a Conditional Neural Process with both supervised and reinforcement signals, ACNMPs enable robots to preserve demonstrated motions while adapting to new environments or morphologies. The approach achieves strong generalization and sample efficiency across tasks like obstacle avoidance, pick-and-place, and pouring, both in simulation and on real robots.
cover:          /assets/images/covers/ACNMP_cover.png
authors:
  - M. Tuluhan Akbulut
  - Erhan Oztop
  - M. Yunus Seker
  - Honghu Xue
  - Ahmet E. Tekden
  - Emre Ugur
links:
  Paper: https://arxiv.org/abs/2003.11334
  Presentation: https://www.youtube.com/watch?v=6ZreL7y3UAY
  Code: https://github.com/mtuluhanakbulut/ACNMP
---
