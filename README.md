# Chatbot for Python Queries
A chatbot that answers queries related to Python programming language. The chatbot is built using the Python StackOverflow questions dataset obtained from Kaggle (https://www.kaggle.com/stackoverflow/pythonquestions).

Its a retrieval chatbot where the answer displayed is based on the Cosine Similarity betweeen the question asked and the questions present in the dataset. To avoid huge computation, a Tagger has been built which classifies the questions under the tags into which it will fall, and a retrieval is done based on those tags. 

## Future Scope
1. Inclusion of Huggingface Transformers for better performance.
2. Adding speech recognization.
3. Extending it to other programming languages.
