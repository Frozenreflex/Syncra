# Syncra

A game-engine engine with a focus toward networked VR and desktop use cases. Isomorphic to a butterfly.

The overall philosophy is to only use the minimum required crates/packages to conform to existing specifications. Anything that isn't a specification should be implemented directly.

## Current Goals

- Networking
- VR and desktop support
- Efficient state synchronization
- Rendering
- Cross-platform support
- Extensible architecture allowing different data models to be downloaded and used at runtime
- In-game scripting using a paradigm that has a graph-code isomorphism
- Physics
- Architectural inspirations from various topics in pure math, like type theory, category theory, and homotopy type theory
- In-game shader graphs, also with a graph-code isomorphism
- In-game asset creation tools
- Editor tools
- Multithreading
- Native plugin/mod support
- API and architecture documentation
- Asynchronous rendering
- Decentralized networking authority
- HDRP-like rendering specification

## Research Topics

- What crates to use?
- How much to focus on manual implementation of platform-specific differences?
- How will C# tie into the architecture?
- Will ECS patterns work well here?
- How to modularize the data model while making it safe?
- The general strategy here seems to be to use high-level crates/libraries to start off and gradually reimplement them in lower-level ways as needed.
