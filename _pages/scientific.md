---
permalink: /Scientific_Interests/
title: "Scientific Interests"
---
**Mathematics for AI/ML:**

Current major interests lie in revealing connections between the mathematics, physics, and machine/deep learning worlds. I am the founder of the _Mathephysical perspectives_ research program: a quest for implementing novel, data-driven methods inspired from various subfields of mathematics/physics to design, benchmark, and optimize efficient Machine Learning models. These methods are relevant to a wide class of implementations and target systems that are reliant on iterative optimization algorithms. For example, by envisioning the training process as a discrete dynamical flow of parameters in training iteration time, we can identify and construct [Koopman operators/modes to drive this](https://proceedings.neurips.cc/paper/2020/hash/169806bb68ccbf5e6f96ddc60c40a044-Abstract.html) [flow](https://proceedings.neurips.cc/paper/2020/hash/169806bb68ccbf5e6f96ddc60c40a044-Abstract.html) - side-stepping the standard optimization methods and gaining significant computational savings. Similarly, we can prove that Iterative Magnitude Pruning, a major technique for sparsifying ML models, effects a block spin [renormalization group scheme on the model parameters](https://proceedings.mlr.press/v162/redman22a.html), thus allowing us to use the techniques from the field to characterize this process.

**Mathematics with AI/ML:**

I also pursue goals in the reverse direction - the creation of [machine learning techniques to aid the study of scientific systems](https://arxiv.org/abs/2007.04433). I achieve this by constructing strategies that leverage known information about the chosen systems to optimize the ML models studying it. For ex, in [SHAPER: Can you hear the shape of a Jet?](https://github.com/rikab/SHAPER), we constructively build the optimal algorithm to search for jet substructures in experimental data, while simultaneously encoding physical constraints into our framework. Indeed, we went a step further and demonstrated that our framework not only optimally solves the problem, but also precisely provides a definition for the searched objects, by recasting it in a measure theoretic sense.

Similarly, I focus on constructively building Neural Network based Differential Equation solvers that can exactly encode associated invoilable constraints (such as boundary/initial conditions, regularity requirements on the solutions, etc). We handle such problems from the perspective of optimization viability (where we produce guarantees on when it is possible, at what rates, etc), model validation (where we produce unsupervised guarantees on the errors associated with the models and often are able to correct them as well), and investigation of the associated PDEs themselves (where we produce mathematical statements on the equation operators themselves, which often help with the first two things too). We have successfully applied this approach to studying [dynamical systems](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.105.065305), PDEs of relevance in [bio-chemical settings](https://openreview.net/forum?id=a40XE0dgOdL), [fluids, plasmas,](https://github.com/MathePhysics) etc.

**Modelling without AI/ML:**

In fluid mechanics, my major contribution has been the construction of a theoretical model that explains the phenomenology of the [laminar-turbulent regime in pipe-flow](https://journals.aps.org/prfluids/abstract/10.1103/PhysRevFluids.4.102401). We achieved this by demonstrating the existence of a homoclinic tangle in the regime. This necessitates gateways that guarantee the experimentally observed escape from turbulence.

I contributed significantly to the discovery of the [background radiation-induced quasiparticle generation](https://www.nature.com/articles/s41586-020-2619-8) phenomenon that limits superconducting qubit performance. As a core member of a multi-year, multi-institutional project, I handled the creation and study of computational simulations that provided a rough understanding of the limits and timescales within which the effect could be significant and discoverable. I also assisted in designing and studying the shielding experiment that ultimately isolated and discovered the effect.

**On the side:**

The remainder of my time is devoted to establishing connections between statements on the complexity of natural numbers and a class of open problems in number theory. Most notably, I have shown that the former are intimately connected with the Sophie Germain prime conjecture and conjectures on the maximum allowed gap between the successive elements of _k_N*_k_N multiplication tables, where _k_ is a positive integer. A secondary aim is to obtain useful generalizations of those connections between partially ordered sets and the complexity of their constituent elements (if the complexity is _well defined_ and _well behaved_).