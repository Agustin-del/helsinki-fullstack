```mermaid
sequenceDiagram
    actor user
    participant browser
    participant server
    user ->>browser: mensaje ->> save
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    activate server
    server-->>browser:REDIRECT https://studies.cs.helsinki.fi/exampleapp/notes
    deactivate server
    Note right of browser: se repite la secuencia puesta de ejemplo
```
