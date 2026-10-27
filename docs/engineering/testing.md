# Testing and Quality

**Status:** Proposed baseline.

Testing should match risk and architecture:
- Unit tests for business logic
- Integration tests for databases, APIs, and service boundaries
- End-to-end tests for critical user journeys
- Security tests for authorization boundaries and sensitive flows
- Regression tests for fixed defects
- AI/ML evaluation sets, baselines, error analysis, and reproducibility checks for research systems

Do not claim coverage or quality gates without CI evidence. Define per-repository commands, thresholds, test data handling, and release criteria in that repository's documentation.
