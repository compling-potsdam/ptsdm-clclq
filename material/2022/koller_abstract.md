# Compositional Semantic Parsing

*Alexander Koller, Saarland University*

*June 15th, 2022*

### Abstract

There are many approaches to mapping natural-language sentences to symbolic meaning representations. The current dominant approach is with neural sequence-to-sequence models which map the sentence to a string version of the meaning representation. Seq2seq models work well for many NLP tasks, including tagging and parsing, and deliver excellent accuracy on broad-coverage semantic parsing as well.

However, as I will show in the talk, seq2seq models struggle with compositional generalization: they have a hard time generalizing from training examples to structurally similar unseen test sentences. This is true not only for semantic parsing, but also for syntax. I will show some new results that pinpoint this difficulty more precisely, and discuss what this means for how to best evaluate semantic parsers.

I will then present our own research on compositional semantic parsing, which combines neural models with the Principle of Compositionality from theoretical semantics. Our semantic parser uses a neural supertagger to predict word meanings and a neural dependency parser to predict the compositional structure, and then evaluates this dependency structure in a graph algebra to obtain the meaning representation. Our parser is one of a very small group of models that performs well both on compositional generalization and on broad-coverage semantic parsing, where it achieves parsing speeds of up to 10k tokens/second.


### Bio

Alexander Koller is a Professor of Computational Linguistics in the Department of Language Science and Technology at Saarland University. He received his PhD from Saarland University in 2004 and was then a postdoc at Columbia University and the University of Edinburgh and a professor at the University of Potsdam. His research interested span a broad range of topics in computational linguistics, including semantics, parsing, and dialogue. He is currently particularly interested in neurosymbolic models that bring together principled linguistic modeling with the accuracy and robustness of neural methods.
