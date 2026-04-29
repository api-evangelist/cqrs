# CQRS (cqrs)

Command Query Responsibility Segregation (CQRS) is an architectural pattern that separates read and write operations for a data store into distinct models. Commands mutate state and produce events; queries return data optimized for the read side. CQRS is frequently combined with Event Sourcing, Domain-Driven Design (DDD), and message-based integration to scale complex domains.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cqrs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** Open Source
- **x-type:** topic

## Tags

- Architecture, Command Query Responsibility Segregation, Commands, CQRS, Domain-Driven Design, Event Sourcing, Events, Patterns, Queries, Read Models

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

CQRS is a software architectural pattern, not an API. This index captures key references, foundational essays, pattern guidance from cloud providers, and ecosystem frameworks that implement CQRS.

## Key References

- [Martin Fowler on CQRS](https://martinfowler.com/bliki/CQRS.html)
- [Greg Young CQRS Documents (PDF)](https://cqrs.files.wordpress.com/2010/11/cqrs_documents.pdf)
- [Microsoft CQRS Pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs)
- [AWS CQRS Pattern](https://docs.aws.amazon.com/prescriptive-guidance/latest/modernization-data-persistence/cqrs-pattern.html)
- [Command-Query Separation (Fowler)](https://martinfowler.com/bliki/CommandQuerySeparation.html)
- [Event Sourcing Pattern](https://microservices.io/patterns/data/event-sourcing.html)
- [DDD Community](https://www.dddcommunity.org/)

## Implementation Frameworks

- [Axon Framework](https://www.axoniq.io/products/axon-framework)
- [EventStoreDB](https://www.eventstore.com/)
- [NServiceBus](https://particular.net/nservicebus)
- [MediatR (.NET)](https://github.com/jbogard/MediatR)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
