---
layout: post
title: progressive determination of structure and operation
---

The exact interpretation of the expression of the chain of transformations \\(S_1 \rightarrow O_1 \rightarrow S_2 \rightarrow O_2 \rightarrow S_3 \rightarrow...\\) is important:

* operation \\(O_i\\) can be interpreted as a function which transforms one structure to another: \\(O_2 = S_i(O_1)\\);

* likewise, structure \\(S_i\\) is a function which transforms one operation to another: \\(O_2 = S_i(O_1)\\);

* note that \\(S_1 \neq S_2\\) and \\(O_1 \neq O_2\\) -- they are **different** functions;

* also note the \\( \rightarrow \\) denotes **not** piping of inputs and outputs  through the chain of transformations, but the **relations of dependency between** the transformations themselves; therefore every transformation (whether structure of operation) depends on the full history of previous transformations.



In [^1] we describe this aspect of transduction as follows:

> Perhaps the most important aspect revealed in transduction is the progressive co-determination of structure and function (see also above regarding the notion of metastability). Individuation can be seen as a chain of operations \\(O\\) on structures \\(S\\): \\(S \rightarrow O \rightarrow S \rightarrow O \rightarrow S...\\) [^2]. Every operation is a conversion of one structure into another, while every structure mediates between one operation and another. Each structure in the chain constrains the operations that can immediately follow. Each operation can transform the previous structure into a limited number of new structures. Every intermediate structure is a partial resolution of incompatibility but it is driven away from its relative stability as long as the existing tensions are not exhausted. This is reminiscent of the propagation of a computation in evolutionary programming. Executed code and the data are analogous to operation and structure. But the code itself is also data that can be progressively modified to produce inexhaustible variety and innovation. This analogy helps us understand how operation and structure are reciprocally determining expressions of the transductive process.

Another attempt to formalize the progressive determination, which also grasps the concept of metastability proposed in the previous slide, is due to Marsh and Onof. They propose the modified Particle Swarm Algorithm (PSO) where the global fitness function \\(f\_t\\) is defined as **dependent** on the actual configuration of particles at time \\(t\\) within the state space:

> [..] this would amount to having the moves made by the individuals (either each individual’s trajectory, or perhaps only the evolution of the group’s best position) have an impact upon the actual shape of the landscape – one could imagine these individuals’ movements causing earthquakes or landslides, for instance [^3].

[^1]: Weinbaum, David, and Viktoras Veitas. [“Synthetic Cognitive Development: Where Intelligence Comes from.”](http://arxiv.org/abs/1411.0159) ArXiv Preprint arXiv:1411.0159, 2014.
[^2]: Combes, Muriel. Gilbert Simondon and the Philosophy of the Transindividual. MIT Press, 2013., p. 14-15.
[^3]: Marsh, Leslie, and Christian Onof. “Stigmergic Epistemology, Stigmergic Cognition.” Cognitive Systems Research 9, no. 1 (2008): 136–49, p. 11.
