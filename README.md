# spaCy-talk-demo
Slides and Python notebook for PyData Vancouver talk (25-02-2020)

In this talk, we first review spaCy's basic usage:
- Loading models for different languages.
- Identifying special tokens: punctuation, stopwords, etc.
- Compute part-of-speech (POS) tags, dependency parsing, named entity recognition (NER).
- Visualize dependencies and named entities, along with tag explanations.

In the second half, we take a stab at customizing spaCy pipelines to solve two tasks:
- Create a tokenizer that does not split hyphenated words.
- Create a simple noun chunker that identifies only consecutive nouns, optionally preceded by a simple adjective.
