```mermaid
flowchart TD
A([Start]) --> B[/Input number/]
B --> C{Is number >= 0?}
C -- Yes --> D[/Display Positive/]
C -- No --> E[/Display Negative/]
D --> F([End])
E --> F
```