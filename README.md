# KnowledgeBase

There seems to be an endless amount of information with much less time to think or structure that information. How can we store information so that it is easily accessible in the future? 

What I continually experience is that writing notes down is good for the storing the current train of thought. But when we want to relate two trains of thoughts together, it is structurally difficult to connect them in a 2D space. Furthermore, a train of thought is usually useful when trying to understand something but it can be difficult to find the key points when reading it in the future. 

How can I understand something I once understood without having to read through the full train of thought? 
- Maybe by storing the key points/entities when initially writing down the train of thought?
If so, how do I create a new train of thought while creating key points with ease. (you wouldn't want to have to think too much about the key points when creating a new train of thought)

Basically what we want is a compressed representation of the train of thought so that when trying to create another train of thought, we can just visually experience the compressed form of knowledge that has previously been established which would save time and effort in trying to re-understand the previous train of thought. 

At the core, a train of thought is just a sequence of logic.
Instead of writing down a logical explanations again and again,
it would be better if we can combine those previously established logical explanations together in order to create a new one.
And it would be great if it can automatically do that for us (in natural language)

---

Since facts are usually given as declarative sentences. The phrasal structure of facts follow ( S →  NP →  VP ). 

- The cat | jumps high.
- The goverment | is ineffective.
- The sun | is white.
- Shrek | is love.
- Shrek | is life.
- Force | equals the change in momentum.
- Momentum | is the product of mass and velocity.
- Velocity | is the change in position over time.
- Facts | are usually given as declarative sentences.
- Declarative sentences | have the structure ( S →  NP →  VP ). 

Moreover, verb phrases have a single verb followed by noun phrases and optionally prepositional phrases. Therefore, the strucutre follows something like ( S →  NP →  verb →  ( NP | NP PP | PP ) ). This structure can be modelled as a graph with NPs as entities and verbs as connections.

By modelling facts into graphs, a sequence of facts can thus be traversed to complete a train of thought.

- NP ← \*→  NP
- \*→  NP
- NP →  verb \*→ 

---
