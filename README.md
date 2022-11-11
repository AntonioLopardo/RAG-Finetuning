# RAG-Finetuning

In this project, we demonstrate that for domain specific QA, the size of the non-parametric memory used in the RAG model can be cut down significantly. Specifically for the medical domain we managed to reduce the size to less than 5 % compared to the non-parametric memory used in the original RAG implementation. We also managed to replace the encoder for indexing the non-parametric memory and encoding the questions to a domain specific model, which improved the QA performance under the specific domain.
