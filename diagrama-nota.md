```mermaid
secuenceDiagram

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    server-->>browser:REDIRECT https://studies.cs.helsinki.fi/exampleapp/notes
     

```
