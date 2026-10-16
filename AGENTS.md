# Maintenance

- `README.md` is the only list. Two sections: `Agent × Real2Sim2Real` and `Real2Sim2Real`. Newest first.
- Line format: `- YYYY-MM-DD [Title](https://arxiv.org/abs/<id>) — one line on what it does and why it matters.` Date = first arXiv submission date.
- One paper appears once. Check the arXiv id before adding.
- Agent × Real2Sim2Real: an agent (LLM / VLM / agentic pipeline) builds, edits, verifies or uses a simulation made from real data. Real2Sim2Real: real-to-sim, sim-to-real loops, digital twins, reconstruction for policy training or evaluation, with no agent.
- Skip papers that only mention sim-to-real in passing (plain domain randomization, pure sim RL) or only do agents in sim with no real data.
- Write the one-liner from the abstract. Do not invent results.
- No other files, scripts or databases unless the user asks.
- Commit message: `Add papers YYYY-MM-DD`. Push to `origin main`.
