# System Diagram

```mermaid
flowchart TD
    A[Telegram] --> B[OpenClaw Runtime]
    B --> C[GPT-Powered Reasoning]
    C --> D[Local Scripts and Tools]
    D --> E[Machine Workflows]
    E --> F[Results / Updates]
    F --> A
```

## Plain-English view

1. A request comes in through Telegram.
2. OpenClaw receives and routes the request.
3. GPT-powered reasoning helps interpret the request.
4. Local scripts, tools, and workflows are used where appropriate.
5. The result is sent back through Telegram.
