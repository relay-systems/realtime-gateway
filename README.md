# realtime-gateway

Real-time gateway of Relay: handles WebSocket connections for real-time communication and routes messages between services.

**Status:** not implemented yet. This repository only holds the project setup.

## Planned stack

Go and WebSockets. No application code or `go.mod` exists yet; both will be added as a separate task.

## Planned responsibilities

Per the architecture overview:

- WebSocket handling for real-time communication
- Message routing between services
- Redis for presence tracking and caching (planned component, not yet provisioned)

## Related repositories

- `core-service`: application user profiles and core messaging logic
- `api-gateway`: single entry point for clients
- `infrastructure`: local PostgreSQL and ZITADEL (Docker Compose)

## Branches

`TASK_<kebab-case>` -> `test` -> `main`, both through pull requests, enforced by the `branch-policy` workflow. Feature branches are created from `test`.
