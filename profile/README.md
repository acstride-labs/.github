<div align="center">

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/logo.svg" width="100" height="100" alt="AC-Stride logo">

# AC-Stride

**Problem statements, code and tests. Together in VS Code.**

[Website](https://acstride.com/en) · [Download](https://github.com/acstride-labs/acstride-vscode-extension/releases) · [Documentation](https://github.com/acstride-labs/acstride-vscode-extension#readme) · [Discussions](https://github.com/orgs/acstride-labs/discussions)

**English** | [简体中文](https://github.com/acstride-labs/.github/blob/main/profile/README.zh-CN.md) | [日本語](https://github.com/acstride-labs/.github/blob/main/profile/README.ja.md) | [Русский](https://github.com/acstride-labs/.github/blob/main/profile/README.ru.md)

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/workflow.svg" width="100%" alt="An illustrated overview of the AC-Stride workflow: import a challenge, read the statement, write code and check the result">

</div>

## Your contest workspace

AC-Stride is a collection of tools for Codeforces contests and everyday competitive programming practice. Bring problems into your editor, work in your preferred language, and test your solution alongside the statement.

| | What you can do |
| --- | --- |
| **Import and read** | Import a contest or a single Codeforces problem, or create a local practice problem. Statements and samples download automatically. |
| **Write in your language** | Use C++, Python, Java or Kotlin with independent source files, starter templates and environment checks. Keep your usual VS Code extensions and shortcuts. |
| **Test and compare** | Run official samples and custom cases, inspect stdout and stderr, and find the first output difference. Stop a run or apply a time limit. |
| **Follow the round** | View submission history, official verdicts and standings. Copy code and open the official submission page, or use confirmed one-click submission after signing in. |
| **Translate when needed** | Connect your own AI provider for on-demand or automatic statement translation. Choose the target language and prompt, with optional local LRU caching. |

The interface is available in English, Simplified Chinese, Japanese and Russian.

## Get started

1. **Install the extension.** Download the VSIX for your platform from [Releases](https://github.com/acstride-labs/acstride-vscode-extension/releases), then run **Extensions: Install from VSIX...** in VS Code.
2. **Check your tools.** Open a trusted local folder. In **AC-Stride Settings**, choose your default programming language and check its compiler or runtime.
3. **Import a challenge.** Add a Codeforces contest or problem, or create a local problem. Open the statement, write your solution and run the tests.

Codeforces tools are bundled with the extension; no separate CF Tool installation is needed. Install the compiler or runtime for your solution language separately. Java needs a JDK; Kotlin also needs the Kotlin compiler.

> **Preview:** Login and automatic submission are experimental and may be blocked by Codeforces site verification. Public problem downloads and local practice work without login. Automatic submission always requires confirmation.

## The projects

| Project | Role |
| --- | --- |
| [VS Code Extension](https://github.com/acstride-labs/acstride-vscode-extension) | The editing workspace: statements, solutions, local tests and contest information. |
| [CF Tool](https://github.com/acstride-labs/acstride-cf-tool) | The Codeforces client and CLI behind downloads, contest data and submission operations. |
| [Website](https://github.com/acstride-labs/acstride-web) | Product information, downloads and getting-started guides. |

## Questions, ideas or a bug?

- **Ask a question:** visit [Q&A](https://github.com/orgs/acstride-labs/discussions/categories/q-a).
- **Suggest an improvement:** share it in [Ideas](https://github.com/orgs/acstride-labs/discussions/categories/ideas).
- **Report a bug:** open an issue in the [extension](https://github.com/acstride-labs/acstride-vscode-extension/issues), [CF Tool](https://github.com/acstride-labs/acstride-cf-tool/issues) or [website](https://github.com/acstride-labs/acstride-web/issues) repository. Include reproduction steps, your platform and version, and logs with secrets removed.
- **Follow updates:** check [Announcements](https://github.com/orgs/acstride-labs/discussions/categories/announcements) and the [extension changelog](https://github.com/acstride-labs/acstride-vscode-extension/blob/master/CHANGELOG.md).
