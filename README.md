## 简介
  1. git push 测试
  2. 定时任务1（8:00~13:00），执行bash脚本
  3. 定时任务2 (18:00)，修改定时任务1的执行时间

## 配置
- [生成带workflow权限的token](https://github.com/settings/tokens)
- 配置环境变量WORKFLOW_TOKEN

## 文档
- [workflows官方文档](https://docs.github.com/en/actions/using-workflows/about-workflows)
- [workflows action uses查询](https://github.com/marketplace?type=actions)
- [actions/checkout@v3](https://github.com/actions/checkout#Push-a-commit-using-the-built-in-token)
- [About the GITHUB_TOKEN secret](https://docs.github.com/en/actions/security-guides/automatic-token-authentication)

  When you enable GitHub Actions, GitHub installs a GitHub App on your repository. The GITHUB_TOKEN secret is a GitHub App installation access token. You can use the installation access token to authenticate on behalf of the GitHub App installed on your repository. The token's permissions are limited to the repository that contains your workflow.
  
  
  ## cla push test
