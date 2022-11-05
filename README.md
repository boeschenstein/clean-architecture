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

### Domain Centric approaches

- Hexagonal: https://alistair.cockburn.us/hexagonal-architecture/
- Onion: https://jeffreypalermo.com/2008/07/the-onion-architecture-part-2/
- Clean: https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html
- Comparison aka it's all the same: https://blog.ploeh.dk/2013/12/03/layers-onions-ports-adapters-its-all-the-same/

## CQS

### Single DB CQS

### 2 DB CQS

### Event Sourcing CQS
