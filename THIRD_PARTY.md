# Third-party software and attribution

No upstream code, text, or binary is included in this repository. Everything under `lib/`, `test/`, `cordis.patch.yml`, and `package.json` is original work; this file records what it runs on.

## Host and dependencies

| Component | Role here | Project | Licence | Distribution |
|---|---|---|---|---|
| DeepSeek Harness | Host: permission presets, the `approval/request` waterfall, and the system-prompt service | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | MIT | installed separately, not vendored |
| Node.js | Runtime for the plugin and its tests | <https://nodejs.org> | MIT | installed separately |

## Copyright and licence compliance

- **Original files:** the MIT [`LICENSE`](LICENSE) covers `package.json`, `cordis.patch.yml`, `lib/index.js`, `test/index.test.mjs`, and the documentation in this repository.
- **Upstream notices:** none are redistributed, because no upstream file is present here.
- **Unresolved:** none.
