# 🧩 Emin Akcil Claude Mods

[![CI](https://github.com/eminakcil/claude-code-mods/actions/workflows/ci.yml/badge.svg)](https://github.com/eminakcil/claude-code-mods/actions/workflows/ci.yml)

**Mods for [Claude Code](https://docs.claude.com/en/docs/claude-code), in one plugin marketplace.**

Each mod lives in its own repository, with its own README, tests and CI. This repository lists them, so one `marketplace add` gives you all of them.

## 📦 Mods

| Mod | What it does |
| --- | --- |
| 📊 [**session-hud**](https://github.com/eminakcil/session-hud) | Your CLI status line in the desktop app: context, prompt cache, response speed, usage limits and git |

![Real capture of the session-hud band above the prompt](https://raw.githubusercontent.com/eminakcil/session-hud/main/assets/band.png)

## 🚀 Install

Add the marketplace once, then install the mods you want:

```sh
claude plugin marketplace add eminakcil/claude-code-mods
claude plugin install session-hud@emin-akcil-claude-mods
```

Restart Claude Code or run `/reload-plugins` in an open session.

**Desktop app**: **+** next to the prompt box → **Plugins** → **Add marketplace** `eminakcil/claude-code-mods` → **Add plugin**.

Each mod's README lists the Claude Code version it needs and what it can reach.

## 🤝 Contributing

- 🐛 A bug or an idea for a mod: open an issue in that mod's repository.
- 🧩 A new mod for this list: open a [new mod proposal](https://github.com/eminakcil/claude-code-mods/issues/new?template=new_mod.yml) first. A listed mod lives in its own public repository and has a README with a "What it can reach" section, tests and CI running `claude plugin validate` and `claude plugin test`.

CI validates `marketplace.json` on every pull request.

Built by [Emin Akcil](https://github.com/eminakcil). [MIT](LICENSE) licensed.
