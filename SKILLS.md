# Prebid.js — Skills & Capabilities

## Role
**Frontend Sub-Agent (Role C)** — Prebid.js fork with custom adpulse modules.

## Primary Capabilities
- Prebid.js fork with custom bidder adapters and analytics modules
- Global variable namespace: `adppbjs` (not standard `pbjs`)
- Gulp build pipeline with ESLint code quality checks
- Integration with adp-publisher-tag for GPT + Prebid auction strategies

## LightRAG Collection
`prebid-js_voyage_code_3`

## Agent Skills to Activate
*(none — Prebid.js development, no special skills required)*

## Key Constraints
- **Branch naming**: branch names MUST include 'codex' or 'agent'
- **Global var**: always use `adppbjs` (not `pbjs`)
- **PR messages**: follow Prebid.js community guidelines
- **Test before PR**: run `gulp test --file` for changed modules
- This is a **fork** of upstream Prebid.js — merge conflicts with upstream must be handled carefully

## References
- [AGENTS.md](./AGENTS.md) — Full architecture, build commands, PR guidelines, agent detection clause
