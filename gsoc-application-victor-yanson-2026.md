## Project proposal
### High-level summary
…
### Context
#### What is closures.osm.ch?
…
#### Proposed project idea
…
### Problem
…

### Solution
#### Considerations
…
#### Basic architecture
```mermaid
graph TD
    DB[closures.osm.ch API] -->|"HTTP Poll"| B

    subgraph Server Environment
        direction TB
        B[Closure Sync Container]
        C[(Closure Overlay)]
        A[Valhalla Container]
    end

    B -->|"Generate / Update"| C
    A -->|"Read"| C
```
#### Internal pipeline
…
#### Additional information
…
#### Benefits & limitations
…
### Continuation
#### General
…
#### OSRM
…
#### Graphhopper
…
### Schedule for project completion
…
### AI use
…
