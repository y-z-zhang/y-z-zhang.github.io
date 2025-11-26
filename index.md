---
layout: home
title: Home
landing-title: 'Yuanzhao Zhang (章元肇)'
description: Research Homepage of Yuanzhao Zhang
image: null
author: Yuanzhao Zhang
---

<div 
  style="
    display: flex; 
    align-items: top; 
    gap: 100px; 
    flex-wrap: wrap;
  "
>

  <img 
    src="assets/images/me.jpeg"
    alt="Yuanzhao Zhang"
    style="
      width: 450px; 
      max-width: min(80vw, 450px);   /* mobile-friendly scaling */
      height: auto;
      border-radius: 8px;
      flex-shrink: 0;
    "
  />

  <div
    style="
      flex: 1;
      min-width: 260px;              /* prevents awkward squeezing */
      max-width: 1000px;
    "
  >
    <p>
      I am an Omidyar Fellow at the Santa Fe Institute working at the interface between complex networks, nonlinear dynamics, and machine learning. Before that, I was a Schmidt Science Fellow at Cornell working with 
      <a href="http://www.stevenstrogatz.com" target="_blank" rel="noopener">Steven Strogatz</a>.
      I received my Ph.D. in Physics from Northwestern, advised by 
      <a href="http://dyn.phys.northwestern.edu/" target="_blank" rel="noopener">Adilson Motter</a>.
      You can reach me at 
      <a href="mailto:yzhang@santafe.edu">yzhang@santafe.edu</a>.
    </p>

    <p>
      Broadly, I am interested in systems that exhibit rich emergent behaviors, but at the same time can be understood by our (at least my) tiny brain when looked at from the right angle. Half jokingly, I like to say that I am interested in the simplest complex systems and not-too-nonlinear dynamics. Here are some questions currently keeping me awake at night: 
      1. **When and how can machine learning models extrapolate without physics?** Incorporating physics knowledge into neural networks, such as symmetry and conservation laws, can improve their ability to generalize beyond training data. This is one of the main motivations behind physics-informed machine learning. However, such prior knowledge may not be available for many complex system. Can machine learning models extrapolate to unseen conditions without physics priors? If so, what hidden inductive bias or implicit regularization are enabling such out-of-distribution generalization? By studying systems including reservoir computers and time-series foundation models, I am hoping to develop a theory for physics-uninformed machine learning.
      2. **How do collective dynamics emerge from decentralized interactions?** From fireflies spontaneously starting to flash synchronously to neurons generating avalanches of firing activities, nature is full of examples of interacting agents acting collectively without central control. What are the mechanisms generating such collective order from apprenant chaos? I like to abstract those coupled systems into networks or hypergraphs of nonlinear nodes and analyze them using techniques from dynamical systems and network theory. What role does network structure play in shaping the collective dynamics we see? How do basins of attraction look like in such high-dimensional nonlinear systems? Understanding these questions can have applications from designing neural networks that navigate high-dimensional loss landscapes more effectively to finding optimal control strategy to restore disrupted circadian rhythms after long-haul flights.
    </p>
  </div>

</div>