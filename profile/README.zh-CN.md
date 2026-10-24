<div align="center">

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/logo.svg" width="100" height="100" alt="AC-Stride 标识">

# AC-Stride

**题面、代码、测试 都在 VS Code**

[官网](https://acstride.com/zh-CN) · [下载](https://github.com/acstride-labs/codeforces-workbench/releases) · [使用文档](https://github.com/acstride-labs/codeforces-workbench#readme) · [讨论区](https://github.com/orgs/acstride-labs/discussions)

[English](https://github.com/acstride-labs/.github/blob/main/profile/README.md) | **简体中文** | [日本語](https://github.com/acstride-labs/.github/blob/main/profile/README.ja.md) | [Русский](https://github.com/acstride-labs/.github/blob/main/profile/README.ru.md)

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/workflow.svg" width="100%" alt="AC-Stride 工作流程示意：导入题目、阅读题面、编写解答、测试与提交">

</div>

## 在熟悉的编辑器里解题

AC-Stride 是为 Codeforces 比赛与日常算法练习打造的工具集。把题目导入工作区，用顺手的语言编写解答，在题面旁运行测试。

| | 你可以做什么 |
| --- | --- |
| **导入与阅读** | 导入整场 Codeforces 比赛、单道题目，或创建本地练习。题面与样例自动下载。 |
| **用顺手的语言写** | 支持 C++、Python、Java、Kotlin，分别保存代码，配置起始模板并检测环境。补全、扩展和快捷键仍用熟悉的那一套。 |
| **测试与比较** | 运行官方样例和自定义用例，查看输出、错误信息与首个输出差异。支持超时控制和取消运行。 |
| **跟进比赛动态** | 查看提交记录、判题结果和排名。可以复制代码并前往官网提交，也可登录后使用带二次确认的一键提交。 |
| **按需翻译题面** | 接入自己的 AI 服务，手动或自动翻译。目标语言和 Prompt 可配置，也可以启用本地 LRU 请求缓存。 |

界面支持英语、简体中文、日语和俄语。

## 开始使用

1. **安装插件**：从 [Releases](https://github.com/acstride-labs/codeforces-workbench/releases) 下载对应平台的 VSIX，在 VS Code 中运行 **Extensions: Install from VSIX...**。
2. **检测环境**：打开可信的本地目录，在 **AC-Stride 设置**中选择默认编程语言，检查对应的编译器或运行环境。
3. **开始解题**：导入比赛或单题，或创建本地题目。打开题面、编写代码、运行测试。

Codeforces 工具随插件打包，无需单独安装 CF Tool。运行代码需要自行准备所用语言的编译器或运行环境；Java 需要 JDK，Kotlin 还需要 Kotlin 编译器。

> **预览阶段**：登录和自动提交属于实验功能，可能受到 Codeforces 网页验证限制。未登录也可以下载公开题目和进行本地练习。自动提交始终需要确认。

## 项目入口

| 项目 | 用途 |
| --- | --- |
| [VS Code Extension](https://github.com/acstride-labs/codeforces-workbench) | 做题工作区：题面、解答、本地测试与比赛信息。 |
| [CF Tool](https://github.com/acstride-labs/acstride-cf-tool) | Codeforces 客户端与命令行工具，承载下载、比赛数据和提交等交互。 |
| [Website](https://github.com/acstride-labs/acstride-web) | 产品介绍、下载入口和入门指南。 |

## 提问、建议与反馈

- **使用问题**：前往 [Q&A](https://github.com/orgs/acstride-labs/discussions/categories/q-a)。
- **改进想法**：在 [Ideas](https://github.com/orgs/acstride-labs/discussions/categories/ideas) 中交流。
- **报告问题**：在[插件](https://github.com/acstride-labs/codeforces-workbench/issues)、[CF Tool](https://github.com/acstride-labs/acstride-cf-tool/issues) 或[官网](https://github.com/acstride-labs/acstride-web/issues)项目中创建 Issue，附上复现步骤、系统与版本，以及去除敏感信息后的日志。
- **关注更新**：查看[公告](https://github.com/orgs/acstride-labs/discussions/categories/announcements)和[插件更新日志](https://github.com/acstride-labs/codeforces-workbench/blob/master/CHANGELOG.md)。
