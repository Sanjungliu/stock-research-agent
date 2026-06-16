# Glossary learned from building this app

- LLM: a Large Language Model which is one of type of model that created by Machine Learning. This model is specificly to handle text generation. How it is created is by feed a huge unstructured data into ML and teach it to store and give weight to the each token.
- Token: a chuncked section from a word. For example, word "Honestly" can be chuncked into "Honest", "Honestly" and "ly" token. Each of them having its own weight inside LLM.
- Weight: is an identifier/location that token have. During a training, ML will give each token a weight, which token that has close similarity with another token will have a closer gap of weight compared to other token that is not relevant.
- Agent: an system that utilize LLM and tools to achieve goals.
- Agentic System: a system that can autonomously doing action to achieve goals that determined to the agent.
- LangChain: framework that used to build an AI-powered application.
- LangGraph: framework from LangChain that built to orchestrate agentic workflow to several components and its connection with each component.
- Vector Database: a database that specificly to store the weight of tokens and its identifier or key.
- Chunk: process to separate a single word into several tokens. Chunk has several architecture with its advantage and disadvantage,
- Embedding: process to process tokens and give weight to each of them.
- Tool: functionality that used to accomplish goals. We can provide tools to LLM, and LLM will decide whether to use which tools to accomplish the target.
- Workflow: an end to end process from input (trigger) until agentic app return the result.
