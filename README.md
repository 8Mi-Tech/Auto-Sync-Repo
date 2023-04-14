# 8Mi-Tech / Auto-Sync-Repo

这是一个自动同步 & 减少Commit数量的神器<br>

Single版本工作原理 (以CefDetectorX举例)<br>
A = 原作Repo | B = 组织Fork的Repo | C = 用户Fork的Repo
<br>
| | A | B | C |
| - | - | - | - |
| Fork方式 | | A | A
| 自动同步挂载在| | X| 
| 同步哪里的?|||X|

Multi版本工作原理 （建议自己看main.yml 通俗易懂）<br>
需要一个新仓库（最好是组织）<br>
需要一个[Token V1](https://github.com/settings/tokens/new) 仅选择`workflow` 时效和名称自己定义<br>
