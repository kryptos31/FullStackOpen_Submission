
```mermaid
sequenceDiagram
Browser->>Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
Note left of Server: Server requests new HTTP GET with URL redirect
Server->>Browser: Great!
```
