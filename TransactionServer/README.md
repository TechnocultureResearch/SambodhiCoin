# Transaction Server

## Architecture
```mermaid
flowchart TB

D[IOT Device] --> |HTTPS| I[AWS IOT Core]
I --> R{AWS IOT Rule}
R --> SM[SMS API]
R --> Lambda
subgraph Lambda
F[FastAPI]
end
F --> S[(Supabase Postgres)]

<!-- AWS IOT Core -> AWS IoT Rule -> AWS Lambda -> FastAPI -> Supabase -->
```