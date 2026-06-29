'''mermaid
flowchart TD
A([Start]) --> B[/INput grade/]
B --> C{Is grade >= 60?}
C -- Yes --> D[/Display Passed/]
C -- No --> E[/Display/ Failed/]
D --> F([End])
E --> F
'''


