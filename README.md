# Nexora typescript Analysis Profile

This repository contains the independent Nexora analysis profile for **typescript** (`typescript`). The profile is declarative data consumed by a compatible `nexora-api` engine; it does not execute source code.

## Version

Initial public version: `0.1.0`.

## Contents

- `profile/` lexer, grammar, language, and graph definitions.
- `fixtures/` representative source inputs.
- `tests/` profile-specific verification space.
- `docs/` capabilities, limitations, compatibility, and verification.

## Use

Pass the `profile/` directory to a compatible Nexora CLI or API installation. The engine remains responsible for validation, resource limits, evidence, and authorization.

## License

MIT. See `LICENSE`.
