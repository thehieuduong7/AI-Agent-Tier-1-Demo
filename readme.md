# AI Agent Tier 1 - Demo

## Use Case

This project demonstrates an AI Agent acting as a **Tier 1 Engineer**:
- Receives alerts from monitoring systems.
- Collects and analyzes relevant monitoring data based on each alert type.
- Notifies customers with a clear status update and action context.

## System Architecture

The high-level architecture is shown below:

![Overview Architecture](Overview%20Architecture.png)

### Flow (from architecture)
1. Smart NOC sends an alert/problem.
2. Agent generates tasks based on defined guidelines/instructions.
3. Single task agent executes tasks in a loop.
4. Agent fetches data, updates state with results, and can send Microsoft messages.
5. Agent replans tasks if needed, then ends when complete.
6. Monitoring/observability traces and monitors AI system behavior.
7. Customer reads message updates in MS Teams channel.

## Tech Stack

- LangGraph
- LangChain
- FastMCP
- LangSmith
- MongoDB (as VectorStore)
- Azure OpenAI
- Microsoft Graph API
- LiteLLM

## Demo

- Demo video: [Demo AI](Demo%20AI%20Agent%20tier%201.mp4)

## Git Repository

- URL: _I will paste url later_
