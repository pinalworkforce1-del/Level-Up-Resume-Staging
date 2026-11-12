# Level Up — Northern résumé builder staging

**Isolated non-production testing site.**

This repository deploys only the direct-copy Northern BOOST staged résumé builder integrated with Level Up Nova. It does **not** deploy the full Level Up application or overwrite `LU_Discovery` GitHub Pages.

- Upstream source: `pinalworkforce1-del/LU_Discovery`
- Source branch: `northern-resume-direct-copy-20261111`
- Version initially pinned to: `7dc2cb642a621dbb19699270f3d62835e1dfe4c6`
- Deployment: GitHub Actions → GitHub Pages in **this repository only**
- Authentication: Existing Level Up email OTP, no new user creation
- Data: Uses Level Up Supabase, **not** a sandbox database. Test only with authorized test participant accounts.
- No Vercel or production application updates.

The staged site is not approved for real participant use until browser workflow checks, live authentication, cloud-save/version persistence, and completion routing are verified.
