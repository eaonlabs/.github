<div align="center">
  <img src="https://avatars.githubusercontent.com/u/310382997?v=4" width="80" alt="Eaon">

  # Eaon

  **Every model, on your machine.**

  [eaon.dev](https://eaon.dev) &nbsp;·&nbsp; [developer@eaon.dev](mailto:developer@eaon.dev)
</div>

<br>

Two native apps that put AI where you already work — on your own keys, or on a
model that never leaves your machine. Hosted, bring-your-own-key and fully
local models sit behind the same picker, whichever one you're in.

## [Eaon](https://github.com/eaonlabs/eaon-desktop)

A native chat client — SwiftUI on macOS, Tauri on Windows and Linux, a
terminal build for everywhere else — all in one repo. Every large model in
one picker: Eaon's hosted catalog, your own OpenAI/Anthropic/Gemini-style
key, or Ollama, llama.cpp and MLX running on the machine in front of you, no
account needed for the local-only path. Plugins reach real accounts over
MCP, an agent mode writes and runs actual files on your disk, and a local
API server can turn the app itself into an OpenAI-compatible endpoint for
whatever else you're building.

## [Eaon ADE](https://github.com/eaonlabs/Eaon-ADE)

An agentic development environment. Run a dozen CLI coding agents side by
side — Claude Code, Codex, whatever else speaks a terminal — see which ones
are working and which are stuck, and drive them from one grid. Every pane is
a genuine pseudo-terminal running your own login shell; ADE just knows the
thing inside it is usually an agent. Sessions come back on their own after a
restart, a shared Brain lets every agent in a project pick up what the last
one learned, and voice dictation runs a Whisper model entirely on-device,
with remote loading switched off so it has no way to reach the network.

## [R.E\\D.](https://github.com/eaonlabs/Eaon-RP)

The odd one out, and the one running live at
[rp.eaon.dev](https://rp.eaon.dev): a roleplay site. Build a character, find
one someone else made on a shared shelf, and read a story that streams back
a turn at a time. No account and no key to paste in anywhere — the story
engine sits behind a free gateway, shared by every visitor under the same
rate limit.

---

<div align="center">

All three repos are GPL-3.0. Issues and pull requests are read; `good first
issue` is where to start on any of them.

</div>
