# Project Constitution

The owning team's agreed standards take precedence over these shared rules. **MUST** marks a requirement. **SHOULD** marks a default that may be overridden with a documented reason. In a Spec Kit plan's **Constitution Check**, record how the proposed change meets each applicable rule and explain any conflicts or departures.

## Core Principles

### I. Inspect Before Planning

Before planning a material change, you **MUST** establish the intended behavior and relevant constraints, inspect the affected parts of the existing system, and record the findings that shape the plan. You **MUST** record unverified assumptions that could change the plan and how they will be checked.

**Rationale:** Plans grounded in the system as it exists are less likely to miss constraints or redo work.

### II. Keep the Change Focused

Changes **MUST** stay within the agreed scope, and the team **MUST** agree before that scope expands. Changes **SHOULD** deliver the smallest increment that meets the agreed outcome and defer unrelated work.

**Rationale:** A focused change is easier to review and gives the team feedback sooner.

### III. Justify New Boundaries

A new application **SHOULD** start with one deployable unit when it meets the known needs. Before adding a service, queue, datastore, or architectural layer, the plan **MUST** state the need it meets, why a simpler option is insufficient, and what it adds to development or operations.

**Rationale:** Boundaries can solve real problems, but they also create costs the team will have to carry.

### IV. Test at the Right Layer

Every change **MUST** have a verification plan that says what behavior to check and at which layer. Before merge, you **MUST** report which checks ran, their results, and any gaps. Verification **SHOULD** use practical automated regression checks at the simplest layer that can catch the failure, and CI checks **SHOULD** be reproducible locally where possible.

**Rationale:** Checks that match the behavior give useful evidence, and visible gaps let reviewers judge what remains unverified.

### V. Merge in Reversible Chunks

Each merge **MUST** leave the project working without relying on a follow-up merge. If reverting the code would not restore safe behavior, the change **MUST** document how to recover before it merges. Each repository chooses its own merge strategy.

**Rationale:** Independently working changes limit disruption and give the team a clear recovery path.

---

Source: speckit-constitution contributors. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
