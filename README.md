# ARDEN - AI-Driven Game Narrative Editor

ARDEN (AI-Driven Game Narrative Editor) extends Microsoft's GENEVA research by implementing a native editor architecture for game narrative design. It provides a unified platform for game narrative development with AI assistance, persistent state management, and direct game engine integration.

## Project Components

- **[ARDEN Studio Web](https://github.com/ARDEN-MC/arden-studio-web)** - React frontend
- **[ARDEN Studio API](https://github.com/ARDEN-MC/arden-studio-api)** - FastAPI backend
- **[ARDEN Studio Data Service](https://github.com/ARDEN-MC/arden-studio-data-service)** - Node.js data service

## Key Features

- **Unified Platform**: Handles all stages of narrative development
- **AI-Assisted Graph Construction**: Automates graph creation while maintaining human creative control
- **Persistent Conversational Context**: Enables iterative refinement of narrative elements
- **Direct Game Engine Integration**: Provides Unity integration through a custom Unity package
- **Narrative Coherence Management**: Ensures consistency across complex narrative structures

## Technical Architecture

- **Frontend**: React-based UI with resizable panel system and SVG-based graph rendering
- **Backend**: Python application server with AI workflow orchestration and Node.js database service
- **Data Layer**: PostgreSQL for user authentication, project storage, and relationship mapping
- **AI Pipeline**: LangGraph workflow management with OpenAI GPT models and vector embeddings
- **Unity Integration**: JSON export format with runtime parser for Unity compatibility

## McMaster University Computer Science Undergraduate Capstone Project
