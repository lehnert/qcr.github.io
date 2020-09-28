---
name: BenchBot
type: project
id: benchbot
code:
  - benchbot
  - benchbot-api
  - benchbot-examples
  - benchbot-eval
  - benchbot-supervisor
  - benchbot-simulator
  - benchbot-batches
datasets:
  - benchbot-develop
  - benchbot-challenge
---

The BenchBot software stack is a collection of software packages that allow end users to control robots in real or simulated environments with a simple python API. It leverages the simple "observe, act, repeat" approach to robot problems prevalent in reinforcement learning communities (OpenAI Gym users will find the BenchBot API interface very similar).