# Your vault: how it works

This folder is your business's memory. It has three zones: `raw/`, `wiki/`, and `scratch/`.

- **raw/**: drop anything in `raw/inbox/`: an article, a call transcript, an export.
  Nothing in here ever gets edited. It is the evidence locker.
- **wiki/**: the distilled truth. Your lessons, your procedures, your decisions, your
  research. The AI writes and maintains every page. You read it; the AI handles filing.
- **scratch/**: the AI's workbench. Ignore it.

Four root files keep it reliable: `index.md`, `log.md`, `queue.md`, and `inbox-ledger.md`.
`queue.md` keeps work alive between skills, and `inbox-ledger.md` prevents duplicate ingests.
One shipped check, `graph-audit`, blocks broken lifecycle state and bad receipts before a skill
calls its filing complete.

The AI handles the bookkeeping. Drop things in the inbox, run your skills, make your calls.
The vault stays organized because the AI does the maintenance no one wants to do.
