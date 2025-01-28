# Advanced Rag

<h1> 1) Chunking </h1>





<h1> 2) Embedding </h1>


<h1> 3) Retrieval </h1>

(a) Sentence-window retrieval
How it Works:
Instead of retrieving entire documents or long passages, this method retrieves smaller sentence-level context windows.
When a query is made, the pipeline selects the most relevant sentences based on embedding similarity.
A sliding window approach ensures that adjacent sentences are included, maintaining context and coherence.
Benefits:
Reduces the chance of retrieving irrelevant content.
Ensures that LLMs generate responses grounded in precise, high-quality information.
(b) Auto-merging retrieval
How it Works:
After retrieving multiple relevant text chunks, this method merges overlapping or complementary passages dynamically.
Uses semantic similarity to combine text pieces that reinforce each other, ensuring a more comprehensive response.
This can involve techniques like fuzzy matching or vector clustering to consolidate related information.
Benefits:
Reduces redundancy and prevents conflicting information.
Enhances the completeness of retrieved context, leading to better-grounded responses.
