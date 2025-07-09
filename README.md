# NLP Sentence Embedding and Encoding Using the All-Minim-L6-v2 General Purpose Transformer Model
---
Sentence embeddings are a way to convert whole sentences into vectors of fixed size called embeddings. 

Embeddings capture the semantic meaning of the text. Literally, if two sentences mean the same thing but use different words, their embeddings will be close to each other in the vector space.

Suppose we have two sentences viz:
Sentence 1: "I hate playing soccer"
Sentence 2: "I detest all sports but I like reading"

The semantic embeddings of these two sentences will be quite similar in the embeddings vector space. For enterprise applications, due to cost implications and speed (latency) of outputting responses, it may not be feasible to use large models. Also, using large models in lieu of smaller models may entail that the enterprise may need expensive GPU hardware to run the models. Also, for some enterprise applications, it is crucial to experiment with various models to determine fitness and generalizability. 

## The all-MiniLM-L6-v2 Model for Enterprise Applications
---
The all-MiniLM-L6-v2 is a compact but powerful model trained to generate high-quality sentence embeddings. It is advantageous for many enterprise applications since is small (only 22MB), fast, and accurate for many applications, making it a great choice for numerous enterpise applications developers. In addition to numerous other applications, the all-MiniLM-L6-v2 can be deployed for determining:

(i) sentence similarities

(ii) for clustering (grouping sentence by meaning)

(iii) As an encoder:  given an input text, it outputs a vector which captures the semantic information. The sentence vector may be used for information retrieval, clustering or sentence similarity tasks

(iv) for semantic search; i.e. for finding similar sentences

## Deployment for Enterprise Applications
---
There are two main ways to use this model:
(i) With Sentence-Transformers (an easy-to-use Python library).
(ii) With Hugging Face Transformers (if the developer prefer using Hugging Face’s library).

Several examples of deployment scenarios are available in the 'SentenceEmbeddingsTokenizationsAndEncoding.ipynb' file attched to this repository.
