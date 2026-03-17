# Bugs & Iterations

## : |2026-03-15|||refactor release workflows for explicit publish flow

**Problem:** |2026-03-15|||refactor release workflows for explicit publish flow
**Details:** Split release prep from publish so merges to main stay test-only and version bumps are reviewed in a release PR. Stamp the final publish date during the manual publish workflow and open a follow-up PR when the real publish day differs from the merged release metadata.
**Files:** .github/workflows/publish-release.yml,.github/workflows/release.yml,CHANGELOG.md,CONTRIBUTING.md,scripts/release_workflow.py
**Commit:** 14a0606

## : |2026-03-15|||Merge pull request #11 from psi-oss/refactor/release-workflow-explicit-publish

**Problem:** |2026-03-15|||Merge pull request #11 from psi-oss/refactor/release-workflow-explicit-publish
**Details:** refactor release workflows for explicit publish flow
**Files:** 
**Commit:** 28077b7

<!-- Format:
## YYYY-MM-DD: Short Title

**Problem:** What went wrong or needed changing
**Root cause:** Why it happened
**Fix:** What was done to resolve it
-->
