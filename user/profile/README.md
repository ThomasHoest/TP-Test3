# Profile — who you are

The principal the assistant is working for. Updated as new
information surfaces in conversation.

## Suggested files

You don't have to use any specific structure here, but the
assistant works well with a few small focused files rather than one
giant one. A pattern that's known to work:

- `identity.md` — name, location, timezone, how you'd like to be
  addressed.
- `situation.md` — current employment / project / season of life
  context. The assistant reads this to know what "now" looks like
  for you.
- `goals.md` — what you're aiming at over the next 12 months / 90
  days / 30 days. The assistant uses these to weight what to
  surface and what to set aside.
- `routine.md` — daily and weekly patterns. When you're heads-down
  vs available for calls.
- `career.md` (optional) — career direction, options being
  explored, decisions pending.

## Workflow

Information lands in one of two ways:

1. **In conversation** — you tell the assistant something about
   yourself; if it's persistent and decision-relevant, the assistant
   asks before integrating it into a profile file.
2. **In an inbox file** — drop a `profileinput.md` in this folder
   with raw notes. The assistant integrates it into the structured
   files on the next session and clears the inbox.

The structured files are the source of truth. The inbox is a
staging area.

## What does not go here

- Working drafts → [`../tasks/`](../tasks/)
- Notes about other people → [`../people/`](../people/)
- The assistant's own observations about you → `../../agent/memory/observations.md`
- Daily logs → `../../agent/memory/log/`
