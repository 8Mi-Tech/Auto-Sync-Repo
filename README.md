# 8Mi-Tech / Auto-Sync-Repo

这是一个自动同步 & 减少Commit数量的神器<br>
前置：[Token V1](https://github.com/settings/tokens/new) 仅选择`workflow`<br>粘贴到`https://github.com/<your_org>/<your_repo>/settings/secrets/actions`
变量名`AUTO_SYNC_GH_KEY` ，可任意放置，个人建议放在`Repository secrets`，不会被其他Repo调用到

工作原理 （建议自己看main.yml 通俗易懂）<br>
先点击生成模,选择挂在组织<br>
然后[点我](../../actions/workflows/generate.yml),
