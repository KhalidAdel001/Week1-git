1. **Token:** a small piece of text (a word, part of a word, or a character) that the model reads and writes instead of whole words; in English, about 4 characters is 1 token, and Arabic usually needs more tokens for the same sentence.
2. **Context window:** the maximum number of tokens the model can see at one time (your prompt, the chat history, and its own answer together); anything beyond this limit is cut off or causes an error.
3. **Temperature:** a setting that controls randomness; a low value gives safe, repeatable answers, and a high value gives more varied and creative answers but with more mistakes.
4. **Cost:** you pay per token, with a separate price for input and output (output costs more): cost = input tokens × input price + output tokens × output price.
5. **What an LLM cannot do reliably:** it can hallucinate, meaning it can invent facts or sources and sound completely sure, so its answers must be checked before anyone trusts them.
