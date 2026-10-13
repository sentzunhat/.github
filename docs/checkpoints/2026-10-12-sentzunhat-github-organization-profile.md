# 2026-10-12 — Sentzunhat GitHub organization profile published and refined

Conversation/event date: 2026-10-12

Checkpoint/archive date: 2026-10-13

Repository: `sentzunhat/.github` (`main`)

## Before

The GitHub organization had no public profile README or `.github` repository. Its public code consisted of HAWP and Zacatl. The Sentzunhat website already supplied the company positioning, project descriptions, and landscape brand mark, but those had not been brought together on the GitHub organization page.

## During

1. A company profile README was drafted from the public website and public repositories. It described Sentzunhat, the Mochilada product direction, HAWP, and Zacatl, while separating research and prototypes from released work.
2. Before publication, the copy was narrowed for a public audience: personal identity and contact details, location, and links to nonpublic repositories were removed. The Mochilada link leads to its public website page; it does not imply public source code or a completed release.
3. The public `sentzunhat/.github` repository was created. `profile/README.md` was committed and pushed to `main` as `8697314`.
4. After reviewing the Debian and SolidJS organization profiles, the README gained a warmer welcome, direct navigation, and the existing public [Sentzunhat landscape mark](https://sentzunhat.com/sentzunhat-mark.svg). Live GitHub release checks supplied HAWP `0.0.24` (pre-release) and Zacatl `v0.0.64`. This revision was pushed as `3fb94fd`.

## After / verified state

- The [organization profile](https://github.com/sentzunhat) renders the README from [`profile/README.md`](../../profile/README.md). The mark, welcome, and both version labels were observed on the live page after the push.
- On 2026-10-13, the public-repository list contained only `.github`, `human-ai-workflow-protocol`, and `zacatl`. This is a point-in-time visibility check, not a permanent inventory.
- On 2026-10-13, the GitHub release lists still showed HAWP `0.0.24` as a pre-release and Zacatl `v0.0.64` as a non-pre-release. The README links directly to those releases.
- No application source, product release, repository visibility setting, or organization membership was changed by this checkpoint.

## Decisions and boundaries

- Keep the organization profile short, welcoming, and grounded in public evidence. The website is the company story; GitHub is the entry point to public engineering work.
- Keep the existing brand mark linked from the website rather than copying a second asset into this repository. The profile image therefore depends on that public URL remaining available.
- Keep personal details and nonpublic repository context out of this public repository, including future checkpoint files.
- Treat version links as dated release references. Check GitHub again before calling a version current or changing the table; preserve HAWP's pre-release label when applicable.

## Continuation

Current state: the profile is live on `main`; `3fb94fd` is the last profile-content commit before this archival checkpoint. There is no known blocker to the published profile.

Next milestone: on the next profile edit, recheck the rendered organization page, the public mark URL, release metadata, and public-repository visibility. Update `profile/README.md` only when a material public fact or presentation choice changes. Keep this checkpoint as the canonical timeline for the October 12 profile publication rather than creating another summary of the same event.
