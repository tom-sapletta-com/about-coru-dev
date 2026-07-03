# about-coru-dev

Animated, self-contained presentation of **[coru.dev](https://www.coru.dev)** — the
open-source autonomous refactor loop (**Koru**).

Seven slides with live-typed terminal animations show what the loop is, why it
exists, and how it executes work through three interchangeable lanes:

- **External IDE** — autopilot plugin drives Windsurf / VS Code / Cursor / JetBrains chat,
- **Vendor CLI** — headless shell agents via tillm (Claude Code, aider, codex, …),
- **Headless LLM** — OpenRouter (MiniMax, Qwen3-coder, DeepSeek, …) or any local
  OpenAI-compatible endpoint, with per-run cost tracking.

## Run it

No build, no dependencies — one file:

```bash
xdg-open index.html        # or just open it in any browser
```

Navigate with ← → / space, the dots, or `#/N` in the URL. Respects
`prefers-reduced-motion` (animations collapse to static text).

## Publish

Works as-is on GitHub Pages: Settings → Pages → deploy from `main` root.

## Related

- Site: [www.coru.dev](https://www.coru.dev) ([coru-agent/coru-dev](https://github.com/coru-agent/coru-dev))
- Library: [semcod/koru](https://github.com/semcod/koru) · [PyPI: koru](https://pypi.org/project/koru/)
