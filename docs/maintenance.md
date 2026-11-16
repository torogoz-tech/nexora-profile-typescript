# Profile maintenance

This profile is maintained independently from the Nexora engine and from every other language profile. A change should be understandable from the YAML diff and reproducible with fixtures.

## Change procedure

1. Describe the language construct in human terms.
2. Update only the relevant profile contract.
3. Add a valid fixture and, when useful, a partial or rejected fixture.
4. Run schema and domain validation with a compatible Nexora API version.
5. Inspect tokens, syntax, graph output, evidence, diagnostics, and coverage.
6. Record compatibility and limitations in the release notes.

Do not claim complete language support because one fixture passes. Preserve ambiguous, unresolved, rejected, and not-assessed outcomes. Profile releases use version `0.1.0` in this publication preparation.

