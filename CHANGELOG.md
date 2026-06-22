# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project uses Semantic Versioning.

## [Unreleased]

## [0.2.0] - 2026-06-22

### Added
- What changed: Added a complete Builder Camp 2026 event page (`events/builder-camp-2026.md`) with full competition format — four-round elimination funnel, per-round rules and scoring dimensions, finals-day schedule, awards breakdown, judging mechanism, rules, and sign-up links — plus a top-of-page Announcement banner in the README that drives readers to it.
- Why: The community page only had a summary of the hackathon; the team needed the full event details published and a prominent announcement to guide people to view it.
- Impact: Visitors now see an Announcement banner near the top of the profile and can open a dedicated, complete event page with the authoritative rules and schedule.
- Verification: Rendered the README and event page locally; confirmed the announcement banner, the updated 黑客松 section, and the new event page render with embedded poster assets and a working cross-link.
- Files: `README.md`, `events/builder-camp-2026.md`, `VERSION`, `CHANGELOG.md`

### Changed
- What changed: Reconciled the README hackathon summary with the authoritative competition plan — awards now show 冠/亚/季 (¥8,000 / ¥5,000 / ¥3,000) + four ¥1,000 special awards (was 一/二/三等奖), and the scale/format reflect the four-round funnel (was "12 强 Demo Day").
- Why: The published summary diverged from the finalized 赛制总方案 and judging tables; the public page needed to be internally consistent.
- Impact: README award and format details now match the full event page and the judging scoresheets.
- Verification: Cross-checked README figures against `events/builder-camp-2026.md` and the source 赛制总方案.
- Files: `README.md`

## [0.1.1] - 2026-06-22

### Changed
- What changed: Replaced the WeChat community QR codes with the current official Groups 2, 3, and 4 assets.
- Why: Official Group 1 is full, and the repository needed the latest active join codes.
- Impact: The community section now points users to active groups and explicitly notes that Group 1 is full.
- Verification: Updated the README preview locally and confirmed the community section renders the new QR assets and text.
- Files: `README.md`, `assets/qr/wechat-group-2.png`, `assets/qr/wechat-group-3.png`, `assets/qr/wechat-group-4.png`

## [0.1.0] - 2026-06-22

### Added
- What changed: Published the initial public profile repository content for ClawHunt.
- Why: Establish a canonical repository for the project overview, event materials, and community entry points.
- Impact: The repository now provides a shareable project profile with assets and onboarding links.
- Verification: Repository assets and README content were added as the initial baseline.
- Files: `README.md`, `assets/`
