---
name: st
description: >-
  Run git status and print output. Trigger when the user sends
  "st" or "git status" as their message.
model: claude-haiku-4-5-latest
user-invocable: false
disable-model-invocation: false
allowed-tools: Bash(git status)
---

Run `git status` and print the output. Do not use `cd` or `git -C`. Do not add
any commentary, chat messages, or thinking. Just run the command and show the
raw output.
