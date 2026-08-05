# file-tunnel-test organization handbook

> Shared operating defaults for repositories maintained under **file-tunnel-test**. Repository-local policy may strengthen these rules but should not silently weaken them.

## Mission

file-tunnel-test maintains isolated fixtures, compatibility scenarios, and end-to-end validation for file-tunnel clients, servers, protocols, and infrastructure. This `.github` repository is the canonical home for shared policy, reusable templates, community health files, and planning links.

## Repository contract

Each active repository must document its test objective, ownership, maturity, supported transports and platforms, reproducible setup and teardown commands, authoritative fixtures and expected results, compatibility scope, and GitHub Project/Linear links. Test systems should also document isolation, synthetic-data requirements, credentials and secret handling, ports and resources, cleanup, timeouts, determinism, fault injection, artifact retention, and destructive-operation safeguards.

## Change workflow

1. Anchor work in an issue, Linear item, or documented validation objective.
2. Keep branches and pull requests focused.
3. Explain the behavior covered, scope, validation, compatibility impact, and cleanup or rollback.
4. Test empty, large, corrupt, interrupted, resumed, duplicated, reordered, expired, unauthorized, overloaded, and partial-failure paths as relevant.
5. Resolve conflicts semantically by reconstructing both sides' intent.
6. Prefer squash merges for focused work unless commit structure materially improves the test record.

## Evidence, security, and documentation

Pull requests should include exact commands, environments, deterministic synthetic fixtures, expected and observed checksums and states, negative-path evidence, cleanup confirmation, documentation updates, and CI or local-equivalent results. Never commit credentials, production files, private keys, personal data, or sensitive logs. Follow `SECURITY.md` for private reporting. Keep tests isolated from production resources, pin external dependencies, and document compatibility, fault, retention, and cleanup decisions.

## Planning ownership

GitHub owns code, reviews, checks, releases, and delivery evidence. Linear owns priority, dependencies, sequencing, and cross-project planning. The organization GitHub Project is the cross-repository execution view; see `PROJECTS.md` for routing details.

## Organization health

- [ ] Profiles, descriptions, topics, and READMEs are current.
- [ ] Community health files and reusable issue/PR guidance are present.
- [ ] Isolation, fixtures, determinism, faults, credentials, cleanup, retention, and expected outcomes are documented.
- [ ] Required checks cover corruption, interruption, authorization, load, compatibility, and supply-chain risk.
- [ ] Stale fixtures and scenarios are removed or clearly marked.
- [ ] GitHub Project and Linear links resolve and reflect completed work.
