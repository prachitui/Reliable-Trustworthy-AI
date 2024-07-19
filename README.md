# Reliable-Trustworthy-AI

### Introduction and Background:

When I first began working on my thesis on Explainable Artificial Intelligence, my interest in addressing the black box issue of neural networks and enhancing their explainability, 
reliability, trustworthiness, and fairness was sparked. This led me to delve deeper into the field of Reliable AI. Among the extensive resources available online, I discovered a course on 
Reliable and Trustworthy AI taught by Professor Martin Vechev at ETH Zurich in 2020. You can find the course [here](https://www.youtube.com/playlist?list=PLWjm4hHpaNg6c-W7JjNYDEC_kJK9oSp0Y). The knowledge I gained from these lectures was substantial.


### Summary of the lectures from the Course:
Below is a summary of the key points from each lecture-

**Adversarial Examples (lectures 1–3):** These lectures cover how to generate small, invisible perturbations to input data that cause the model to make mistakes. Methods such as FGSM and 
PGD are introduced.

**Adversarial Defenses (lecture 4a):** This lecture focuses on training models to be immune to adversarial attacks, thereby enhancing their robustness.

**Certification (lectures 4b-7):** These lectures explore how to prove a neural network's immunity to adversarial attacks. Various methods for certification are presented, each with
increasing computational complexity: Box and Zonotope relaxation, DeepPoly, and Mixed Integer Linear Programming (MILP). Most methods are sound but incomplete, providing answers like 
"network is safe" or "I don't know." MILP theoretically always works but is not solvable in polynomial time.

**Certified Defense (lecture 8):** This lecture discusses training a network to be provably robust.

**Geometric Robustness (lecture 9):** A generalization of adversarial attacks where the input undergoes geometric perturbations (rotation, translation, scaling). Certification in this 
context is more complex but possible.

**Visualization (lecture 10):** Various techniques for visualizing decision-making in computer vision systems are covered, including methods to determine what specific neurons are 
responsible for and which parts and properties of the input image contribute to the output label.

**Enforcing Logic in the Training Process (lecture 11):** This lecture generalizes adversarial defense by enforcing additional logical properties during training beyond accuracy.
The topic of semi-supervised learning is introduced in this context.

**Randomized Smoothing (lecture 12):** This framework enhances the robustness of black-box models by taking multiple perturbed samples of input during inference and choosing the most
popular label as the output.


### Other Material to watch out:

- Watch Christoph Molnar talk about Interpretable AI [here](https://www.youtube.com/watch?v=0LIACHcxpHU). This is his [book](https://www.amazon.de/-/en/Christoph-Molnar/dp/B09TMWHVB4) on
making more interpretable and explainable.
- Responsible AI by [Tensorflow](https://www.tensorflow.org/responsible_ai)
- Trustworthy AI by [IBM](https://research.ibm.com/topics/trustworthy-ai).
