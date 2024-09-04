# gas turbine

```mermaid
graph LR
    A[air] --> B[compressor]
    B --> |cd|C[combustor]
    c[fuel] --> C[combustor]
    C --> |comb|D[nozzle]
    D --> |fire|E[expander]
    E --> F[exh]

    B --> |cool| D
    B --> |bleed| E
