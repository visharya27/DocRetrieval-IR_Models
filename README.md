# DocRetrieval-IR_Models
Document Retrieval using Boolean Retrieval and Vector Space Model.

Implemented and Compared two Spell Check and correction method - 1. Using Edit Distance 2. Using Jaccard Coefficient.
Then compared two Information Retrieval Modals - Boolean Retrieval and Vector Space Model.

Boolean Retrieval Model
The Boolean Retrieval Model is a basic information retrieval model that uses Boolean logic to retrieve documents based on search queries. It's a simple yet powerful model that allows users to search for documents using Boolean operators like AND, OR, and NOT.
Key Features:
Binary Retrieval: Documents are either relevant or not relevant to the search query.
Boolean Operators: AND, OR, and NOT are used to combine search terms.
Exact Matching: Documents must contain exact matches of the search terms.
Example:
Search Query: (coffee OR tea) AND India
Retrieves documents that contain either "coffee" or "tea" and also contain "India".


Vector Space Model (VSM)
The Vector Space Model (VSM) is a more advanced information retrieval model that represents documents and search queries as vectors in a high-dimensional space. This allows for more nuanced and relevant search results.
Key Features:
Vector Representation: Documents and queries are represented as vectors, where each dimension corresponds to a term or feature.
Term Weighting: Terms are weighted based on importance, using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).
Similarity Measurement: Documents are ranked based on their similarity to the query vector, using metrics like cosine similarity.
How it Works:
Document Representation: Documents are converted into vectors, where each dimension represents a term's weight.
Query Representation: Queries are also converted into vectors.
Similarity Calculation: The similarity between the query vector and each document vector is calculated.
Ranking: Documents are ranked based on their similarity scores.
Example:
Search Query: "machine learning"
VSM represents the query as a vector, with weights for related terms like "AI", "deep learning", etc.
Documents are represented as vectors, with weights for terms like "machine learning", "natural language processing", etc.
Similarity scores are calculated, and documents are ranked accordingly.
