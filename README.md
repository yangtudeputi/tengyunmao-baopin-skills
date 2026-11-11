# 腾云猫 · 爆品带货 Skills

每个 Skill 对应一个单品，按商品名查找。

| 单品 | 爆品 Skill 作者 | 使用资料 |
|---|---|---|
| 《孩子为你自己读书吧》 | 微辣 | [单品手册](skills/haizi-wei-ni-ziji-dushu-ba/references/playbook.md) · [学员工作单](skills/haizi-wei-ni-ziji-dushu-ba/assets/workbook.md) |

### 第一次安装：复制这一句到 Codex

> 帮我从 GitHub 安装腾云猫的爆品带货 Skill。

本仓库是腾云猫的爆品带货 Skill 库。目前只有《孩子为你自己读书吧》这一款，爆品 Skill 作者：微辣。按仓库中的单品目录安装到个人技能目录即可。

如果 Codex 没找到仓库，把这一句发给它：

> 从 https://github.com/yangtudeputi/tengyunmao-baopin-skills 安装爆品带货 Skill。

也可以在终端安装（需 Node.js/npm）：

```sh
npx skills add https://github.com/yangtudeputi/tengyunmao-baopin-skills --skill haizi-wei-ni-ziji-dushu-ba --agent codex --global --copy --yes
```

再次使用时直接说：“用《孩子为你自己读书吧》的 Skill 看看我的开头，这是书页和初稿。”如果当前对话没有发现刚安装的 Skill，新开对话即可。旧版安装名为 weila-book，新版按书名安装；原有作业无需迁移。
