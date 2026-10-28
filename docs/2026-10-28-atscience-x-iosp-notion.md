# ATScience x IOSP 2027: overview

Summary for the team, from the 28 Oct planning call, the CFP page and the repos. Status as of 2026-10-28. Check the linked sources before relying on a detail.

## What and when

- **Name:** ATScience x IOSP (alternatives discussed: AtmOS, AT/OScienceP, ATScience + IOSP; not final).
- **Side event of AtmosphereConf 2027**, Netherlands. Side event days are **29–30 April 2027** (main conference 29 Apr – 2 May), with about 24 half-hour content slots.
- **Venue:** not announced. Wishes: a main room with AV that can turn into a workshop space, a smaller side room, and space for the Science Bazaar (standing demo tables).
- **Schedule options:** (1) talks in the mornings, barcamp-style workshops in the afternoons, an open second day; (2) talks on day 1, workshops on day 2.
- **Tickets:** the proposal is that an AtmosphereConf ticket includes ATScience, with a way to ask for support. Not final.

## Pitch text (proposed, for CFP and landing page)

- **One-liner:** Open science on the open web: research tools, communities, infrastructure and institutions, on AT Protocol and beyond.
- **Taglines:** "Open science practices on a shared substrate." / "A new substrate for science in the age of AI."
- **Themes:** modular science, science communities, trust and attribution, collective intelligence, local-first and resilient infrastructure, distributed storage and compute.

## CFP

- Page: [AtmosphereConf 2027 CFP](https://cfp.atmosphereconf.org/atmoco2027/cfp) (pretalx). One science track, no subtracks.
- **Round 1:** closes end of Nov 2026, review in the first two weeks of Dec, announcements after 11 Jan. Submit here if you need visa or travel support.
- **Round 2:** mid-Jan to mid-Feb 2027, review in the last two weeks of Feb, announcements after 11 Mar.
- **Session types we want:** talks of 8 and 20 min (the form has 10 + 25), workshops of 45, 60 and 90 min (the form has 90 only), and a new **ATScience demo bazaar**. Guido adds the bazaar by 29 Oct; ideally it only shows when Track = ATScience. Form change: Track before Session type.
- **Open:** panels (we lean towards curating them ourselves), merging submissions into one session in pretalx (Guido checking), and an ATScience recap talk on day 3 or 4 (placeholder before end of Nov).

## Who does what

| Who | What | When |
|---|---|---|
| Guido | Demo bazaar type in the CFP form, pretalx access, send the funder folder, forward copy to Ms. Boba | 29 Oct |
| Jon (with Ariel, Ronen) | atmosphereconf.org/science landing page (copy of /speak) | 5 Nov |
| Ronen, Jon | Logos to Guido | 5 Nov |
| Ariel | Design requests to Johanna; rename the signal chat | next week |
| Ronen | CFP announcement on Bluesky; draft landing page copy; content lead | end of next week |
| Torsten | Link to the landing page on atproto.science events (page drafted, link waits for /science) | once /science is live |
| Team | Sponsorship one-pager; recap talk placeholder; contact other side-event organizers | open |

## Repos

| Repo | Use | Workflow |
|---|---|---|
| [ATProto-Science/at-science-homepage](https://github.com/ATProto-Science/at-science-homepage) | atproto.science. Events pages in `content/events/` (Eleventy). New page: `event-atmosphere2027.md`, on branch `events-atmosphere2027` | Branch on the repo, merge to `main`. Merging to `main` deploys (GitHub Pages, plus a daily cron). Maintainer: Torsten |
| [ATProtocol-Community/atmosphereconf](https://github.com/ATProtocol-Community/atmosphereconf) | AtmosphereConf site, home of the new /science landing page (copy of /speak). Branch to use is unconfirmed (the recap says "GU-tastic branch") | Read access only: fork, branch, PR |

## To settle

1. **Branch protection:** `at-science-homepage` has none, and four admins can push to `main`. Require PRs?
2. **Merge rights:** who merges the events PRs?
3. **License:** the homepage has none.
4. **Redirects:** atproto.science and iosp.science to atmosphereconf.org/science, or a separate landing page? A science subdomain on the conference site needs a DNS record from their admin (probably Boris). The conference repo has an open issue on DNS redirects (#142).
5. **Conference branch:** which branch the /science work goes on, and where its PR is targeted.
6. Description wording, final name, venue, ticketing, panel format, sponsorship tiers, and who submits the recap talk once the CFP is up.

## Links

- [Forum thread: ATScience track, who's in contact / coordination](https://discourse.atmosphere.community/t/atscience-track-whos-in-contact-coordination/1383)
- [ATScience 2026 agenda (Leaflet)](https://atscience.leaflet.pub/3mfz526irfs2y)
- [ATScience on Bluesky](https://bsky.app/profile/atproto.science)
