### [时序图](https://github.com/knsv/mermaid#sequence-diagram)

```mermaid
sequenceDiagram
  Alice->>John: Hello John, how are you?
  loop Every minute
    John-->>Alice: Great!
  end
```

```mermaid
sequenceDiagram
  participant Alice
  participant Bob
  Alice->John: Hello John, how are you?
  loop Healthcheck
    John->John: Fight against hypochondria
  end
  Note right of John: Rational thoughts <br/>prevail...
  John-->Alice: Great!
  John->Bob: How about you?
  Bob-->John: Jolly good!
```
