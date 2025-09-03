#1 Asistente de Investigación Inteligente (Multi-Agente + RAG)

Sistema multi-agente colaborativo para investigar un tema, buscar y curar fuentes en la web y redactar un informe final con citas. Construido con CrewAI para la orquestación, 
LangChain para herramientas/RAG, DuckDuckGo para búsqueda sin claves, y OpenAI para el razonamiento del LLM. Incluye ejemplo de RAG con FAISS.

#2 ¿Qué hace?

Explorador: entiende la consulta y busca en la web (DuckDuckGo).

Curador: filtra ruido y elige fuentes confiables.

Sintetizador: resume hallazgos y evidencia.

Redactor: entrega un informe claro con citas/URLs.

Flujo: Usuario → (Explorador → Curador → Sintetizador → Redactor) → Informe final.

#3 Stack

Python

CrewAI (orquestación multi-agente)

LangChain / langchain-community (herramientas, RAG)

DuckDuckGo Search (duckduckgo-search) – sin API Key

OpenAI (Chat/Responses) – requiere API Key

FAISS (vector DB local para RAG)

Embeddings:

OpenAI (text-embedding-3-large) o

HuggingFace (mixedbread-ai/mxbai-embed-large-v1)


#4 Licencia

Libre uso educativo. Ajusta según la política de tu organización.

#5 Agradecimientos

A la comunidad de CrewAI, LangChain y al ecosistema open-source por facilitar el desarrollo de sistemas basados en agentes.
