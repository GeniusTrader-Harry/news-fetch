---
name: Bug report
about: Something in the routine isn't working as expected
title: "[Bug] "
labels: bug
---

## What happened

<!-- What did you expect, what did you get? -->

## At which step

- [ ] Setup (Telegram bot creation / cookie export / scheduled task registration)
- [ ] Daily run (the scheduled task itself fails or produces wrong output)
- [ ] Telegram delivery (brief synthesised but not sent)
- [ ] Other

## Reproduction

<!-- Exact commands you ran or the section of routine-prompt.md you were on -->

## Environment

- macOS version:
- Claude Code version (`claude --version`):
- Python version (`python3 --version`):
- `curl_cffi` version (`pip show curl_cffi`):
- Repo commit (`git rev-parse HEAD` in your install):

## Brief output (if relevant)

<!-- A line or two of the brief that's wrong, or the agent's session log line that errored. -->
<!-- IMPORTANT: redact any secrets — bot tokens, chat_ids, cookie strings, personal email. -->

## What you tried

<!-- e.g. "re-exported cookies, restarted Claude Code, ran Run Now twice" -->
