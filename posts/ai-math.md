---
layout: default
title: The Role of AI in Mathematical Research
---

# The Role of AI in Mathematical Research  
**Juan Diego Torres García**  
_November 2025_

Mathematics differs from other sciences because of a very simple—yet incredibly powerful—concept: truth.
We tend to believe that truth belongs to science; however, “truth” is not quite the right word.

Think, for example, about physics. With Newton, we believed we had understood how motion occurs in the universe, how forces interact, and how gravity behaves. Nearly three hundred years later, with the theory of relativity, we realized that Newton had actually found an excellent *approximation* of physical phenomena within our frame of reference: macroscopic and with speeds far below that of light. Einstein changed this with his relativistic theory, which, however, is incompatible with another pillar of modern physics: quantum mechanics.

There are many similar examples: from the structure of the atom to the origin of species to the functioning of the human body.  
But in mathematics, this does not happen.

Once an axiomatic system is established—that is, the set of statements accepted as true and on which the entire theoretical structure will be built—any proposition proven to be true will remain true forever.

And although Gödel showed that sufficiently complex systems contain statements that can neither be proven true nor false, something interesting about this notion of truth is that even the slightest error, contradiction, or incomplete argument is enough to turn an absolute truth into complete falsehood. In mathematics there is no such thing as “a bit more true” or “slightly less false”: only truth or falsehood. And while this might sound exaggerated or restrictive, this concept—unique to mathematics—is extremely powerful.

This is where artificial intelligence comes in. Large Langmduage Models (LLMs), such as ChatGPT, Grok, Gemini, or LLaMA, have grown at unimaginable speed. They have gone from giving nonsensical answers—though beautifully written—to solving almost any simple task correctly and efficiently within seconds.

But how do these models actually work?  
The architecture used by most of them is known as a *transformer* (hence the “T” in ChatGPT). Roughly speaking, the model receives a set of tokens (the words or text fragments we input when asking a question, requesting a reference, etc.). Using massive amounts of training data, the model calculates the most probable next token. Then it adds it and repeats the process until it generates a token indicating the end of the response—all done probabilistically.

The more information the model has, the better it will perform. There are, of course, technical details: the model does not always choose the *most* probable token but instead selects one among several “sufficiently probable” ones. Additionally, models are often fine-tuned with specific objectives, so many are designed to respond in a friendly or helpful tone.

These models are ideal for writing essays, poems, or retrieving information already available on the internet. Imagine they continue to improve for many years but still operate probabilistically. They might eventually give “correct” answers 99.999999% of the time. We could keep adding more nines—and this would be excellent for many applications.

For example, imagine an essay of one hundred thousand words where only one word sounds slightly off or misused. The rest is flawless. We would surely consider it one of the greatest essays ever written.

But what about mathematics?  
First, mathematics requires a formal language, while these models operate in natural language—the one we use in everyday life. Translating a natural-language question into a formal mathematical statement is the first step in solving a problem. Then one must prove, step by step, what is to be shown. The idea is to reduce the problem to propositional logic—statements like “$ P $ implies $ Q $” or “if $ P $, then $ Q $.” Then this is divided into smaller steps: $ P_1 \Rightarrow P_2 $, $ P_2 \Rightarrow P_3 $, and so on.

What’s the issue?  
As we said, in mathematics there are no middle grounds: only true or false, correct or incorrect. This means that an error in any intermediate step leads to a completely wrong result. And although the probability of error in each step is small, if the problem is long and requires many steps, the probabilities accumulate—making human verification necessary.

Let’s illustrate this.  
Take two real numbers $a$ and $b$ such that $ a = b $. Then $ ab = a^2 $, which means $ ab - b^2 = a^2 - b^2 $. Rewriting, we get:

$$

b(a - b) = (a + b)(a - b).

$$

Finally, if we divide both sides by $ a - b $, we conclude that $ b = a + b = 2b $, and therefore $ 1 = 2 $.  
The issue is that dividing by $a-b$ is equivalent to dividing by zero since $a = b$. Even though the rest of the steps were correct, that single error led to complete nonsense.

Of course, humans also make such mistakes. We’ve all read incorrect results in books, articles, or elsewhere. And the way these errors are caught is through collaboration and peer review.

All of this is true only from today’s perspective. It’s impossible to know what will happen in the future—technology advances unimaginably fast. But for now, if there is one science in which we are safe from being replaced by artificial intelligence, it is mathematics.

This does not mean we shouldn’t use it.  
Recently, Alex Kontorovich wrote the article *The Shape of Math To Come*, discussing a possible framework that could exploit LLMs to improve and grow proof assistants. Terence Tao has also spoken about the benefits of using these tools correctly. Yet it seems to me that, as things stand today, these systems remain tools—like calculators, programming languages, or proof assistants. They can help mathematics advance faster, but they must be used correctly and adapted to our needs.
