# Sources of syntactic inductive biases in language models

*Tal Linzen (New York University & Google NY)*

*July 11th, 2023*

### Abstract

Speakers of a language generalize their knowledge of syntax in a systematic way to constructions they have never encountered before. This observation has motivated the influential position in linguistics that humans are innately endowed with syntax-specific inductive biases. Inspired by this observation, we have used paradigms from psycholinguistics to examine the syntactic generalization capabilities of contemporary neural network architectures. I will show that, when trained to perform tasks such as transforming a declarative sentence to a question, models such as transformers tend to generalize in ways that are very different from humans. Following self-supervised pre-training, however, transformers become substantially more likely to generalize in line with syntactic structure. We examine how architecture and pre-training affect the model’s bias, and find that the likelihood of syntactic generalization is higher for deeper models (though not necessarily larger ones!), and for models pre-trained on simpler language such as child-directed speech.


### Bio

Tal is an Assistant Professor of Linguistics and Data Science at New York University, and a Research Scientist at Google. At NYU, he directs the Computation and Psycholinguistics Lab, which uses behavioral experiments and computational methods to study how people learn and understand language. The lab also develops methods for evaluating, understanding and improving computational systems for language processing.
