<div align="center">
  <br />
  <a href="https://github.com/Vaquum"><img src="https://github.com/Vaquum/Home/raw/main/assets/Logo.png" alt="Vaquum" width="150" /></a>
  <br />
</div>
<br />
<div align="center"><strong>Vaquum Veritas turns four independent module truths into one observable, attestable, queryable system-wide record.</strong></div>
<br />
<div align="center">
  <a href="#veritas">Veritas</a> •
  <a href="#what-veritas-is-not">What Veritas Is Not</a> •
  <a href="#capabilities">Capabilities</a> •
  <a href="#first-release">First Release</a> •
  <a href="#learn-more">Learn More</a>
</div>


<hr />

# Veritas

Veritas is the source of truth for system-wide convergence across Vaquum. It turns four independent module truths into one observable, attestable, queryable system-wide record without displacing source authority.

Veritas asynchronously projects the event streams from Origo, Limen, Nexus, and Praxis into a single unified read model with provenance pointers to every source event. It is the one place where all truths converge: the god view across the system that turns system-wide observability into actionable insight.

## What Veritas Is Not

Veritas is not:

- a replacement for source authority in Origo, Limen, Nexus, or Praxis
- a synchronous control plane for the four upstream modules
- a generic analytics surface detached from provenance, attestation, and replay

In the wider Vaquum architecture, Origo, Limen, Nexus, and Praxis remain the authoritative producers. Veritas sits across them as the convergence layer for observability, attestation, verification, and auditability.

## Capabilities

- Asynchronous convergence projection of all module event streams into one unified read model with provenance pointers to every source event
- End-to-end lineage from Origo data partitions through Limen signals and Nexus decisions to Praxis fills, traversable in both directions
- Decision-time attestation of the exact data state, model version, features, and risk conditions each action actually consumed
- Cross-module boundary verification detecting mismatches between what one module emitted and the next consumed
- Full-lifecycle P&L and cost attribution across Origo liquidity, Limen signal quality, Nexus capital rules, and Praxis execution costs
- Policy enforcement visibility with structured reasoning traces for every allow, block, and abort across the system
- Active anomaly detection and regression surveillance for cross-module inconsistencies and behavioral drift
- Point-in-time system-wide state reconstruction and replay across all four modules
- Cross-module queries indexed by Bitcoin-native dimensions including block height, halving epoch, and regime alongside wall-clock time
- Auditor query library progressing from LLM-assisted exploration to hardened deterministic queries with audit-ready export

## First Release

```python
# Veritas will have its first release in Q3/2026.
```

## Learn More

- Start with the developer docs in [docs/Developer/README.md](docs/Developer/README.md)

## Contributing

The simplest way to start contributing is by [joining an open discussion](https://github.com/Vaquum/Veritas/issues?q=is%3Aissue%20state%3Aopen%20label%3Aquestion%2Fdiscussion), contributing to [the docs](https://github.com/Vaquum/Veritas/tree/main/docs), or by [picking up an open issue](https://github.com/Vaquum/Veritas/issues?q=is%3Aissue%20state%3Aopen%20label%3Abug%20OR%20label%3Aenhancement%20OR%20label%3A%22good%20first%20issue%22%20OR%20label%3A%22help%20wanted%22%20OR%20label%3APriority%20OR%20label%3Aprocess).

Before contributing, start with [docs/Developer/README.md](docs/Developer/README.md).

## Vulnerabilities

Report vulnerabilities privately through [GitHub Security Advisories](https://github.com/Vaquum/Veritas/security/advisories/new).

## Citations

If you use Veritas for published work, please cite:

Vaquum Veritas [Computer software]. (2026). Retrieved from https://github.com/Vaquum/Veritas.

## License

[MIT License](https://github.com/Vaquum/Veritas/blob/main/LICENSE).
