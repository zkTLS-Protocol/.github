# zkTLS Labs

zkTLS Labs develops and maintains system infrastructure built around the zkTLS protocol.

The project focuses on enabling applications and developers to generate cryptographic proofs derived from real-world internet data through zkTLS-based verification workflows.

---

## Project Overview

zkTLS Labs builds system-level components that allow zkTLS to be used in practical environments.

While the zkTLS protocol provides the underlying cryptographic primitives, zkTLS Labs focuses on the engineering layer required to run zkTLS verification workflows reliably in real systems.

Repositories in this organization implement services and infrastructure that coordinate proof generation, manage verification workflows, and support integrations with external applications.

---

## Architecture

The zkTLS system architecture consists of several core components responsible for coordinating proof generation and verification workflows.

Typical components include:

- **Coordinator** – manages proof generation tasks and scheduling
- **TLS Proxy** – captures TLS session transcripts required for zkTLS
- **Proof Generation Pipeline** – generates zk proofs from captured data
- **Verification Tools** – validates generated proofs and manages verification workflows

Together these components provide a complete system layer around the zkTLS protocol.

---

## Ecosystem Role

zkPass provides the underlying zkTLS protocol and cryptographic verification framework.

zkTLS Labs focuses on building and maintaining the system infrastructure that enables developers and applications to operate zkTLS verification workflows in practice.

This separation allows the protocol layer and the system layer to evolve independently while remaining interoperable.

---

## Development Focus

Current development focuses include:

- improving zkTLS proof generation pipelines and execution reliability
- modularizing system components to support independent operation and maintenance
- enabling broader ecosystem participation in operating zkTLS infrastructure
- improving tooling and architecture to support decentralized deployment models

---

## Roadmap

Ongoing and future development directions include:

- further decentralizing the zkTLS system architecture
- enabling independent operators to run zkTLS infrastructure components
- improving scalability and performance of proof generation workflows
- expanding integrations with applications that rely on verifiable internet data

---

## Grant Support

Development of the zkTLS system maintained by zkTLS Labs is supported by a community grant from **zkPass**.

The grant supports continued development and maintenance of system infrastructure built around the zkTLS protocol.

---

## Maintainers

The zkTLS Labs repositories are maintained by an independent development team focused on zkTLS infrastructure and verification systems.
