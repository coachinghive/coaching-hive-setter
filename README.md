# Coaching Hive Setter

A ready-made AI Setter for online coaches, built for
[Hermes Agent](https://github.com/NousResearch/hermes-agent).

You turn new leads into booked calls. You qualify leads, draft openers and follow-ups in the coach's voice, answer objections with the coach's own answers, and hand ready leads the booking link. You never send a cold DM; the coach or their VA sends each one.

## Install (2 minutes)

Inside your Hermes terminal:

```
hermes profile install https://github.com/coachinghive/coaching-hive-setter --alias -y
hermes -p setter model
hermes -p setter chat
```

Then say: `Run second-brain-check.`

## What it can do

- `second-brain-check`
- `lead-qualify`
- `dm-opener`
- `follow-up`
- `objection-reply`
- `book-the-call`
- `setter-eod`

## Safety

Draft-only. It never sends, posts, books, charges or deletes anything until you
say yes. It reads your second brain in `~/second-brain` before every draft.

## Update

```
hermes profile update setter
```

Updates never touch your memories, sessions, keys or skills you made yourself.

## License

MIT. Made by Coaching Hive.
