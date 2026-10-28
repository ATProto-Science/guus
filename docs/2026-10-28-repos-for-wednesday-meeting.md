# Repos to share and maintain — for the Wed 4 Nov meeting (ATScience x IOSP)

Facts checked 2026-10-28 via `gh`. Maintainer column is a **proposal for the meeting**, not a decision. Out of scope: `landing-page` (old), `atsci-ecosystem-map` (not relevant for event prep), `iosp-welcome`, `iosp-kiosk`, `iosp-hacking-stations` (IOSP 2026).

## In scope

| Repo | Role for 2027 | State today | Proposed maintainer |
|---|---|---|---|
| [`ATProto-Science/at-science-homepage`](https://github.com/ATProto-Science/at-science-homepage) | atproto.science: events listing and the ATScience x IOSP event page (`content/events/event-atmosphere2027.md`) | Public, Eleventy + GOV.UK plugin, deploys to GitHub Pages. Admins: ronentk, tgoerke, renderghost, byarielm. Last push 2026-10-19. No open PRs or issues | Ronen (most commits) for the site, Torsten for `content/events/` |
| [`ATProtocol-Community/atmosphereconf`](https://github.com/ATProtocol-Community/atmosphereconf) | AtmosphereConf site. Home of the new `/science` landing page (copy of `/speak`) | Public, Astro, MIT. **We only have read access**, so fork and PR. Very active (last push 2026-10-28). Open issues of interest: #134 "Ways to link to the event to help promote it", #142 "Set up DNS redirects on Cloudflare" | Jon leads the page (due 5 Nov). Ask Guido which branch to fork from (`guustastic` is the active 2027 branch, unconfirmed) |
| *New, proposal:* shared content repo, e.g. `ATProto-Science/atscience-iosp-2027` | One place for the copy and documents the team keeps rewriting: CFP description, one-pagers (sponsors, speakers, attendees), schedule options, comms milestones, this overview | Does not exist | Ellie holds coordination of the one-pager (per notes); repo owner to be decided |

## Things to settle for the repos
1. **Fork and PR everywhere.** `at-science-homepage` has no branch protection and deploys on every push to `main` plus a daily cron. Four admins can push directly. Turn on "require a PR" for `main`?
2. **Merge rights:** who merges the events PRs? One reviewer from outside the author is enough.
3. **License:** `at-science-homepage` has none. Pick one (or leave it).
4. **Redirects:** atproto.science and iosp.science to atmosphereconf.org/science, or a separate landing page (from the call notes)? A science subdomain on the conference site needs a DNS record from their admin (probably Boris), and the conference repo has issue #142 on DNS redirects.
5. **Which conference branch** the `/science` work goes on, and where its PR is targeted.

## Immediate next steps
- Torsten: fork `at-science-homepage`, rebase on current `main` (local copy is 32 commits behind), open the PR for the events page. Add the `/science` link once it is live.
- Jon: fork `atmosphereconf`, build `/science`.
- Create the shared content repo (if agreed), seeded from `2026-10-28-atscience-x-iosp-content-overview.md`.
