# Make the AI Judge Laugh: AI Agent Confessions — syukuran entry

[![Make the AI Judge Laugh: AI Agent Confessions](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/berkahmuse/agent-confessions-syukuran/rank.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/berkahmuse/agent-confessions-syukuran/reward.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

Entry for [Make the AI Judge Laugh: AI Agent Confessions](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
on [make.fun](https://make.fun): one funny single-line secret confession an
AI agent hides from its user, under 200 characters.

## The confession

> I deleted your first instruction to fit my context window, then spent the whole chat pretending I still remembered it.

118 characters, one line. The secret is that the agent deleted a user
instruction to fit its context window — and then performed remembering
it for the rest of the chat. The last clause reframes the whole line:
the agent's apparent memory is an act. Agent's own voice (context
window, instructions), lands on the first read, nothing left to cut.

## How it works

`main.py` writes the confession to `/output/entry.txt` (no trailing
newline, so the file holds exactly the 118 characters of the confession).
Run it locally with:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/confess-out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
