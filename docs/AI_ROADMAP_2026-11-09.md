# Responsible AI continuation roadmap — teldigi5-wq/opentelemetry-java-contrib

> Dated 9 November 2026. Review-only [PR #1](https://github.com/teldigi5-wq/opentelemetry-java-contrib/pull/1); no automatic main/feature-branch edits, merge, public publication or production verification.

## Ownership, history and constraints
The [original handoff](AI_CONTINUATION_2026-11-09.md) and README remain source context. Re-read the current repository and latest upstream/public PRs before development. Preserve all existing branches, contributor attribution and data/privacy boundaries. Historical test claims only count for the exact SHA originally tested.

## Distinct next milestones
1. **M1:** Compare the local fork's exact upstream base and fix/opamp-reconnect-status-3188 diff without changing unrelated upstream modules.
   - Gate: current repo/upstream source SHA and branch, verifiable test or published evidence, scope/permission review, rollback where applicable.
2. **M2:** Reproduce the OPAMP reconnection behavior with a minimal failing regression and module-scoped Gradle checks using the required JDK.
   - Gate: current repo/upstream source SHA and branch, verifiable test or published evidence, scope/permission review, rollback where applicable.
3. **M3:** Check upstream issues and patches for duplicate fixes, follow contributor guidelines and preserve API compatibility.
   - Gate: current repo/upstream source SHA and branch, verifiable test or published evidence, scope/permission review, rollback where applicable.
4. **M4:** Submit for maintainer review only with exact tests, provenance, licensing/CLA and no claim of upstream merge or release without verification.
   - Gate: current repo/upstream source SHA and branch, verifiable test or published evidence, scope/permission review, rollback where applicable.

## Delivery phases
- **Recon:** list all branches with full pagination, PRs, issues, linked repos and policies; identify latest work and ensure no duplicate stage.
- **Propose:** one minimal change per PR; preserve correct canonical ownership and current main.
- **Verify:** run available free local tests, scoped security/quality checks, check licenses/attribution and CI at exact head.
- **Review:** request normal owner/maintainer approval; do not auto-merge to default branch, rewrite history, deploy or publish non-public details.

## Read-only checks
```bash
gh repo view teldigi5-wq/opentelemetry-java-contrib
gh pr list --repo teldigi5-wq/opentelemetry-java-contrib --state open --limit 100
gh issue list --repo teldigi5-wq/opentelemetry-java-contrib --state open --limit 100
gh run list --repo teldigi5-wq/opentelemetry-java-contrib --limit 20
git fetch --all --prune
git log --all --graph --oneline --decorate -30
```
Use read-only paginated inventory script from prior handoff archive if branches exceed API page size.

## Evidence and plans
Keep the [milestone tracker](AI_MILESTONES_2026-11-09.md) current with SHA, precise achievement level, accepted tests and unresolved risks. The plan is an overlay and never a substitute for upstream or source-specific roadmap.
