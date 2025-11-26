---
layout: home
title: Home
landing-title: 'Yuanzhao Zhang (章元肇)'
description: Homepage of Yuanzhao Zhang
image: null
author: Yuanzhao Zhang
---

<div 
  style="
    display: flex; 
    align-items: flex-start; 
    gap: 100px; 
    flex-wrap: wrap;
  "
>

  <img 
    src="assets/images/me.jpeg"
    alt="Yuanzhao Zhang"
    style="
      width: 450px; 
      max-width: min(80vw, 450px);
      height: auto;
      border-radius: 8px;
      flex-shrink: 0;
      object-fit: contain; 
    "
  />

  <div
    style="
      flex: 1;
      min-width: 260px;
      max-width: 1000px;
      font-size: 1.4rem;
    "
  >
    <p>
      I am an Omidyar Fellow at the Santa Fe Institute, working at the interface between
      complex networks, nonlinear dynamics, and machine learning. Before that, I was a
      Schmidt Science Fellow at Cornell working with 
      <a href="http://www.stevenstrogatz.com" target="_blank" rel="noopener">Steven Strogatz</a>.
      I received my Ph.D. in Physics from Northwestern, advised by 
      <a href="http://dyn.phys.northwestern.edu/" target="_blank" rel="noopener">Adilson Motter</a>.
      You can reach me at 
      <a href="mailto:yzhang@santafe.edu">yzhang@santafe.edu</a>.
    </p>

    <p>
      Broadly, I am interested in systems that exhibit rich emergent behaviors, but at
      the same time can be understood (either analytically or heuristically) when viewed
      from the right perspective. Half jokingly, I like to say that I am into the
      simplest complex systems and not-too-nonlinear dynamics. Here are some of the questions
      currently keeping me awake at night:
    </p>

    <ol>
      <li>
        <strong>When and how can machine learning models extrapolate without physics?</strong>
        Incorporating physics into neural networks—symmetries, conservation laws, 
        and other inductive biases—is known to improve out-of-distribution generalization. 
        Yet many real-world complex systems lack fully understood or easily encoded physics. 
        Can machine learning models still extrapolate in such cases? 
        If so, what hidden inductive biases or implicit regularization are responsible? 
        By studying systems ranging from reservoir computers to time-series foundation models, 
        I hope to uncover the principles that enable physics-uninformed extrapolation in machine learning.
      </li>

      <li>
        <strong>How do collective dynamics emerge from decentralized interactions?</strong>
        From fireflies spontaneously synchronizing their flahes to neurons generating avalanches
        of firing activities, nature is full of examples of order emerging without central control. 
        What mechanisms allow such global behaviors to arise from local interactions?
        I study these systems by representing them as networks or hypergraphs of nonlinear nodes 
        and analyzing them through the lenses of dynamical systems and network theory. 
        How does network structure shape macroscopic behavior? 
        How do basins of attraction look in such high-dimensional nonlinear systems? 
        Insights from these questions can inform everything from designing neural networks that 
        navigate complex loss surfaces more effectively to developing strategies 
        to restore disrupted circadian rhythms after long-haul flights.
      </li>
    </ol>

  </div>

</div>