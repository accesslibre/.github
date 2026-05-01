# Security policy

This is the org-wide default. Repositories may add their own `SECURITY.md`
with repo-specific scope; the guidance here applies when a repo does not.

## Reporting a vulnerability

Please **do not** open a public GitHub issue for security reports.

Email <contact@iatf.cc> with:

- A short description of the issue.
- The repository, page, route, or endpoint where you saw it.
- Steps to reproduce, if possible.
- Whether the issue exposes user data or only affects deployment.

We aim to acknowledge reports within a few days. If you do not get a reply,
ping again on Discord at <https://iatf.cc/discord>.

## Coordinated disclosure

If a fix is non-trivial, we will coordinate a disclosure window with you
before publishing details. We prefer to credit reporters publicly unless you
ask us not to.

## Out of scope

- Findings that depend on a victim configuring their own deployment in an
  insecure way (e.g. leaking their own access tokens).
- Volumetric attacks against shared infrastructure (Cloudflare, GitHub).
- Reports from automated scanners with no demonstrated impact.
- Issues in archived repositories — those are kept as a public record and
  are not actively maintained.

## Accessibility issues

Accessibility barriers on the site are tracked in public — those go to
<accessibility@iatf.cc> or the
[`/accessibility/`](https://iatf.cc/accessibility/) page, not here.
