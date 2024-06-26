# AMLD Africa 2021 Workshop
## Hands-on Multi-Agent Reinforcement Learning using Mava

<a href="https://actu.epfl.ch/news/amld-africa-2021-tickets-now-available/" target="_blank">
  <img src="https://actu.epfl.ch/image/108066/original/2048x1150.jpg"/>
</a>

This workshop aims to provide an overview of multi-agent reinforcement learning theory
and its applications.

MARL systems have gained more interest in the last years as it extends the decision-making capabilities
of single-agent reinforcement learning to larger and more complex systems.

In real world applications, most of the problems are designed as a multi-agent decision systems:
This is the case for managing a fleet of autonomous vehicles, or augmenting the capacity
of train management systems, etc. - the list is long.

Having said that, this workshop will guide you from the theory and foundations of RL & MARL
to hands-on experience with introductory examples using the `mava` framework.

### RL foundations
We start by giving an introduction to the RL field, explaining the value based and policy methods,
and providing the ideas behind some algorithms like `DQN`, `DDPG`, `D4PG`.

### Deep RL in practice
In this section, we talk about Multi agent RL via the Deutsche Bahn use case.
We provide intuitions on the different MARL training architectures as well as details on their machinery.

### Mava: Open-Source Framework for Multi-Agent Reinforcement Learning
We finish the presentation part by explaining the `mava` framework, how it works, and the
panoply of features it provides.

---

In the second part of the workshop, we will walk through two notebooks and showcase the flexibility
of `mava` in implementing and training multi agent systems.

### Part I: Flatland notebook

In this notebook, we use `MADQN` from `mava` to learn the route of trains using the open sourced
flatland environnement.

<img src=https://i.imgur.com/VrTQVeM.gif>

For more information regarding flatland, we recommend visiting their [official documentation](http://flatland-rl-docs.s3-website.eu-central-1.amazonaws.com/01_readme.html).

### Part II: Mava overview notebook
In this notebook, we showcase the `mava` features and capabilities.
We demonstrate the simplicity of using different networks, architectures, agents, and an easy-to-use
integrated loggers like `tensorboard` to benchmark results.

We also provide insights on the distributed training, which is one of the essential building
blocks of `mava` that enhance scaling properties.
