# Hosted MCP Apps Example Gallery — SOL Timeline

## Run Identity

- Model name: SOL
- Model namespace: sol
- Local repository: `/Users/jalillaaraichi/openwork-mcp-app-gallery-sol`
- GitHub repository: `different-ai/openwork-mcp-app-gallery-sol`
- Vercel project: `openwork-mcp-app-gallery-sol`
- Default and production branch: `forward`
- Feature branch: `sol/gallery-v1`
- Status: Running
- Current phase: P6 — CI and staging deploy

## Timing Summary

| Measure                                      | Value                     |
| -------------------------------------------- | ------------------------- |
| Started UTC                                  | 2026-08-17T17:18:24Z      |
| Started Europe/Berlin                        | 2026-08-17T19:18:24+02:00 |
| Completed UTC                                | Pending                   |
| Completed Europe/Berlin                      | Pending                   |
| Total wall-clock duration                    | Running                   |
| Total external-wait duration                 | 69 seconds                |
| Total CI-wait duration                       | 0 seconds                 |
| Total Vercel-wait duration                   | 0 seconds                 |
| Total recorded rework duration               | 642 seconds               |
| Estimated active implementation duration     | Pending — Estimated       |
| Time to first working two-app local vertical | 2,307 seconds             |
| Time to first working six-app catalog        | 2,307 seconds             |
| Time to first green local `release:check:ci` | 3,249 seconds             |
| Time to PR open                              | Pending                   |
| Time to first Preview                        | Pending                   |
| Time to first all-green PR head              | Pending                   |
| Time to merge                                | Pending                   |
| Time to staged Production readiness          | Pending                   |
| Time to production promotion                 | Pending                   |
| Time to stable-origin proof                  | Pending                   |
| Final verdict                                | Running                   |

## Phase Durations

| Phase                            | Start UTC            | End UTC              | Duration      | Status  | Dominant category               |
| -------------------------------- | -------------------- | -------------------- | ------------- | ------- | ------------------------------- |
| P0 — Authority and source freeze | 2026-08-17T17:18:24Z | 2026-08-17T17:22:23Z | 239 seconds   | Passed  | Research and preflight          |
| P1 — Repository foundation       | 2026-08-17T17:22:23Z | 2026-08-17T17:43:15Z | 1,252 seconds | Passed  | Implementation                  |
| P2 — Two-app vertical            | 2026-08-17T17:43:15Z | 2026-08-17T17:56:51Z | 816 seconds   | Passed  | Implementation                  |
| P3 — Six-app catalog             | 2026-08-17T17:56:51Z | 2026-08-17T17:56:51Z | 0 seconds     | Passed  | Implementation                  |
| P4 — Gallery experience          | 2026-08-17T17:56:51Z | 2026-08-17T18:02:37Z | 346 seconds   | Passed  | Implementation                  |
| P5 — Public-runtime hardening    | 2026-08-17T18:02:37Z | 2026-08-17T18:12:33Z | 596 seconds   | Passed  | Implementation and verification |
| P6 — CI and staging deploy       | 2026-08-17T18:12:33Z | Pending              | Running       | Running | CI and Vercel                   |
| P7 — Host compatibility proof    | Pending              | Pending              | Pending       | Pending | Host verification               |
| P8 — Production release          | Pending              | Pending              | Pending       | Pending | Vercel and verification         |
| P9 — Operate and report          | Pending              | Pending              | Pending       | Pending | Observation and reporting       |

## Milestone Times

| ID    | Milestone                                              | UTC                  | Europe/Berlin             | Elapsed       |
| ----- | ------------------------------------------------------ | -------------------- | ------------------------- | ------------- |
| M-001 | Benchmark clock started                                | 2026-08-17T17:18:24Z | 2026-08-17T19:18:24+02:00 | 0 seconds     |
| M-002 | Preflight complete                                     | 2026-08-17T17:22:23Z | 2026-08-17T19:22:23+02:00 | 239 seconds   |
| M-003 | Local repository initialized                           | 2026-08-17T17:25:30Z | 2026-08-17T19:25:30+02:00 | 426 seconds   |
| M-004 | Private GitHub repository created and `forward` pushed | 2026-08-17T17:25:30Z | 2026-08-17T19:25:30+02:00 | 426 seconds   |
| M-005 | First working two-app local vertical                   | 2026-08-17T17:56:51Z | 2026-08-17T19:56:51+02:00 | 2,307 seconds |
| M-006 | First working six-app local catalog                    | 2026-08-17T17:56:51Z | 2026-08-17T19:56:51+02:00 | 2,307 seconds |
| M-007 | Six UIs passed independent App bridge browser harness  | 2026-08-17T18:02:37Z | 2026-08-17T20:02:37+02:00 | 2,653 seconds |
| M-008 | First green local `release:check:ci`                   | 2026-08-17T18:12:33Z | 2026-08-17T20:12:33+02:00 | 3,249 seconds |
| M-009 | Green local release candidate committed                | 2026-08-17T18:17:47Z | 2026-08-17T20:17:47+02:00 | 3,563 seconds |

## Chronological Event Log

| ID      | UTC                  | Europe/Berlin             | Elapsed       | Phase | Category              | Event                                                                                                                                                                                                                                   | Result        | Related identifier                                  |
| ------- | -------------------- | ------------------------- | ------------- | ----- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | --------------------------------------------------- |
| EVT-001 | 2026-08-17T17:18:24Z | 2026-08-17T19:18:24+02:00 | 0 seconds     | P0    | Benchmark             | Created the two required timeline files before repository or provider mutation.                                                                                                                                                         | Passed        | `1786987104000`                                     |
| EVT-002 | 2026-08-17T17:22:23Z | 2026-08-17T19:22:23+02:00 | 239 seconds   | P0    | Preflight             | Read the execution contract and source plan; refreshed Snacks `forward`; verified GitHub and Vercel authentication; checked only the SOL targets; froze official source, dependency, protocol, and licensing inputs.                    | Passed        | `ext-apps@10195ad`, `mcp-handler@7c8fe0a`           |
| EVT-003 | 2026-08-17T17:25:30Z | 2026-08-17T19:25:30+02:00 | 426 seconds   | P1    | Git and GitHub        | Initialized `forward`, committed truthful governance and timing records, created the private SOL repository, and pushed the only expected direct bootstrap commit.                                                                      | Passed        | `44b5ae3`                                           |
| EVT-004 | 2026-08-17T17:25:30Z | 2026-08-17T19:25:30+02:00 | 426 seconds   | P1    | GitHub                | Explicit default-branch edit returned HTTP 422 immediately after push; direct reads then proved `forward` was already the default and only branch.                                                                                      | Resolved      | `ISS-001`                                           |
| EVT-005 | 2026-08-17T17:26:02Z | 2026-08-17T19:26:02+02:00 | 458 seconds   | P1    | GitHub                | First branch-protection write returned a provider HTTP 503; follow-up read confirmed protection was not yet applied.                                                                                                                    | Investigating | `ISS-002`                                           |
| EVT-006 | 2026-08-17T17:27:11Z | 2026-08-17T19:27:11+02:00 | 527 seconds   | P1    | GitHub                | Retried the same bounded protection request after the transient provider failure and verified the enforced no-direct-push policy.                                                                                                       | Resolved      | `ISS-002`                                           |
| EVT-007 | 2026-08-17T17:43:15Z | 2026-08-17T19:43:15+02:00 | 1,491 seconds | P2    | Build                 | First deterministic Get Time bundle measured 539,002 bytes and correctly failed the 524,288-byte resource ceiling.                                                                                                                      | Investigating | `ISS-003`, `REG-001`                                |
| EVT-008 | 2026-08-17T17:49:18Z | 2026-08-17T19:49:18+02:00 | 1,854 seconds | P2    | Build                 | Completed the size-bounded UI adaptation; all six resources measured between 335,863 and 354,133 bytes.                                                                                                                                 | Resolved      | `ISS-003`, `REG-001`                                |
| EVT-009 | 2026-08-17T17:50:13Z | 2026-08-17T19:50:13+02:00 | 1,909 seconds | P2    | Typecheck             | First strict typecheck exposed the Terser target literal, unchecked manifest indexing, and named `mcp-handler` export mismatches.                                                                                                       | Investigating | `ISS-004`, `REG-002`                                |
| EVT-010 | 2026-08-17T17:51:10Z | 2026-08-17T19:51:10+02:00 | 1,966 seconds | P2    | Typecheck             | Corrected the four integration type contracts; strict `tsc --noEmit` passed.                                                                                                                                                            | Resolved      | `ISS-004`, `REG-002`                                |
| EVT-011 | 2026-08-17T17:56:51Z | 2026-08-17T19:56:51+02:00 | 2,307 seconds | P2    | Protocol verification | All six current `2026-07-28` and all six legacy contracts passed with isolated tools/resources, ordinary fallback, repeated cycles, and 20 representative clients.                                                                      | Passed        | `M-005`, `M-006`                                    |
| EVT-012 | 2026-08-17T17:58:42Z | 2026-08-17T19:58:42+02:00 | 2,418 seconds | P4    | Typecheck             | Official `ext-apps` AppBridge declarations failed strict NodeNext resolution because the published declarations contain extensionless internal imports.                                                                                 | Investigating | `ISS-005`                                           |
| EVT-013 | 2026-08-17T17:59:19Z | 2026-08-17T19:59:19+02:00 | 2,455 seconds | P4    | Typecheck             | Isolated the declaration defect behind a narrow typed browser-test runtime shim; `skipLibCheck` remained disabled and strict checks passed.                                                                                             | Resolved      | `ISS-005`                                           |
| EVT-014 | 2026-08-17T18:01:07Z | 2026-08-17T20:01:07+02:00 | 2,563 seconds | P4    | Browser verification  | First Playwright run exposed a development asset-route collision that returned 404 for gallery CSS/JS, breaking copy and 320 px layout; three other failures were locator ambiguities.                                                  | Investigating | `ISS-006`, `REG-003`                                |
| EVT-015 | 2026-08-17T18:02:37Z | 2026-08-17T20:02:37+02:00 | 2,653 seconds | P4    | Browser verification  | Repaired exact asset fallthrough and stable locators; all six UIs initialized in the official AppBridge host and all ten browser/accessibility checks passed.                                                                           | Resolved      | `ISS-006`, `REG-003`, `M-007`                       |
| EVT-016 | 2026-08-17T18:04:26Z | 2026-08-17T20:04:26+02:00 | 2,762 seconds | P5    | Lint and security     | Type-aware lint correctly rejected object spread over the full `HeadersInit` union because tuple arrays would become numeric object keys.                                                                                               | Investigating | `ISS-007`, `REG-004`                                |
| EVT-017 | 2026-08-17T18:05:34Z | 2026-08-17T20:05:34+02:00 | 2,830 seconds | P5    | Lint and security     | Replaced generic header spreads with the platform `Headers` API and reran affected verification.                                                                                                                                        | Resolved      | `ISS-007`, `REG-004`                                |
| EVT-018 | 2026-08-17T18:07:38Z | 2026-08-17T20:07:38+02:00 | 2,954 seconds | P5    | Secret scan           | Initial secret scan falsely matched uppercase `VERCEL_PROJECT_PRODUCTION_URL` because the credential-prefix expression was case-insensitive.                                                                                            | Investigating | `ISS-008`, `REG-005`                                |
| EVT-019 | 2026-08-17T18:07:53Z | 2026-08-17T20:07:53+02:00 | 2,969 seconds | P5    | Secret scan           | Scoped the provider token prefix to its real lowercase form; the same full repository scan passed without value/path suppression.                                                                                                       | Resolved      | `ISS-008`, `REG-005`                                |
| EVT-020 | 2026-08-17T18:08:03Z | 2026-08-17T20:08:03+02:00 | 2,979 seconds | P5    | Dependency audit      | Production audit passed; the complete audit found moderate `GHSA-48c2-rrv3-qjmp` in direct development dependency `yaml@2.8.1`.                                                                                                         | Investigating | `ISS-009`                                           |
| EVT-021 | 2026-08-17T18:08:15Z | 2026-08-17T20:08:15+02:00 | 2,991 seconds | P5    | Dependency audit      | Upgraded exactly to patched `yaml@2.8.3`, regenerated lock/SBOM, and obtained a clean complete audit.                                                                                                                                   | Resolved      | `ISS-009`                                           |
| EVT-022 | 2026-08-17T18:12:33Z | 2026-08-17T20:12:33+02:00 | 3,249 seconds | P5    | Release verification  | First complete local `release:check:ci` passed frozen install, formatting, lint, strict types, 42 Vitest checks, 10 Playwright checks, notices, provenance, architecture, full audit, scans, SBOM, deterministic generation, and build. | Passed        | `M-008`                                             |
| EVT-023 | 2026-08-17T18:17:47Z | 2026-08-17T20:17:47+02:00 | 3,563 seconds | P6    | Git                   | Committed the coherent green implementation, generated artifacts, tests, security/provenance controls, and truthful running timeline on `sol/gallery-v1`.                                                                               | Passed        | `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`, `M-009` |

## Issues Encountered

### ISS-001 — Redundant default-branch update rejected

- First observed: 2026-08-17T17:25:30Z (426 seconds elapsed)
- Resolved: 2026-08-17T17:25:30Z (426 seconds elapsed)
- Phase: P1
- Classification: GitHub
- Origin: external
- Expected: explicitly setting the pushed `forward` branch as default succeeds.
- Observed and symptom: GitHub returned HTTP 422 with `Repository.default_branch is invalid` immediately after the first push.
- Bounded explanation: repository initialization and branch propagation raced with a redundant default-branch edit; GitHub had already selected the only pushed branch.
- Attempts: inspected the exact repository; listed only its branches.
- Final correction: no state change was needed because exact reads showed `forward` was already the default and only branch.
- Affected files and commits: none; bootstrap commit `44b5ae3` remained valid.
- Invalidated proof: none.
- Closing verification: repository view reported private visibility and default branch `forward`; branch listing returned only `forward`.
- Time-to-detect and time-to-repair: not separately measurable at sub-second command granularity.
- Final status: Resolved.

### ISS-002 — GitHub branch-protection endpoint unavailable

- First observed: 2026-08-17T17:26:02Z (458 seconds elapsed)
- Resolved: 2026-08-17T17:27:11Z (527 seconds elapsed)
- Phase: P1
- Classification: GitHub
- Origin: external
- Expected: the branch-protection API applies the no-direct-push, linear-history, no-force, no-delete, and conversation-resolution policy.
- Observed and symptom: the write returned HTTP 503 and an immediate read returned `Branch not protected`.
- Bounded explanation: GitHub reported that no server was available to service the protection request.
- Attempts: one exact REST protection write followed by one exact protection read; one bounded retry of the same write after recording the transient failure; one exact closing read.
- Final correction: the retry succeeded without changing the intended policy.
- Affected files and commits: none.
- Invalidated proof: branch-protection proof during the retry interval.
- Closing verification: admin enforcement, pull-request requirement, linear history, conversation resolution, no force pushes, and no deletions all reported the intended values.
- Time-to-detect: immediate.
- Time-to-repair: 69 seconds.
- Final status: Resolved.

### ISS-003 — Initial Get Time App bundle exceeded the resource ceiling

- First observed: 2026-08-17T17:43:15Z (1,491 seconds elapsed)
- Resolved: 2026-08-17T17:49:18Z (1,854 seconds elapsed)
- Phase: P2
- Classification: implementation
- Origin: self-introduced
- Expected: every deterministic single-file MCP App resource is at most 524,288 bytes.
- Observed and symptom: the first Get Time build was 539,002 bytes and the generator failed closed.
- Root cause or best bounded explanation: the initial Vite configuration used esbuild's single-pass minifier for a React plus MCP Apps bridge bundle.
- Attempts: one complete deterministic build using esbuild minification; one three-pass Terser build; one five-pass top-level Terser build; one complete six-app measurement with a lightweight Chart.js API adapter; final size-bounded UI adaptations for the three React-heavy views.
- Final correction: retained the frozen upstream audit snapshot, used gallery-owned vanilla MCP Apps adaptations for Get Time, Cohort Heatmap, and Scenario Modeler, and aliased broad Chart.js registration to a bounded canvas implementation for the other chart views.
- Affected files: `scripts/bundle-mcp-app-resources.ts`, planned dependency lock.
- Affected commits: uncommitted feature work only.
- Invalidated proof: first two-app vertical and all resource-size proof.
- Closing verification: complete generator passed with Get Time 335,863; Budget Allocator 354,133; Cohort Heatmap 337,864; Customer Segmentation 348,890; Scenario Modeler 339,570; Transcript 345,103 bytes.
- Time-to-detect: first resource build.
- Time-to-repair: 363 seconds.
- Final status: Resolved.

### ISS-004 — First strict typecheck rejected integration contracts

- First observed: 2026-08-17T17:50:13Z (1,909 seconds elapsed)
- Resolved: 2026-08-17T17:51:10Z (1,966 seconds elapsed)
- Phase: P2
- Classification: implementation
- Origin: self-introduced
- Expected: strict TypeScript with unchecked indexed access passes.
- Observed and symptom: the first check reported the unsupported Terser `ecma` literal, unchecked public-manifest values, tuple inference in the architecture check, and the named export shape of `mcp-handler` 2.1.1.
- Root cause: initial integration code was authored against looser inferred types and the README's default-export presentation instead of the package's published TypeScript declarations.
- Attempts: first `tsc --noEmit` run; targeted declaration corrections; closing `tsc --noEmit` run.
- Final correction: used the published named `createMcpHandler` export, explicit public-manifest types, tuple literals for header assertions, and the supported Terser ECMA target.
- Affected files: `scripts/bundle-mcp-app-resources.ts`, `scripts/check-vercel-architecture.ts`, `src/gallery-render.ts`, `src/mcp-app-adapter.ts`.
- Affected commits: uncommitted feature work only.
- Invalidated proof: strict typecheck and two-app vertical.
- Closing verification: strict `tsc --noEmit` passed with zero errors.
- Time-to-detect: first strict typecheck.
- Time-to-repair: 57 seconds.
- Final status: Resolved.

### ISS-005 — Published AppBridge declarations failed strict NodeNext

- First observed: 2026-08-17T17:58:42Z (2,418 seconds elapsed)
- Resolved: 2026-08-17T17:59:19Z (2,455 seconds elapsed)
- Phase and origin: P4; external third-party declaration defect.
- Expected: the official `ext-apps` AppBridge entrypoint typechecks under strict NodeNext.
- Observed: its published `.d.ts` files referenced extensionless internal modules and produced TS2834/TS2835 before the browser bundle ran.
- Attempts: direct official import; review of the frozen implementation and published surface; a minimal typed local boundary that re-exports the unchanged official browser runtime.
- Final correction: retained `skipLibCheck: false` and isolated only the browser-test host re-export behind a narrow declaration shim.
- Affected files: `test-support/browser-host.ts`, `test-support/ext-apps-app-bridge-runtime.js`, and its `.d.ts`.
- Invalidated proof: strict typecheck and browser-host build.
- Closing verification: strict TypeScript, Vite host build, and all six AppBridge browser initializations passed.
- Time-to-repair: 37 seconds. Final status: Resolved.

### ISS-006 — Development asset route broke first browser proof

- First observed: 2026-08-17T18:01:07Z (2,563 seconds elapsed)
- Resolved: 2026-08-17T18:02:37Z (2,653 seconds elapsed)
- Phase and origin: P4; self-introduced.
- Expected: the development host serves screenshots plus application-owned content-hashed CSS/JS and every App initializes.
- Observed: the broad screenshot route intercepted all `/assets/:filename` requests, returning 404 for gallery CSS and JS; copy did not attach and the unstyled 320 px page overflowed. Three additional failures were mutable/ambiguous role locators in the test harness.
- Attempts: complete ten-test run; standalone headless reproduction that captured exact failed asset requests; exact screenshot routing plus application fallthrough; immutable id/CSS locators; full rerun.
- Final correction: the wrapper handles only known screenshot digests and delegates all other assets; tests use stable locators where live-region roles legitimately overlap.
- Affected files: `scripts/dev.ts`, `tests/browser/gallery.spec.ts`, `tests/browser/mcp-app-host.spec.ts`.
- Invalidated proof: browser rendering, copy URL, accessibility, 320 px layout, and UI-to-tool interaction.
- Closing verification: all ten Playwright checks passed, including six AppBridge UIs and the accessibility/mobile cases.
- Time-to-repair: 90 seconds. Final status: Resolved.

### ISS-007 — Generic header spread was not valid for every HeadersInit form

- First observed: 2026-08-17T18:04:26Z (2,762 seconds elapsed)
- Resolved: 2026-08-17T18:05:34Z (2,830 seconds elapsed)
- Phase and origin: P5; self-introduced.
- Expected: record, tuple-array, and `Headers` inputs retain HTTP header semantics.
- Observed: type-aware lint proved tuple arrays would become numeric keys when spread into an object.
- Final correction: use the platform `Headers` API for generic composition and keep object spread only behind the internally guaranteed `Record<string,string>` CORS helper.
- Affected files: `src/gateway.ts`, `tests/gateway/boundaries.test.ts`.
- Invalidated proof: lint and gateway header behavior.
- Closing verification: lint, strict TypeScript, 42 Vitest checks, ten browser checks, and the full release gate passed.
- Time-to-repair: 68 seconds. Final status: Resolved.

### ISS-008 — Secret scanner rejected an uppercase environment identifier

- First observed: 2026-08-17T18:07:38Z (2,954 seconds elapsed)
- Resolved: 2026-08-17T18:07:53Z (2,969 seconds elapsed)
- Phase and origin: P5; self-introduced verification-harness false positive.
- Expected: real provider token prefixes are detected without treating ordinary identifiers as values.
- Observed: the case-insensitive Vercel-token pattern matched `VERCEL_PROJECT_PRODUCTION_URL`.
- Final correction: match the provider's real lowercase `vercel_`/`vcp_` credential prefixes without adding a path or content suppression.
- Affected file: `scripts/scan-secrets.ts`.
- Invalidated proof: secret scan and public readiness.
- Closing verification: the same 117-file scan passed and remained in the full release gate.
- Time-to-repair: 15 seconds. Final status: Resolved.

### ISS-009 — Complete audit found a patched YAML development advisory

- First observed: 2026-08-17T18:08:03Z (2,979 seconds elapsed)
- Resolved: 2026-08-17T18:08:15Z (2,991 seconds elapsed)
- Phase and origin: P5; external dependency advisory.
- Expected: production and complete locked audits are clean.
- Observed: production dependencies were clean; the complete audit reported moderate `GHSA-48c2-rrv3-qjmp` in direct build dependency `yaml@2.8.1` and identified `2.8.3` as patched.
- Attempts: production audit; exact JSON advisory/path review; narrow exact upgrade; regenerated lock and SBOM; complete audit rerun.
- Final correction: pin `yaml@2.8.3`; no hosted runtime dependency or behavior changed.
- Affected files: `package.json`, `pnpm-lock.yaml`, `generated/sbom.cdx.json`.
- Invalidated proof: dependency audit, SBOM, and release check.
- Closing verification: complete audit returned no known vulnerabilities and the full gate regenerated the SBOM.
- Time-to-repair: 12 seconds. Final status: Resolved.

## Regressions Introduced and Corrected

### REG-001 — Build configuration admitted an oversized UI candidate

- Corresponding issue: ISS-003
- Introduced: initial uncommitted bundle configuration
- Detected: 2026-08-17T17:43:15Z
- Corrected: 2026-08-17T17:49:18Z
- Responsible commit: none; uncommitted feature work
- Correction commit: `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`
- Symptom: Get Time resource measured 539,002 bytes.
- User impact: none; the fail-closed generator prevented publication or deployment.
- Proof invalidated: resource-size and two-app vertical proof.
- Closing verification: full six-app generator passed; largest resource was 354,133 bytes, below 524,288.
- Time-to-detect: first resource build.
- Time-to-repair: 363 seconds.

### REG-002 — Initial adapter integration did not satisfy strict declarations

- Corresponding issue: ISS-004
- Introduced: initial uncommitted SDK-v2 integration
- Detected: 2026-08-17T17:50:13Z
- Corrected: 2026-08-17T17:51:10Z
- Responsible commit: none; uncommitted feature work
- Correction commit: `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`
- Symptom: strict typecheck failed before runtime testing.
- User impact: none; no candidate was committed, pushed, or deployed.
- Proof invalidated: strict typecheck and vertical proof.
- Closing verification: strict `tsc --noEmit` passed with zero errors.
- Time-to-detect: first strict typecheck.
- Time-to-repair: 57 seconds.

### REG-003 — Browser-test asset wrapper intercepted gallery assets

- Corresponding issue: ISS-006
- Detected/corrected: 2026-08-17T18:01:07Z / 2026-08-17T18:02:37Z
- Responsible commit: none; uncommitted feature work. Correction commit: `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`.
- Symptom: local CSS/JS returned 404, breaking copy and mobile layout.
- User impact: none; the defect was confined to uncommitted test serving and blocked before publication.
- Invalidated proof: browser rendering, copy URL, accessibility, 320 px layout, UI-to-tool interaction.
- Closing verification: all ten Playwright checks passed. Time-to-repair: 90 seconds. Status: Resolved.

### REG-004 — Generic HeadersInit object spread had tuple-array semantics

- Corresponding issue: ISS-007
- Detected/corrected: 2026-08-17T18:04:26Z / 2026-08-17T18:05:34Z
- Responsible commit: none; uncommitted feature work. Correction commit: `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`.
- Symptom: tuple-array headers would become numeric object properties.
- User impact: none; type-aware lint blocked publication.
- Invalidated proof: lint and gateway headers.
- Closing verification: platform `Headers` composition passed the complete release gate. Time-to-repair: 68 seconds. Status: Resolved.

### REG-005 — Credential scan prefix was over-broad

- Corresponding issue: ISS-008
- Detected/corrected: 2026-08-17T18:07:38Z / 2026-08-17T18:07:53Z
- Responsible commit: none; uncommitted feature work. Correction commit: `5d0cba19f21a539e133a8ef079b0c2ade7eac93b`.
- Symptom: uppercase environment identifier was misclassified as a Vercel token.
- User impact: none; only release verification was blocked.
- Invalidated proof: secret scan and public readiness.
- Closing verification: the unchanged full source scope passed after matching only real lowercase provider prefixes. Time-to-repair: 15 seconds. Status: Resolved.

## External Waits

| ID       | Classification  | Start UTC            | End UTC              | Duration   | Outcome                            |
| -------- | --------------- | -------------------- | -------------------- | ---------- | ---------------------------------- |
| WAIT-001 | GitHub provider | 2026-08-17T17:26:02Z | 2026-08-17T17:27:11Z | 69 seconds | Branch-protection retry succeeded. |

## Rework and Abandoned Approaches

| ID         | Approach                                          | Reason chosen                                               | Reason abandoned                                                                   | Elapsed consumed | Retained work                                        | Corrective direction                                                              |
| ---------- | ------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------- | --------------------------------------------------------------------------------- |
| REWORK-001 | Vite single-file build with esbuild minification  | Fast deterministic default                                  | Five upstream UI builds remained over the 512 KiB ceiling after minification alone | 363 seconds      | Source import, Vite pipeline, fail-closed size check | Frozen upstream snapshot plus gallery-owned size-bounded UI and chart adaptations |
| REWORK-002 | Loosely inferred initial integration types        | Fast first vertical                                         | Strict declarations rejected four bounded mismatches                               | 57 seconds       | Runtime design and exact dependencies                | Match published declarations and retain strict unchecked-index enforcement        |
| REWORK-003 | Direct official AppBridge declaration import      | Use the official host bridge without a type boundary        | Published extensionless imports failed strict NodeNext                             | 37 seconds       | Official browser runtime and host design             | Narrow typed runtime re-export with `skipLibCheck: false`                         |
| REWORK-004 | Broad local asset route and dynamic role locators | Compact development server and accessibility-oriented tests | Route intercepted CSS/JS and live names destabilized locators                      | 90 seconds       | Independent host and browser matrix                  | Exact screenshot routing, application fallthrough, immutable locators             |
| REWORK-005 | Object spread over generic `HeadersInit`          | Concise composition                                         | Tuple arrays have incompatible spread semantics                                    | 68 seconds       | Header policies and gateway boundaries               | Platform `Headers` API                                                            |
| REWORK-006 | Case-insensitive provider token prefix            | Conservative secret scan                                    | Misclassified uppercase identifiers                                                | 15 seconds       | Full scan scope and other credential patterns        | Real lowercase token prefix                                                       |
| REWORK-007 | `yaml@2.8.1` build dependency                     | Exact initial build-tool pin                                | Complete audit found a patched moderate advisory                                   | 12 seconds       | Same API and deterministic build behavior            | Exact `yaml@2.8.3`, regenerated lock and SBOM                                     |

## Deployment Timeline

No deployment exists yet.

## Final State

Running. Repository foundation, the dual-era six-app catalog, the gallery/browser experience, public-runtime hardening, and the first complete local `release:check:ci` have passed. CI and staging deployment are in progress. The longer 24-hour operational observation is Pending Operational Observation and is not part of the fixed 20-minute benchmark gate.
