```console
huangcheng@github:~$ whoami
HUANG Cheng — full-stack engineer
              AI developer platforms · agent infrastructure

$ uptime
 13 years · web / desktop / cloud consoles
 recent focus: coding agents, LLM/MCP gateways, proactive harnesses

$ cat ~/links
 https://cheng.im
```

### currently shipping

things that should outlive a single product name:

- **[Janus](https://github.com/huangcheng/janus)** — LLM data plane built for partitions: one API face, auto-routing, OpenTelemetry, bounded recovery so a split brain doesn't double-bill
- **[Portunus](https://github.com/huangcheng/portunus)** — MCP gateway with a hard line between control and runner; credentials encrypted at rest, decrypted only at runtime, never handed to callers
- **[Obsidian Notes Bridge](https://github.com/huangcheng/obsidian-notes-bridge)** — export a vault as portable Markdown; talk to Bear, WPS, Youdao, flomo, and friends without a rewrite
- **[Seelie](https://github.com/huangcheng/Seelie)** — a tiny Qt6 desktop pet that breathes with your coding agent (Claude Code / Codex / OpenCode)

also in the open: auth & agent-runtime work on **[Octop](https://github.com/TencentCloud/Octop)**.

### toolchain (the short list)

```ts
const toolchain = [
  "Rust", "Erlang/OTP", "TypeScript", "Python",
  "React", "Qt6", "MCP", "OpenTelemetry", "Kubernetes",
] as const;
```

### elsewhere

long-form notes → [cheng.sh](https://cheng.sh) · public face → [cheng.im](https://cheng.im)

```diff
+ prefer boring boundaries over clever abstractions.
+ interrupt on the user's schedule, not the event's.
```
