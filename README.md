# AI Knowledge Vault  

Welcome to the AI Knowledge Vault template. This repository provides a skeleton for an Obsidian-compatible vault that you can use as a starting point for organising your research, projects and knowledge graphs, especially for retrieval-augmented generation (RAG) workflows.  

## Folder Structure  

- `01_Projects/`  
  This folder contains project-specific notes. Use it to collect all the documents, tasks and resources related to each project.  

- `02_Docs/`  
  General documentation and reference material.  

- `03_KnowledgeGraph/`  
  Notes that form the core of your knowledge graph, such as topics, entities and their relationships.  

- `templates/`  
  Contains reusable note templates and guidelines. The file `AI-tagging-guidelines.md` explains how to tag your notes so that AI models can understand them.  

## Importing into Obsidian  

1. Clone this repository or download it as a ZIP.  
2. Open Obsidian and choose **Open folder as vault**.  
3. Select the `ai-knowledge-vault` directory. Obsidian will load the folder and recognise the markdown files as notes.  

## Customising for RAG Workflows  

Retrieval-Augmented Generation workflows depend on well-structured and tagged notes. To customise this vault:  

- Use consistent frontmatter in your notes (e.g. `title`, `tags`, `aliases`). This makes it easier for retrieval systems to parse the content.  
- Organise related notes within the appropriate folders.  
- Follow the guidelines in `templates/AI-tagging-guidelines.md` to tag entities, relationships and metadata.  
- Consider adding a plugin like **Dataview** or **Omnisearch** in Obsidian to perform structured queries over your knowledge base.  

Feel free to modify the folder structure or add your own templates to suit your needs. Pull requests and suggestions are welcome!
