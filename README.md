# mosaic-ai-agent-demo

```mermaid
%%{init: {'theme': 'neutral'}}%%
graph LR;
  A[Agent] --> T1[SQL Lookup]
  A --> T2[Similarity Search]
  A --> T3[Image Generation]
  A --> T4[Messaging]
  subgraph Tools
    T1
    T2
    T3
    T4
  end
```
