# Chat with context
- parses pdf into pages
- stores pages into embeddings db (context)
- looks up query in embeddings db
- passes query / context to gpt
- return response

# Deps:
- chromadb (req pydantic=1.9.0)
- openai
- tokenizers
