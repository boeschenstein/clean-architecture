# Clean Architecture

## History

- Oninon Architecture
- Port and Adapter

## Principle

### Classic 3 Layer

```mermaid
stateDiagram-v2

    state UI {

        state Business-Logic {

            state Data-Access {

                Database
            }
        }
    }
```

## CQS

### Single DB CQS

### 2 DB CQS

### Event Sourcing CQS
