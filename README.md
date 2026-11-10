# 腾云猫 · 爆品带货 Skills
**首个单品：微辣 ×《孩子为你自己读书吧》｜V1.0 试用版**。给学员的 AI 实操包，适合支持本地 Agent Skills 的工具。装好后不需要记模块名。

### 收到 ZIP，给 Codex 发这句话
> 请从我附上的“微辣爆品Skill-V1.0.zip”安装 weila-book 到我的个人技能目录。请检查 SKILL.md 和 references、assets 都在；如果需要重新开对话，告诉我。安装后用中文给我开始使用的口令。

请把 ZIP 放在本机并附给能读取本地文件的 AI。没有安装权限时，解压，直接打开 skills/weila-book/references/playbook.md 阅读。

### 从仓库安装
仓库管理员发布后，复制浏览器里**实际 GitHub 仓库地址**，发给你的 Agent：“从这个地址安装微辣的 weila-book 到我的个人技能目录，安装后检查文件并告诉我怎么开始。”私有仓库需要该学员有读取权限。只有名称没有地址，不能保证助手找到正确仓库。
   
也可在已解压的本目录打开终端（需 Node.js/npm）：
   
```sh
npx skills add . --skill weila-book --agent codex --global --copy --yes
```
   
从 GitHub 安装时把上面单独的点换成完整仓库 URL。更新时用同一可信来源重新安装；请勿把自己的作业存在安装目录。安装后若当前对话没发现技能，新开对话使用。
   
### 安装后直接说
- “用微辣爆品 Skill 带我开始打这本书，我还没有选题。”
- “用 weila-book 看我的开头。书页和草稿在这里，请直接改。”
- “用 weila-book 帮我复盘：发布两小时 130 播放，没有持续流速，订单我还没查。下一步看什么？”
   
读[单品手册](skills/weila-book/references/playbook.md)或复制[学员工作单](skills/weila-book/assets/workbook.md)。本包没有主访谈原件、爆款剪映原工程、可公开复用的人物素材或收益承诺。
