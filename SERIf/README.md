### Summarization Module
Inspired by text summarization techniques using LLMs, the 'Extractive - Abstractive' two-step strategy is adopted. This approach selects key sentences from news articles and then generates a concise, cohesive summary, ensuring accuracy without unnecessary details.

### Sentence-level Evidence Retrieval Module
Key sentences are extracted from scientific articles to support or refute news claims. This module operates with precision, comparing sentences to specific queries and utilizing CORD-19 for focused evidence retrieval. An LLM aids in enhancing the effectiveness and accuracy of this process.

### Inference Module
The module evaluates the summarized news article's reliability based on the retrieved evidence sentences. It produces a binary output indicating the credibility of each news-evidence pair.
