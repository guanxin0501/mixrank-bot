# mixrank-bot

dsh-superagent 的演示与试验仓库。

## 使用方式

在本仓库开 Issue 或在评论里 `@<agent 账号> <需求>`，superagent 会轮询到请求、
建 Ticket、在独立 worktree 里干活，并把结果回到原会话。

## 约定

- 主线分支：`main`
- agent 分支：`agent/<name>`
- 单次请求保持小而明确，便于验证「评估 → 执行 → 交付」整条链路
