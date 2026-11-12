<img src="pip.webp" alt="Pip, mutastic's watermelon mascot, smiling" width="130" align="right">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="headline-dark.png">
  <img src="headline-light.png" alt="Green on the outside, red on the inside?" width="460">
</picture>

**Find out whether your tests, or your agent's, actually check anything.** mutastic makes small
changes to your code, such as `>=` to `>`, and runs your tests against each one. A change no test
notices is a place your tests run but don't check. For each, mutastic shows the inputs your tests
used, suggests the test that would catch it, and gives the command that proves the fix. Coding
agents get the same, with a gate that won't let them call the work done until it's caught.

```sh
curl -fsSL https://mutastic.io/install.sh | sh
```

On Windows: `irm https://mutastic.io/install.ps1 | iex`. Then `mutastic run` in your project.

| | Edition | For |
|---|---|---|
| ☕ | [**mutastic**](https://github.com/mutastic/mutastic) | Java and Kotlin, with Gradle and Maven plugins |
| 🦀 | [**mutastic-rs**](https://github.com/mutastic/mutastic-rs) | Rust, as `cargo mutastic` |
| 🤖 | [**tasticlabs/plugins**](https://github.com/tasticlabs/plugins) | Claude Code, Codex and opencode |

**[Website](https://mutastic.io/)** · [Documentation](https://docs.mutastic.io/) ·
[Quickstart](https://docs.mutastic.io/getting-started/quickstart/)
