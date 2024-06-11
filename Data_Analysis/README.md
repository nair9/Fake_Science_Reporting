## Dataset
The SciNews dataset encompasses a vast collection of scientific news articles, each paired with corresponding technical scientific publications. With 2,400 articles in total, evenly distributed between Reliable and Unreliable categories, it provides a balanced representation. Each news article is linked with up to three relevant scientific abstracts from the extensive CORD-19 repository, known for its vast array of scholarly articles, including a significant focus on COVID-19.

## Dataset Analysis
Upon further analysis of the SciNews Dataset, the following observations were noted:

- In human-written articles, the maximum number of sentences per article is 557, with a minimum of 6. The average number of sentences per article is 54.49, and the average number of words per sentence across all articles is 19.39.
- For LLM-generated articles, the maximum number of sentences per article is 35, with a minimum of 1. The average number of sentences per article is 8.24, and the average number of words per sentence across all articles is 21.88.

Visualizing the distribution of sentence length and the average number of sentences in the dataset, it is evident that human-written articles tend to be longer than LLM-generated ones. This difference arises due to the token limit imposed on LLM outputs, as the input prompt includes the abstract from a scientific paper, consuming a significant portion of token allocation and limiting the length of LLM-generated articles.

Despite this discrepancy, the distributions of sentence length in human-written and LLM-generated articles are remarkably similar. Further analysis reveals a high consistency in the distribution of sentence lengths between the two, suggesting that LLMs are capable of producing articles that closely mimic human writing.
