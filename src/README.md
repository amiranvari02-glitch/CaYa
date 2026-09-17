# Caya Source Structure

This directory is the implementation root for the Caya application.

- `ui/` — reusable user-interface components and layout logic
- `modules/` — engineering domain modules
- `services/` — shared application services
- `data/` — data access and controlled master-data interfaces
- `calculation/` — shared calculation infrastructure

The current MVP remains a browser-based static application shell. Backend and database services will be introduced without changing the domain ownership model defined by CSAS v1.0.
