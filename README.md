# Clean Architecture

Based on:  <https://app.pluralsight.com/library/courses/clean-architecture-patterns-practices-principles/>
By Mathew Renze
Source Code: https://github.com/matthewrenze/clean-architecture-demo

## History

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

### Application Layer

Overview

![image](https://user-images.githubusercontent.com/38001274/200128820-6153ad8a-2bae-4dc1-b53c-bde66ee01543.png)

Interfaces

![image](https://user-images.githubusercontent.com/38001274/200128890-671acaab-c15c-4db3-93f0-066ff918904e.png)


## CQS

### Single DB CQS

### 2 DB CQS

### Event Sourcing CQS
