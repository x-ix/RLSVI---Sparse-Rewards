---
license: mit
language:
- en
tags:
- pdf
pretty_name: '*'
---
# RLSVI – An Introduction and Analysis in a sparse reward environment

With recent advancements in the field of machine learning, the sub-field of Reinforcement Learning has become an ever-significant aspect of our current technological landscape as we seek to optimise our current practices beyond human limits in fields such as automation, language processing and healthcare. Consequently, a multitude of approaches have been developed with the goal of overcoming critical challenges such as the efficiency of exploration, and its optimal balance, with exploitation and generalisation.

These methods often scale in theoretical complexity, potentially leading to difficulties, for some, in the appreciation of the contributions they make. One such method is Randomised Least Squares Value Iteration (RLSVI) [Osband, Van Roy and Wen, 2016], a model-free algorithm that offers an elegant approach to learning by inducing randomness within the least-squares approximation of an action-value function to instigate efficient exploration, something that is especially important when state-action spaces scale.

Here an in-depth introduction and analysis of RLSVI is presented to build up foundational elements such that the reader can better understand the algorithms intricacies before introducing a simple, sparse reward environment in which its performance can be evaluated.