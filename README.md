# Agentic RAG com CrewAI

Este projeto implementa um sistema de Retrieval-Augmented Generation (RAG) baseado em agentes utilizando o framework CrewAI e ferramentas do LangChain. O objetivo é criar um chatbot de suporte técnico capaz de consultar informações em um banco de dados SQL e em um manual PDF.

## Principais características:

- Utiliza CrewAI para orquestração de agentes
- Integração com AWS Bedrock (Claude 3.5 Sonnet)
- Banco de dados SQLite com informações de tickets
- Base vetorial FAISS para busca semântica em documentos
- Dois agentes especializados: Data Retriever e Support Specialist

Para mais detalhes sobre a implementação e funcionamento, consulte o notebook Jupyter no repositório.
