# Mermaid Diagrams

## Sequence

```mermaid
sequenceDiagram

Actor ui as UI
participant db as DB

ui ->> api : Call
api ->> db : Call
db ->> api : Value
api ->> ui : Value

loop
api ->> ui : Value
end
```

```mermaid
classDiagram

a --> b
```
