# `file-tunnel-test` repository relationships

Generated from reviewed policy and the current **public** repository inventory.

- Public repositories declared: **18**
- Private repository names withheld: **8**
- Relationship edges: **26**

## Repository roles

| Repository | Role | Lifecycle |
|---|---|---|
| [`.github`](https://github.com/file-tunnel-test/.github) | `organization_governance` | `active` |
| [`api-contract-e2e`](https://github.com/file-tunnel-test/api-contract-e2e) | `interfaces` | `active` |
| [`mcp-contract-e2e`](https://github.com/file-tunnel-test/mcp-contract-e2e) | `interfaces` | `active` |
| [`clients-dart-consumer`](https://github.com/file-tunnel-test/clients-dart-consumer) | `client_sdk` | `active` |
| [`clients-go-consumer`](https://github.com/file-tunnel-test/clients-go-consumer) | `client_sdk` | `active` |
| [`clients-rust-consumer`](https://github.com/file-tunnel-test/clients-rust-consumer) | `client_sdk` | `active` |
| [`clients-typescript-consumer`](https://github.com/file-tunnel-test/clients-typescript-consumer) | `client_sdk` | `active` |
| [`cross-client-wire-e2e`](https://github.com/file-tunnel-test/cross-client-wire-e2e) | `end_to_end_tests` | `active` |
| [`download-integrity-e2e`](https://github.com/file-tunnel-test/download-integrity-e2e) | `end_to_end_tests` | `active` |
| [`encryption-key-rotation-e2e`](https://github.com/file-tunnel-test/encryption-key-rotation-e2e) | `end_to_end_tests` | `active` |
| [`infra-cloudflare-e2e`](https://github.com/file-tunnel-test/infra-cloudflare-e2e) | `end_to_end_tests` | `active` |
| [`large-file-performance-e2e`](https://github.com/file-tunnel-test/large-file-performance-e2e) | `end_to_end_tests` | `active` |
| [`network-fault-e2e`](https://github.com/file-tunnel-test/network-fault-e2e) | `end_to_end_tests` | `active` |
| [`resumable-chunk-upload-e2e`](https://github.com/file-tunnel-test/resumable-chunk-upload-e2e) | `end_to_end_tests` | `active` |
| [`sync-offline-e2e`](https://github.com/file-tunnel-test/sync-offline-e2e) | `end_to_end_tests` | `active` |
| [`ui-components-e2e`](https://github.com/file-tunnel-test/ui-components-e2e) | `end_to_end_tests` | `active` |
| [`web-ui-e2e`](https://github.com/file-tunnel-test/web-ui-e2e) | `end_to_end_tests` | `active` |
| [`websocket-progress-e2e`](https://github.com/file-tunnel-test/websocket-progress-e2e) | `end_to_end_tests` | `active` |

## Declared edges

| From | Relationship | To | Status/basis |
|---|---|---|---|
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/api-contract-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/clients-dart-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/clients-go-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/clients-rust-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/clients-typescript-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/cross-client-wire-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/download-integrity-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/encryption-key-rotation-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/infra-cloudflare-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/large-file-performance-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/mcp-contract-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/network-fault-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/resumable-chunk-upload-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/sync-offline-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/ui-components-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/web-ui-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/.github` | `governs` | `file-tunnel-test/websocket-progress-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `file-tunnel-test/clients-dart-consumer` | `generated_from` | `file-tunnel-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-dart-consumer` | `generated_from` | `file-tunnel-test/mcp-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-go-consumer` | `generated_from` | `file-tunnel-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-go-consumer` | `generated_from` | `file-tunnel-test/mcp-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-rust-consumer` | `generated_from` | `file-tunnel-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-rust-consumer` | `generated_from` | `file-tunnel-test/mcp-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-typescript-consumer` | `generated_from` | `file-tunnel-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `file-tunnel-test/clients-typescript-consumer` | `generated_from` | `file-tunnel-test/mcp-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `organization://file-tunnel-test` | `packaged_via` | `platform://zed-pkg` | `platform-default` / `platform-policy`: Zed resolves artifacts while submodules compose editable source |

## Composition, service, and observability contract

Git submodules compose editable source; Zed packages resolve packages/artifacts; dual-managed commits must match. Production deploys immutable image digests, not runtime source builds. Cross-service access uses APIs/SDKs/events rather than another service database. MCP uses the product API/SDK. Services emit OpenTelemetry traces, bounded metrics, and correlated structured logs.

## Privacy boundary

This public registry deliberately omits private repository names and edges; the count above makes the boundary explicit.
