# AI-Powered Troubleshooting Multi-Agent System using RAG and Langflow

## Project Overview

This project is an AI-powered troubleshooting system that helps users solve common technical problems.

The system uses Langflow to create a multi-agent workflow. A Router Agent analyzes the user's problem and sends it to the appropriate specialized troubleshooting agent.

## Problem Categories

The system supports four main categories:

- Laptop / Computer
- Network / Wi-Fi
- Printer / Peripheral
- Mobile Phone

## System Architecture

User
↓
Chat Input
↓
Router Agent
↓
Laptop Agent / Network Agent / Printer Agent / Mobile Agent
↓
RAG
↓
Troubleshooting Knowledge Base
↓
Google Gemini
↓
Chat Output

## Technologies Used

- Langflow
- Google Gemini
- Python
- RAG (Retrieval-Augmented Generation)
- Chroma Vector Database
- FAISS Vector Search

## Langflow Components

- Chat Input
- Router Agent
- Laptop Agent
- Network Agent
- Printer / Peripheral Agent
- Mobile Agent
- Read File
- Split Text
- Embedding Model
- Chroma
- FAISS
- Google Gemini / Language Model
- Chat Output

## Knowledge Base

The project contains a troubleshooting knowledge file with common problems and solutions related to:

- Laptop troubleshooting
- Network and Wi-Fi troubleshooting
- Printer troubleshooting
- Mobile phone troubleshooting

## Features

1. Automatic problem category detection.
2. Multi-agent troubleshooting.
3. RAG-based knowledge retrieval.
4. Vector similarity search.
5. Simple step-by-step troubleshooting instructions.
6. Safe troubleshooting recommendations.
7. Chat-based user interaction.
8. Support for multiple technical problem categories.

## Example Queries

### Laptop
"My laptop is very slow."

### Network
"My Wi-Fi is connected but there is no internet."

### Printer
"My printer is offline."

### Mobile
"My phone is overheating."

## Project Files

- `README.md` - Project documentation
- `troubleshooting_knowledge.txt` - Troubleshooting knowledge base
- Langflow workflow export - Complete Langflow workflow

## Future Scope

- Add more troubleshooting categories.
- Support multiple languages.
- Add voice-based interaction.
- Allow users to upload screenshots of errors.
- Add real-time diagnostic tools.
- Deploy the system as a web or mobile application.
- Expand the troubleshooting knowledge base.

## Author

Student Project
