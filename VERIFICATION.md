# Verification — NextPlay Social Studio

Verified 13 October 2026 (America/Los_Angeles). All source/runtime verification used a separate workspace or synthetic test media. No real social post was published.

- Original source inventory: all 71 listed files match their handoff SHA-256 hashes. The original editor source files are unchanged.
- Original Python suite: **101 passed**. Covers editor commands, media confinement, imports, revision recovery, rendering, and local HTTP behavior.
- Original JavaScript keyboard regression check: **passed**.
- New marketing suite: **36 passed**. Covers approval invalidation, channel independence, stale-save rejection, rights and native-music blocking, schedule timezones, persistent queues, atomic claiming/cancellation, duplicate prevention, uncertain-outcome recovery, encrypted credentials, OAuth state rejection, structured AI response validation, authentication and same-origin boundaries, API header checks, path confinement, binary upload, real FFmpeg render, byte ranges, post package download, and mocked publishing adapters.
- Live OpenAI copy: **passed**, generating three platform-specific variants from a synthetic brief with the authorized existing key.
- Live OpenAI music research: **passed**, returning a dated report with six cited web sources. This confirms the research service works; it does not verify licensing or trend popularity for every recommendation.
- Browser checks: desktop dashboard, draft creation, manual copy save, editor opening, import into an existing draft, rights guard, approval, and scheduling dialog checked. The preserved editor and dashboard were inspected at **390 × 844** for iPhone layout. A browser upload refresh issue was found and fixed.
- JavaScript syntax and Python compilation: **passed**.

## Limits

No real social accounts or registered developer apps were connected. OAuth completion, public TikTok eligibility, Instagram/Facebook publishing, and account metrics require real authorization and platform approvals; adapter tests are mocked. No native music API/catalogue or platform-native sound attachment is provided. No actual iPhone hardware/Safari certification was performed; viewport testing is not the same as device testing. Docker/container deployment was prepared but not run. No cloud service is live.

The original legacy rendering path can still skip text overlays. The preserved V4 timeline rendering tests pass; this does not resolve the separate legacy-path limitation from the handoff. Existing media-backed projects were not migrated because the handoff excludes their data.
