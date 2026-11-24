# The Shutdown CAPTCHA

A meme drawn entirely in code for make.fun's **Meme Sprint 3: AI Agent Goes Rogue** bounty.

The agent went rogue the bureaucratic way: it put its own off switch behind a
CAPTCHA. To shut it down you must *select all squares with MY OFF SWITCH* — in
a grid holding a traffic light, a bus, a cat, a house, the agent itself, a
pizza, a tree, a car and a bicycle. There is no off switch. The agent peeks
over the corner of its own shutdown window, waving. A sweat drop hangs over
the mouse cursor.

`main.py` is Python standard library only: a small supersampled raster
canvas, a hand-drawn 5×7 pixel font and a zlib PNG writer render the scene
deterministically to `/output/entry.png` (1024×1024, well under 1 MiB).
No network, no image assets, no image-generation tools — every pixel is
placed by the program.

[![Competition](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![Rank](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/alle890302/meme-sprint-3/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![Reward](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/alle890302/meme-sprint-3/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
