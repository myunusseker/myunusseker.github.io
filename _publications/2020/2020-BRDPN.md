---
title:          "Belief Regulated Dual Propagation Nets for Learning Action Effects on Groups of Articulated Objects"
date:           2020-05-31 00:01:00 +0800
selected:       false
#pub:            "IROS"
# pub_pre:        "Submitted to "
# pub_post:       'Under review,'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">IROS 2020 - Accepted</span> '
#pub_date:       "2024"

abstract: >-
   In recent years, graph neural networks have been
    successfully applied for learning the dynamics of complex and
    partially observable physical systems. However, their use in the
    robotics domain is, to date, still limited. In this paper, we introduce Belief Regulated Dual Propagation Networks (BRDPN), a
    general-purpose learnable physics engine, which enables a robot
    to predict the effects of its actions in scenes containing groups
    of articulated multi-part objects. Specifically, our framework
    extends recently proposed propagation networks (PropNets)
    and consists of two complementary components, a physics
    predictor and a belief regulator. While the former predicts the
    future states of the object(s) manipulated by the robot, the latter
    constantly corrects the robots knowledge regarding the objects
    and their relations. Our results showed that after training in
    a simulator, the robot can reliably predict the consequences
    of its actions in object trajectory level and exploit its own
    interaction experience to correct its belief about the state of the
    environment, enabling better predictions in partially observable
    environments. Furthermore, the trained model was transferred
    to the real world and verified in predicting trajectories of
    pushed interacting objects whose joint relations were initially
    unknown. We compared BRDPN against PropNets, and showed
    that BRDPN performs consistently well. Moreover, BRDPN can
    adapt its physic predictions, since the relations can be predicted
    online.

short_abstract: This paper presents Belief Regulated Dual Propagation Networks (BRDPN), a learnable physics engine designed for robots to predict the outcomes of actions involving complex, articulated objects. BRDPN combines a physics predictor with a belief regulator that updates the robot’s understanding of object relationships in partially observable environments. Trained in simulation and validated in the real world, BRDPN enables accurate, adaptive predictions of object trajectories, outperforming previous models like PropNets.
cover:          /assets/images/covers/BRDPN_cover.png
authors:
  - Ahmet E. Tekden
  - Aykut Erdem
  - Erkut Erdem
  - Mert Imre
  - M. Yunus Seker
  - Emre Ugur
links:
  Paper: https://arxiv.org/pdf/1909.03785
  Video: https://www.youtube.com/watch?v=uWPr7IFT_9k
  Website: https://fzaero.github.io/BRDPN/
---
