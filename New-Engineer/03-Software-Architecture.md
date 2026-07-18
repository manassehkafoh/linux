# 03 Software Architecture

Architecture defines the high-level structure of a system.

## Architectural Patterns
- **Monolith:** All components are bundled into a single unit. Easy to develop initially but can become hard to scale and maintain.
- **Microservices:** The application is broken down into small, independent services that communicate over a network. Easier to scale but introduces complexity in deployment and networking.
- **Serverless:** Outsourcing server management to a cloud provider. You pay only for what you compute.

## Design Patterns
Design patterns are reusable solutions to common problems in software design.
- **Creational:** E.g., Singleton, Factory. Deal with object creation mechanisms.
- **Structural:** E.g., Adapter, Decorator. Deal with object composition.
- **Behavioral:** E.g., Observer, Strategy. Deal with communication between objects.

## SOLID Principles
- **S:** Single Responsibility Principle
- **O:** Open/Closed Principle
- **L:** Liskov Substitution Principle
- **I:** Interface Segregation Principle
- **D:** Dependency Inversion Principle
