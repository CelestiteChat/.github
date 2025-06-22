# Celestite

**Celestite** is a modular, scalable, open source chat platform inspired by Discord. It is designed from the ground up using a distributed microservices architecture written entirely in Go. Every component is purpose-built for performance, portability, and low external dependencys.

## About the Project

Celestite is not a monolith. It is a collection of specialized services that together form a full-featured chat system, with both frontend and backend components. Each piece is developed to run independently, allowing for horizontal scaling and service isolation.

### Key Features

- Channel- and server-based communication
- Real-time messaging with message history
- Role-based permissions and moderation tools
- Custom embedded database system (Strontium)
- Image processing and CDN handling
- Clients for web/desktop (Selenite) and mobile (Lazulite)
- Documentation and clean architecture across services

## Repositories

Here’s a breakdown of the main components that make up Celestite:

- [`Celestite`](https://github.com/CelestiteChat/Celestite): Main entry and overview of the system
- [`Peridotite`](https://github.com/CelestiteChat/Peridotite): Backend services written in Go
- [`Strontium`](https://github.com/CelestiteChat/Strontium): Custom embedded database for all services
- [`Ilmenite`](https://github.com/CelestiteChat/Ilmenite): Image processor and media handling service
- [`Selenite`](https://github.com/CelestiteChat/Selenite): Web and desktop UI built with modern frameworks
- [`Lazulite`](https://github.com/CelestiteChat/Lazulite): Mobile client developed with Flutter
- [`celestite-docs`](https://github.com/CelestiteChat/celestite-docs): Full project documentation

## Architecture Philosophy

Celestite is structured for clarity and modularity:

- Each microservice maintains its own data using Strontium
- No external databases, no Redis or third-party caching
- Services are compiled Go binaries with zero runtime dependencies
- All components are open source and documented

## Development Status

The project is in active development. Each repository is independently versioned and regularly updated. You can follow progress across services or contribute to individual modules.

## Get Involved

We welcome developers interested in contributing to a clean, modular, and modern communication stack. Whether you’re interested in backend architecture, database design, frontend UI, or mobile UX, there’s a place to help.

Feel free to explore the code, open issues, or reach out with questions and ideas.
