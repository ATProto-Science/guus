# guus: coordination hub for ATScience x IOSP at AtmosphereConf 2027

Shared planning repo for the side event (Netherlands, 29-30 April 2027). Not a code project. Tasks live in `.beans/` (prefix `guus-`), notes and drafts in `docs/`.

## How to collaborate

1. **Clone** the repo. Never work in someone else's checkout or edit files on a shared drive copy.
2. **Branch, or use a worktree**, for every piece of work: `git switch -c <short-topic>` or `git worktree add ../guus-<topic> -b <short-topic>`. Do not commit to `main` directly.
3. **Humans and agents both use the `beans` CLI** ([hmans/beans](https://github.com/hmans/beans)). Bootstrap: `go install github.com/hmans/beans@latest` (needs Go; the binary lands in `~/go/bin`), then `beans prime` for the usage guide. Run it from the repo root to create and update tasks: `beans list`, `beans create`, `beans update`. Do not hand-edit `.beans/*.md`. Bean IDs are random, so parallel branches rarely collide. Do not rename or recreate beans, since other branches reference their IDs.
4. **Keep changes small** and one topic per branch. Put the bean ID in the commit message when a commit relates to a bean.
5. **Open a PR against `main`** and say what changed. Someone other than the author merges.
6. **Pull before you start**: `git pull --rebase origin main`.

## Rules for agents

- Do not push to `main` and do not force-push. Push only your own branch.
- Do not put personal, employment, funding or contract details of any individual in this repo.
- Do not paste meeting recordings or transcripts here. Only decisions and action items.
- Mark anything unconfirmed as unconfirmed. Do not turn a guess into a decision.
- Dates and facts that come from a call or the CFP page should name their source.
