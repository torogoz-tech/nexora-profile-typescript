# Nexora TypeScript analysis profile

This repository independently maintains the declarative Nexora profile for TypeScript (`typescript`). It recognizes the documented TypeScript subset without compiling or executing projects.

`language.yaml`, `lexer.yaml`, `grammar.yaml`, and `graph.yaml` define the profile contract. Fixtures, reports, and limitations define the real support boundary. Validate with a compatible `nexora-api` `0.1.0` engine. Profile version: `0.1.0`.

## Architecture and stewardship

Nexora's architecture and the independent profile model are led by [Abner Velasco](https://www.linkedin.com/in/abnervelasco/), who is also responsible for the ongoing maintenance and evolution of this profile repository. Profile changes remain independently versioned, tested, and reviewed.

MIT. See `LICENSE`.
