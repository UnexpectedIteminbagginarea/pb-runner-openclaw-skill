# PB-Runner skill for OpenClaw

An OpenClaw skill that connects your agent to [PB-Runner](https://pb-runner.com), a running coach for iPhone, Apple Watch, Android and Garmin.

With it, your agent can read your runs, recovery and goal, check in with you on a schedule, and draft training sessions that play on your watch or phone, which it is asked to save only after you say yes.

- The skill is text only: [`pb-runner/SKILL.md`](pb-runner/SKILL.md). It contains no code, no install scripts and no keys.
- It connects to PB-Runner's MCP server at `https://mcp.pb-runner.com/mcp` with the `streamable-http` transport and OAuth. You sign in with Apple or Google, using the same account as the PB-Runner app.
- Your agent sees your runs, recovery, profile, personal bests, goal and schedule. PB-Runner never gives it GPS routes or coordinates. A run or race name can still mention a place, because Garmin names runs after the town they started in.
- Coaching and recovery readings are not medical advice.
- Step-by-step setup for people: https://pb-runner.com/guide/openclaw

Install from ClawHub (listing: https://clawhub.ai/pb-runner/pb-runner):

```
openclaw skills install @pb-runner/pb-runner
```

You need a PB-Runner account: the app is free on the App Store, Google Play and the Connect IQ Store.

Made by Bunker 47 LTD. Support: support@pb-runner.com. Privacy policy: https://pb-runner.com/privacy

Licensed MIT-0, as every ClawHub skill is.
