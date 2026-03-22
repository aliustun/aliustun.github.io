---
title: "The FitzHugh-Nagumo Model in Neuromorphic Computing"
layout: post
---

## What is the FitzHugh-Nagumo (FHN) model? 
The FitzHugh-Nagumo (FHN) model is a two-dimensional simplification of the Hodgkin-Huxley model. It plays a significant role in neuromorphic computing by capturing the essential dynamics of biological neurons, such as rapid depolarization (spike) followed by a slower recovery. This makes it computationally efficient and ideal for hardware implementation while retaining key characteristics essential for brain-inspired computation.

<div class="large">
  <!-- <img src="../images/fhn_model.png" alt="FitzHugh-Nagumo Phase Plane"> -->
</div>

Because of its reduced complexity, the FHN model is particularly suitable for both analog and digital hardware implementations in neuromorphic systems. It offers a powerful balance between biological accuracy and computational tractability, drastically reducing energy capabilities, which is highly desirable for brain-inspired chips.

## Spiking Neural Networks and FHN

The FHN model is frequently employed as a spiking neuron model within Spiking Neural Networks (SNNs). By processing information through discrete events (spikes) rather than continuous values, SNNs utilizing the FHN model can better mimic the event-driven and energy-efficient nature of biological brains.

## Emerging Hardware Technologies
Researchers are exploring the deployment of FHN models with emerging technologies like memristors and spintronic devices. Coupling FHN neurons with memristive synapses allows for the investigation of bio-plausible learning rules like Spike-Timing-Dependent Plasticity (STDP). 

## References 
[1] FitzHugh, R. (1961). Impulses and physiological states in theoretical models of nerve membrane. Biophysical journal, 1(6), 445-466.

[2] Nagumo, J., Arimoto, S., & Yoshizawa, S. (1962). An active pulse transmission line simulating nerve axon. Proceedings of the IRE, 50(10), 2061-2070.
