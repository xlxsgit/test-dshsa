# test-dshsa

Sandbox repository for trying out `dsh-superagent` (DeepSeek Harness super-agent prototype).

The agent watches this repository: mention it in an issue or comment and it will open
a work item, work in its own checkout, and reply — usually with a pull request.

## 快速开始

### 环境要求

- Git
- 一个 GitHub 账号，用于创建 Issue 和评审 PR

### 获取仓库

```bash
git clone https://github.com/xlxsgit/test-dshsa.git
cd test-dshsa
```

### 运行测试

本仓库目前只有文档，没有应用代码、测试框架、测试脚本或 CI 配置，因此没有可在本地运行的自动化测试命令。

验证 agent 是否正常工作，可以执行一次手动冒烟测试：

1. 在仓库中新建 Issue，或在现有 Issue / PR 评论中 `@xlxsgit` 并描述一个小任务；
2. 等待 agent 在该线程中回复，确认它已收到任务；
3. agent 通常会在自己的分支上完成改动并提交 PR。打开该 PR 检查改动，即可判断本次测试是否通过。
