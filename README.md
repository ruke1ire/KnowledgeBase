# KnowledgeBase

There seems to be an endless amount of information with much less time to think or structure that information. How can we store information so that it is easily accessible in the future? 

What I continually experience is that writing notes down is good for the storing the current train of thought. But when we want to relate two trains of thoughts together, it is structurally difficult connect them in a 2D space. Furthermore, a train of thought is usually useful when trying to understand something but it can be difficult to find the key points when reading it in the future. 

How can I understand something I once understood without having to read through the full train of thought? 
- Maybe by storing the key points/entities when initially writing down the train of thought?
If so, how do I create a new train of thought while creating key points with ease. (you wouldn't want to have to think too much about the key points when creating a new train of thought)

Basically what we want is a compressed representation of the train of thought so that when trying to create another train of thought, we can just visually experience the compressed form of knowledge that has previously been established which would save time and effort in trying to re-understand the previous train of thought. 

At the core, a train of thought is just a sequence of logic.
Instead of writing down a logical explanations again and again,
it would be better if we can combine those previously established logical explanations together in order to create a new one.
And it would be great if it can automatically do that for us (in natural language)


## Example Implementation:

1. Find all words in [wikipedia](https://www.wikipedia.org/) with **NP** (Noun Phrase) -- **VP** (Verb Phrase) -- **NP**. *Note that this is just to limit the form of logic to make it simpler*
2. Set all the NP as entities and VP as connections in a graph model.
3. Any relationship between two NP can be traced. NP -\*- NP.

### Example NP -- *VP* -- NP

- Earth *contains* water.
- Earth *contains* air.
- Earth *contains* land.
- Plants *grow* on land.
- Animals *eat* plants.
- Humans *eat* animals.

### Example Query

Earth -\*- Humans:

- Earth contains land which grows plants, which animals eat, which humans eat.

