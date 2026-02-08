# VexoraDevelopment

VexoraDevelopment builds high-performance Minecraft: Bedrock server tooling and game infrastructure.

## What we build
- **Core engine forks** for Bedrock server development.
- **Practice platform modules** (`app`, `platform`, `domain`, `storage`) with clean boundaries.
- **Gameplay systems**: Hub, FFA, Duels, Training, ranks, cosmetics, statistics.
- **Ops tooling**: profiling, diagnostics, structured logging, runtime status commands.

## Architecture
- `app` - bootstrapping, runtime wiring, command registration.
- `platform` - adapters, services, UI/forms, game-facing integrations.
- `domain` - business logic, managers, use-cases.
- `storage` - persistence layer and data providers.

## Engineering principles
- Predictable module boundaries.
- Runtime safety first (deadlock avoidance, transaction discipline, watchdogs).
- Observability by default (debug traces, pprof, status metrics).
- Backward-compatible, incremental delivery.

## Current focus
- Stabilizing world/teleport transaction flows.
- Finishing duel/training lifecycle phases.
- Expanding ranked systems and moderation tooling.
- Improving hub UX, holograms, and cosmetic integrations.

## Repositories
- [platform](https://github.com/VexoraDevelopment/platform)
- [domain](https://github.com/VexoraDevelopment/domain)
- [storage](https://github.com/VexoraDevelopment/storage)
- [app](https://github.com/VexoraDevelopment/app)

## Contributing
We prefer focused PRs with clear scope and reproducible test steps.

If you want to collaborate on gameplay systems, infra, or engine-level work, open an issue or discussion in the target repository.
