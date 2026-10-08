# goals

## 日本語

GitHub Issue の課題解決を AI エージェントに任せるための、反復実行用ゴール定義テンプレートです。

[goal.md](./goal.md) には、完了条件・検証方法・制約・反復手順・停止条件を定義しています。エージェントは調査・検証・Issue への報告を繰り返し、完了条件を満たすか、継続が困難になった時点で停止します。

**使い方:** `goal.md` を対象プロジェクトに配置し、解決したい GitHub Issue を指定して、対応する AI エージェントに実行させてください。

## English

A goal-definition template for AI agents to iteratively resolve GitHub issues.

[goal.md](./goal.md) defines success criteria, verification steps, constraints, an iteration workflow, and blocking conditions. The agent investigates, validates, and reports findings to the issue until the goal is met or further progress is blocked.

**Usage:** Copy `goal.md` into your project, specify the GitHub issue to address, and have your AI agent follow the instructions.

## License

[MIT](./LICENSE)
