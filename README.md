# Agentic AI coding intern


## Core structure
```text
langgraph-coder/
│
├── deploy.py                 # (NEW) Script to push the agent to Vertex AI
├── requirements.txt          # (UPDATED) 
├── main.py                   # Compiles the graph and exposes the agent
│
└── src/
    ├── __init__.py
    ├── state.py              
    ├── schemas.py            
    ├── llm.py                # (UPDATED) Initializes Gemini Flash
    │
    └── nodes/
        ├── __init__.py
        ├── coder.py          # (UPDATED) Injects system prompts natively
        ├── tester.py         
        └── executor.py
```