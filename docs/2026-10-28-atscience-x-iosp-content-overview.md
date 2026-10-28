# ATScience x IOSP — condensed overview (2026-10-28)

One-page summary for the team, from the 28 Oct planning call (notes + Fathom recap), the CFP page and the repos. Status as of 2026-10-28; check the linked sources before relying on a detail.

## What and when
- **Name:** ATScience x IOSP (alternatives discussed: AtmOS, AT/OScienceP, ATScience + IOSP; not final).
- **Side event of AtmosphereConf 2027**, Netherlands. Side event days **29–30 April 2027** (main conference 29 Apr – 2 May). About 24 half-hour content slots.
- **Venue:** not announced. Wishes: a main room with AV that can turn into a workshop space, a smaller side room, space for the Science Bazaar (standing demo tables).
- **Schedule options:** (1) talks in the mornings, barcamp-style workshops in the afternoons, an open second day; (2) talks on day 1, workshops on day 2.
- **Tickets:** proposal is that an AtmosphereConf ticket includes ATScience, with a way to ask for support. Not final.

## Pitch text (proposed, for CFP/landing page)
- **One-liner:** Open science on the open web: research tools, communities, infrastructure and institutions, on AT Protocol and beyond.
- **Taglines:** "Open science practices on a shared substrate." / "A new substrate for science in the age of AI."
- **Themes:** modular science, science communities, trust and attribution, collective intelligence, local-first and resilient infrastructure, distributed storage and compute.

## CFP
- Page: <https://cfp.atmosphereconf.org/atmoco2027/cfp> (pretalx), one science track, no subtracks.
- **Round 1:** closes end of Nov 2026, review first two weeks of Dec, announcements after 11 Jan. Submit here if you need visa or travel support.
- **Round 2:** mid-Jan to mid-Feb 2027, review last two weeks of Feb, announcements after 11 Mar.
- **Session types we want:** talks of 8 and 20 min (the form has 10 + 25), workshops of 45, 60, 90 min (the form has 90 only), and a new **ATScience demo bazaar** (Guido adds it by 29 Oct; ideally only shown when Track = ATScience). Form change: Track before Session type.
- **Open:** panels (we lean to curating them ourselves), merging submissions into one session in pretalx (Guido checking), an ATScience recap talk on day 3 or 4 (placeholder before end of Nov).

## Who does what
| Who | What | When |
|---|---|---|
| Guido | Demo bazaar type in CFP form, pretalx access, send the funder folder, forward copy to Ms. Boba | 29 Oct |
| Jon (with Ariel, Ronen) | atmosphereconf.org/science landing page (copy of `/speak`) | 5 Nov |
| Ronen, Jon | Logos to Guido | 5 Nov |
| Ariel | Design requests to Johanna; rename the signal chat | next week |
| Ronen | CFP announcement on Bluesky; draft landing page copy; content lead | end of next week |
| Torsten | Link to the landing page on atproto.science events (page drafted, link waits for /science) | once /science is live |
| Team | Sponsorship one-pager (Linux Foundation etc.); recap talk placeholder; contact other side-event organizers | open |

## Repos (team works with forks and PRs)
| Repo | Use | Link |
|---|---|---|
| `ATProto-Science/at-science-homepage` | atproto.science, events pages in `content/events/` (Eleventy). New: `event-atmosphere2027.md` | <https://github.com/ATProto-Science/at-science-homepage> |
| `ATProtocol-Community/atmosphereconf` | AtmosphereConf site, `/speak` template; recap says "GU-tastic branch", branch to use unconfirmed (ask Jon/Guido) | <https://github.com/ATProtocol-Community/atmosphereconf> |

**Workflow:** fork, branch, open a PR against `main`. The homepage has an active deploy workflow (`.github/workflows/deploy2.yml`), so merging to `main` can go live.

## Links
- Forum thread, ATScience track coordination: <https://discourse.atmosphere.community/t/atscience-track-whos-in-contact-coordination/1383>
- Previous event page (2026): `content/events/event-atmosphere2026.md` in the homepage repo; agenda <https://atscience.leaflet.pub/3mfz526irfs2y>
- ATScience on Bluesky: <https://bsky.app/profile/atproto.science>

## Still open
Description wording, final name, venue, ticketing, panel format, sponsorship tiers, who submits the recap talk once the CFP is up.
