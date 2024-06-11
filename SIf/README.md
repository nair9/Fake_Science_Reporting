## SIf
The second architecture, SIf, is a modified version of the first architecture, SERIf. In SIf, the evidence retrieval module from SERIf is removed, retaining only the Summarization and Inference modules. The summarization module operates in the same manner as in SERIf.

However, the inputs to the inference module differ. Instead of prompting the LLM with the news-evidence pair, the LLM is prompted to directly assess the credibility of the provided news summary. It offers justifications based on the paired scientific abstracts from the evidence corpus in the SciNews dataset.
