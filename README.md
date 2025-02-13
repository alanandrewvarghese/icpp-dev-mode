# icpp-dev-mode

# sYs aRcH sMpL

```mermaid
graph TD;
    A["Frontend (React)"] -->|API Calls| B["API Gateway (Django REST Framework)"];
    B -->|Handles Requests| C["Backend (Django)"];
    C -->|Executes Logic| D["Code Execution (Python Sandbox)"];
    C -->|Stores Data| E["Database (PostgreSQL)"];


    subgraph Frontend
        A
    end

    subgraph Backend
        B
        C
    end

    subgraph Execution
        D
    end

    subgraph Data
        E
    end
```
