

# OCI GEN AI Agents - Architure

## Interface

This is the point where the user interacts with the AI agent. It can be a chatbot, a web app, a voice interface, or any application where the user inputs a query or a command. The system feeds various inputs to large language model.

## Short/Long Term Memory
It can provide context from past interactions, enabling continuity and relevance in conversations.

## Tools
different external tools, for example, different APIs, databases, or third-party systems to enhance the model's capabilities.

## Prompt
It contains the specific query or task provided by the user guiding the AI on how to generate responses. And at the heart of the system.

## Large language model (LLM)
It basically performs four key operations, reasoning, acting, persona, and planning. 
- Reasoning, it analyzes the input to generate logical and coherent responses. 
- Acting, it determines actions based on the task, for example, whether it's about querying databases or calling different APIs. 
- Persona is maintaining a consistent tone, style, and behavior aligned with the brand or use case. 
- planning, that is strategically organizing responses or actions, especially in multi-step workflows.

## Knowledge
The LLM can also access external knowledge bases, such as databases or document repositories, to enrich its responses with accurate and up-to-date information. You have already seen a use case of RAG. This allows the agent to go beyond just its internal training data.

![OCI AI Agent Architecture.](./images/oci_gen_ai_arch.png)


# Agent Concepts

- Generative AI Model : A large language model trained on large amout of data.
- Agent : An LLM based autonomous system that understands and generates human like text with high answerability and groundedness.
- Knowledge Base : An agent connects to a knowledgebase which is a vector based storage that can connect to and ingest data from a data source. Examples :- object storage buckets or databases.
- Data Source and Data Store : The data source, it provides connection details to the data store, enabling the agent to access and retrieve data. The knowledge base is basically the vector storage system that ingests data from the data source, organizing it for efficient retrieval and use by the agent. And this structure ensures that agents can seamlessly access and utilize the necessary information to generate informed responses.
- Data Ingestion : A process that extracts data from data source document and coverts it into a structured format suitable for analysis and then stores it in a knowledge base.













This site was built using [GitHub Pages](https://pages.github.com/).
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

