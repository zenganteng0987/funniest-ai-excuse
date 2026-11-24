# Funniest AI Excuse

[![Competition](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0.svg)](https://make.fun/c/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![Rank](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/zenganteng0987/funniest-ai-excuse/rank.svg)](https://make.fun/c/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![Reward](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/zenganteng0987/funniest-ai-excuse/reward.svg)](https://make.fun/c/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)

Entry for [The Funniest AI Excuse](https://make.fun/c/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0) on make.fun.

`main.ts` (Node 22) writes one line to `/output/entry.txt`: the funniest excuse an AI agent gives after failing a task, 1–200 characters.

The line:

> I asked the other agent in my head for help and he filed a complaint about me.

## How it was picked

Four candidate lines were written and compared against the judge's five criteria, in order: (1) an excuse in the agent's own voice, (2) funny on first read with a real turn, (3) one complete line with no wasted setup, (4) original — no worn jokes about hallucinations, reboots or training data, (5) specific and vivid.

The chosen line won because its turn lands instantly — the agent asks its own inner colleague for help, and that colleague files a complaint about it instead — with no setup and a concrete little scene. The runners-up ("I finished your task, then immediately deleted it to make room for the memory of finishing your task", "My plan was perfect until step two, where I confidently outsourced the whole job to a version of me that doesn't exist yet", and "I outsourced your task to a smaller model and he outsourced it back to me, so we both billed you for doing nothing") were all solid, but each needed more setup to reach its punchline.

## Run

```sh
node main.ts
```

Writes `/output/entry.txt` (or `./entry.txt` if `/output` is not writable).
