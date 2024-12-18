# Dual RAG with LLMs for contextualization and factual accuracy

To run, initialize a `DualRagModel` instance as follows:
`model = DualRagModel()`

Logging and generator models can be changed (see comments in code).

To submit queries, use the `generate_response` method:
`user_query = "who shot the uhc ceo"`
`response = model.generate_response(user_query)`
