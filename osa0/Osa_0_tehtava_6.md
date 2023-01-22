
sequenceDiagram
    participant browser
    participant server
    
    browser->>server: POST new_note_spa.json
    activate server
    server-->>browser: 201
    deactivate server
    
   
