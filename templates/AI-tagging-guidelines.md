# AI Tagging Guidelines  

To make your notes AI-friendly for retrieval and generation:  
- Always include YAML frontmatter at the top of each note with fields like `title`, `tags`, `aliases`, and `created`.  
- Use descriptive tags (e.g., `project`, `research`, `concept`, `person`) to categorize notes and enable semantic search.  
- Establish links between notes using Obsidian's wikilinks syntax `[[Note Name]]` to build a knowledge graph.  
- Keep filenames concise and use kebab-case for cross-platform compatibility.  
- For entities and concepts, add `type` fields (e.g., `type: entity` or `type: relation`) in the frontmatter to distinguish them in RAG pipelines.
